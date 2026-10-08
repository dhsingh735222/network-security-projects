# Network Security Projects

**Dheeraj Kumar** · Cyber Security Analyst · [Portfolio](https://dhsingh735222.github.io) · [LinkedIn](https://www.linkedin.com/in/dheeraj-kumar-netsec/)

Case studies of network security work I did at **Wipro Limited** (Sep 2024 – Aug 2026) for an enterprise client, Adani Enterprises.

> **Note:** This was client work. Firewall configurations, IP addresses, rule exports and other client data are confidential, so they are not in this repository. Each case study describes the problem, what I did and the result.

## At a glance

| | |
|---|---|
| Firewalls supported | 100+ Palo Alto and Fortinet FortiGate firewalls |
| Sites | 15+ global sites |
| Rules reviewed | 5,000+ |
| Policy complexity | reduced by 25% |
| Tickets | about 40 change requests and incidents a month, through ServiceNow |

---

## 1. Firewall policy standardisation

**Tools:** Palo Alto NGFW, Panorama, Fortinet FortiGate, ServiceNow (ITIL change management)

### Problem
Each site had grown its own firewall policy objects over time. The same server or network was defined several times under different names, and the rule base held duplicate, redundant and shadowed rules. That made the policy hard to read, audit and change safely.

### What I did
- Reviewed more than 5,000 firewall rules managed through Panorama.
- Found duplicate, redundant and shadowed rules, and duplicate or conflicting object definitions.
- Replaced site-specific objects with one standard set of policy objects shared across 15+ global sites.
- Raised and delivered every change through ServiceNow under ITIL change management.

### Result
- Firewall policy complexity reduced by **25%**.
- One consistent set of objects across all sites, which makes rule reviews and new changes faster and less error-prone.

---

## 2. GCP cloud firewall policies

**Tools:** Google Cloud Platform, Cloud NGFW, firewall policy, URL filtering

### Problem
Web applications hosted in Google Cloud needed firewall protection that matched the standard already used for the on-premises network.

### What I did
- Created and configured firewall rules and security policies on Google Cloud NGFW for cloud-hosted web applications.
- Kept the cloud rules in line with the existing on-premises firewall policy, so the hybrid environment followed one standard.
- Built custom web-filtering rules to govern employee access to AI tools.

### Result
- Cloud-hosted applications protected under the same policy standard as the on-premises network.
- Controlled, policy-based access to AI tools for employees.

---

## Related work in the same role
- **Log analysis automation:** wrote Regex-based parsing for security logs, which removed about 2 hours of manual log review every day.
- **Operations:** handled about 40 change requests and incidents a month end to end in ServiceNow.

## Skills shown
Firewall policy management · Rule base optimisation · Palo Alto · Panorama · FortiGate · Google Cloud NGFW · URL filtering · Log analysis · Regex · ServiceNow · ITIL change management
