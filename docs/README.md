<h1 align="center">DOCUMENTACIÓN DEL PROYECTO</h1>
<br>



# **Introducción**
For this project I have used Zane Ryan's video, entitled "¿Montar un SOC por componentes o implementar un todo en uno?", where the speaker explains the services that make up a SOC, both in theory and in practice. Later, for the more technical implementation I have used another video by Maurice Frayssinet uploaded to the YouTube platform entitled "Implementing the Security Operations Center (SOC)". In it we can see a series of more in-depth definitions, unlike Zane Ryan's video.

**This introduction is constantly changing, as resources and their sources are added to the project they will be added to the current section.**

&nbsp;

## **What is a SOC?**
A SOC is traditionally a physical facility within an organization, which houses an information security team. This team analyzes and monitors the organization's security systems. The SOC's mission is to protect the company from security breaches by identifying, analyzing, and reacting to cybersecurity threats. SOC teams are comprised of managers, security analysts, and sometimes security engineers. The SOC works with the company's IT development and operations teams (Frayssinet, 2022).

A SOC was once thought to be only suitable for large companies. Today, many smaller organizations are establishing lightweight SOCs, such as a hybrid SOC, which combines internal or part-time staff with no hired experts, or a virtual SOC, which has no physical facility at all, and is a team of internal staff that also performs other functions (Frayssinet, 2022).

SOCs are a proven way to improve threat detection, distribute the likelihood of security breaches, and ensure an appropriate organizational response when incidents occur. SOC teams isolate unusual activity on servers, databases, networks, endpoints, applications, etc., identify security threats, investigate them, and react to security incidents as they occur (Frayssinet, 2022).

### **How ​​a SOC Works**
An organization must first define its security strategy and then provide an appropriate infrastructure for the SOC team to work with. The information system underlying SOC activity is a security information and event management (SIEM) system, which collects logs and events from hundreds of security tools and organizational systems and generates actionable security alerts, which the SOC team can analyze and respond to.

### **SOC Core Responsibilities**

**Security Monitoring Tools Maintenance**
The team must maintain and update tools regularly. Without the right and most up-to-date tools, they cannot adequately protect systems and networks. Team members must maintain the tools used in each part of the security process.

**Security Monitoring Tools Maintenance**
The SOC team must investigate suspicious and malicious activity within networks and systems. Generally, your SIEM or analytics software will issue alerts that the team will then analyze and examine, triage, and uncover the scope of the threat.

## **SOC Types**
There are different approaches to implementing a Security Operations Center (SOC), each with its advantages and disadvantages depending on the organization's needs and capabilities. Below are three main options: building a componentized SOC, opting for an all-in-one SOC, or outsourcing the service to a third party. Each one presents different levels of customization, cost, complexity and implementation, which will allow companies to choose the most appropriate solution for their context.


#### **Option 1 - Build a SOC by components**

**Disadvantages:**
- Buy SOC parts one by one
- From different manufacturers or even the same manufacturer
- Integrate them
- Customize them
- Have programmers with experience in cybersecurity
- Recruit a team of security analysts
- Create a 24 x 7 x 365 security operations center
- Continuous training for the security team
- Manage and implement updates for different programs
- Manage purchases with different manufacturers
- Long implementation and production time

**Advantages:**
- Gain greater knowledge and experience in the field of cybersecurity
- Greater ability to customize the environment
- End up with a service very tailored to your needs

___
#### **Option 2 - Build an All-in-One SOC**

**Advantages:**
- No need to evaluate a ton of products
- No need to integrate different products
- No need for a team of programmers
- No need to worry about compatibility issues when making updates
- Fast rollout
- Unlimited scalability
- Native Multi-Tenant
- No need to manage purchases from multiple manufacturers
- Short implementation time

**Disadvantages:**
- You have to install and maintain the software
- You have to set up a SOC
- Have a team of analysts
- Train and retain them

