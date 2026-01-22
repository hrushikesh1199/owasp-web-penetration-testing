# Cross-Site Scripting (XSS)

## Description
Cross-Site Scripting allows attackers to inject malicious scripts into web pages
that are executed in the victim’s browser.

---

## Types Identified
- Reflected XSS
- Stored XSS

---

## Proof of Concept
Payload:
<script>alert('XSS')</script>

---

## Impact
- Session hijacking
- Credential theft
- Malicious content injection

---

## Severity
Medium to High

---

## Mitigation
- Proper output encoding
- Input validation and sanitization
- Implement Content Security Policy (CSP)
