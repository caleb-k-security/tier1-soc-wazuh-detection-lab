# SOC Incident Tickets

---

## Ticket 1 - Failed Login Attempt

Severity: Informational  
Classification: False Positive  

A single failed login occurred from localhost. Activity originated from a Windows system process and showed no malicious indicators.

Decision: No action required.

---

## Ticket 2 - Brute Force Attack

Severity: Medium  
Classification: True Positive  

Multiple authentication failures occurred within two minutes from a single source IP.

Action:
- Escalated to Tier 2
- Recommended account lockout
- Recommended IP blocking

---

## Ticket 3 - Malware Execution

Severity: High  
Classification: Confirmed Event  

EICAR test file executed and detected by endpoint protection.

Action:
- Recommended endpoint isolation
- Escalated to Tier 2
