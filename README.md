# CVE-2023-7028

Gitlab CVE-2023-7028: Account Takeover via Password Reset without user interactions

A critical vulnerability in GitLab CE/EE (CVE-2023-7028) can be easily exploited by attackers to reset GitLab user account passwords.

While also vulnerable, users who have two-factor authentication enabled on their account are safe from account takeover. Also LDAP logins are safe too!

### About CVE-2023-7028

CVE-2023-7028 affects GitLab self-managed instances running GitLab Community Edition (CE) and Enterprise Edition (EE) versions:

    * 16.1 prior to 16.1.5
    * 16.2 prior to 16.2.8
    * 16.3 prior to 16.3.6
    * 16.4 prior to 16.4.4
    * 16.5 prior to 16.5.6
    * 16.6 prior to 16.6.4
    * 16.7 prior to 16.7.2


How to use
---

```
usage: CVE-2023-7028.py [-h] [-u URL] -v VICTIM -a ATTACKER [-p PROXY]

options:
  -h, --help            show this help message and exit
  -u URL, --url URL     URL of host to check will need http or https
  -v VICTIM, --victim VICTIM
                        victim email address
  -a ATTACKER, --attacker ATTACKER
                        attacker email address
  -p PROXY, --proxy PROXY
                        Proxy for debugging
```
