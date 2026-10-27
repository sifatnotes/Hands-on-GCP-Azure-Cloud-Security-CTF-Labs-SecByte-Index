# Hands-on-GCP-Azure-Cloud-Security-CTF-Labs-SecByte-Index
A curated index of practical CTF labs covering Google Cloud Platform (GCP) &amp; Microsoft Azure security, IAM misconfigurations, serverless Cloud Functions, Cloud Armor WAF, Secret Manager, Sentinel/Azure SecOps, and Azure governance.
# GCP & Azure Cloud Security CTF Lab Collection

Welcome to the **GCP & Azure Cloud Security CTF Lab Collection**. This repository serves as a structured, searchable catalog of hands-on security labs and Capture The Flag (CTF) challenges hosted on Learn SecByte.

This collection spans enterprise cloud infrastructure defense across **Google Cloud Platform (GCP)** and **Microsoft Azure**, covering Identity and Access Management (IAM/RBAC), serverless application analysis, network security (WAF), cloud telemetry, and cloud incident response.

---

## Lab Collection Index

### 1. Google Cloud Platform (GCP) Core & Identity Security
* **Google Cloud Fundamentals: Securing Identity, Storage, and Workloads**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-cloud-fundamentals-securing-identity-storage-and-work](https://learn.secbyte.org/ctf/google-cloud-fundamentals-securing-identity-storage-and-work)  
  *Focus:* Architecture baselines, securing Cloud Storage buckets, service accounts, and workload identity boundaries.

* **Google IAM: Identity, Access, and Misconfiguration Defense**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-iam-identity-access-and-misconfiguration-defense](https://learn.secbyte.org/ctf/google-iam-identity-access-and-misconfiguration-defense)  
  *Focus:* Auditing IAM roles, primitive vs. predefined roles, privilege escalation paths, service account key abuse, and policy binding cleanup.

* **Google Compute Engine Security Foundations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-compute-engine-security-foundations](https://learn.secbyte.org/ctf/google-compute-engine-security-foundations)  
  *Focus:* Hardening GCE virtual machines, OS Login configuration, VPC firewall rules, shield VMs, and service account association security.

* **Google Cloud Functions: Secure Serverless App Analysis**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-cloud-functions-secure-serverless-app-analysis](https://learn.secbyte.org/ctf/google-cloud-functions-secure-serverless-app-analysis)  
  *Focus:* Analyzing serverless code vulnerabilities, unauthenticated HTTP triggers, environment variable leaks, and minimal-privilege execution.

* **Google Secret Manager: Securing Cloud Secrets in Practice**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-secret-manager-securing-cloud-secrets-in-practice](https://learn.secbyte.org/ctf/google-secret-manager-securing-cloud-secrets-in-practice)  
  *Focus:* Eliminating hardcoded credentials, secret versioning, IAM secret accessor roles, automatic rotation, and audit logging.

### 2. GCP Perimeter Defense, Detection & Operations
* **Google Cloud Armor: Web Defense and Policy Enforcement**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-cloud-armor-web-defense-and-policy-enforcement](https://learn.secbyte.org/ctf/google-cloud-armor-web-defense-and-policy-enforcement)  
  *Focus:* Configuring WAF rules, DDoS protection policies, IP allowlisting/denylisting, adaptive protection, and OWASP Top 10 mitigation.

* **Google Security Command Center: Cloud Threat Detection & Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-security-command-center-cloud-threat-detection-respon](https://learn.secbyte.org/ctf/google-security-command-center-cloud-threat-detection-respon)  
  *Focus:* Utilizing SCC for vulnerability management, anomaly detection, misconfiguration tracking, and automated alert response.

* **Google Cloud Logging: From Signal to Incident**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-cloud-logging-from-signal-to-incident](https://learn.secbyte.org/ctf/google-cloud-logging-from-signal-to-incident)  
  *Focus:* Structuring Cloud Audit Logs (Admin Activity, Data Access), log sinks, metrics creation, and tracking administrative abuse.

* **Google Cloud Monitoring: Detect, Investigate, Defend**  
  *Lab Link:* [https://learn.secbyte.org/ctf/google-cloud-monitoring-detect-investigate-defend](https://learn.secbyte.org/ctf/google-cloud-monitoring-detect-investigate-defend)  
  *Focus:* Constructing alerting policies, uptime checks, monitoring metric anomalies, and integrating alerts into SecOps workflows.

### 3. Microsoft Azure Security & Operations
* **Azure Pentesting Foundations: Identity, Storage, Misconfiguration Hunting**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-pentesting-foundations-identity-storage-misconfig-hunt](https://learn.secbyte.org/ctf/azure-pentesting-foundations-identity-storage-misconfig-hunt)  
  *Focus:* Enumerating Entra ID (Azure AD), public blob storage containers, key vault access policies, and privilege escalation vectors.

* **Azure Governance: Policies, RBAC, Landing Zones**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-governance-policies-rbac-landing-zones](https://learn.secbyte.org/ctf/azure-governance-policies-rbac-landing-zones)  
  *Focus:* Implementing Azure Policy definitions, custom RBAC roles, subscription hierarchy governance, and enterprise landing zone security.

* **Azure Security Operations: From Logs to Incident Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-security-operations-from-logs-to-incident-response](https://learn.secbyte.org/ctf/azure-security-operations-from-logs-to-incident-response)  
  *Focus:* Triaging Azure Activity Logs, Defender for Cloud alerts, KQL hunting in Log Analytics, and incident containment workflows.

---

## Learning Path

### Path A: Google Cloud Security & Engineering
1. **Core Foundations:** Start with [Google Cloud Fundamentals](https://learn.secbyte.org/ctf/google-cloud-fundamentals-securing-identity-storage-and-work), [Google Compute Engine Security](https://learn.secbyte.org/ctf/google-compute-engine-security-foundations), and [Google IAM Defense](https://learn.secbyte.org/ctf/google-iam-identity-access-and-misconfiguration-defense).
2. **Application & Secret Security:** Practice via [Google Cloud Functions](https://learn.secbyte.org/ctf/google-cloud-functions-secure-serverless-app-analysis) and [Google Secret Manager](https://learn.secbyte.org/ctf/google-secret-manager-securing-cloud-secrets-in-practice).
3. **Perimeter & Monitoring:** Secure edge traffic using [Google Cloud Armor](https://learn.secbyte.org/ctf/google-cloud-armor-web-defense-and-policy-enforcement) and monitor with [Google Cloud Logging](https://learn.secbyte.org/ctf/google-cloud-logging-from-signal-to-incident), [Cloud Monitoring](https://learn.secbyte.org/ctf/google-cloud-monitoring-detect-investigate-defend), and [Security Command Center](https://learn.secbyte.org/ctf/google-security-command-center-cloud-threat-detection-respon).

### Path B: Microsoft Azure Infrastructure & Defense
1. **Governance & Architecture:** Begin with [Azure Governance: Policies, RBAC, Landing Zones](https://learn.secbyte.org/ctf/azure-governance-policies-rbac-landing-zones).
2. **Offensive Auditing:** Identify vulnerabilities with [Azure Pentesting Foundations](https://learn.secbyte.org/ctf/azure-pentesting-foundations-identity-storage-misconfig-hunt).
3. **Security Operations:** Master cloud triage in [Azure Security Operations: From Logs to Incident Response](https://learn.secbyte.org/ctf/azure-security-operations-from-logs-to-incident-response).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to open the exercise environment directly on Learn SecByte.
3. Review scenario directives, architecture diagrams, and task goals.
4. Audit cloud resources, fix misconfigurations, analyze telemetry, or execute attacks to retrieve flags.

---

## Target Audience

* **Cloud Security Engineers:** Master multi-cloud security baselines across GCP and Azure platforms.
* **SOC Analysts & Cloud Responders:** Analyze cloud audit logs, construct monitoring rules, and contain cloud breaches.
* **Penetration Testers & Red Teams:** Practice cloud IAM privilege escalation, serverless exploitation, and storage misconfiguration discovery.
* **Cybersecurity Students:** Gain real-world experience across leading public cloud service providers.

---

## Disclaimer

All lab links in this repository direct to official training environments hosted on Learn SecByte. These materials are provided exclusively for authorized security training, defensive skill development, and educational research. Unapproved testing against external public cloud tenants is strictly prohibited.
