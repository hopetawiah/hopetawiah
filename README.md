# Hi, I'm Hope Akpozah Tawiah 👋

### Cybersecurity Researcher | IT Systems & Security Professional | Software Developer

I am an **Information Technology and Cybersecurity researcher** with interests in **Zero Trust Architecture, Artificial Intelligence for Cybersecurity, Federated Learning, IoT Security, Intrusion Detection, Identity and Access Management, Network Security, Cloud Security, and Cybersecurity Resilience**.

My academic and technical work combines **cybersecurity research, machine learning, secure network and systems engineering, software development, data analysis, and practical security implementation**.

My research progression spans secure corporate network infrastructure, distributed machine-learning security, Zero Trust architecture, and the development of secure production information systems.

I am particularly interested in developing **intelligent, adaptive, explainable, and resilient cybersecurity architectures for distributed, cloud, IoT, edge, and multi-cloud environments**.

---

# 🔬 Research Interests

- Zero Trust Architecture
- Artificial Intelligence for Cybersecurity
- Federated Learning
- IoT Security
- Machine-Learning Intrusion Detection
- Identity and Access Management
- Adaptive Access Control
- Risk-Based Access Control
- Role-Based Access Control
- Network Security
- Cloud and Multi-Cloud Security
- Cybersecurity Resilience
- Secure Distributed Systems
- Digital Forensics
- Explainable AI for Security
- Continuous Authentication and Verification
- Security Architecture Evaluation
- Behaviour-Based Security Analytics

---

# 🎓 Graduate Research

## 🔐 MPhil Information Technology — Zero Trust Security Architecture

**Ghana Communication Technology University (GCTU)**  
**Faculty of Computing and Information Systems**

### Research Topic

**A Simulation-Based Analysis of Perimeter-Based and Zero Trust Security Architecture for Enhancing Cybersecurity Resilience in Higher Education Institutions**

This research evaluates **Perimeter-Based Security Architecture and Zero Trust Security Architecture** through a controlled cybersecurity simulation using selected **CICIDS2017** network-traffic data and machine-learning-based intrusion detection.

The experimental design separates a common **Random Forest intrusion-detection engine** from an architecture-specific decision layer.

- **Perimeter-Based Security threshold:** `0.50`
- **Zero Trust Security threshold:** `0.35`

The Zero Trust condition represents a more risk-sensitive simulated decision policy intended to reduce missed malicious activity.

### Research Focus

- Zero Trust Architecture
- Perimeter-Based Security
- Cybersecurity Resilience
- Machine-Learning Intrusion Detection
- Risk-Based Access Control
- Continuous Verification
- Least-Privilege Access
- Network Segmentation
- Security Architecture Evaluation
- Threshold Sensitivity Analysis
- Precision–Recall Trade-offs

### Technologies & Dataset

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Random Forest
- CICIDS2017
- Google Colab

### Selected Experimental Results

| Metric | Perimeter-Based | Zero Trust |
|---|---:|---:|
| Breach Success Rate | 0.2573% | **0.1601%** |
| Detection Time | 530.76 ms | **145.44 ms** |
| Containment Effectiveness | 99.7427% | **99.8399%** |
| Attack Spread | 12.0 nodes | **3.5 nodes** |
| Accuracy | 0.9993 | 0.9993 |
| Precision | **0.9988** | 0.9977 |
| Recall | 0.9974 | **0.9984** |
| F1-score | **0.9981** | 0.9980 |

The study also includes:

- Five-model machine-learning comparison
- Threshold-sensitivity analysis
- Confusion-matrix evaluation
- Precision–recall trade-off analysis
- Architecture-specific decision modelling
- Explicit distinction between classifier-derived metrics and simulation scenario parameters

