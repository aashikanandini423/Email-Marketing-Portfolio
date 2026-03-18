# Project 4: Multi-Channel CRM Automation (Re-Engagement Campaign)

## Objective
Design a scalable CRM automation to re-engage inactive users using personalized email and SMS campaigns.

---

## Business Problem
Users who have not interacted or made a purchase in the last 30 days are at risk of churn.

---

## Target Audience
Inactive users:
- No activity in last 30 days
- No recent purchases

---

## Solution Overview
Built a multi-channel re-engagement journey using:
- Email (primary channel)
- SMS (fallback channel)
- Personalized messaging

---

## Journey Architecture

Entry Condition:
- last_activity_date < 30 days

Flow:
1. Email 1: “We Miss You”
2. Wait: 3 Days
3. Check:
   - If opened → Send Offer Email
   - If not opened → Send SMS
4. Wait: 2 Days
5. Final Reminder Email

Exit Criteria:
- User engages or makes purchase

---
