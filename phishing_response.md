
---

### File Templates:

1. **[phishing_response.md]** (Phishing Email Analysis Playbook)
   ```markdown
   # Phishing Email Analysis Playbook

   ## Overview
   This playbook outlines the steps SOC teams should take to analyze and respond to phishing emails.

   ## Step 1: Identify Suspicious Emails
   - Check the sender's email address for any irregularities.
   - Look for unexpected attachments or links.
   - Verify if the email is requesting personal information or asking for urgent action.

   ## Step 2: Verify the Authenticity of the Sender
   - Cross-check the sender's domain using WHOIS or DNS lookup tools.
   - Reach out to the sender through alternate communication channels (e.g., phone or verified email) to confirm legitimacy.

   ## Step 3: Mitigate the Threat
   - Isolate the affected machine(s) from the network.
   - Block malicious email addresses or IP addresses on the email gateway.

   ## Step 4: Remediation
   - Scan the affected systems for any malware.
   - Apply necessary patches to prevent further exploitation.
   - Educate users on recognizing phishing attempts.

   ## Step 5: Reporting
   - Document the incident and the steps taken.
   - Share the details of the attack with internal teams and external threat intelligence platforms.
