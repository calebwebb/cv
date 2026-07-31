---
title: "Caleb Webb - Cloud DevOps Engineer"
name: "Caleb Webb"
position: "Cloud DevOps Engineer"
location: "Greater Melbourne Area, Australia"
linkedin: "https://linkedin.com/in/caleb-webb"
github: "https://github.com/calebwebb"

summary: "I started as a network engineer, and over the years that turned into a habit of picking up whatever infrastructure needed solving - Cisco security and Zero Trust architectures, identity and access control (dot1x) across hospital, defence and enterprise networks, unified communications platforms (CUCM, UCM, Webex Contact Centre) supporting hundreds of staff, and software-defined data centres built on Cisco ACI as Infrastructure-as-Code. Somewhere along the way, I got tired of doing all of it manually and started automating instead - deploying ACI configurations through CI/CD pipelines, scripting infrastructure validation, and building policy-as-code frameworks. Seven years and four Azure certifications later, I now work as a Cloud DevOps Engineer, but I still think like an infrastructure engineer first: I don't just automate deployments, I automate systems - networking, compute, security, identity, and compliance."

experience:
  - title: "Cloud DevOps Engineer"
    company: "Hollard Insurance"
    location: "Remote"
    period: "Nov 2025 - Present"
    items:
      - Deployed and manage scalable Azure infrastructure using Infrastructure as Code, enabling consistent, repeatable environment provisioning across teams.
      - Strengthened organisational security posture by managing Entra ID identities and Service Principals under a strict least-privilege, Zero Trust framework - applying identity-governance discipline built over years of on-prem NAC and RADIUS design.
      - Engineered high-availability network security architectures integrating NSGs, ASGs, Azure Firewalls, and Palo Alto appliances to protect critical cloud workloads — bridging cloud-native controls with deep firewall and segmentation expertise most cloud engineers outsource.
      - Built a Policy-as-Code CI/CD framework for Azure AD B2C, with automated unit testing to validate identity policies pre-deployment, replacing manual review with pipeline-enforced governance and catching misconfigurations before they reached production.
      - Led enterprise cloud portfolio optimisation and licensing governance, right-sizing resource allocation and consolidating license usage across the estate to eliminate waste and improve cost visibility for leadership.

  - title: "Senior Infrastructure Engineer"
    company: "Hollard Insurance"
    location: "Remote"
    period: "Jun 2025 - Nov 2025"
    items:
      - Architected enhanced infrastructure telemetry and health-check automation, standardising reporting across the enterprise and mitigating operational risk.
      - Designed proactive automation strategies that eliminated manual bottlenecks and streamlined cross-functional infrastructure services.
      - Led a six-member engineering team as Technical Lead, owning operational logistics, strategic planning, and performance metrics.
      - Built automated M365 governance tooling delivering weekly utilisation insights and executing license-reclamation logic - a self-serve reporting layer that removed manual audit work.
      - Designed rules-based automation to migrate shared mailboxes to archive storage, optimising cost and licensing at scale.

  - title: "Network Engineer (Projects)"
    company: "BAE Systems Australia"
    location: "Melbourne, VIC"
    period: "Aug 2024 - Jun 2025"
    items:
      - Led a full data centre migration from legacy to software-defined architecture using Terraform-driven IaC - bringing version control, code review, and CI/CD discipline to infrastructure that was previously manually configured.
      - Built and maintained CI/CD pipelines in Jenkins and GitLab to manage Nexus-as-Code for Cisco ACI, treating network infrastructure as software.
      - Built centralised Python and Bash tooling to automate cross-platform configuration, validation, and API-driven tasks.
      - Architected enterprise-wide Zero Trust NAC (802.1X) using Cisco ISE for secure endpoint identity - the same access-control principles now applied at the cloud IAM layer.
      - Designed and deployed a full monitoring ecosystem on Zabbix, and optimised F5 controllers for L4/7 load balancing, APM, and SSL offload.
      - Owned incident management and root-cause analysis across Security, Data Centre, and Automation platforms.
      
  - title: "Network Engineer"
    company: "Monash Health"
    location: "Clayton, VIC"
    period: "Dec 2021 - Aug 2024"
    items:
      - Directed a 12-month campus refresh, automating replacement of 800+ edge and 8 core switches via Cisco DNA Center and zero-touch provisioning - infrastructure-as-code principles applied to physical hardware at scale.
      - Developed Python and REST API tooling to automate UC provisioning, generating $60k in annual savings.
      - Built custom telemetry and validation suites in Netmiko and Python, delivering $120k p.a. in efficiency gains - early proof of the automation-first approach now central to my DevOps work.
      - Designed and deployed enterprise-wide Zero Trust NAC (802.1X) across 5 hospitals and 50+ clinics to ISO 27001 standard.
      - Automated DHCP migration for 250+ scopes using PowerShell, cutting manual overhead and hardware costs.
      - Owned end-to-end technical lifecycles - requirements, design, implementation, and support transition across networking, wireless, security, and data centre.

  - title: "System Administrator"
    company: "Monash Health"
    location: "Clayton, VIC"
    period: "Sept 2019 - Dec 2021"
    items:
      - Built a Service Desk Multi-tool automating daily and bulk tasks, saving $150k p.a. - the earliest example of the automation-first mindset that now runs through every role since.
      - Managed Citrix, AD/AAD, M365 Admin Center, EXO, InTune, SCCM, DHCP, and DNS infrastructure.
      - Wrote PowerShell and Python scripts to automate recurring tasks and lift team productivity.
      - Contributed to planning, development, and delivery of virtual workspace solutions.

education:
  - degree: "Bachelor of Computer Science"
    institution: "Deakin University"
    period: "2019 - 2023"