___
#### **Option 3 - Outsourcing the service to a third party**

**Advantages:**
- You eliminate the disadvantages of the two previous options
- You take advantage of the advantages of the two previous options
- You will have the possibility of requesting customizations according to your circumstances
- Cost can be lower depending on the volume scale that the MSSP has
- Very short start-up time
- Benefit from the extensive experience of the service provider since it will have multiple clients

**Disadvantages:**
- Dependence on a third party
- Without the benefit of gaining knowledge and experience by not having an internal SOC
- Less possibilities for customizations
- Cost can be higher

&nbsp;

## **SOC Deployment Models**
There are a variety of Security Operations Center (SOC) deployment models, each tailored to the organization’s needs and capabilities. These models range from dedicated SOCs with internal staff and resources, to more flexible options such as virtual SOCs or third-party managed services (MSSP/MDR). The most common models are detailed below, which vary in operational structure, level of customization, and reliance on external resources.

### **Dedicated SOC**
Classic SOC with dedicated facilities, full-time dedicated staff, operated entirely in-house, 24x7 operations. Distinguished by its complete independence and autonomy, unlike the others, it offers the greatest control and customization, but entails high costs and operational complexity.

### **Distributed SOC**
Distributed SOC is based on the decentralization of security operations, using both full-time and part-time staff. This model allows monitoring tasks to be divided geographically or by areas of specialization, which optimizes the use of resources. Generally, its operation is limited to a standard 8x5 business schedule in each region where it operates. This can result in less surveillance coverage during non-business hours, although it also reduces costs and facilitates integration into companies with fewer needs for uninterrupted security.

### **Multifunctional SOC/NOC**
This type of SOC combines the functions of a Security Operations Center (SOC) and a Network Operations Center (NOC) in a single facility. This integration allows the dedicated team to manage both network infrastructure and security, offering a more efficient and cost-effective solution. However, it requires staff to possess specialized skills in both areas, which can complicate hiring and training. This approach is ideal for organizations looking to maximize the use of their resources and maintain centralized oversight of all operational aspects.

### **Fusion SOC**
The fusion SOC represents an evolution of the traditional model, adding advanced capabilities such as threat intelligence integration and security management across operational technology (OT) environments. This allows for a more complete view of risks and the ability to proactively respond to emerging threats. This model is particularly useful for organizations that manage critical infrastructure or want security that is more integrated with their operational processes. However, its implementation requires careful planning and the acquisition of new technical skills.

### **SOC Command/Global SOC**
This model acts as a centralized coordination center to manage and oversee other distributed SOCs within a global enterprise. Its primary function is to consolidate threat intelligence, maintain situational awareness, and provide strategic guidance to regional teams. This approach is ideal for large, multinational corporations, as it allows for standardizing procedures and improving overall incident response. It also facilitates communication across regions and ensures that security decisions are aligned with corporate objectives.

### **Virtual SOC**
The virtual SOC stands out for its flexibility and low cost, as it does not require physical facilities or permanent staff dedicated exclusively to security operations. This model is activated only in response to high-priority incidents or critical alerts, making it an efficient option for organizations with limited resources. In addition, the term is also used to describe solutions provided by external managed security service providers (MSSPs), allowing for partial or full outsourcing of SOC functions.

### **Managed SOC/MSSP/MDR**
Many organizations are turning to managed security service providers (MSSPs) to provide SOC services on an outsourced basis. Modern offerings are called Managed Detection and Response (MDR). Managed SOCs can be fully outsourced or co-managed with in-house security staff.

&nbsp;

## **Organizational Table**
The table below summarizes the main options and deployment models for a Security Operations Center (SOC), highlighting their key features along with a practical assessment of their complexity, estimated cost, and use cases. It ranges from highly customizable solutions, such as componentized SOCs that require significant resources, to outsourced options such as MSSPs, ideal for small and medium-sized businesses. Hybrid and global combinations are also covered, offering flexibility for organizations with distributed operations. This classification aims to facilitate the choice of the appropriate model according to the needs, capabilities, and budget of each organization.


