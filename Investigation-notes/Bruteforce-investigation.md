## Investigation Summary

### Logs Reviewed:
- Windows Security Logs (Event ID 4625)
- Source IP analysis

### Findings:
- Repeated failed login attempts targeting one user
- Same source IP observed
- Attempts occurred outside business hours
- No successful login observed

### Assessment:
The activity matches brute-force attack behavior targeting a user account.

### Decision:
Escalate to SOC Level 2 for further response.
