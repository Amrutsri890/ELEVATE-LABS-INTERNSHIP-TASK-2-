# ELEVATE-LABS-INTERNSHIP-TASK-2-
Identify phishing characteristics in a suspicious email sample.
# What I Did:

Collected a phishing email sample that appeared to impersonate PayPal.
Extracted the raw email headers (email_headers.txt) and performed header analysis to check for spoofing, SPF/DKIM/DMARC failures, and mismatched sender domains.
Inspected the email body for red flags such as urgent language, fake links, poor grammar, and brand impersonation.
Hovered over suspicious links and captured the real URL (link_hover.png).
Used analysis tools (SpamAssassin / header analyzers / VirusTotal) to validate the findings.
Documented the results in analysis_report.md along with screenshots.

# Repository Contents
email_raw.eml – raw phishing email sample.
email_headers.txt – extracted headers for analysis
show_original.png – screenshot of raw header view.
headers_analysis.png – screenshot of automated header analysis.
annotated_body.png – screenshot of email body with suspicious traits highlighted.
link_hover.png – screenshot showing the real phishing link when hovered.
url_scan_results.png – results of scanning the suspicious link.
analysis_report.md – detailed findings and explanation.
README.md – this short summary of the task.

# Summary
This task helped me understand how phishing emails are structured, how spoofing works, and how to analyze both headers and body content to detect threats. It also improved my practical skills in email forensics and cybersecurity awareness.
