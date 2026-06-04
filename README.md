# Task 4 - Firewall Configuration on Windows

## Objective

Configure and test basic firewall rules using Windows Defender Firewall to allow or block network traffic.

## Tool Used

* Windows Defender Firewall with Advanced Security
* Windows 11

## Tasks Performed

1. Opened Windows Defender Firewall.
2. Viewed existing inbound firewall rules.
3. Created a new inbound rule.
4. Configured TCP Port 23 (Telnet).
5. Blocked incoming connections on Port 23.
6. Applied the rule to Domain, Private, and Public profiles.
7. Verified the rule configuration.
8. Removed the test rule to restore the original firewall configuration.

## Rule Configuration

| Parameter | Value                   |
| --------- | ----------------------- |
| Rule Type | Inbound Rule            |
| Protocol  | TCP                     |
| Port      | 23                      |
| Action    | Block Connection        |
| Profiles  | Domain, Private, Public |

## Result

Successfully configured and tested a firewall rule to block inbound traffic on TCP Port 23 using Windows Defender Firewall.

## Files Included

* Task4_Report.pdf

## Author

Riddhi Manani
