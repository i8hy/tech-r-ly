# Översikt
**Tech-R-LY** är ett bolag som efter egen forskning utvecklar, producerar och
säljer avancerade produkter till en liten men högspecialiserad kundbas. Hemsidan
säger följande:

"Introducing Tech-R-LY, where innovation meets excellence in the realm of
cutting-edge technology! At Tech-R-LY, we're pioneers in research, development,
and distribution of advanced products that redefine the boundaries of
possibility.

Our passion for pushing the limits of what's achievable drives us to constantly
explore new horizons, seeking out the latest breakthroughs to bring to our
discerning clientele. With a dedication to quality and a relentless pursuit of
perfection, we craft each of our products with meticulous attention to detail,
ensuring they exceed even the highest expectations.

What sets Tech-R-LY apart is not just our commitment to innovation, but also our
unwavering focus on meeting the unique needs of our customers. Through close
collaboration and a deep understanding of their requirements, we tailor
solutions that seamlessly integrate into their lives, providing unparalleled
performance and reliability.

From sleek designs to unparalleled functionality, our diverse range of products
represents the pinnacle of technological achievement. Whether it's enhancing
productivity, streamlining processes, or unlocking new possibilities, Tech-R-LY
has the perfect solution to elevate your experience to the next level.

Join us on a journey of discovery and imagination as we continue to
revolutionize the world of technology. With Tech-R-LY, the future is not just
within reach – it's already here."



(Tack ChatGPT, kunde inte dravla fram något bätte själv).

Det är tydligt att detta bolag är något att vara extra omsorgsfull med när det
gäller deras cybersäkerhet.


# Organisationen
Vi spinner vidare på ChatGPT's förmåga att generera saker med kuslig
kliché-halt. Organisationen ser ut såhär:

**Chief Executive Officer (CEO)**:
- **Ava Patel**
- *Responsibilities: Sets the overall direction and vision for the company,
  oversees operations, and ensures alignment with strategic goals.*

**Chief Technology Officer (CTO)**:
- **Michael Chen**
- *Responsibilities: Leads the technological vision and innovation strategy,
  oversees research and development initiatives, and ensures the company remains
  at the forefront of technological advancement.*

**Chief Operating Officer (COO)**:
- **Emily Rodriguez**
- *Responsibilities: Manages daily operations, optimizes processes for
  efficiency, and ensures smooth execution of projects and initiatives.*

**Chief Marketing Officer (CMO)**:
- **Olivia Thompson**
- *Responsibilities: Develops marketing strategies to promote Tech-R-LY's
  products, enhances brand awareness, and drives customer engagement.*

**Chief Financial Officer (CFO)**:
- **David Nguyen**
- *Responsibilities: Manages financial planning, budgeting, and forecasting,
  oversees accounting and financial reporting, and ensures financial stability
  and growth.*

**Chief Human Resources Officer (CHRO)**:
- **Sarah Washington**
- *Responsibilities: Leads talent acquisition, employee development, and HR
  policies to foster a positive and productive work environment.*

**Chief Information Officer (CIO)**:
- **Luisa Martinez**
- *Responsibilities: Oversees information technology infrastructure, data
  management, and cybersecurity to ensure the integrity and security of
  Tech-R-LY's systems and data.*

**Director of Product Development**:
- **Ethan Johnson**
- *Responsibilities: Leads the product development team, oversees the creation
  and enhancement of Tech-R-LY's products, and ensures they meet quality
  standards and market needs.*

**Director of Research**:
- **Aisha Khan**
- *Responsibilities: Manages the research team, conducts exploratory research,
  identifies new technologies and trends, and drives innovation within the
  company.*

**Director of Sales**:
- **Sophia Miller**
- *Responsibilities: Develops sales strategies, manages sales teams, and
  cultivates relationships with customers and partners to drive revenue growth.*

**Middle Managers (various departments)**:
- **Jessica Lee**, **Daniel Singh**, **Alexandra Carter**, **Jamal Jackson**
- *Responsibilities: Supervise teams within specific departments such as product
  development, research, marketing, sales, finance, and HR, ensuring goals are
  met and operations run smoothly.*