|             **Opción**             | **Modelos de Implementación**                                                                                                                                                                                                         | **Complejidad** | **Coste Estimado** |                **Ejemplo de Uso**                 |
| :--------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :-------------: | :----------------: | :-----------------------------------------------: |
| **Opción 1 - SOC por componentes** | - **SOC dedicado**: SOC clásico con instalaciones y personal dedicados, operando 24x7 completamente internas                                                                                                                          |      Alta       |      Muy alto      |      Grandes empresas con recursos internos       |
|   **Opción 2 - SOC todo en uno**   | - **SOC/NOC multifuncional**: Combina funciones de Centro de Operaciones de Red (NOC) y Centro de Operaciones de Seguridad (SOC)<br><br>- **SOC de fusión**: Incorpora inteligencia de amenazas y tecnología operativa (OT)           |      Media      |        Alto        |      Organizaciones con necesidades híbridas      |
|   **Opción 3 - Externalización**   | - **SOC/MSSP/MDR administrado**: Servicios SOC subcontratados a proveedores de seguridad<br><br>- **Virtual SOC**: Equipo reactivo sin instalaciones dedicadas                                                                        |      Baja       |      Variable      |      Pymes que buscan externalizar seguridad      |
|    **Combinaciones Especiales**    | - **SOC distribuido**: Personal a tiempo completo y parcial operando en horarios 8x5 según región<br><br>- **Comando SOC/SOC global**: Coordina SOC a nivel global, proporcionando inteligencia de amenazas y orientación estratégica |   Media-Alta    |        Alto        | Empresas globales con operaciones interconectadas |

&nbsp;

## **SOC Roles and Responsibilities**

### **Security Analyst**
The first to respond to incidents. Their response typically occurs in three stages:
- Threat Detection
- Threat Investigation
- Timely Response

Security analysts must also ensure that proper training is in place and that staff can implement policies and procedures. Security analysts work alongside internal IT staff and business managers to communicate information about security limitations and develop documentation.

### **Security Engineer/Architect**
Maintains and suggests monitoring and analysis tools. They create a security architecture and work with developers to ensure that this architecture is part of the development cycle. A security engineer can be a software or hardware specialist who pays close attention to security aspects when designing information systems. They develop tools and solutions that enable organizations to effectively prevent and respond to attacks. They document procedures, requirements, and protocols.

### **SOC Manager**
Manages the SOC team and reports to the CISO. They oversee the security team, provide technical guidance, and manage financial activities. The SOC Manager oversees the activity of the SOC team, including hiring, training, and evaluating staff. Additional responsibilities include creating processes, evaluating incident reports, and developing and implementing crisis communication plans. They write compliance reports, support the audit process, measure SOC performance metrics, and report on security operations to business leaders.

### **CISO**

Defines the organization's security operations. They communicate with management about security issues and oversee compliance tasks. The CISO has the final say on the organization's cybersecurity-related policies, strategies, and procedures. They also have a central role in compliance and risk management, and implement policies to meet specific security demands.

&nbsp;

# **Justification**

The design and implementation of a domestic SOC aims to demonstrate my skills and knowledge acquired in the analysis and response to cybersecurity incidents, especially in the role of L1 analyst. This project is structured to reflect the typical functions and responsibilities of a SOC, which will allow me to practically apply the knowledge gained during my training. In the case of a security analyst, who is the central figure in this project, my focus will be on the detection, investigation, and response to security incidents. The L1 analyst is the first line of defense, responsible for detecting threats through monitoring systems, investigating alerts, and responding appropriately and quickly. As part of this project, I will work to configure the necessary tools to identify threats, process alerts, and document incidents, which simulates the daily responsibilities of a security analyst.

