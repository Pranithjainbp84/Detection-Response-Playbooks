# Ransomware Containment Playbook

## Overview
This playbook provides the steps for SOC teams to take when responding to a ransomware attack.

## Step 1: Identification of Ransomware Attack
- Check for unusual file extensions or system behavior (e.g., files becoming encrypted).
- Verify alerts from endpoint protection or SIEM systems regarding ransomware activity.

## Step 2: Containment and Isolation
- Isolate the affected system(s) from the network to prevent further spread.
- Disable all external network access if necessary (e.g., VPN, remote desktop).

## Step 3: Analysis of the Attack
- Identify the strain of ransomware and its known variants (use online threat intelligence sources).
- Look for indicators of compromise (IOCs) such as file hashes, domains, or IP addresses.

## Step 4: Eradication and Recovery
- Remove the ransomware and associated files.
- Restore files from backups that were not affected by the attack.

## Step 5: Post-Incident Actions
- Review and improve security measures (e.g., patching vulnerabilities, enhancing email filtering).
- Educate users about phishing and ransomware attacks.
