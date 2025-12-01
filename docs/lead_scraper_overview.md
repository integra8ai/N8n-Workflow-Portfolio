# Lead Scraper → Google Sheets → Auto Outreach Email

## Problem  
Many businesses still manually search websites for emails and send outreach messages, losing hours weekly.

## Solution  
This automated workflow:

1. Scrapes a business listing webpage  
2. Extracts all valid email addresses  
3. Stores them in Google Sheets as a CRM  
4. Sends a personalized outreach email automatically  

## Workflow Logic  
- Cron trigger runs every hour  
- HTTP Request scrapes the target URL  
- Regex node extracts all email addresses  
- Google Sheets logs new leads  
- Gmail sends custom outreach messages  

## Benefits  
- Saves 20–40 hours per month  
- Zero paid APIs needed  
- Perfect for sales outreach pipelines  

## Screenshot  
Add `assets/lead_scraper_screenshot.png`