Although the project does not cover the functions of security engineers or SOC managers, it is relevant to understand how these roles influence the infrastructure and operation of the SOC. In this project, I will focus primarily on configuring tools, implementing systems for security data collection and analysis, and continuously improving these systems, reflecting the core tasks of a security analyst who works closely with these other roles. The **CISO**, while not directly responsible for day-to-day operations in a small SOC, plays an important role in creating security policies. This project aligns with the cybersecurity and compliance strategies defined by a CISO, as the work structure and documentation I generate will be a reflection of the policies and procedures a SOC must follow.

Through simulating these functions and roles within a controlled environment, this project seeks to not only demonstrate my technical skills, but also my ability to work in a team and collaborate in identifying and resolving security issues in a practical context, aligned with the goals and expectations of an L1 analyst in a professional cybersecurity environment.

### **Type of SOC chosen**
For the development of this project, I have chosen to implement a **virtual SOC** due to several reasons that facilitate the creation of a security operations center in a domestic environment. The main advantage of a virtual SOC is the flexibility and reduction of costs associated with physical infrastructure, since by not requiring dedicated facilities or a team of full-time staff, I can manage the entire process from a controlled environment at home, which makes it possible to adapt the project to my available capabilities and resources.

In addition, the virtual SOC offers remarkable scalability, since it allows you to start with a basic configuration and add functionalities as your needs or experience grow. This makes it a practical solution for small projects like this one, domestic or learning environments, with limited resources. In addition, its implementation is accessible thanks to the wide availability of open source or low-cost tools, which facilitates its adoption without compromising the budget. Finally, it stands out for its speed of implementation, avoiding the long times associated with physical installations and allowing it to be operational in a much shorter period of time.

### **Project Limitations**
One of the limitations I would face when opting for a **dedicated SOC** would be the need to manage a more complex physical infrastructure, which, in addition to increasing costs, would require more time and effort to maintain the tools and configure the networks and servers. This type of implementation would also imply greater complexity in hiring resources, such as security analysts or programmers, something not very feasible for a personal project in which a self-taught experience is sought.

### **Project Advantages**
On the other hand, by opting for a virtual SOC, I not only optimize resources, but I can integrate security tools and solutions in a modular way, adapting the tools to my needs and learning about each component in a more practical and efficient way. Although in a virtual SOC some control over the infrastructure is lost, the possibility of activating tools and capabilities only when necessary allows me to simulate a real environment efficiently.

In short, a **virtual SOC** will allow me to work more flexibly and cost-effectively, while keeping the focus on acquiring practical knowledge without being overloaded with logistical tasks. In addition, this model gives me the opportunity to integrate security solutions in a scalable way, which is ideal for a project like the one I am undertaking.

&nbsp;


# **Project Objectives**

The purpose of this project is to design, implement and document a functional Security Operations Center (SOC) in a domestic environment, using accessible tools and appropriate techniques to develop practical experience in cybersecurity. Through this process, it is intended to gain a deeper understanding of SOC principles and practices, and acquire skills that are relevant to future career opportunities in the cybersecurity field.

### **General Objectives**
To design, implement and document a functional SOC (Security Operations Center) in a domestic environment, using accessible tools and techniques, with the purpose of:

1. **Develop practical skills** in analysis, monitoring and response to cybersecurity threats.
2. **Gain demonstrable experience** that is relevant to professional roles in the cybersecurity field.

### **Specific Objectives**

1. **Study of Fundamental Concepts**
- Understand the key services and functions that make up a SOC, integrating both theoretical and practical aspects
- Research and apply security information and event management (SIEM) principles

2. **Technical Implementation**
- Set up a home environment that simulates a functional SOC, using a modular architecture based on Zane Ryan's recommendations
- Incorporate specific tools for the collection, analysis and visualization of security data, based on the methodology explained by Maurice Frayssinet

3. **Practice in Detection and Response**
- Set up systems to identify and manage alerts generated by suspicious activities
- Develop skills in log analysis, incident classification and reaction to security threats in real time

