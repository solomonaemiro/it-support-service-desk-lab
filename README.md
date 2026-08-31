# IT Support & Service Desk Lab — osTicket

A hands on IT Support and Service Desk laboratory built to simulate a small organization's internal technical support environment and the types of incidents handled by an IT Support, Help Desk, or Service Desk Technician.

The project uses osTicket, hosted on an Ubuntu Server virtual machine with Apache, PHP, and MariaDB. A Windows workstation was used as the end user troubleshooting environment for reproducing and investigating practical support incidents.

The project goes beyond ticket creation by demonstrating the complete support process from user report → ticket submission → triage → investigation → diagnosis → resolution → verification → customer communication → closure.

---

## Project Objective

The goal of this project was to build a functional Service Desk environment and use it to practice realistic IT Support workflows rather than simply configuring a ticketing application.

The lab focuses on practical skills relevant to:

- IT Support
- Help Desk
- Service Desk
- Desktop Support
- IT Technician
- Technical Support
- Junior IT Support roles

The project emphasizes evidence based troubleshooting, clear documentation, appropriate user communication, and verification of resolutions.

---

## Lab Environment

Component| Configuration   

Service Desk| osTicket  
Server OS| Ubuntu Server  
Web Server| Apache  
Database| MariaDB  
Scripting Platform| PHP  
Virtualization| Oracle VirtualBox  
End-User OS| Windows  
Server Hostname| "osticket-server"  
Linux User| "*******"  
Documentation| MkDocs  
Documentation Theme| Material for MkDocs  
Version Control| Git  
Hosting| GitHub Pages  

The environment was built as a controlled laboratory rather than a production service desk.

---

## What I Built

The project included:

- Ubuntu Server virtual machine
- Apache web server
- PHP runtime
- MariaDB database
- osTicket Service Desk
- Support department
- Support agent accounts
- Help Topics
- Ticket priorities
- SLA plans
- Ticket assignment and ownership
- Email identity configuration
- Knowledge Base
- Public FAQ articles
- End-user ticket submission
- Internal ticket notes
- Customer facing responses
- Ticket verification and closure
- Windows troubleshooting environment
- Network and DNS diagnostic testing
- MkDocs technical documentation
- GitHub Pages deployment

The environment was designed to simulate how an internal IT Support team receives, investigates, documents, resolves, and closes user incidents.

---

## Service Desk Ticket Scenarios

Practical support tickets were created and worked through the Service Desk workflow.

01| Internet Access Issue  
02| Black Screen After Login  
03| Zoom Microphone Access  
04| Amharic Keyboard Layout Setup  

Each scenario involved investigation of the reported symptoms, collection of technical evidence, application of an appropriate resolution, verification of the result, documentation, customer communication, and ticket closure.

The scenarios were designed around actual reproducible Windows troubleshooting.

---

## Complete Service Desk Workflow

The project demonstrates the complete incident lifecycle:
```text
User Reports Issue
        ↓
Ticket Submitted
        ↓
Initial Triage
        ↓
Assignment / Ownership
        ↓
Investigation
        ↓
Evidence Collected
        ↓
Diagnosis
        ↓
Resolution Applied
        ↓
Functionality Verified
        ↓
Internal Documentation
        ↓
Customer Communication
        ↓
Ticket Closed
```

---

## Technical Troubleshooting

The Windows troubleshooting portion of the project covered four common Level 1 support scenarios.


### Windows Shell Troubleshooting

Investigated a black screen after login and restored the Windows desktop by manually launching:

explorer.exe

### Application Permissions

Investigated a Zoom microphone problem and identified Windows microphone privacy permissions as the relevant configuration area.

### Language & Keyboard Configuration

Configured Amharic language support and keyboard input switching so the user could switch between configured input languages and enter Amharic text.

---

## Network & DNS Troubleshooting

The project included a practical Internet access troubleshooting scenario.

Diagnostic tools included:

ipconfig /all  
nslookup google.com  
ping google.com  

These were used to examine:

- IPv4 configuration
- Default gateway
- DNS configuration
- Hostname resolution
- External connectivity
- Packet loss


---

## Knowledge Base

An end user Knowledge Base was created to provide self service guidance for common Level 1 IT Support problems.

The Knowledge Base contains 8 public FAQs organized into four support categories:

### Windows & Software

- Windows Computer Running Slowly
- Windows Application Not Responding

### Network & Connectivity

- Wi-Fi Connectivity Problems
- Connected to Wi-Fi but No Internet Access

### Accounts & Access

- Account Locked
- Login Problem

### Hardware & Peripherals

- Keyboard Problem
- Printer Not Printing

The FAQs were written from an end user perspective using clear, step-by-step instructions and appropriate escalation guidance.

The purpose was to demonstrate how recurring support issues can be documented so users can attempt safe self service troubleshooting before opening a ticket.

---

###  Service Desk Configuration

