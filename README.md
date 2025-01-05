# **Threat Model Examples**

This repository contains various threat model examples for different technologies and systems. These resources provide illustrative examples of threat models across different domains, helping security professionals, developers, and researchers better understand how threat modeling can be applied effectively to address security risks.

> This project was established to give an idea of how the end results of a threat model might look like. With so many guidelines and methodologies available, we noticed that having concrete examples would help the community better understand what 'good' looks like.

---

## 🛡️ **1. Web & API Security**

- **OAuth 2.0**  
   - [OAuth 2.0 Threat Model (RFC 6819)](https://datatracker.ietf.org/doc/html/rfc6819)

- **SSL**  
   - ![SSL Threat Model Diagram](https://www.ssllabs.com/downloads/SSL_Threat_Model.png)

- **DNSSEC, DoT, and DoH**  
   - [DNSSEC, DoT, and DoH Threat Model](https://www.netmeister.org/blog/doh-dot-dnssec.html)

- **Web Application**  
   - [OWASP Threat Modeling Process](https://owasp.org/www-community/Threat_Modeling_Process)

---

## ☁️ **2. Cloud & Container Security**
> Cloud and container environments are essential for scalable infrastructure but are also prime targets for attacks. The following examples showcase key threat models in these areas.

- **Kubernetes**  
   - [Kubernetes Threat Model - CNCF Financial User Group](https://github.com/cncf/financial-user-group/tree/main/projects/k8s-threat-model)  
   - [Kubernetes Hardening Guidance (DoD)](https://media.defense.gov/2022/Aug/29/2003066362/-1/-1/0/CTR_KUBERNETES_HARDENING_GUIDANCE_1.2_20220829.PDF) (Page 5)  
   - [Kubernetes Threat Model - CloudSecDocs](https://cloudsecdocs.com/containers/theory/threats/k8s_threat_model/)  
   - [A Deep Dive Into Kubernetes Threat Modeling - Trend Micro](https://www.trendmicro.com/vinfo/us/security/news/security-technology/a-deep-dive-into-kubernetes-threat-modeling)

- **Docker**  
   - [Docker Threat Model - CloudSecDocs](https://cloudsecdocs.com/container_security/theory/threats/docker_threat_model/)

- **AWS Fargate**  
   - [AWS Fargate Threat Modeling - Sysdig](https://sysdig.com/blog/ecs-fargate-threat-modeling/)

- **Amazon S3**  
   - [Amazon S3 Threat Model - TrustonCloud](https://controlcatalog.trustoncloud.com/dashboard/aws/s3#Data%20Flow%20Diagram)

- **Google Cloud Storage**  
   - [Google Cloud Storage Threat Model - NCC Group](https://www.nccgroup.com/us/research-blog/threat-modelling-cloud-platform-services-by-example-google-cloud-storage/)

---

## 📱 **3. Mobile & IoT Security**
> Mobile and IoT devices are integral to modern systems, but they introduce unique security challenges. These examples demonstrate approaches to mitigate such risks.

- **Mobile Applications**  
   - [Securing Mobile Applications Guide - Synopsys](https://www.synopsys.com/content/dam/synopsys/sig-assets/ebooks/developers-guide-securing-mobile-applications-threat-modeling.pdf)  
   - [Mobile Application Threat Modeling - TeamCISO](https://teamciso.com/2016/06/threat-modeling-a-mobile-application.html)

- **IoT Authentication**  
   - [IoT Authentication Threat Modeling - SAFECode](https://safecode.org/wp-content/uploads/2017/05/SAFECode_TM_Whitepaper.pdf) (Page 18)

- **IoT Devices**  
   - [IoT Devices Security Threat Models - PSA Certified](https://www.psacertified.org/development-resources/building-in-security/threat-models/)

- **Smart Home**  
   - [Smart Home Threat Model - GitHub](https://github.com/kkredit/smart-home-threat-model)

- **IoT Supply Chain**  
   - [Supply Chain for IoT Threat Model - ENISA](https://www.enisa.europa.eu/publications/guidelines-for-securing-the-internet-of-things)

---

## 🏢 **4. Enterprise Security**

- **PCI DSS**  
   - [PCI Threat Model - Adam Shostack](https://shostack.org/files/papers/A_PCI_Threat_Model_2020.pdf)

- **Password Storage Module (PSM)**  
   - [Secure Password Storage - OWASP](https://owasp.org/www-pdf-archive//Secure_Password_Storage.pdf)

- **Certificate Transparency**  
   - [Certificate Transparency Threat Analysis](https://datatracker.ietf.org/doc/html/draft-ietf-trans-threat-analysis-16)

- **Account Takeover (ATO)**  
   - [ATO Threat Model Checklist](https://raw.githubusercontent.com/magoo/ato-checklist/master/model.svg)

- **Password Managers**  
   - [Password Manager Threat Model - Stanford](https://crypto.stanford.edu/~dabo/pubs/papers/pwdmgrBrowser.pdf) (Page 5)

---

📢 **Contributing**
> We welcome contributions from the community! Open a pull request to share your expertise.

📝 **License**
> This repository is licensed under the MIT License. See the **[LICENSE](LICENSE)** file for more details.
