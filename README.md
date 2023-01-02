# Microsoft SC-900: Microsoft Security, Compliance, and Identity Fundamentals
My Microsoft SC-900 Microsoft Security, Compliance, and Identity Fundamentals Notes

Created by: Brad Voris<BR />
<img alt="GitHub" src="https://img.shields.io/github/license/bvoris/MSSC-900">
<img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/bvoris/MSSC-900">
<img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/bvoris/MSSC-900/total">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/bvoris/MSSC-900">
<img alt="GitHub language count" src="https://img.shields.io/github/languages/count/bvoris/MSSC-900">
<img alt="GitHub issues" src="https://img.shields.io/github/issues/bvoris/MSSC-900">
<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/bvoris/MSSC-900">

## What is the SC-900?
This exam is targeted to those looking to familiarize themselves with the fundamentals of security, compliance, and identity (SCI) across cloud-based and related Microsoft services.<BR /><BR />

This is a broad audience that may include business stakeholders, new or existing IT professionals, or students who have an interest in Microsoft security, compliance, and identity solutions.<BR /><BR />

Candidates should be familiar with Microsoft Azure and Microsoft 365 and want to understand how Microsoft security, compliance, and identity solutions can span across these solution areas to provide a holistic and end-to-end solution.<BR /><BR />

https://docs.microsoft.com/en-us/learn/certifications/exams/sc-900

## Link to Microsoft SC-900 Training Online
https://docs.microsoft.com/en-us/learn/certifications/exams/sc-900

## Passing Score: 700

