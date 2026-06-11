# Security Hardening

## Objective
Improve the security posture of FILE01.

## Firewall Configuration
UFW was configured to allow only required services:

* SSH (TCP 22)
* SMB (TCP 445)

All other inbound traffic is denied by default.

## Intrusion Prevention
Fail2Ban was installed and enabled to protect against repeated unauthorized login attempts.

## Security Benefits
* Reduced attack surface
* Basic intrusion prevention
* Improved server security
* Better operational practices

## Result
Security hardening controls were successfully implemented and verified.