The osTicket environment was configured to simulate the operational structure of a small internal IT Support team.

Configuration included:

- Support department
- Support agents
- Help Topics
- Ticket priorities
- SLA plans
- Ticket settings
- Email identity
- Knowledge Base
- FAQ categories
- Ticket queues
- Alerts and notices
- Autoresponder configuration
- Attachment configuration

The configuration provided the foundation for the practical support scenarios and ticket workflow.

---

###  Documentation & Communication

The project demonstrates two distinct forms of ticket documentation.

Internal Technical Documentation

Internal notes were used to record:

- User-reported symptoms
- Diagnostic tests
- Technical findings
- Root-cause information
- Actions performed
- Verification results

Customer Communication

Customer facing responses were written separately from technical notes.

The responses focused on:

- Explaining the outcome clearly
- Avoiding unnecessary technical terminology
- Confirming whether the issue was resolved
- Providing relevant user guidance
- Explaining whether further action was required

This separation reflects a common Service Desk practice where technical investigation details and customer communication serve different purposes.

---

###  Evidence Based Documentation

The project documentation is supported by screenshots captured during the actual lab work.

Screenshots are placed alongside the relevant configuration, troubleshooting, or workflow step.

The documentation demonstrates:
```text
Configuration
      ↓
Investigation
      ↓
Technical Evidence
      ↓
Resolution
      ↓
Verification
      ↓
Documentation
```
Screenshots provide evidence of the Service Desk configuration, Knowledge Base, ticket workflow, Windows troubleshooting, network diagnostics, and completed ticket scenarios.

---

## Tools & Technologies

Technology / Tool| Demonstrated Use  
osTicket| Service Desk and ticket management  
Ubuntu Server| Linux server environment  
Apache| Web server  
PHP| osTicket application runtime  
MariaDB| Database backend  
VirtualBox| Virtualization  
Windows| End-user troubleshooting  
Task Manager| Windows diagnostics  
Safe Mode| Troubleshooting and isolation  
"ipconfig"| Network configuration diagnostics  
"nslookup"| DNS testing  
"ping"| Connectivity testing  
Git| Version control  
MkDocs| Technical documentation  
Material for MkDocs| Documentation presentation  
GitHub Pages| Portfolio hosting  

---

##  Skills Demonstrated

### Service Desk Operations

- Ticket management
- Ticket categorization
- Ticket assignment and ownership
- Priority management
- SLA awareness
- Internal documentation
- Customer communication
- Ticket verification
- Ticket closure

### Windows Support

- Windows application troubleshooting
- Windows shell troubleshooting
- Windows privacy and permissions
- Language and keyboard configuration

### Networking & Diagnostics

- IP configuration analysis
- DNS troubleshooting
- Connectivity testing

###  User Support

- User-reported issue analysis
- Clear troubleshooting instructions
- Customer-facing communication
- Appropriate escalation
- End-user Knowledge Base development

### Technical Documentation

- Incident documentation
- Troubleshooting evidence
- Resolution documentation
- Verification records
- Knowledge Base articles
- Structured technical documentation

---

###  Key Takeaways

The most important lesson from this project was that effective IT Support is not simply about finding a technical fix.

A professional support process combines:
```text
User Report
    ↓
Investigation
    ↓
Evidence
    ↓
Diagnosis
    ↓
Resolution
    ↓
Verification
    ↓
Documentation
    ↓
Communication
    ↓
Closure
```
The project reinforced several important Service Desk principles:

- User reports are starting points, not diagnoses.
- Troubleshooting should be systematic.
- Technical changes should be supported by evidence.
- Simple fixes can still require good diagnosis.
- Verification is part of the resolution.
- Internal documentation creates continuity.
- Customer communication should match the audience.
- Not every problem requires a configuration change.
- Knowledge Base content can reduce repetitive support requests.
- Ticket management is an important part of technical support.

---

###  Project Outcome

The completed lab demonstrates practical exposure to both technical troubleshooting and Service Desk operations.

It provides hands on evidence of experience with:

IT Support • Service Desk Operations • osTicket • Windows Troubleshooting • Network Troubleshooting • DNS Diagnostics • Application Support • User Support • Ticket Management • SLA Management • Knowledge Base Management • Technical Documentation • Incident Resolution • Customer Communication • Problem Solving

The project demonstrates the ability to work through support incidents from initial user report to verified resolution and ticket closure rather than treating technical troubleshooting and Service Desk processes as separate activities.

---

## Full Documentation

Complete project documentation live:

[https://solomonaemiro.github.io/it-support-service-desk-lab/]

Project repository:

[https://github.com/solomonaemiro/it-support-service-desk-lab]

The full documentation contains the detailed lab environment, osTicket configuration, Knowledge Base, ticket scenarios, troubleshooting evidence, Service Desk workflow, skills demonstrated, and lessons learned.

---