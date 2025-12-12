---
title: "Curriculum Vitae — Principal Engineer / Architect"
author: "Joseph Wortmann"
date: "`date +%Y-%m-%d`"
geometry: margin=1in
fontsize: 11pt
mainfont: "Helvetica"
sansfont: "Helvetica"
monofont: "Menlo"
colorlinks: true
linkcolor: blue
urlcolor: blue
---
# Joseph Wortmann

**Location:** Milton, Florida, United States  
**Email:** joseph.wortmann@gmail.com
**Mobile:** +1 (205) 612-3826
**LinkedIn:** https://www.linkedin.com/in/josephwortmann  

---

## Technical Summary

Principal Engineer / Architect with 30+ years of experience designing and delivering large-scale, mission-critical systems in healthcare, integration platforms, developer tooling, and secure software supply chains. Expert in cloud-native architectures, serverless systems, WASM-based plugin models, Model Context Protocol (MCP) design, and reusable platform components. Combines deep hands-on engineering skill with strong architectural intuition, enabling rapid prototyping, high-leverage design decisions, and large systemic improvements.

---

## Core Technical Competencies

- **Languages:** Rust, Go, Python, Objective-C, C-family, SQL  
- **Cloud:** AWS (Lambda, API Gateway, S3, DynamoDB, SNS/SQS, ECS/Fargate, CloudWatch, Cognito)  
- **Architecture:** Serverless, event-driven systems, microservices, WASM plugin architectures, MCP-based tooling ecosystems  
- **Infra/DevOps:** Terraform/OpenTofu, Packer, Linux, containerization (Docker), CI/CD automation  
- **Security:** Software supply-chain hardening, artifact signature & provenance, CVE/CVSS risk gating, OIDC/OAuth2, secure multi-tenancy  
- **Domains:** Healthcare integration (HL7, FHIR, imaging/DICOM), clinical workflow systems, SaaS platforms, high-availability enterprise systems  
- **Practices:** Systems design, performance engineering, developer experience (DX), high-leverage library design, refactoring and modernization

---

# Selected Technical Projects

### **ReliQuery — Secure Python Package Index & Artifact Firewall (2024–Present)**
- Designed and built a private PyPI-compatible index with multi-tenant isolation and secure artifact storage.  
- Implemented upstream proxying with real-time risk evaluation of OSS packages.  
- Added CVSS-based enforceable security policies and curated allow/deny lists controlling ingestion of external dependencies.  
- Built deterministic indexing, version metadata handling, and signature/parsing tooling in Rust.  
- Created high-performance publishing, retrieval, and caching workflows supporting millions of artifacts.

### **EchoStream iPaaS — Cloud-Native Integration Platform (2022–Present)**
- Designed a Python-based integration execution environment where integrations are treated as first-class assets.  
- Built a composable framework for event-driven and scheduled integrations with formal lifecycle management.  
- Implemented IaC provisioning (OpenTofu/Terraform) supporting multi-tenant workloads and environment isolation.  
- Established patterns for secure connector development, retries, observability, and multi-step orchestration.

### **OrthoCheck — Bayesian Network Clinical Decision Support (2024–2025)**
- Architected a Bayesian Network engine for orthopedic clinical assessment.  
- Implemented evidence propagation and inference logic using AWS serverless components.  
- Designed decision graphs and question-selection heuristics to optimize clinical workflows.  
- Integrated BN outputs with provider profiles and operational analytics.

### **MCP Tooling Ecosystem — Secure WASM Plugin Architecture (2023–Present)**
*(personal + professional experimentation)*  
- Designed and implemented WASM plugin execution models supporting multiple languages (Rust, Go, Python).  
- Built input/output caching, host function linking, byte-reuse frameworks, and safe memory handling for high-performance plugin invocation.  
- Designed secure host capabilities, including token exchange, controlled resource access, and tooling discovery patterns.

### **Healthcare Enterprise Platforms (1998–Present)**
Across Emageon, Awarix, IllumiCare, and YourCareUniverse:  
- Led architecture of large-scale clinical systems including imaging, workflow optimization, event-driven dashboards, and cloud-based patient engagement solutions.  
- Designed HL7 engines, clinical integration pipelines, and EHR-adjacent systems requiring high reliability and compliance.

---

# Experience

## Co-Founder, CEO, CTO — ReliQuery.io  
**ReliQuery.io** · Feb 2024 – Present

