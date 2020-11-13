# Cyber and Technical Security Guidance

## Summary

This site documents some of the security decisions that the [Ministry of Justice \(MoJ\)](https://www.gov.uk/government/organisations/ministry-of-justice) has made for the products we operate, and our relationships with suppliers.

The MoJ [Technical Guidance](https://ministryofjustice.github.io/technical-guidance/) covers technical decisions in the MoJ more widely.

**Note:**

This guidance is dated: 13 November 2020.

For convenience, offline versions of this guidance are available.

|Audience|PDF format|EPUB format|
|--------|----------|-----------|
|All users. Does not include lots of technical detail.|[PDF](moj-guidance.pdf)|[EPUB](moj-guidance.epub)|
|Technical users. Includes lots of technical detail.|[PDF](moj-guidance-tech.pdf)|[EPUB](moj-guidance-tech.epub)|

The offline versions of this guidance are time-limited, and are not valid after 13 December 2020.

### Getting in touch

-   [To report an incident](reporting-an-incident.md).
-   For general assistance on MoJ security matters, email [security@digital.justice.gov.uk](mailto:security@digital.justice.gov.uk).
-   For Cyber Security assistance or consulting, email [CyberConsultancy@digital.justice.gov.uk](mailto:CyberConsultancy@digital.justice.gov.uk). More information about the Cyber Security Consultancy Team is [available](user-guide.md).
-   Suppliers to the MoJ should first communicate with their usual MoJ points of contact.

### Background

[Government Functional Standard - GovS 007: Security](https://www.gov.uk/government/publications/government-functional-standard-govs-007-security) replaces the [HMG Security Policy Framework \(SPF\)](https://www.gov.uk/government/publications/security-policy-framework), last published in May 2018. It also incorporates the [Minimum Cyber Security Standard \(MCSS\)](https://www.gov.uk/government/publications/the-minimum-cyber-security-standard) which defines the minimum security measures that departments implement with regards to protecting their information, technology and digital services to meet their SPF and National Cyber Security Strategy obligations.

![A diagram showing a hierarchy of the key components within the Government Functional Standard. It is in three sections. In the first section, at the top is a triangle labelled Principles. This stands on a block marked Content, which itself stands on a block marked Governance, showing that governance and content underpin the principles. The second section is called Security Life Cycle. It shows a flow from left to right. To the left of the section is a large arrow entitled Security Strategy and Planning. This arrow splits on the right hand side into two small arrows. The top small arrow is labelled Prevention and Detection. The bottom small arrow is labelled Security Incident Management. A small line arrow drops down from the top Prevention and Detection arrow to the bottom Security Incident Management arrow. To the right hand side of this section of the diagram, the Prevention and Detection and the Security Incident Management arrows converge into a final large arrow, entitled Review and Learn from Experience. A dotted line arrow, labelled Improvement, goes back from the Review and Learn arrow over to the beginning of this section of the diagram, linking to the Security Strategy and Planning arrow. Underneath these arrow diagrams is the third and final section. This is a summary text, called Security Practices. Many practices are listed using three columns in this section. The left column list includes: Critical Assets and Services, Risk Management, and Access to information. The middle column list includes: Capability, capacity and resources, Security culture, Security education and awareness, and Physical security. The right column list includes: Personnel security, Cyber security, and Technical security.](images/gov007overview.png)

Sections 6.9 Cyber security and 6.10 Technical security of the standard state:

-   > The security of information and data is essential to good government and public confidence. To operate effectively, HMG needs to maintain the confidentiality, integrity and availability of its information, systems and infrastructure, and the services it provides. Any organisation that handles government information shall meet the standards expected of HM Government.
-   > Technical security relates to the protection of security systems from compromise and/or external interference that may have occurred as a result of an attack.

## Information structure

The MoJ has developed our cyber and technical security taxonomy as follows:

|Level 1|Level 2|
|-------|-------|
|[Information security policies](#information-security-policies)|[Management direction for information security](#management-direction-for-information-security)|
|[Mobile devices and teleworking](#mobile-devices-and-teleworking)|[Mobile device policy](#mobile-device-policy)|
||[Teleworking](#teleworking)|
|[Human resource security](#human-resource-security)|[Prior to employment](#prior-to-employment)|
||[During employment](#during-employment)|
|[Asset management](#asset-management)|[Responsibility for assets](#responsibility-for-assets)|
||[Information classification](#information-classification)|
||[Media handling](#media-handling)|
|[Access control](#access-control)|[Business requirements of access control](#business-requirements-of-access-control)|
||[User access management](#user-access-management)|
||[User responsibilities](#user-responsibilities)|
||[System and application access control](#system-and-application-access-control)|
|[Cryptography](#cryptography)|[Cryptographic controls](#cryptographic-controls)|
|[Physical and environmental security](#physical-and-environmental-security)|[Equipment](#equipment)|
|[Operations security](#operations-security)|[Operational procedures and responsibilities](#operational-procedures-and-responsibilities)|
||[Protection from malware](#protection-from-malware)|
||[Backup](#backup)|
||[Logging and monitoring](#logging-and-monitoring)|
||[Control of operational software](#control-of-operational-software)|
||[Technical vulnerability management](#technical-vulnerability-management)|
|[Communications security](#communications-security)|[Network security management](#network-security-management)|
||[Information transfer](#information-transfer)|
|[System acquisition, development and maintenance](#system-acquisition-development-and-maintenance)|[Security requirements of information systems](#security-requirements-of-information-systems)|
||[Security in development and support processes](#security-in-development-and-support-processes)|
||[Test data](#test-data)|
|[Supplier relationships](#supplier-relationships)|[Information security in supplier relationships](#information-security-in-supplier-relationships)|
||[Supplier service delivery management](#supplier-service-delivery-management)|
|[Information security incident management](#information-security-incident-management)|[Management of information security incidents and improvements](#management-of-information-security-incidents-and-improvements)|
|[Information security aspects of business continuity management](#information-security-aspects-of-business-continuity-management)|[Information security continuity](#information-security-continuity)|
|[Compliance](#compliance)|[Compliance with legal and contractual requirements](#compliance-with-legal-and-contractual-requirements)|
||[Information security reviews](#information-security-reviews)|
|[Risk Assessment](#risk-assessment)|[Risk Assessment Process](#risk-assessment-process)|

The documents have been developed and defined within this taxonomy, and are listed in the next section, together with their suggested target audiences.

Content tagged with the Intranet icon \(![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png)\) is on the MoJ Intranet. You will need Intranet access to view that content.

### Information security policies

#### Management direction for information security

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Avoiding too much security](https://intranet.justice.gov.uk/guidance/security/it-computer-security/setecastronomy/)|All users|
|[IDENTIFY, PROTECT, DETECT, RESPOND, RECOVER](identify-protect-detect-respond-recover.md)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Line Manager approval](https://intranet.justice.gov.uk/guidance/security/it-computer-security/line-manager-approval/)|All users|
|[Shared Responsibility Models](shared-responsibility-models.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

### Mobile devices and teleworking

#### Mobile device policy

|[Remote Working](remote-working.md)|All users|

#### Teleworking

|[Accessing MoJ IT Systems From Abroad](accessing-moj-it-systems-from-abroad.md)|All users|
|[General advice on taking equipment abroad](general-advice-on-taking-equipment-abroad.md)|All users|
|[Security Guidance for Using a Personal Device](personal-devices.md)|All users|

### Human resource security

#### Prior to employment

|[Personnel security clearances](personnel-security-clearances.md)|All users|

#### During employment

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Training and Education](https://intranet.justice.gov.uk/guidance/security/it-computer-security/training-and-education/)|All users|

### Asset management

#### Responsibility for assets

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Acceptable use](https://intranet.justice.gov.uk/guidance/security/it-computer-security/acceptable-use/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Acceptable use policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/acceptable-use-policy/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [IT Acceptable Use Policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/it-acceptable-use-policy/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Protect Yourself Online](https://intranet.justice.gov.uk/guidance/security/it-computer-security/protect-yourself-online/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Web browsing security](https://intranet.justice.gov.uk/guidance/security/it-computer-security/web-browsing/)|All users|

#### Information classification

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Data Handling and Information Sharing Guide](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/data-handling-and-information-sharing-guide/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Government Classification Scheme](https://intranet.justice.gov.uk/guidance/security/it-computer-security/government-classification-scheme)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Information Classification and Handling Policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/information-classification-and-handling-policy/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[`OFFICIAL` and `OFFICIAL-SENSITIVE`](official-official-sensitive.md)|All users|
|[Secrets management](secrets-management.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Media handling

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Removable media](https://intranet.justice.gov.uk/guidance/security/it-computer-security/removable-media/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Secure disposal of ICT equipment](https://intranet.justice.gov.uk/guidance/security/it-computer-security/secure-disposal-of-ict-equipment/)|All users|

### Access control

#### Business requirements of access control

|[Access Control Guide](access-control-guide.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Enterprise Access Control Policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/moj-enterprise-access-control-policy/)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### User access management

|[Authentication](authentication.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Management access](management-access.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Managing User Access Guide](managing-user-access-guide.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Minimum User Clearance Levels Guide](minimum-user-clearance-requirements-guide.md)|All users|
|[Multi-Factor Authentication](multi-factor-authentication-mfa-guide.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Privileged Account Management Guide](privileged-account-management-guide.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### User responsibilities

|[Protecting Social Media Accounts](protecting-social-media-accounts.md)|All users|

#### System and application access control

|[Account management](account-management.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Authorisation](authorisation.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Multi-user accounts and Public-Facing Service Accounts Guide](multi-user-accounts-and-public-facing-service-accounts-guide.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Password Creation and Authentication Guide](password-creation-and-authentication-guide.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Password Management Guide](password-management-guide.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Password Managers](password-managers.md)|All users|
|[Passwords](passwords.md)|All users|
|[Password Storage and Management Guide](password-storage-and-management-guide.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Policies for Google Apps administrators](https://intranet.justice.gov.uk/guidance/security/it-computer-security/policies-for-google-apps-administrators/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Policies for Macbook Administrators](https://intranet.justice.gov.uk/guidance/security/it-computer-security/policies-for-macbook-administrators/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [System User and Application Administrators](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/system-administrators/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Using LastPass Enterprise](using-lastpass.md)|All users|

### Cryptography

#### Cryptographic controls

|[Automated certificate renewal](automated-certificate-renewal.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Cryptography](cryptography.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [HMG Cryptography Business Continuity Management Standard](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/hmg-cryptography-business-continuity-management-standard/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Public Key Infrastructure Policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/public-key-infrastructure-policy/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Use of HMG Cryptography Policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/use-of-hmg-cryptography-policy/)|Technical Architect, DevOps, IT Service Manager, Software Developer|

### Physical and environmental security

#### Equipment

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Clear Screen and Desk Policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/clear-screen-and-desk-policy/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Laptops](https://intranet.justice.gov.uk/guidance/security/it-computer-security/laptops/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Locking and shutdown](https://intranet.justice.gov.uk/guidance/security/it-computer-security/locking-and-shutdown/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Policies for Macbook Users](https://intranet.justice.gov.uk/guidance/security/it-computer-security/policies-for-macbook-users/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [System Lockdown and Hardening Standard](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/system-lockdown-and-hardening-standard/)|Technical Architect, DevOps, IT Service Manager, Software Developer|

### Operations security

#### Operational procedures and responsibilities

|[Active Cyber Defence: Mail Check](mail-check.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Active Cyber Defence: Public Sector DNS](public-sector-dns.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Active Cyber Defence: Web Check](web-check.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Offshoring Guide](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/offshoring-guide/)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Protection from malware

|[Malware Protection Guide \(Overview\)](malware-protection-guide-introduction.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Malware Protection Guide: Defensive Layer 1](malware-protection-guidance-defensive-layer-1.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Malware Protection Guide: Defensive Layer 2](malware-protection-guidance-defensive-layer-2.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Malware Protection Guide: Defensive Layer 3](malware-protection-guidance-defensive-layer-3.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Backup

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [System backup guidance](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/system-backup-guidance/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [System backup policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/system-backup-policy/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [System backup standard](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/system-backup-standard/)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Logging and monitoring

|[Accounting](accounting.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Commercial off-the-shelf applications](cots-applications.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Custom Applications](custom-applications.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Online identifiers in security logging & monitoring](online-identifiers.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Protective Monitoring Guide](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/protective-monitoring-guide/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Security Log Collection](security-log-collection.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Security Log Collection: Enterprise IT - Infrastructure](enterprise-it-infrastructure.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Security Log Collection: Enterprise IT - Mobile Devices](enterprise-it-mobile-devices.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Security Log Collection: Hosting Platforms](hosting-platforms.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Security Log Collection: Log entry metadata](log-entry-metadata.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Security Log Collection: Maturity Tiers](security-log-collection-maturity-tiers.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Control of operational software

|[Guidance for using Open Internet Tools](guidance-for-using-open-internet-tools.md)|All users|

#### Technical vulnerability management

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Patch Management Standard](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/patch-management-standard/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Vulnerability Disclosure](vulnerability-disclosure-policy.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Vulnerability Disclosure: Implementing `security.txt`](implement-security-txt.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Vulnerability scanning](vulnerability-scanning.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

### Communications security

#### Network security management

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Code of Connection Standard](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/code-of-connection-standard/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Defensive domain registrations](defensive-domain-registration.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Internet v. PSN](internet-v-psn.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[IP DNS Diagram Handling](ip-dns-diagram-handling.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Multiple Back-to-back Consecutive Firewalls](multiple-consecutive-back-to-back-firewalls.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Networks are just bearers](networks-bearers-not-trust.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Information transfer

|[Bluetooth](bluetooth.md)|All users|
|[Criminal Justice Secure Mail \(CJSM\)](cjsm.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Data Sovereignty](data-sovereignty.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Email security](https://intranet.justice.gov.uk/guidance/security/it-computer-security/email/)|All users|
|[General Apps Guidance](general-user-video-and-messaging-apps-guidance.md)|All users|

### System acquisition, development and maintenance

#### Security requirements of information systems

|[Technical Security Controls Guide](technical-security-controls-guide.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Technical Security Controls Guide: Defensive Layer 1](technical-security-controls-guide-defensive-layer-1.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Technical Security Controls Guide: Defensive Layer 2](technical-security-controls-guide-defensive-layer-2.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Security in development and support processes

|[Maintained by Default](maintained-by-default.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Secure by Default](secure-by-default.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Source Code Publishing](https://intranet.justice.gov.uk/guidance/security/it-computer-security/source-code-publishing/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [System Test Standard](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/system-test-standard/)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Test data

|[Using Live Data for Testing purposes](using-live-data-for-testing-purposes.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

### Supplier relationships

#### Information security in supplier relationships

|[Suppliers to MoJ: Assessing Suppliers](assessing-suppliers.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Suppliers to MoJ: Contracts](contracts.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Suppliers to MoJ: Security Aspect Letters](security-aspect-letters.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Suppliers to MoJ: Supplier Corporate IT](supplier-corporate-it.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Supplier service delivery management

|[Baseline for Amazon Web Services accounts](baseline-aws-accounts.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

### Information security incident management

#### Management of information security incidents and improvements

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Forensic Principles](https://intranet.justice.gov.uk/guidance/security/it-computer-security/forensic-principles/)|All users|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Forensic Readiness Guide](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/forensic-readiness-guide/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Forensic Readiness Policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/moj-forensic-readiness-policy/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Incident Management Plan and Process Guide](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/incident-management-plan-and-process-guide/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [IT Incident Management Policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/it-incident-management-policy/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Lost Laptop or other IT security incident](lost-laptophardware.md)|All users|
|[Reporting an incident](reporting-an-incident.md)|All users|

### Information security aspects of business continuity management

#### Information security continuity

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [ICT Disaster Recovery Plan and Process Guide](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/ict-disaster-recovery-plan-and-process-guide/)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [IT Disaster Recovery Policy](https://intranet.justice.gov.uk/guidance/security/it-computer-security/ict-security-policy-framework/it-disaster-recovery-policy/)|Technical Architect, DevOps, IT Service Manager, Software Developer|

### Compliance

#### Compliance with legal and contractual requirements

|[Data Destruction](data-destruction.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Data Destruction: Contract Clauses - Definitions](data-destruction-contract-clauses-definitions.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Data Destruction: Contract Clauses - Long Format](data-destruction-contract-clauses-long-format.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Data Destruction: Contract Clauses - Long Format \(Appendix\)](data-destruction-contract-clauses-long-format-appendix.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Data Destruction: Contract Clauses - Short Format](data-destruction-contract-clauses-short-format.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Data Destruction: Instruction and Confirmation Letter](data-destruction-instruction-and-confirmation-letter.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Data Security and Privacy](data-security-and-privacy.md)|All users|
|[Data Security & Privacy Lifecycle Expectations](data-security-and-privacy-lifecycle.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|
|[Data Security & Privacy Triage Standards](data-security-and-privacy-triage-standards.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

#### Information security reviews

|[Standards Assurance Tables](standards-assurance-tables.md)|Technical Architect, DevOps, IT Service Manager, Software Developer|

### Risk Assessment

#### Risk Assessment Process

|![A small UK Government Crown, to indicate that the link is to the MoJ Intranet.](images/gov-uk-logotype-crown.png) [Risk reviews](https://intranet.justice.gov.uk/guidance/security/it-computer-security/risk-reviews/)|All users|

## Other Guidance

### Intranet

There are other cyber and technical security guidance documents available to reference. A large number of these documents are available in the [IT and Computer Security](https://intranet.justice.gov.uk/guidance/security/it-computer-security/) repository on the MoJ Intranet, but these documents are currently being reviewed and progressively are being incorporated into this main [Security Guidance](cyber-and-technical-security-guidance.md) repository.

### Technical Guidance

The MoJ [Technical Guidance](https://ministryofjustice.github.io/technical-guidance/) should be read together with this security-focused guidance.

The [Government Functional Standard - GovS 007: Security](https://www.gov.uk/government/publications/government-functional-standard-govs-007-security) provides the base material for all security guidance in the MoJ.

