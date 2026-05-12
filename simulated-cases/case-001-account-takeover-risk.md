# Case 001 - Account Takeover Risk

## Case Type

Simulated risk operations case

## Summary

This case reviews a simulated account takeover risk scenario involving repeated failed login attempts, a successful login from an unusual location, a new device, and a suspicious transaction attempt.

The purpose of this case is to practice evidence review, risk assessment, suspicious activity analysis, and escalation-quality reporting.

## Scenario

A customer account showed multiple failed login attempts within a short time period. Shortly after the failed attempts, a successful login occurred from a new device and an unusual location. After the login, the account password was changed and a new transaction attempt was initiated.

This activity may indicate possible account takeover risk and should be reviewed to determine whether the activity was authorized by the account holder.

## Observed Activity

| Time | Event | Notes |
|---|---|---|
| 09:12 | Multiple failed login attempts | Several attempts from the same source |
| 09:18 | Successful login | Login from a new device |
| 09:21 | Password changed | Account security setting modified |
| 09:25 | New transaction attempt | Activity inconsistent with normal pattern |

## Key Risk Indicators

- Multiple failed login attempts in a short period
- Successful login following failed attempts
- Login from a new or unusual device
- Login from an unusual location
- Password change after successful login
- Transaction attempt shortly after account access
- Activity inconsistent with expected customer behavior

## Evidence Reviewed

- Login attempt history
- Source IP and device information
- Location associated with the successful login
- Account change history
- Transaction activity after login
- Previous account activity pattern

## Risk Assessment

The activity presents a potential account takeover risk. The combination of repeated failed login attempts, successful access from a new device, password change, and a transaction attempt creates a suspicious pattern.

The successful login should be reviewed to determine whether it was expected or authorized by the customer. The transaction attempt should also be reviewed before processing.

## Recommended Action

- Temporarily hold or review the suspicious transaction
- Verify whether the successful login was authorized
- Review device, IP, and location information
- Check for additional account changes
- Escalate the case to a senior analyst or fraud-risk team if unauthorized access is suspected
- Recommend customer verification if required by procedure

## Escalation Note

Potential account takeover risk identified. The account showed multiple failed login attempts followed by a successful login from a new device and unusual location. After access was obtained, the password was changed and a new transaction attempt was initiated. The activity appears inconsistent with the expected account pattern and should be reviewed to determine whether the login and transaction were authorized.

## Analyst Reflection

This case demonstrates the importance of reviewing activity as a sequence rather than as isolated events. A failed login attempt alone may not be enough to indicate compromise. However, failed attempts followed by a successful login, account changes, and transaction activity create a stronger suspicious pattern.

## Skills Practiced

- Evidence review
- Suspicious activity analysis
- Account takeover risk assessment
- Timeline building
- Escalation-quality reporting
- Professional English documentation

## Note

This is a simulated case created for learning and portfolio purposes. It does not contain real customer data, real institutional information, or confidential operational details.
