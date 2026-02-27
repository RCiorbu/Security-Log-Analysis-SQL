# Security Log Analysis Using SQL

## Scenario
An organization needed to investigate potential security incidents using stored authentication and employee system data. Log records were stored in a database, requiring filtered queries to identify suspicious behavior and affected systems.

## Objective
Identify abnormal login activity and determine which systems required security updates by analyzing structured log data.

## Tools Used
- SQL
- Log database tables
- Query filtering operators (AND, OR, NOT, LIKE)

---

## Investigation 1 – After Hours Failed Logins
Filtered login records occurring after business hours and marked as unsuccessful.

### Purpose
Detect possible unauthorized access attempts outside normal operating time.

### Finding
Failed authentication attempts outside business hours indicate possible password guessing or unauthorized access attempts.

---

## Investigation 2 – Suspicious Date Activity
Filtered login attempts occurring on specific suspicious dates.

### Purpose
Correlate activity with known incident timeline.

### Finding
Targeted date filtering helps isolate attacker activity during a potential breach window.

---

## Investigation 3 – Geographic Anomaly Detection
Filtered login attempts originating outside the organization’s expected location.

### Purpose
Identify potential compromised accounts or remote unauthorized access.

### Finding
Logins from unexpected countries may indicate credential compromise.

---

## Investigation 4 – Targeted System Remediation
Filtered employee device records to identify machines requiring security updates based on department and location.

### Purpose
Apply security patches selectively during incident response.

### Finding
Structured filtering enables efficient containment and remediation actions.

---

## Security Impact
Database logs can be used as a primary investigation source during incident response. Proper querying enables analysts to quickly identify suspicious authentication patterns and affected assets.

## Skills Demonstrated
- Log analysis
- Threat detection logic
- Incident investigation workflow
- Data filtering for containment actions

---

Detailed query examples available in attached documentation.
