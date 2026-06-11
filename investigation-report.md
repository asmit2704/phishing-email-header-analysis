\# Phishing Email Header Analysis Report



\## Objective



Analyze email headers and verify sender authenticity.



\## Tools Used



\* Gmail

\* AbuseIPDB

\* VirusTotal



\## Emails Analyzed



\### Email 1 - Legitimate Test Email



A standard Gmail message was sent between accounts to establish a baseline for normal email behavior.



\### Email 2 - Simulated Phishing-Themed Email



A security-themed email containing a sample URL was created to simulate a phishing investigation workflow.



\## Header Analysis



Sender Domain:

gmail.com



Sender IP:

209.85.220.41



\## Email Authentication



SPF:

PASS



DKIM:

PASS



DMARC:

PASS



\## Reputation Analysis



Source IP:

209.85.220.41



ISP:

Google LLC



Abuse Confidence Score:

0%



Analysis:



The sender IP belongs to Google's mail infrastructure and did not show evidence of malicious activity.



\## URL Analysis



URL Investigated:



https://example.com/login



Result:



No malicious indicators were identified during analysis.



\## Findings



\* SPF validation passed successfully.

\* DKIM validation passed successfully.

\* DMARC validation passed successfully.

\* Sender IP belongs to trusted Google infrastructure.

\* No indicators of compromise were identified.

\* URL investigation produced no malicious findings.



\## Conclusion



The analyzed email appears legitimate and shows no evidence of phishing activity. Email authentication mechanisms were successfully validated and threat intelligence checks did not reveal suspicious behavior.



