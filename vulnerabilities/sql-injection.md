# SQL Injection

## Description
SQL Injection is a vulnerability that allows an attacker to manipulate backend
database queries by injecting malicious SQL statements through user input.

---

## Affected Component
- SQL query parameter without proper input validation

---

## Proof of Concept
Payload used:
' OR '1'='1

The payload resulted in unauthorized retrieval of database records.

---

## Impact
- Unauthorized access to sensitive data
- Possible authentication bypass
- Risk of database compromise

---

## Severity
High

---

## Mitigation
- Use prepared statements and parameterized queries
- Validate and sanitize user input
- Apply least privilege to database accounts