## Skills Measured:
Describe the concepts of security, compliance, and identity (10-15%)<BR />
Describe the capabilities of Microsoft identity and access management solutions (25-30%)<BR />
Describe the capabilities of Microsoft Security solutions (25-30%)<BR />
Describe the capabilities of Microsoft compliance solutions (25-30%)<BR />
## Preamble
While the Microsoft learning path has the majority of high level information required to pass the exam, it is not enough. I'd highly recommend reading Microsoft Security, Compliance and Identity Fundamentals Exam Ref SC-900. The book itself is good but also missing updated components, so additional supplementations should be considered. I'd also suggest getting some hand on familiarity with the basics of M365 and Azure. This will provide a substantial benefit to futher your learning path. 
I've tried to include as much information as possible between my studies via the learning path, exam ref, MS docs, and youtube videos I've found helpful.
<BR />
## My SC-900 Notes:
-------------------------------------------------------------------------------------------------------------------------------------------------------------<BR />
Describe the concepts of security, compliance, and identity (10-15%)<BR />
-------------------------------------------------------------------------------------------------------------------------------------------------------------<BR />
------Shared Responsibility Model<BR />
------------Software as a Service (SaaS) - SaaS is hosted and managed by the cloud provider<BR />
------------Platform as a Service (PaaS) - Environment for building, testing, and deploying software applications.<BR />
------------Infrastructure as a Service (IaaS) - Computing and network physical infrastructure is provided<BR />
------------On-premise datacenter<BR />
------Defense In Depth -  layered approach to security<BR />
------------Physical <BR />
------------Identity & Access<BR />
------------Perimeter<BR />
------------Network<BR />
------------Compute<BR />
------------Application<BR />
------------Data<BR />
------CIA Triad<BR />
------------Confidentiality -  the need to keep confidential sensitive data such as customer information, passwords, or financial data<BR />
------------Integrity - refers to keeping data or messages correct<BR />
------------Availability -  refers to making data available to those who need it, when they need it<BR />
------Zero Trust -  assumes everything is on an open and untrusted network<BR />
------------Verify Explicitly<BR />
------------Least Privileged Access<BR />
------------Assume Breach<BR />
------------6 foundational Pillars<BR />
------------------Identities<BR />
------------------Devices<BR />
------------------Applications<BR />
------------------Data<BR />
------------------Infrastructure<BR />
------------------Networks<BR />
------Encryption and Hashing<BR />
------------Encryption -  the process of making data unreadable and unusable to unauthorized viewers<BR />
------------------Symmetric Encryption - same/shared key<BR />
------------------Asymmetric Encryption - Private key / public key (https)<BR />
------------------------Encryption in transit<BR />
------------------------Encryption at rest<BR />
------------------------Encryption for data in use<BR />
------------Hashing - uses an algorithm to convert text to a unique fixed-length value called a hash<BR />
------Compliance Concepts<BR />
------------Data Residency - where data can be stored and how and when it can be transferred, processed, or accessed internationally<BR />
------------Data Sovereignty -  laws and regulations of the country/region in which data's physically collected, held, or processe<BR />
------------Data Privacy - Providing notice and being transparent about the collection, processing, use, and sharing of personal data are fundamental principles of privacy laws and regulations.<BR />
<BR />
-------------------------------------------------------------------------------------------------------------------------------------------------------------<BR />
Describe the capabilities of Microsoft identity and access management solutions (25-30%)<BR />
-------------------------------------------------------------------------------------------------------------------------------------------------------------<BR />
------Authentication - the process of proving that a person is who they say they are<BR />
------Authorization - What an identity once authenticated has access to<BR />
------Four Pillars of an Identity Infrastructure<BR />
------------Administration - creation and management of identities<BR />
------------Authentication<BR />
------------Authorization<BR />
------------Auditing - tracking, reporting, and governance<BR />
------Identity Provider (IDP) - creates, maintains, and manages identity information while offering authentication, authorization, and auditing services.<BR />
------Modern Authentication - authentication and authorization methods between a client, such as your laptop or phone, and a server, like a website or application.<BR />
------Single sign-on - the user logs in once and that credential is used to access multiple applications or resources.<BR />
------Federation - enables the access of services across organizational or domain boundaries by establishing trust relationships between the respective domain’s identity provider.<BR />
------Active Directory Domain Services (ADDS) -  a set of directory services developed by Microsoft as part of Windows 2000 for on-premises domain-based networks<BR />
------Azure Active Directory (ADS) - provides organizations with an Identity as a Service (IDaaS) solution for all their apps across cloud and on-premises<BR />
------------Azure Active Directory Free - free version included with Azure and Office 365<BR />
------------Azure Active Directory Premium P1. The Premium P1 edition includes all the features in the free and Office 365 apps editions. It also supports advanced administration, such as dynamic groups, self-service group management, Microsoft Identity Manager (an on-premises identity and access management suite) and cloud write-back capabilities, which allow self-service password reset for your on-premises users.<BR />
------------Azure Active Directory Premium P2. P2 offers all the Premium P1 features, and Azure Active Directory Identity Protection to help provide risk-based Conditional Access to your apps and critical company data. P2 also gives you Privileged Identity Management to help discover, restrict, and monitor administrators and their access to resources, and to provide just-in-time access when needed.<BR />
------------Azure AD Identity Types<BR />
------------------User - employees and guests<BR />
------------------Service Principal - identity for an application<BR />
------------------Managed identities<BR />
------------------------System Assigned - When you enable a system-assigned managed identity, an identity is created in Azure AD that's tied to the lifecycle of that service instance. <BR />
------------------------User Assigned - Once you create a user-assigned managed identity you can assign it to one or more instances of an Azure service. <BR />
------------------Device - A device is a piece of hardware, such as mobile devices, laptops, servers, or printers. <BR />
------------------------Azure AD Registered Devices - The goal of Azure AD registered devices is to provide users with support for bring your own device (BYOD) or mobile device scenarios.<BR />
------------------------Azure AD Joined Devices - a device joined to Azure AD through an organizational account, which is then used to sign in to the device.<BR />
------------------------Hybrid Azure AD Joined Devices - Organizations with existing on-premises Active Directory implementations can benefit from the functionality provided by Azure AD by implementing hybrid Azure AD joined devices. These devices are joined to your on-premises Active Directory and Azure AD requiring organizational account to sign in to the device<BR />
------------------External Identities<BR />
------------------------B2B Collaboration -  collaboration allows you to share your organization’s applications and services with guest users from other organizations, while maintaining control over your own data<BR />
------------------------B2C Access Management - customer identity access management (CIAM) solution. Azure AD B2C allows external users to sign in with their preferred social, enterprise, or local account identities to get single sign-on to your applications<BR />
------------Hybrid identity<BR />
------------------Azure AD Password hash synchronization -  is the simplest way to enable authentication for on-premises directory objects in Azure AD. Users can sign in to Azure AD services by using the same username and password that they use to sign in to their on-premises Active Directory instance. Azure AD handles users' sign-in process.<BR />
------------------Azure AD Pass-through authentication -  allows users to sign in to both on-premises and cloud-based applications using the same passwords, like password hash synch. A key difference, however, is when users sign in using Azure AD, pass-through authentication validates users' passwords directly against your on-premises Active Directory.<BR />
------------------Federated authentication -  recommended as an authentication for organizations that have advanced features not currently supported in Azure AD, including sign-on using smart cards or certificates, sign-on using on-premises multi-factor authentication (MFA) server, and sign-on using a third party authentication solution.<BR />
<BR />
-------------------------------------------------------------------------------------------------------------------------------------------------------------<BR />
Describe the capabilities of Microsoft Security solutions (25-30%)<BR />
-------------------------------------------------------------------------------------------------------------------------------------------------------------<BR />
------Azure DDoS<BR />
------------Basic - Always-on traffic monitoring and real-time mitigation of common network-level attacks provide the same defenses that Microsoft’s online services use.<BR />
------------Standard - The Standard service tier provides extra mitigation capabilities that are tuned specifically to Microsoft Azure Virtual Network resources. DDoS Protection Standard is simple to enable and requires no application changes. Protection policies are tuned through dedicated traffic monitoring and machine learning algorithms. Policies are applied to public IP addresses, which are associated with resources deployed in virtual networks, such as Azure Load Balancer and Application Gateway.<BR />
------Azure Firewall -  managed, cloud-based network security service that protects your Azure virtual network (VNet) resources from attackers.<BR />
------Web Application Firewall - provides centralized protection of your web applications from common exploits and vulnerabilities.<BR />
------Network Segmentation - Abililty to group related assets, isolation of resources, governance policies set by organization<BR />
------Azure Network Security Groups - let you filter network traffic to and from Azure resources in an Azure virtual network; for example, a virtual machine.<BR />
------------AllowVNetInBound<BR />
------------AllowAzureLoadBalancerInBound<BR />
------------DenyAllInBound<BR />
------Azure Bastion - a service you deploy that lets you connect to a virtual machine using your browser and the Azure portal. Protects RDP and SSH sessions.<BR />
------Azure JIT -  access allows lock down of the inbound traffic to your VMs, reducing exposure to attacks while providing easy access to connect to VMs when needed.<BR />
------Azure Encryption<BR />
------------Azure Storage Service Encryption -  helps to protect data at rest by automatically encrypting before persisting it to Azure-managed disks, Azure Blob Storage, Azure Files, or Azure Queue Storage, and decrypts the data before retrieval.<BR />
------------Azure Disk Encryption - helps you encrypt Windows and Linux IaaS virtual machine disks. Azure Disk Encryption uses the industry-standard BitLocker feature of Windows and the dm-crypt feature of Linux to provide volume encryption for the OS and data disks.<BR />
------------Transparent Data Encryption (TDE) -  helps protect Azure SQL Database and Azure Data Warehouse against the threat of malicious activity. It performs real-time encryption and decryption of the database, associated backups, and transaction log files at rest without requiring changes to the application.<BR />
------------Azure Key Vault -  centralized cloud service for storing your application secrets<BR />
------------------Secrets Management - You can use Key Vault to store securely and tightly control access to tokens, passwords, certificates, Application Programming Interface (API) keys, and other secrets.<BR />
------------------Key Management - You can use Key Vault as a key management solution. Key Vault makes it easier to create and control the encryption keys used to encrypt your data.<BR />
------------------Certificate Management -  Key Vault lets you provision, manage, and deploy your public and private Secure Sockets Layer/ Transport Layer Security (SSL/ TLS) certificates for Azure, and internally connected, resources more easily.<BR />
------------------Store Secrets backed by hardware security models (HSM) -  The secrets and keys can be protected either by software or by FIPS 140-2 Level 2 validated HSMs.<BR /><BR />
------Azure Security Center (https://securitycenter.microsoft.com/) - <BR />
------Azure Secure Score<BR />
------Microsoft Defender for Cloud Apps (formerly Microsoft Cloud App Security or MCAS) (https://docs.microsoft.com/en-us/defender-cloud-apps/what-is-defender-for-cloud-apps)<BR />
Microsoft Defender for Cloud Apps is a Cloud Access Security Broker (CASB) that supports various deployment modes including log collection, API connectors, and reverse proxy. It provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyberthreats across all your Microsoft and third-party cloud services.<BR />
<BR />
------Microsoft Defender (https://protection.office.com)<BR />
------------Defender for Office 365 (https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/overview?view=o365-worldwide)<BR />
------------What is Defender for Office 365 security?<BR />
------------Every Office 365 subscription comes with security capabilities. The goals and actions that you can take depend on the focus of these different subscriptions. In Office 365 security, there are three main security services (or products) tied to your subscription type:<BR />
------------------1) Exchange Online Protection (EOP) - Prevents broad, volume-based, known attacks.<BR />
------------------2) Microsoft Defender for Office 365 Plan 1 (Defender for Office P1) - Protects email and collaboration from zero-day malware, phish, and business email compromise.<BR />
------------------3) Microsoft Defender for Office 365 Plan 2 (Defender for Office P2) - Adds post-breach investigation, hunting, and response, as well as automation, and simulation (for training).<BR /><BR />
------------------Exchange Online Protection Capabilities:<BR />
------------------------Prevent/Detect:<BR />
------------------------------spam<BR />
------------------------------phish<BR />
------------------------------malware<BR />
------------------------------bulk mail<BR />
------------------------------spoof intelligence<BR />
------------------------------impersonation detection<BR />
------------------------------Admin Quarantine<BR />
------------------------------Admin and user submissions of False Positives and False Negatives<BR />
------------------------------Allow/Block for URLs and Files<BR />
------------------------------Reports<BR />
<BR />
------------------------Investigate:<BR />
------------------------------Audit log search<BR />
------------------------------Message Trace<BR />
<BR />
------------------------Respond:<BR />
------------------------------Zero-hour auto purge (ZAP)<BR />
------------------------------Refinement and testing of Allow and Block lists<BR />
<BR />
 ------------------Defender for Office 365, Plan 1<BR />
