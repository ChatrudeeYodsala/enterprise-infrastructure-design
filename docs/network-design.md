# Network Design

## VLAN Plan
| VLAN | Department | Network |
| 10 | HR | 192.168.10.0/24 |
| 20 | Finance | 192.168.20.0/24 |
| 30 | IT | 192.168.30.0/24 |
| 40 | Marketing | 192.168.40.0/24 |

## Purpose
Network segmentation is used to isolate departments and improve security.

## Gateway Design
| VLAN | Gateway |
| 10 | 192.168.10.1 |
| 20 | 192.168.20.1 |
| 30 | 192.168.30.1 |
| 40 | 192.168.40.1 |