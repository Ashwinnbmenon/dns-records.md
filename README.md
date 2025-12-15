# dns-records.md

Creates an alias from one domain to another domain.  
Used when multiple services point to one main domain.

Example:
www.example.com → example.com

---

## SOA Record
Start of Authority record.  
Contains important information about the domain:
- Primary name server
- Admin email
- Domain serial number
- Refresh & retry intervals

---

## PTR Record
Used for **reverse DNS lookup** (IP → domain name).  
Commonly used in email server verification.

Example:
93.184.216.34 → example.com

---

## SRV Record
Specifies location of services like:
- SIP
- LDAP
- XMPP

Example:
_service._protocol.example.com

---

## DNS Security Notes
- DNS is vulnerable to spoofing and cache poisoning
- DNSSEC helps protect integrity and authenticity
- Open DNS resolvers can be abused for amplification attacks

---

## Common DNS Attacks (Cybersecurity)
- DNS Spoofing
- DNS Cache Poisoning
- DNS Tunneling
- DNS Amplification DDoS