skills:
  - category: "Cloud Platforms"
    items: ["Azure", "Entra ID", "Bicep"]
  - category: "Infrastructure as Code"
    items: ["Terraform", "Policy-as-Code", "Ansible"]
  - category: "CI/CD & Git"
    items: ["Azure DevOps", "GitLab", "Jenkins"]
  - category: "Scripting & Automation"
    items: ["Python", "PowerShell", "Go", "Neovim"]
  - category: "Security & Identity"
    items: ["Firewalls", "Dot1x", "RADIUS", "ZTNA"]
  - category: "Monitoring & Observability"
    items: ["Zabbix", "Dynatrace", "Grafana"]

# Remaining sections are optional.
certifications:
  - name: "Cisco Certified Networking Professional, Security"
    issuer: "Cisco"
    year: "2026"
  - name: "Cisco Certified Specialist - Network Security VPN"
    issuer: "Cisco"
    year: "2026"
  - name: "Cisco Certified Specialist - Security Core"
    issuer: "Cisco"
    year: "2024"
  - name: "Cisco Certified Network Associate"
    issuer: "Cisco"
    year: "2022"
  - name: "ECSE Design"
    issuer: "Ekahau"
    year: "2022"
  - name: "Azure DevOps Engineer Expert"
    issuer: "Microsoft"
    year: "2026"
  # - name: "Azure Solutions Architect Expert"
  #   issuer: "Microsoft"
  #   year: "TBA"
  - name: "Azure Developer Associate"
    issuer: "Microsoft"
    year: "2026"
  - name: "Azure Network Engineer Associate"
    issuer: "Microsoft"
    year: "2025"
  - name: "Azure Administrator Associate"
    issuer: "Microsoft"
    year: "2026"

projects:
  - title: "Automation Suite - $430k Saved"
    description: "Architected multi-platform Python and Go tooling to automate provisioning, validation, and disaster recovery across server, network, and voice environments. Built internal apps and API-driven tooling that turned manual, error-prone processes into repeatable, code-driven workflows - the same discipline now applied to Azure IaC."
  - title: "Data Centre SDN Migration (Infrastructure-as-Code)"
    description: "Migrated a data centre from traditional to fully software-defined architecture using Terraform-driven Cisco ACI, version-controlled through GitLab CI/CD. Paired with true out-of-band management for zero-downtime cutover. A ground-up IaC transformation, not a lift-and-shift."
  - title: "Wired / Wireless NAC (802.1X) - Zero Trust at Scale"
    description: "Designed and implemented network access control across 5 major hospitals, 50+ remote clinics, and Australia's largest private defence contractor using Cisco ISE - securing infrastructure to ISO 27001 standards. This is the identity-and-access layer most cloud engineers never touch, and it's what makes my Zero Trust designs credible end-to-end, not just at the IAM layer."
  - title: "Campus Switch Replacement - Automated at Scale"
    description: "Replaced 800+ edge switches and 8 campus core switches using Cisco DNAC Plug and Play, in under 12 months - a zero-touch provisioning model applied to physical infrastructure, the same principle behind IaC applied to cloud."
  - title: "NEC → Cisco VOIP Migration"
    description: "Led full migration of 13,000 endpoints from legacy telephony to Cisco VOIP, including cutover planning, training, and validation at enterprise scale - proof of large-scale program delivery, not just scripting."
  - title: "Webex Contact Centre Migration"
    description: "End-to-end design and delivery for 23 teams at Monash Health, migrating V1 → V2 with bespoke training for 300+ staff and zero service disruption."

# awards:
#   - title: "Employee of the Year"
#     issuer: "Tech Solutions Inc."
#     year: "2021"
#   - title: "Innovation Award"
#     issuer: "Digital Innovations LLC"
#     year: "2019"

# publications:
#   - title: "Optimizing React Performance"
#     publication: "Journal of Web Development"
#     date: "March 2022"
#   - title: "Microservices Architecture Patterns"
#     publication: "Software Engineering Quarterly"
#     date: "October 2020"

# hobbies:
#   - "Open Source"
#   - "Photography"
#   - "Hiking"
#   - "Chess"
#   - "Travel"

# references:
#   - name: "Jane Smith"
#     position: "CTO, Tech Solutions Inc."
#     email: "jane.smith@techsolutions.com"
#     phone: "(123) 456-7891"
#   - name: "Michael Johnson"
#     position: "Engineering Manager, Digital Innovations LLC"
#     email: "michael.johnson@digitalinnovations.com"
#     phone: "(123) 456-7892"

# in content/_index.md front matter

# metrics:
#   - label: "Performance Improvement"
#     value: "40%"
#   - label: "Cost Reduction"
#     value: "30%"
#   - label: "Code Coverage Increase"
#     value: "65%"
#   - label: "Deployment Speedup"
#     value: "60%"

# courses:
#   - title: "Advanced React Patterns"
#     provider: "Frontend Masters"
#     duration: "4h 30m"
#   - title: "AWS Solutions Architect"
#     provider: "Udemy"
#     duration: "12h"
#   - title: "Kubernetes Deep Dive"
#     provider: "Pluralsight"
#     duration: "8h"

# languages_spoken:
#   - language: "English"
#     level: "Native"

# blog:
#   - title: "Improving React Performance"
#     url: "https://example.com/improving-react-performance"
#     date: "March 15, 2022"
#   - title: "Microservices Best Practices"
#     url: "https://example.com/microservices-best-practices"
#     date: "October 10, 2020"
#   - title: "Building CI/CD Pipelines with GitHub Actions"
#     url: "https://example.com/ci-cd-github-actions"
#     date: "July 5, 2021"

---