4. **Documentation and Disclosure**
- Record daily progress, technical decisions and results obtained to create a useful resource for others interested in the cybersecurity
- Publish the results in a public repository as a demonstration project, demonstrating acquired skills and technical knowledge

5. **Automation and Optimization**
- Implement automation solutions in the SOC to improve efficiency in incident detection and response.
- Evaluate and adjust the tools used according to the results and the needs of the environment.

6. **Preparation for Certifications**
- Align the practical experience obtained with the theoretical and technical requirements of relevant certifications such as **BTL1**.

&nbsp;

# **Planning and Execution of the Home SOC**
### **Availability and Schedules**
In this project, a 24x7 model will be chosen, which is best suited to simulate a functional home SOC that can detect, respond to, and investigate incidents in real time. Although it may be expensive to have a full-time dedicated team in a real environment, simulating this model allows for covering any potential security incident at any time, which is essential to ensure security at all times.

### **Format**
This project will use a standalone SOC, rather than an integrated SOC and NOC. The reason behind this is the intention to focus exclusively on monitoring and responding to security incidents, without the need to manage the network and service infrastructure. A standalone SOC will allow for greater specialization in the area of ​​cybersecurity, with the main focus on protecting IT assets.

### **Organization**
In this case, the project will plan to control everything at home. While an MSSP (Managed Security Service Provider) model could be an option in enterprise environments, this project will focus on implementing a homegrown SOC without outsourcing services. An MSSP refers to a third-party provider that manages and oversees an organization's security, offering services such as monitoring, analysis, and incident response. The reason for opting for the "in-house" model is to learn first-hand the processes involved in managing a SOC, such as threat detection, incident response, and tool configuration.

### **Priorities and capabilities**
In this project, security will be the primary concern. While regulatory compliance is important, ensuring the protection of IT assets from cyber attacks and threats will be the top priority. In terms of capabilities, monitoring will be the top priority. Tools will be set up to detect intrusions and anomalies in real time, but basic ethical hacking capabilities will also be included, such as penetration testing and attack simulation to assess the robustness of the security infrastructure. This comprehensive approach will cover both protection and vulnerability assessment. As for the cloud, the project will not prioritize extensive use, as it will focus on a simulated local environment, although aspects related to remote access and possible integrations with cloud services will be considered.

### **Environment**
The environment will be local, without a hybrid or exclusively cloud-based infrastructure. The main reason for choosing this approach is to create a functional home SOC that simulates a traditional environment, using local hardware and software. This allows direct control of all SOC components, learning how to manage tools, and making adjustments based on project needs without relying on external services. Although a hybrid environment could offer greater flexibility, in this case a simpler and more direct approach is sought for the implementation of a home SOC.

&nbsp;

# **Defense in depth**
In progress

&nbsp;

# Tools used
In progress


&nbsp;


# **Bibliografía**

Frayssinet, M. (2022). Implementación del Centro de operaciones de seguridad (SOC) "Implementación del Centro de operaciones de seguridad (SOC)". YouTube: https://www.youtube.com/watch?v=QyEGELTFkvU.

Frayssinet, M. (2022). Implementación del Centro de operaciones de seguridad (SOC) con Wazuh. YouTube: https://www.youtube.com/watch?v=frzsfkiEL6A&list=PLzumfvfzw5l9l8LB1mLQpTbH3BTdFaTuO&index=2

Ryan, Z. (2022). # CYBERCLOUDSUMMIT22](https://www.youtube.com/hashtag/cybercloudsummit22): ¿Montar un [#SOC](https://www.youtube.com/hashtag/soc) por componentes o implementar un todo en uno? @Dotforce. Youtube: https://www.youtube.com/watch?v=gM_Y_0zUdmA

Kral, P. (2021). *Incident Handler's Handbook*. GIAC Certifications, SANS Institute.

Image taken from: https://x.com/Fisher85M/status/1579782478285672449