**Developers** (Software/Hardware):
- **Ryan Patel**, **Isabella Wong**, **Tyler Thompson**, **Maya Patel**,
  **Jordan Garcia**, **Emma Kim**, **Nathan Chen**
- *Responsibilities: Design, develop, and maintain software and/or hardware
  solutions for Tech-R-LY's products, collaborating closely with other teams to
  deliver high-quality products to market.*

This comprehensive structure showcases the talented individuals behind
Tech-R-LY's success, each playing a crucial role in driving innovation and
excellence within the company.


# Uppdraget
Tech-R-LY har upptäckt att deras nichade specialprodukter inte bara är
attraktiva för sina högt värderade kunder, utan även för de som inte vill att
Tech-R-LY ska antingen vara utan konkurrenter, samt de som inte vill att
Tech-R-LYs kunder ska ha tillgång alls till deras produkter (som är, **minst**,
bäst på marknaden enligt deras marknadsföring och säljpersonal).

Bolaget har bestämt sig för att anlita en grupp cybersäkerhetsspecialister för
att kartlägga deras it-miljö, samt skapa en initial förmåga deras interna
säkerhetsteam använder för att få svar på deras frågor om it-miljön.

**Ni ska därför leverera följande till Tech-R-LYs CIO Luisa Martinez**:
- Ett antal typfall av RFI:er,
- Kompetensfrågor baserade på RFI:erna,
- En terminologi som täcker in de vanligast använda termerna i deras it-miljö,
- Bonus: En maskinkonsumerbar version av deras nätverksstruktur, som just nu
  endast finns som bilder,
- Bonus: Ett inventarie som visar hård- och mjukvara per enhet.


# Beskrivning av nätverk, etc
## DMZ
The Demilitarized Zone (DMZ) is a vital component of Tech-R-LY's network
architecture, strategically positioned between the internal network and the
external internet. It serves as a secure intermediary zone that facilitates
controlled access to public-facing services while enforcing stringent security
measures to safeguard internal resources from potential threats originating from
the internet.

**Description of the DMZ**:
The DMZ is meticulously designed to balance accessibility and security,
providing a buffer zone that segregates public-facing services from the internal
network. This architectural approach minimizes the risk of unauthorized access
and mitigates the impact of potential security breaches, ensuring the integrity
and confidentiality of sensitive data.

**Key Functions of the DMZ**:
1. **Secure Gateway**: The DMZ acts as a secure gateway between the internal
   network and the external internet, regulating inbound and outbound traffic to
   protect internal resources from external threats.
2. **Public-Facing Services**: It hosts a range of public-facing services that
   need to be accessible from outside the company's network, such as web
   servers, email servers, and DNS servers.
3. **Security Enforcement**: Stringent security measures, including firewalls,
   intrusion detection/prevention systems, and access controls, are enforced
   within the DMZ to safeguard public-facing services and prevent unauthorized
   access.
4. **Traffic Filtering**: The DMZ filters and inspects incoming and outgoing
   traffic to identify and block potential threats, ensuring that only
   legitimate traffic reaches the internal network.
5. **Resource Isolation**: Public-facing services hosted in the DMZ are isolated
   from internal resources, minimizing the impact of security breaches and
   limiting the exposure of sensitive data to external threats.

**Services Hosted in the DMZ**:
1. **DNS Server**: Provides domain name resolution for internal and external
   resources, ensuring reliable network connectivity.
2. **External Mail Server**: Hosts email services for external communication,
   handling incoming and outgoing messages securely.
3. **Web Servers**: Hosts Tech-R-LY's public website and other web-based
   services, accessible from the internet while maintaining security.
4. **Internal Client Web Proxy**: Acts as an intermediary between internal
   clients and external web servers, caching and filtering web content for
   improved performance and security.

**Products in the DMZ**:
- **Cisco ISR 4000 Series Router**: Provides advanced routing, security, and
  application services as the gateway between the internal network and the
  external internet.