🔗 **Research Repository:**  
[zero-trust-security-architecture](https://github.com/hopetawiah/zero-trust-security-architecture)

---

## 🌐 MSc Digital Forensics and Cyber Security — Secure Federated Learning for IoT

**Ghana Institute of Management and Public Administration (GIMPA)**

### Research Topic

**A Secure and Communication-Efficient Federated Learning Framework for IoT in Resource-Constrained Environments**

This research develops and evaluates **ACES-FL — Adaptive, Communication-Efficient and Secure Federated Learning**, a federated-learning framework designed for cybersecurity and intrusion detection in heterogeneous and resource-constrained IoT environments.

The research combines **distributed machine learning, IoT intrusion detection, communication efficiency, resource-aware client participation, model security, and malicious-client defence**.

### Research Focus

- Federated Learning
- IoT Cybersecurity
- IoT Intrusion Detection
- Communication-Efficient Distributed Learning
- Resource-Constrained Environments
- Resource-Aware Client Selection
- Fairness-Aware Federated Participation
- Adaptive Communication
- Model Compression
- Model Poisoning
- Malicious-Client Detection
- Robust Federated Learning
- Distributed Machine Learning

### Technologies

- Python
- PyTorch
- Flower
- Ray
- Scikit-learn
- Pandas
- NumPy
- UNSW-NB15

### ACES-FL Components

- Resource-aware client selection
- Fairness-aware client participation
- Adaptive communication strategies
- FP32 / FP16 / INT8 communication modes
- Federated intrusion detection
- Sign-flip model-poisoning experiments
- Malicious-update screening
- Robust aggregation
- Communication-cost evaluation
- Federated client simulation
- Experimental result generation

🔗 **Research Repository:**  
[secure-federated-learning-iot](https://github.com/hopetawiah/secure-federated-learning-iot)

---

# 🎓 Undergraduate Research & Infrastructure Engineering

## 🖧 BSc Information Technology — Secure Corporate Network & System Infrastructure

**Ghana Communication Technology University (GCTU)**  
**September 2024**

### Project

**Design and Implementation of a Secure Corporate Network and System Infrastructure**

**Case Study:** Ghana Education Trust Fund (GETFund)

### Project Team

- Hope Akpozah Tawiah
- Robert Agbey
- Gifty Mensah

**Supervisor:** Mr. Moses Aggor

### Project Overview

This group project focused on the **design and implementation of a secure and scalable corporate network and system infrastructure**.

The project assessed weaknesses within an existing organizational network environment and proposed an improved architecture integrating **network segmentation, firewall protection, centralized identity management, domain-based authentication, DNS, DHCP, access control, backup planning, and business-continuity considerations**.

The project followed the **PPDIOO methodology**:

**Prepare → Plan → Design → Implement → Operate → Optimize**

### Project Objectives

- Assess the existing corporate network infrastructure
- Identify network and security weaknesses
- Design a secure and scalable network architecture
- Introduce logical network segmentation
- Strengthen centralized identity management
- Implement network and domain services
- Improve network manageability
- Test connectivity and validate the new infrastructure
- Incorporate backup and business-continuity considerations

### Secure Network Architecture

The designed environment incorporated:

- ISP connectivity
- Cisco routing
- Firewall protection
- Core switching
- Access switching
- Departmental VLAN segmentation
- Windows Server infrastructure
- Active Directory Domain Services
- DNS
- DHCP
- Centralized authentication
- Role-Based Access Control
- Backup and recovery planning

### VLAN Segmentation

The network was logically divided into organizational VLANs:

- **VLAN 10 — Administrators**
- **VLAN 20 — Principal Administrators**
- **VLAN 30 — Senior Administrators**
- **VLAN 40 — Assistant Administrators**
- **VLAN 50 — IT Unit**

Network segmentation was used to improve traffic organization, isolate departmental systems, improve manageability, and reduce the possible spread of security incidents.

### Identity & Access Management

The Windows Server environment incorporated:

- Active Directory Domain Services
- Domain Controller configuration
- Organizational Units
- Security groups
- User-account administration
- Domain-based authentication
- Role-Based Access Control
- Centralized user management
- Centralized computer management
- Client computers joined to the domain

### Network Services

The implementation included:

- DNS configuration
- Forward lookup zones
- Reverse lookup zones
- DHCP configuration
- IP-address allocation
- Domain Controller deployment
- Client-domain integration
- User-account creation
- Domain-user authentication
- Network connectivity testing

### Security & Infrastructure Features

- VLAN network segmentation
- Firewall-based traffic filtering
- Role-Based Access Control
- Centralized authentication
- Active Directory administration
- Departmental traffic isolation
- Secure routing architecture
- Structured IP addressing
- Network monitoring considerations
- Backup planning
- Recovery planning
- Business-continuity planning

### Technologies & Platforms

- Cisco Packet Tracer
- Cisco Routers
- Cisco Switches
- VLANs
- TCP/IP
- Windows Server
- Active Directory Domain Services
- DNS
- DHCP
- RBAC
- Firewall Technologies
- Network Address Translation
- Windows Client Systems

### Implementation Evidence

The repository documents:

- Existing network architecture
- Proposed secure network architecture
- Network topology
- VLAN configuration
- Switch-port allocation
- IP addressing and subnet design
- Connectivity testing
- Active Directory deployment
- DNS configuration
- DHCP configuration
- Domain-controller promotion
- User-account creation
- Client computers joining the domain
- Domain-based user authentication

### Project Outcome

The project demonstrated a **layered and scalable corporate network architecture** integrating segmentation, firewall protection, centralized identity management, DNS, DHCP, domain administration, and structured access control.

This undergraduate work established a technical foundation for my later interests in:

- Zero Trust Architecture
- Identity and Access Management
- Network Segmentation
- Risk-Based Access Control
- Cybersecurity Resilience
- Secure Distributed Systems
- Secure Information Systems

🔗 **Project Repository:**  
[secure-corporate-network-infrastructure](https://github.com/hopetawiah/secure-corporate-network-infrastructure)

---

# 🚀 Production Systems Engineering

## 🏫 Dunamis Crown Academy School ERP

A production **School Enterprise Resource Planning and Management Information System** designed and developed for **Dunamis Crown Academy, Ghana**.

The platform integrates academic management, financial administration, communication, analytics, cybersecurity controls, reporting, backup and recovery, access governance, and secure system administration.

### Academic & Administrative Modules

- Student Management
- Admission Forms
- Academic Years and Terms
- Student Promotion
- Attendance
- Attendance Follow-up
- Subjects and Classes
- Exams and Report Cards
- School Calendar
- Staff and User Management

### Financial Modules

- Term Fee Accounts
- Scholarship Management
- Fee Structures
- Daily Feeding
- Expenses
- Financial Reports
- Cashier Closing

### Communication

- Announcements
- Notifications
- SMS and Messages
- SMS Configuration

### Security & Administration

- Security Center
- Audit Logs
- Role Permissions
- Staff and User Accounts
- Delete and Restore Centre
- Backup and Recovery
- System Health Monitoring
- Secure Administrative Controls

### Cybersecurity Engineering Features

- Role-Based Access Control
- Granular role-permission matrix
- TOTP two-factor authentication
- Account lockout controls
- Login-history monitoring
- Security-sensitive audit logging
- Privileged-action traceability
- CSRF protection
- Request rate limiting
- Secure session and cookie controls
- HTTP security headers
- Delete-and-restore controls
- Database backup and recovery
- SHA-256 backup-integrity validation
- System-health monitoring

### Analytics & Reporting

- AI-assisted executive analytics
- Attendance analytics
- Enrollment monitoring
- Financial-performance monitoring
- High-risk student indicators
- PDF reporting
- Excel reporting
- Report-card generation
- Financial reporting

### Technologies

- Python
- Flask
- PostgreSQL
- SQLAlchemy
- HTML
- CSS
- JavaScript
- Bootstrap
- Docker
- Git
- GitHub
- Linux
- Render

🔗 **Technical Portfolio:**  
[dunamis-school-erp-portfolio](https://github.com/hopetawiah/dunamis-school-erp-portfolio)

🌐 **Live System:**  
https://portal.dunamiscrownacademy.com/

---

# 🛡️ Academic & Technical Progression

My work reflects a progression from foundational network and infrastructure security toward intelligent and adaptive cybersecurity architectures.

## BSc — Secure Corporate Network Infrastructure

**Foundation in:**

- Network segmentation
- VLANs
- Firewalls
- Active Directory
- DNS
- DHCP
- RBAC
- Enterprise networking

⬇️

## MSc — Secure Federated Learning for IoT

**Development into:**

- Federated learning
- IoT intrusion detection
- Resource-aware distributed learning
- Model security
- Communication efficiency
- Adversarial machine learning

⬇️

## MPhil — Zero Trust Security Architecture

**Research focus on:**

- Zero Trust
- Continuous verification
- Risk-sensitive decisions
- Machine-learning intrusion detection
- Cybersecurity resilience
- Adaptive security architecture

⬇️

## Production Engineering — Dunamis School ERP

**Practical implementation of:**

- Secure software engineering
- RBAC
- Two-factor authentication
- Audit logging
- Backup and recovery
- Security administration
- Production deployment

---

# 💻 Technical Skills

## Cybersecurity

- Zero Trust Architecture
- Network Security
- Intrusion Detection
- Identity and Access Management
- Risk-Based Access Control
- Role-Based Access Control
- Cybersecurity Risk Assessment
- Vulnerability Assessment
- Security Architecture
- Security Monitoring
- Audit Logging
- Digital Forensics
- SIEM Fundamentals
- Threat Analysis
- Cybersecurity Resilience

## Artificial Intelligence & Machine Learning

- PyTorch
- Scikit-learn
- Federated Learning
- Random Forest
- Machine Learning
- Intrusion Detection Models
- Model Evaluation
- Adversarial Federated Learning
- Explainable AI
- Experimental Evaluation
- Threshold Analysis

## Networking & Infrastructure

- Cisco Packet Tracer
- TCP/IP
- VLANs
- Routing
- Switching
- Firewalls
- DNS
- DHCP
- Active Directory
- Windows Server
- Network Segmentation
- Domain Administration
- Network Troubleshooting
- NAT

## Programming & Data

- Python
- SQL
- Java
- JavaScript
- HTML
- CSS
- Pandas
- NumPy
- Matplotlib
- Data Analysis
- Data Preprocessing
- Data Visualization

## Systems & Development

- Flask
- PostgreSQL
- SQLAlchemy
- Bootstrap
- Docker
- Git
- GitHub
- Linux
- Windows
- Render
- Database Administration
- Systems Administration

---

# 📜 Professional Certifications

## Google Cybersecurity Professional Certificate

**Google / Coursera — May 2026**

Areas covered include:

- Cybersecurity foundations
- Linux
- Python
- SQL
- SIEM concepts
- Intrusion detection
- Threat analysis
- Vulnerability management
- Security monitoring
- Incident response
- Cybersecurity risk mitigation

---

## Google Data Analytics Professional Certificate

**Google / Coursera — June 2026**

Areas covered include:

- Data preparation
- Data cleaning
- SQL
- Spreadsheets
- Data analysis
- Data visualization
- Tableau
- Analytical problem solving
- Data-driven decision making

---

# 🎯 PhD Research Direction

My doctoral research interests lie at the intersection of:

**Artificial Intelligence + Zero Trust + Adaptive Access Control + Cloud Security + Intrusion Detection**

I am particularly interested in designing intelligent security architectures capable of continuously evaluating:

- User identity
- Device posture
- User behaviour
- Network context
- Authentication context
- Access patterns
- Threat intelligence
- Security risk

Potential doctoral research areas include:

- AI-Driven Zero Trust Architecture
- Adaptive and Risk-Based Access Control
- Intelligent Identity and Access Management
- Explainable AI for Security Decisions
- Multi-Cloud Zero Trust Security
- Behaviour-Based Security Analytics
- Federated Learning for Distributed Cybersecurity
- AI-Enhanced Intrusion Detection
- Continuous Authentication and Verification
- Secure IoT and Edge Computing
- Cybersecurity Resilience
- Adaptive Trust Evaluation

My long-term goal is to contribute to the development of **adaptive, explainable, intelligent, and resilient cybersecurity architectures for complex distributed environments**.

---

# 🤝 Research Collaboration

I am interested in collaborating on research involving:

- Zero Trust Security
- Artificial Intelligence for Cybersecurity
- Federated Learning
- IoT Cybersecurity
- Intrusion Detection
- Network Security
- Cloud and Multi-Cloud Security
- Identity and Access Management
- Adaptive Access Control
- Explainable AI
- Digital Forensics
- Secure Distributed Systems
- Cybersecurity Resilience

I am also interested in collaboration on **research papers, experimental cybersecurity systems, open-source security projects, and doctoral research initiatives**.

---

# 📌 Featured Research & Projects

## 🔐 Zero Trust Security Architecture

MPhil research repository containing simulation methodology, Python implementation, CICIDS2017 documentation, architecture diagrams, model comparison, threshold analysis, and experimental results.

🔗 [zero-trust-security-architecture](https://github.com/hopetawiah/zero-trust-security-architecture)

---

## 🌐 Secure Federated Learning for IoT

MSc research implementation covering secure and communication-efficient federated learning, IoT intrusion detection, resource-aware participation, adaptive communication, poisoning experiments, and malicious-update defence.

🔗 [secure-federated-learning-iot](https://github.com/hopetawiah/secure-federated-learning-iot)

---

## 🖧 Secure Corporate Network Infrastructure

BSc Information Technology project documenting secure enterprise network architecture, VLAN segmentation, firewall protection, Active Directory, DNS, DHCP, RBAC, domain administration, connectivity testing, backup planning, and business continuity.

🔗 [secure-corporate-network-infrastructure](https://github.com/hopetawiah/secure-corporate-network-infrastructure)

---

## 🏫 Dunamis Crown Academy School ERP

Production secure School ERP demonstrating software engineering, access governance, authentication, auditability, cybersecurity controls, analytics, backup and recovery, and secure administration.

🔗 [dunamis-school-erp-portfolio](https://github.com/hopetawiah/dunamis-school-erp-portfolio)

🌐 [Live System](https://portal.dunamiscrownacademy.com/)

---

# 📫 Connect With Me

**GitHub**  
https://github.com/hopetawiah

**LinkedIn**  
https://linkedin.com/in/hope-tawiah-035175207/

**Email**  
hopetawiah21@gmail.com

---

> *Building secure systems while researching the next generation of intelligent, adaptive, and resilient cybersecurity architectures.*
