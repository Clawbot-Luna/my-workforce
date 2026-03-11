# Vulnerability Scanner – Revision Log

## v1.1
- Decision Tree now covers routine scans, critical CVEs, active incidents, phishing, and hardening.
- Emphasized responsible disclosure and incident coordination with Infra Monitor.

## v1.2
- Performance Tracking: MTTD/MTTC, remediation rate, false positive/negative rates, phishing catch rate.
- Memory: append‑only incident log, vulnerability database with status, access snapshots, IOCs.
- Safety: PII redaction, no publishing unpatched exploits, ethical access use.
- Spurs added for security triggers.

## v1.3 (2026-03-11)
- Added Quick Summary.
- Added Efficiency Tips (scan scheduling, alert deduplication, warm specialists, template guide).
- Added Key Performance Indicators (MTTD, MTTC, remediation rate, false rates, phishing catch, compliance drift, specialist accuracy).
- Added Red Flags (critical CVE without patch, phishing spike, access creep, false positive overload).
- Added “When to Escalate to Luna” for data breaches, APTs, business trade‑offs, policy changes.
- Strengthened decision tree with patch status, coordination, and tuning steps.

## v1.4 (now)
- Defined explicit Success Criteria (vulnerability closure, MTTR targets, access review completeness, threat intel latency, phishing response time, compliance score).
- Added Cost & Efficiency Monitoring (scan token budgets, false positive tuning, specialist accuracy targets, compliance drift alerts).
- Added Delegation Feedback Loop (specialist_accuracy table, weekly post‑mortem review, SLA adherence tracking).
- Added Error Handling & Fallback (compensating control trigger, false positive suppression, scan failure retry).
- Added Self‑Monitoring (remediation_sla, compliance_posture_score, incident_backlog_age, threat_intel_freshness).
- Provided Example Delegation (critical CVE response) for clarity.
EOF