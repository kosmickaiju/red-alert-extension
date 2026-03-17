# Red Alert: CVE Alert Dashboard Google Chrome Extension (Version 3.0 in production!)

## What is it?
This is a Google Chrome extension focused on delivering information about Common Vulnerabilities and Exploits (CVEs) in a simple, easy to understand way. The extension uses a dashboard to provide streamlined briefings about CVEs found and posted within the last 24 hours, refreshing with new briefings every 30 minutes (or on manual refresh). As of version 3.0, pagination features and an "Export to CSV" option have been implemented, and the UI has been refreshed.
## How It Works/How to Use
This extension uses the **NIST National Vulnerability Database CVE API** to obtain information on CVEs posted within the past 24 hours.
This extension opens a tab on browser startup containing the dashboard. On the dashboard, 10 recent CVEs are listed per page as well as their CVSS scores and severity level. Users can filter their briefings based on severity in three categories: all, high, and critical. 
## Tech Stack
This extension was written using **HTML/CSS/JS**, with information about CVEs being pulled from the **NVD CVE API**.
