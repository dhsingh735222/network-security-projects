# Network Security Projects

**Dheeraj Kumar** · Cyber Security Analyst · [Portfolio](https://dhsingh735222.github.io) · [LinkedIn](https://www.linkedin.com/in/dheeraj-kumar-netsec/)

Case studies of network security work I did at **Wipro Limited** (Sep 2024 – Aug 2026) for two clients: **Adani Enterprises** (network and firewall security, Sep 2024 – Oct 2025) and **BluePearl**, a US healthcare company (cloud and infrastructure security, Nov 2025 – Aug 2026).

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

**Client:** Adani Enterprises · **Tools:** Palo Alto NGFW, Panorama, Fortinet FortiGate, ServiceNow (ITIL change management)

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

**Client:** BluePearl (US healthcare) · **Tools:** Google Cloud Platform, Cloud NGFW, NAT/PAT, routing, security logging

### Problem
Applications hosted in Google Cloud needed firewall protection that matched the standard already used for the on-premises network, and traffic between the cloud and on-premises segments had routing and NAT conflicts.

### What I did
- Configured cloud firewall rules and security policies on Google Cloud NGFW, aligned with the existing on-premises firewall estate.
- Mapped traffic flows end to end between cloud and on-premises segments, and corrected NAT and route policies to resolve the conflicts and remove asymmetric paths.
- Set up unified security logging and monitoring across the hybrid infrastructure.

### Result
- Cloud-hosted applications protected under the same policy standard as the on-premises network.
- One view of security logs across cloud and on-premises, for faster incident triage.

---

## Related work in the same role
- **AI tool access governance:** built URL filtering and Regex-based inspection rules on the secure web gateway to allow approved generative AI use while blocking unapproved data uploads.
- **Log analysis automation:** wrote Regex-based parsing for secure web gateway logs, which removed about 2 hours of manual log review every day.
- **Operations:** handled about 40 change requests and incidents a month end to end in ServiceNow.

## Skills shown
Firewall policy management · Rule base optimisation · Palo Alto · Panorama · FortiGate · Google Cloud NGFW · NAT and routing · URL filtering · Log analysis · Regex · ServiceNow · ITIL change management
