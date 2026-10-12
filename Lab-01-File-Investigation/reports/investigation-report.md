# Lab 01 - File Investigation Report

## Investigation Type
Simulated failed login investigation

## Evidence
File: suspicious-log.txt
File size: 37 bytes
Owner: mendell
Permissions: -rw-rw-r--
SHA-256: 91fba6434a641f4cc6ce7384285a2fb39da4703544cb73e7034a981c0880ac2f
## Findings
The simulated log contains one failed login attempt from 192.0.2.10.

## Analysis
The IP address is reserved for documentation.
One failed login attempt alone does not prove an attack.

## Tools Used
- cat
- stat
- sha256sum
- ls -l

## Conclusion
Reviewed a simulated security log and examined file metadata. No actual compromise was identified.