- **Cisco ASA (Adaptive Security Appliance)**: Offers comprehensive threat
  defense for networks, protecting the DMZ from cyber threats.
- **BIND DNS Server**: Open-source DNS server software known for its reliability
  and flexibility, providing domain name resolution within the DMZ.
- **Microsoft Exchange Server**: A robust email server platform that offers
  email, calendar, and collaboration services for businesses.
- **Apache HTTP Server**: A popular open-source web server software that powers
  a large percentage of websites on the internet.

With these components and security measures in place, Tech-R-LY's DMZ ensures
the availability, reliability, and security of public-facing services while
safeguarding the integrity and confidentiality of internal resources against
external threats.

## BYOD/Gäst
**Overview of the BYOD Network**: The BYOD (Bring Your Own Device) network at
Tech-R-LY is designed to accommodate employees who bring their personal devices
into the workplace for work-related activities. This network provides secure and
reliable connectivity for BYOD devices while ensuring the integrity and security
of corporate resources.

**Key Functions of the BYOD Network**:
1. **Secure Connectivity**: The BYOD network offers secure connectivity for
   personal devices, allowing employees to access corporate resources and
   applications while maintaining data privacy and confidentiality.
2. **Access Control**: Access to the BYOD network is controlled and
   authenticated, ensuring that only authorized users and devices can connect to
   the network and access corporate resources.
3. **Security Enforcement**: Stringent security measures, including firewalling,
   intrusion detection/prevention, and content filtering, are enforced within
   the BYOD network to protect against cyber threats and unauthorized access.
4. **User Management**: Centralized user authentication and management ensure
   that BYOD users adhere to security policies and guidelines, facilitating
   efficient management and monitoring of network access.

**Services Hosted in the BYOD Network**:
1. **Wireless Access Points (WAPs)**:
   - **Hardware**: Ubiquiti UniFi AC Lite Access Points
   - **Product Description**: These access points offer high-speed Wi-Fi
     connectivity with reliable performance and seamless roaming capabilities,
     ensuring consistent coverage throughout the office space.
2. **Network Switches**:
   - **Hardware**: Cisco SG250 Managed Switches
   - **Product Description**: These managed switches provide advanced features
     such as VLAN support, quality of service (QoS), and port security, enabling
     efficient and secure connectivity for BYOD devices.
3. **Internet Gateway/Firewall**:
   - **Hardware**: pfSense Security Gateway Appliance
   - **Product Description**: pfSense is an open-source firewall and routing
     platform that offers robust security features, including stateful packet
     filtering, VPN support, and intrusion detection/prevention capabilities,
     ensuring comprehensive protection for the BYOD network.
4. **Network Authentication Server**:
   - **Software**: FreeRADIUS
   - **Product Description**: FreeRADIUS is an open-source RADIUS server that
     provides centralized authentication, authorization, and accounting services
     for BYOD users, ensuring secure access to the network and enforcing user
     policies.
5. **Network Monitoring and Management Tools**:
   - **Software**: Zabbix Network Monitoring
   - **Product Description**: Zabbix is an open-source network monitoring
     solution that provides real-time monitoring, alerting, and reporting
     capabilities, enabling IT administrators to proactively manage and
     troubleshoot the BYOD network for optimal performance and security.
6. **Mobile Device Management (MDM) Solution**:
   - **Software**: MobileIron Unified Endpoint Management
   - **Product Description**: MobileIron offers a comprehensive MDM solution
     that allows organizations to securely manage BYOD devices, enforce security
     policies, and protect corporate data, ensuring compliance with regulatory
     requirements and industry standards.
7. **Virtual Private Network (VPN) Access**:
   - **Software**: OpenVPN
   - **Product Description**: OpenVPN is an open-source VPN solution that
     provides secure remote access to the corporate network for BYOD users,
     encrypting data transmission and ensuring privacy and confidentiality.