- Architected a secure, multi-tenant Python package index with full PyPI compatibility.  
- Designed an artifact firewall enabling organizations to control OSS ingestion through policy-based risk controls.  
- Implemented upstream proxying and deterministic caching layers for high-speed artifact distribution.  
- Built Rust-based indexing and metadata pipelines supporting reproducible builds and secure publishing workflows.  
- Designed fine-grained authorization and auditability for enterprise-grade compliance.

---

## Co-Founder — EchoStream  
**EchoStream** · Jan 2022 – Present

- Designed the core integration runtime using Python, providing a developer-friendly framework for building cloud-native integrations.  
- Established infrastructure patterns allowing automated provisioning of tenant environments (OpenTofu/Terraform).  
- Implemented observability, audit logging, and operational tooling supporting large integration catalogs.  
- Built a connector architecture allowing teams to create reusable, composable integration components.  

---

## Co-Owner, CTO, CIO — QuiNovas  
**QuiNovas** · Jul 2017 – Present

- Architected cloud-native solutions across healthcare and enterprise clients, emphasizing serverless and event-driven systems.  
- Designed reference architectures and reusable libraries accelerating client delivery across multiple teams.  
- Led modernization efforts transitioning monolithic applications to cloud-native microservice and serverless platforms.  
- Implemented IaC, CI/CD, and dev-automation frameworks for engineering organizations.

---

## Chief Technology Officer — Clinekt Health  
**Clinekt Health** · Nov 2024 – May 2025

- Architected OrthoCheck, a Bayesian Network–powered orthopedic assessment system on AWS.  
- Implemented serverless decision-inference pipelines integrated with patient and provider data.  
- Created structured data models for provider profiles combining clinical, financial, and workflow metadata.  
- Guided a remote development team through architectural improvements and delivery acceleration.

---

## Chief Technology Officer — IllumiCare, Inc.  
**IllumiCare, Inc.** · Jan 2016 – May 2017

- Architected real-time, EHR-integrated decision support tools embedded directly into clinician workflows.  
- Implemented secure, compliant data pipelines for sensitive clinical and financial data.  
- Led systems engineering for high-availability deployments in hospital environments.

---

## Vice President, Operations — YourCareUniverse  
**YourCareUniverse (MEDHOST)** · Sep 2013 – Dec 2015

- Directed technical operations for cloud-based patient engagement and integration products.  
- Collaborated with engineering teams to ensure reliable data ingestion and interoperability.  
- Guided architectural decisions improving performance, stability, and scalability.

---

## Director of Sales, Central Region — Acuo Technologies  
**Acuo Technologies** · Feb 2011 – Sep 2013

- Leveraged deep technical expertise in clinical imaging and DICOM architectures to support enterprise sales.  
- Helped customers evaluate storage, migration, and interoperability strategies for large-scale medical imaging systems.

---

## Earlier Engineering, Architecture, and Founder Roles

- **Managing Member & Founder — The Iron Door Company** (2007–2013)  
- **Owner — Cogitavi** (2008–2012)  
- **Software Engineer — Acuitec** (2010–2011)  
- **President — Zoobal** (2010)  
- **SVP & Co-Founder — ComFrame Software Corporation** (2006–2007)  
- **Senior Vice President — Awarix** (2005–2006)  
- **Vice President & Co-Founder — Emageon** (1998–2004)  
- **Software Architect & Co-Founder — ComFrame** (1997–1998)  
- **Director of Software Development — ComFrame** (1997)  
- **Software Engineer — IDEAS Inc.** (1995–1997)  
- **Software Engineer — BillGood Marketing** (1994–1995)  
- **Systems Engineer — EDS** (1991–1994)

(Deep technical detail for early roles available on request.)

---

# Education

- **Georgia Institute of Technology** — Executive MS, Management of Technology (2005–2006)  
- **University of Alabama at Birmingham** — MS, Computer Science (1999–2002)  
- **United States Military Academy at West Point** — BS, top 5% of class (1987–1991)

---

# Additional Technical Interests

- MCP-based tool ecosystems and secure resource abstractions  
- WASM sandboxing, plugin systems, and host capability models  
- Secure CI/CD and attestations (SBOMs, signatures, provenance)  
- Streaming and event-driven design patterns  
- Clinical decision support, probabilistic models, Bayesian inference
