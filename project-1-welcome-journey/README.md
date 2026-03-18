# Project 1: Lifecycle Email Journey (Onboarding + Conversion)
## Project Description

Developed SQL-based customer segmentation to enable targeted and personalized marketing campaigns.

Analyzed customer data to identify key segments such as high-value users, inactive users, and frequent buyers using behavioral and transactional attributes. Wrote SQL queries to extract actionable insights and support audience targeting.

Applied segmentation strategies to align marketing messages with user behavior, improving relevance and engagement. Demonstrated how data-driven segmentation can enhance campaign performance and optimize resource allocation.

## Objective
 To design and implement a scalable lifecycle email journey to onboard new users and drive first purchase conversion.

## Target Audience
- New users who signed up but have not made a purchase
- Segment: First-time users (0 purchases)

## Business Problem
New users sign up but fail to convert into paying customers within the first 7 days.

## Solution Approach
Implemented a 3-stage onboarding journey to:
- Educate users about product value
- Increase Engagement
- Encourage first purchase through incentives

## Journey Architecture

Entry Event:
- User Signup (Data Extension Entry)

Flow:
1. Welcome Email (Immediately)
2. Wait: 2 Days
3. Feature Highlight Email
4. Wait: 3 Days
5. Offer Email (Discount / CTA)

Exit Criteria:
- User makes a purchase → exit journey



## Email Strategy

### Email 1: Welcome
- Goal: Introduce brand
- CTA: Explore products

### Email 2: Features
- Goal: Educate users
- CTA: Discover benefits

### Email 3: Offer
- Goal: Convert users
- CTA: Buy now with discount

##  KPIs Tracked
- Open Rate
- Click-through Rate (CTR)
- Conversion Rate
- Time to First Purchase

##  Optimization Ideas
- Personalization using user name
- Send-time optimization
- Dynamic product recommendations

##  Tools & Concepts
- Salesforce Marketing Cloud (Journey Builder concept)
- Lifecycle Marketing
- Email Automation
- Audience Segmentation

##  Expected Impact
- Increased user activation
- Higher first-purchase conversion rate
