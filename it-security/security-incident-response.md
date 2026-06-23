# Security Incident Response

## Purpose

This runbook explains how Northstar Company triages suspected security incidents involving accounts, devices, customer data, employee data, or critical business systems.

## Report Immediately

Employees should report suspected incidents in the Security Hotline channel and open an IT Support ticket marked `Security incident`. Examples include:

- lost or stolen devices;
- suspicious MFA prompts;
- accidental data sharing;
- suspected phishing with credentials entered;
- malware alerts;
- access to data beyond the employee's role.

## Severity Levels

Severity 1 covers active credential compromise, customer data exposure, ransomware, or production system access by an unauthorized party. Security leads the response and notifies Legal within one hour.

Severity 2 covers contained device loss, suspicious login attempts, or accidental internal data exposure. IT Security leads the response and notifies the affected department owner.

Severity 3 covers suspicious emails, blocked malware alerts, or low-risk policy questions. IT Support handles triage and escalates if new evidence appears.

## Response Steps

The incident lead should:

1. confirm the reporter and affected systems;
2. preserve screenshots, timestamps, ticket IDs, and logs;
3. revoke or rotate credentials when compromise is possible;
4. isolate affected devices if malware or data exposure is suspected;
5. notify Legal for customer data, employee data, contract, or regulatory risk;
6. post status updates every 30 minutes for Severity 1 and every two hours for Severity 2;
7. create a post-incident summary within five business days.

## Ownership

IT Security owns technical containment. Legal owns notification obligations. Support owns employee communication templates. Department leaders own business continuity decisions.

## Escalation

If the incident involves customer data, employee data, or vendor systems, notify Legal and the department leader before external communication. Do not promise notification timelines to customers or employees without Legal approval.
