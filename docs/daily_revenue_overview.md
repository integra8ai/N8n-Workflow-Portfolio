# Daily Revenue Report Automation

## Problem  
Business owners want daily revenue reports without logging into dashboards.

## Solution  
Stripe → Google Sheets → Email summary automation.

## Workflow Logic  
- Stripe webhook logs every payment  
- Google Sheets acts as the revenue database  
- Daily cron collects all entries  
- Function node sums total revenue  
- Gmail sends founder a clean report  

## Benefits  
- Zero manual reporting  
- Real-time finance tracking  
- Great for SaaS or e-commerce  

## Screenshot  
Add `assets/daily_revenue_screenshot.png`