Prevent/Detect:<BR />
------------------------Technologies include everything in EOP plus:<BR />
------------------------------Safe attachments<BR />
------------------------------Safe links<BR />
------------------------------Microsoft Defender for Office 365 protection for workloads (ex. SharePoint Online, Teams, OneDrive for Business)<BR />
------------------------------Time-of-click protection in email, Office clients, and Teams<BR />
------------------------------anti-phishing in Defender for Office 365<BR />
------------------------------User and domain impersonation protection<BR />
------------------------------Alerts, and SIEM integration API for alerts<BR />
<BR />
------------------------Investigate:<BR />
------------------------------SIEM integration API for detections<BR />
------------------------------Real-time detections tool<BR />
------------------------------URL trace<BR />
<BR />
------------------------Respond:<BR />
------------------------------Same<BR />
<BR />
------------------Defender for Office 365, Plan 2:<BR />
------------------------Prevent/Detect:<BR />
------------------------------Technologies include everything in EOP, and Microsoft Defender for Office 365 P1 plus:<BR />
Same<BR />
<BR />
------------------------Investigate:<BR />
------------------------------Threat Explorer<BR />
------------------------------Threat Trackers<BR />
------------------------------Campaign views<BR />
<BR />
------------------------Respond:<BR />
------------------------------Automated Investigation and Response (AIR)<BR />
------------------------------AIR from Threat Explorer<BR />
------------------------------AIR for compromised users<BR />
------------------------------SIEM Integration API for Automated Investigations<BR />
<BR />
Defender for Identity (https://docs.microsoft.com/en-us/defender-for-identity/what-is) <BR />
Defender for Identity enables SecOp analysts and security professionals struggling to detect advanced attacks in hybrid environments to:<BR />
<BR />
Monitor users, entity behavior, and activities with learning-based analytics<BR />
Protect user identities and credentials stored in Active Directory<BR />
Identify and investigate suspicious user activities and advanced attacks throughout the kill chain<BR />
Provide clear incident information on a simple timeline for fast triage<BR />
<BR />
Defender for Endpoint (https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/microsoft-defender-endpoint?view=o365-worldwide)<BR />
Microsoft Defender for Endpoint is an enterprise endpoint security platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.<BR />
Defender for Endpoint uses the following combination of technology built into Windows 10 and Microsoft's robust cloud service:<BR />
<BR />
Endpoint behavioral sensors: Embedded in Windows 10, these sensors collect and process behavioral signals from the operating system and send this sensor data to your private, isolated, cloud instance of Microsoft Defender for Endpoint.<BR />
<BR />
Cloud security analytics: Leveraging big-data, device learning, and unique Microsoft optics across the Windows ecosystem, enterprise cloud products (such as Office 365), and online assets, behavioral signals are translated into insights, detections, and recommended responses to advanced threats.<BR />
<BR />
Threat intelligence: Generated by Microsoft hunters, security teams, and augmented by threat intelligence provided by partners, threat intelligence enables Defender for Endpoint to identify attacker tools, techniques, and procedures, and generate alerts when they are observed in collected sensor data.<BR />
<BR />
Microsoft Secure Score (https://docs.microsoft.com/en-us/microsoft-365/security/defender/microsoft-secure-score?view=o365-worldwide)<BR />
Microsoft Secure Score is a measurement of an organization's security posture, with a higher number indicating more improvement actions taken. It can be found at https://security.microsoft.com/securescore in the Microsoft 365 Defender portal<BR />
Currently there are recommendations for the following products:<BR />
<BR />
Microsoft 365 (including Exchange Online)<BR />
Azure Active Directory<BR />
Microsoft Defender for Endpoint<BR />
Microsoft Defender for Identity<BR />
Defender for Cloud Apps<BR />
Microsoft Teams<BR />
<BR />
Azure Sentinel (https://azure.microsoft.com/en-us/services/microsoft-sentinel) - Azure Sentinel is a SIEM (Security Information and Event Management) and Security Orchestration and Automated Response (SOAR) system in Microsoft's public cloud platform. Sentinel can be accessed here https://aka.ms/microsoftazuresentinel<BR />
SIEM - Security Information and Event Management<BR />
SOAR - Security Orchestration and Automated Response<BR />
XDR - Extended Detect and Response<BR />
Microsoft Intune<BR />
MDM<BR /><BR />
-------------------------------------------------------------------------------------------------------------------------------------------------------------<BR />
Describe the capabilities of Microsoft compliance solutions (25-30%)<BR />
-------------------------------------------------------------------------------------------------------------------------------------------------------------<BR />
------Microsoft 365 Compliance Center Compliance.Microsoft.com<BR />
------------Service Trust portal -  provides information, tools, and other resources about Microsoft security, privacy, and compliance practices<BR />
------------Microsofts Privacy Principles<BR />
------------------control<BR />
------------------Transparency<BR />
------------------Security<BR />
------------------Strong Legal Protections<BR />
------------------No Content based Targeting<BR />
------------Compliance Manager<BR />
------------------Continuous Assessments<BR />
------------------Recommended Actions<BR />
------------------Contorl Mapping<BR />
------------Data Classification<BR />
------------------Discover<BR />
------------------Classify - Trainable Classifiers/Sensitive Info Types<BR />
------------------Review - content explorer/activity explorer<BR />
------------------Monitor<BR />
------------Data Connectors/Alerts/Reports/Policies<BR />
------------Audits<BR />
------------------Basic - 90 days<BR />
------------------Advanced - custom retention, audit policies<BR />
------------DLP <BR />
------------------Conditions/Actions/Locations<BR />
------------------<BR />
------------------OneDrive for Business<BR />
------------------Sharepoint Online<BR />
------------------Microsoft Teams<BR />
------------------Exchange Online<BR />
------------eDiscovery<BR />
------------------Core - create basic cases search content and export<BR />
------------------Advanced - identify preserve collect review analyze and export, with custodians<BR />
------------Information Governance<BR />
------------------Labels<BR />
------------------Label Policies<BR />
------------------Retention Policies<BR />
------------Information Protection<BR />
------------------Labels<BR />
------------------Label Policies<BR />
------------------Auto-Labeleing<BR />
------------Records Management<BR />
------------Insider Risk<BR />
------------Communication Compliance<BR />
------------Information Barriers<BR />
------------Resource Governance<BR />
------------------Azure Policy (https://docs.microsoft.com/en-us/azure/governance/policy/overview) - enforce standrds and assesses compliance<BR />
------------------Azure Blueprints (https://docs.microsoft.com/en-us/azure/governance/blueprints/overview) - define repeatable set of azure resources<BR />
------------------Azure Purview (https://docs.microsoft.com/en-us/azure/purview/overview ) - automates data discoveryand mapping<BR />
-----------------------Data Map - capture metadata about enterprise data, to identify and classify sensitive data.<BR />
-----------------------Data Catalog -  Microsoft Purview Data Catalog provides data curation features like business glossary management and ability to automate tagging of data assets with glossary terms<BR />
-----------------------Data Insights - data insights, data officers and security officers can get a bird’s eye view and at a glance understand what data is actively scanned, where sensitive data is and how it moves.<BR />

## Additional Links:
Azure Security Benchmark<BR />
https://docs.microsoft.com/en-us/security/benchmark/azure/ <BR />
Azure Security Benchmark 3.0<BR />
https://github.com/MicrosoftDocs/SecurityBenchmarks/tree/master/Azure%20Security%20Benchmark/3.0 <BR />

## Rick Kotlarz SC-900 Training
https://github.com/RickKotlarz/SC-900

## FreeCodeCamp.org - Microsoft Security Compliance and Identity (SC-900) - Full Course PASS the Exam
https://www.youtube.com/watch?v=LLKza5oULAA

## SC-900 Microsoft Security, Compliance and Identity Exam Cram (Full Course)
https://www.youtube.com/watch?v=rDxtTM7cOPI

## Microsoft Security Compliance and Identity (SC-900) - Full Course PASS the Exam
https://www.youtube.com/watch?v=Bz-8jM3jg-8

## Exam SC-900: Microsoft Security, Compliance, and Identity (Playlist)
https://www.youtube.com/playlist?list=PLhLKc18P9YOCAt0hPdnPavwr9V4ADItcq

## Microsoft Learning Path Training 
Microsoft Security, Compliance, and Identity Fundamentals: Describe the concepts of security, compliance, and identity - https://docs.microsoft.com/en-us/learn/paths/describe-concepts-of-security-compliance-identity/<BR />
<BR />
Detect and respond to cyber attacks with Microsoft Defender - https://docs.microsoft.com/en-us/learn/paths/defender-endpoint-fundamentals/<BR />
<BR />
Microsoft 365 Fundamentals: Demonstrate fundamental knowledge of Microsoft 365 security and compliance capabilities - 
https://docs.microsoft.com/en-us/learn/paths/m365-security-compliance-capabilities/<BR />
<BR />
Describe concepts of cryptography - https://docs.microsoft.com/en-us/learn/modules/describe-concepts-of-cryptography/<BR />
<BR />

## Azure Secure Score vs. Microsoft SecureScore - by Bojan Magusic
https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/azure-secure-score-vs-microsoft-secure-score/ba-p/2459684<BR />
<BR />

## Microsoft Tech Community: Security Compliance and Identity
https://techcommunity.microsoft.com/t5/security-compliance-and-identity/ct-p/MicrosoftSecurityandCompliance<BR />
<BR />

## Security roadmap - Top priorities for the first 30 days, 90 days, and beyond
https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/security-roadmap?view=o365-worldwide<BR />
<BR />

## Exam Ref SC-900 Microsoft Security, Compliance, and Identity Fundamentals
https://www.amazon.com/Exam-SC-900-Microsoft-Security-Fundamentals/dp/013756810X/ref=sr_1_1?keywords=sc-900+microsoft+security%2C+compliance%2C+and+identity+fundamentals&qid=1650817509&sprefix=microsoft+security+compl%2Caps%2C148&sr=8-1<BR />
<BR />

## Github Microsoft Learning SC-900-Microsoft-Security-Compliance-and-Identity-Fundamentals
https://github.com/MicrosoftLearning/SC-900-Microsoft-Security-Compliance-and-Identity-Fundamentals<BR />
<BR />

## Connect with me at

<a href="https://twitter.com/HMInfoSecViking?ref_src=twsrc%5Etfw"><IMG SRC="https://github.com/bvoris/bvoris/blob/master/twitter.jpg" WIDTH=10% HEIGHT=10% ALIGN=LEFT></a>

<a href="https://www.linkedin.com/in/brad-voris" target="_blank"><IMG SRC="https://github.com/bvoris/bvoris/blob/master/linkedin.png" WIDTH=10% HEIGHT=4% ALIGN=RIGHT></a>

<BR /><BR />
<BR /><BR />

<A HREF="https://www.victimoftechnology.com">Victim Of Technology<A />
<BR /><BR />
<A HREF="https://www.cyberforgesecurity.com">Cyber Forge Security, Inc.<A />
<BR /><BR />