8. **Intrusion Detection/Prevention Systems (IDS/IPS)**:
   - **Software**: Snort Intrusion Detection System
   - **Product Description**: Snort is an open-source IDS/IPS solution that
     provides real-time traffic analysis and threat detection capabilities,
     helping to identify and mitigate security threats targeting BYOD devices
     and the network.

By implementing these hardware and software solutions, Tech-R-LY can establish a
secure and efficient BYOD network environment that meets the needs of employees
while maintaining robust security measures to protect corporate assets and data.


## Internal services
**Overview of the Internal Services Network**:
The Internal Services Network at Tech-R-LY is a critical infrastructure segment
dedicated to hosting essential internal services and resources. This network
facilitates seamless communication and collaboration among employees while
ensuring the availability, reliability, and security of corporate systems and
data.

**Key Functions of the Internal Services Network**:
1. **Centralized Services**: The Internal Services Network centralizes core
   services such as authentication, email, file sharing, and internal web
   applications, streamlining access and management for employees across the
   organization.
2. **Data Storage and Backup**: It provides centralized data storage and backup
   services to safeguard critical business data, ensuring data integrity,
   availability, and disaster recovery capabilities.
3. **Identity and Access Management**: Centralized authentication services, such
   as Active Directory (AD), enable efficient user management, access control,
   and policy enforcement across all networked resources.
4. **Collaboration and Communication**: Internal web applications, email
   servers, and file sharing services foster collaboration and communication
   among employees, enhancing productivity and efficiency.
5. **Resource Sharing**: File sharing services and network drives facilitate
   seamless sharing and access to documents, files, and resources, promoting
   teamwork and information exchange.

**Services Hosted in the Internal Services Network**:
1. **Centralized Active Directory (AD)**:
   - **Software**: Microsoft Active Directory
   - **Product Description**: Microsoft Active Directory provides centralized
     authentication, user management, and policy enforcement services, enabling
     seamless integration with Windows-based environments and facilitating
     secure access to networked resources.
2. **Internal Web Server**:
   - **Hardware**: Dell PowerEdge R Series Servers
   - **Product Description**: Dell PowerEdge R Series servers offer
     high-performance computing power and scalability, making them suitable for
     hosting internal web applications and services. They provide reliability,
     flexibility, and advanced management features to support critical business
     applications.
3. **Internal Email Server**:
   - **Software**: Microsoft Exchange Server
   - **Product Description**: Microsoft Exchange Server is a robust email server
     platform that offers email, calendar, and collaboration services for
     businesses. It provides features such as email encryption, anti-spam, and
     anti-malware protection to secure email communications.
4. **Backup Services**:
   - **Software**: Veeam Backup & Replication
   - **Product Description**: Veeam Backup & Replication is a comprehensive
     backup and disaster recovery solution that offers data protection for
     virtual, physical, and cloud-based workloads. It provides reliable backup,
     replication, and recovery capabilities to ensure data integrity and
     business continuity.
5. **Print Services**:
   - **Hardware**: Brother HL-L5100DN Monochrome Laser Printer
   - **Product Description**: Brother HL-L5100DN is a reliable monochrome laser
     printer suitable for office environments. It offers fast printing speeds,
     high-quality output, and built-in networking capabilities for seamless
     integration into the internal services network.
6. **File Share**:
   - **Software**: Nextcloud
   - **Product Description**: Nextcloud is an open-source file sharing and
     collaboration platform that offers secure file storage, synchronization,
     and sharing capabilities. It provides features such as versioning,
     encryption, and access control to facilitate secure and efficient file
     sharing within the organization.
7. **Internal DNS Server**:
   - **Software**: BIND (Berkeley Internet Name Domain)
   - **Product Description**: BIND is a widely used open-source DNS server
     software that provides reliable domain name resolution services for
     internal resources. It offers robustness, flexibility, and extensive
     feature set to ensure reliable network connectivity and access to internal
     services.

By deploying these hardware and software solutions, Tech-R-LY can establish a
resilient Internal Services Network that centralizes essential services,
promotes collaboration and productivity, and ensures the security and integrity
of corporate resources and data.

