# **Threat Model Examples**

This repository contains various threat model examples for different technologies and systems. These resources can help security professionals, developers, and researchers understand the security risks and best practices for mitigating potential threats in a variety of platforms.

💡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🌐 **1. Web & API Security**

- **OAuth 2.0**  
  [OAuth 2.0 Threat Model (RFC 6819)](https://datatracker.ietf.org/doc/html/rfc6819)

- **SSL**  
  ![SSL Threat Model Diagram](https://www.ssllabs.com/downloads/SSL_Threat_Model.png)

- **DNSSEC, DoT, and DoH**  
  [DNSSEC, DoT, and DoH Threat Model](https://www.netmeister.org/blog/doh-dot-dnssec.html)

- **Web Application**  
  [OWASP Threat Modeling Process](https://owasp.org/www-community/Threat_Modeling_Process)

💡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## ☁️ **2. Cloud & Container Security**

- **Kubernetes**
   - [Kubernetes Threat Model - CNCF Financial User Group](https://github.com/cncf/financial-user-group/tree/main/projects/k8s-threat-model)
   - [Kubernetes Hardening Guidance (DoD)](https://media.defense.gov/2022/Aug/29/2003066362/-1/-1/0/CTR_KUBERNETES_HARDENING_GUIDANCE_1.2_20220829.PDF) (Page 5)
   - [Kubernetes Threat Model - CloudSecDocs](https://cloudsecdocs.com/containers/theory/threats/k8s_threat_model/)
   - [Kubernetes Threat Modeling - Accuknox](https://github.com/accuknox/k8sthreatmodeling)
   - [A Deep Dive Into Kubernetes Threat Modeling - Trend Micro](https://www.trendmicro.com/vinfo/us/security/news/security-technology/a-deep-dive-into-kubernetes-threat-modeling)
   - [Kubernetes Threat Modeling - GitHub](https://github.com/accuknox/k8sthreatmodeling)

- **Docker**
   - [Docker Threat Model - CloudSecDocs](https://cloudsecdocs.com/container_security/theory/threats/docker_threat_model/)
   - [Docker Threat Modeling and Top 10 - OWASP Foundation](https://owasp.org)

- **AWS Fargate**  
   [AWS Fargate Threat Modeling - Sysdig](https://sysdig.com/blog/ecs-fargate-threat-modeling/)

- **Amazon S3**  
   [Amazon S3 Threat Model - TrustonCloud](https://controlcatalog.trustoncloud.com/dashboard/aws/s3#Data%20Flow%20Diagram)

💡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 📱 **3. Mobile & IoT Security**

- **Mobile Applications**
   - [Securing Mobile Applications Guide - Synopsys](https://www.synopsys.com/content/dam/synopsys/sig-assets/ebooks/developers-guide-securing-mobile-applications-threat-modeling.pdf)
   - [Mobile Application Threat Modeling - TeamCISO](https://teamciso.com/2016/06/threat-modeling-a-mobile-application.html)

- **IoT Authentication**  
   [IoT Authentication Threat Modeling - SAFECode](https://safecode.org/wp-content/uploads/2017/05/SAFECode_TM_Whitepaper.pdf) (Page 18)

- **IoT Devices**  
   [IoT Devices Security Threat Models - PSA Certified](https://www.psacertified.org/development-resources/building-in-security/threat-models/)

- **Smart Home**  
   [Smart Home Threat Model - GitHub](https://github.com/kkredit/smart-home-threat-model)

💡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🏢 **4. Enterprise Security**

- **PCI DSS**  
   [PCI Threat Model - Adam Shostack](https://shostack.org/files/papers/A_PCI_Threat_Model_2020.pdf)

- **Password Storage Module (PSM)**  
   [Secure Password Storage - OWASP](https://owasp.org/www-pdf-archive//Secure_Password_Storage.pdf)

- **Certificate Transparency**  
   [Certificate Transparency Threat Analysis](https://datatracker.ietf.org/doc/html/draft-ietf-trans-threat-analysis-16)

- **Account Takeover (ATO)**  
   [ATO Threat Model Checklist](https://raw.githubusercontent.com/magoo/ato-checklist/master/model.svg)

- **Password Managers**  
   [Password Manager Threat Model - Stanford](https://crypto.stanford.edu/~dabo/pubs/papers/pwdmgrBrowser.pdf) (Page 5)

💡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🛠️ **5. Specialized Systems & Technologies**

- **AMPS and SNAP Medical Systems**  
   [MITRE Playbook for Threat Modeling Medical Devices](https://www.mitre.org/sites/default/files/publications/Playbook-for-Threat-Modeling-Medical-Devices.pdf) (Pages 3 and 49)

- **ROS 2 Robotic System**
   - [ROS 2 Threat Model](https://design.ros2.org/articles/ros2_threat_model.html)
   - [MARA Threat Model - GitHub](https://github.com/AcutronicRobotics/MARA_threat_model)

- **Web-based User Feedback System**  
   [SAFECode Threat Modeling Whitepaper](https://safecode.org/wp-content/uploads/2017/05/SAFECode_TM_Whitepaper.pdf) (Page 16)

- **Future E-voting System**  
   [Swiss Post E-voting Vulnerabilities](https://www.reversemode.com/2022/01/finding-vulnerabilities-in-swiss-posts.html?m=1#AttackSurface)

- **Supply Chain**  
   [Supply Chain Threat Modeling Video](https://www.youtube.com/watch?v=EHx_-u3JH8Q)

💡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🌍 **6. Security for Remote & Distributed Work**

- **Remote Work**  
   [Remote Work Threat Modeling - FireEye](https://www.fireeye.com/blog/executive-perspective/2020/03/remote-work-in-an-age-of-covid-19-threat-modeling-the-risks.html)

💡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🔄 **7. CI/CD & Firmware Security**

- **CI/CD Pipeline**
   - [CI/CD Threat Matrix - GitHub](https://github.com/rung/threat-matrix-cicd)
   - [CI/CD Security Risks - GitHub](https://github.com/cider-security-research/top-10-cicd-security-risks)

- **Firmware**
   - [Firmware Threat Modeling Template - GitHub](https://github.com/bpoudel7/Firmware-Threat-Modeling-Template)
   - [Firmware Threat Model - TrustedFirmware](https://tf-m-user-guide.trustedfirmware.org/docs/security/threat_models/generic_threat_model.html)

💡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📢 ### **Contributing**
Feel free to contribute additional threat model examples or improvements. Open a pull request to share your work with the community!

### **License**
This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

💡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
