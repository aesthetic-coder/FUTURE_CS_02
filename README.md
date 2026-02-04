# Phishing Detection & Awareness System

## Project Overview <br>
Phishing remains one of the most common threats in cybersecurity, targeting the human element rather than software vulnerabilities. This project is a Security Analyst's Report, deconstructing real-world phishing samples to identify social engineering tactics and technical red flags. <br>

## Tools & Methodology
To conduct this analysis, the following tools and methods were used: <br>
1. Email Header Analysis: Inspecting records to verify sender authenticity using Google Admin Toolbox. <br>
2. URL Inspection: Analyzing link structures for look-alike domains. <br>
3. Social Engineering Deconstruction: Identifying psychological triggers such as urgency, fear, and curiosity. <br>
4. Baseline Comparison: Comparing malicious samples against legitimate corporate communications (using the Enron Email Dataset) to highlight anomalies. <br>

## Key Findings
During the analysis of the samples provided in this repository, several critical indicators were identified: <br>
Domain Spoofing: Use of look-alike domains like msupdate.net instead of microsoft.com. <br>
Impersonation: High-frequency impersonation of trusted brands like Microsoft, Apple, and Venmo. <br>
Urgency: 90% of analyzed samples used "Account Suspension" or "Unauthorized Login" as a hook to bypass user critical thinking. <br>
Credential Harvesting: The primary goal of most samples was to redirect users to a cloned login page to steal credentials. <br>

## Awareness: The SLAMS Method
As part of this project, I developed/refined the SLAMS checklist for employee training: <br>
Sender: Verify the actual email address, not just the display name. <br>
Links: Hover to inspect the destination URL. <br>
Attachments: Never open unexpected files. <br>
Message: Watch for emotional manipulation (Fear/Greed). <br>
Signature: Look for generic or inconsistent contact details. <br>
