---
layout: post
title: Management of Alarm Systems for the Process Industries 
subtitle: An Introduction to Alarm Management System
cover-img: /assets/img/alarm.jpg
gh-badge: [star, fork, follow]
tags: [Alarm Management]
comments: true
---
# Introduction to Alarm Management
### Background

Prior to the era of distributed control systems (DCS), creating an alarm was manual, time consuming and expensive. A process control system had few dozen alarms that an operator to easily monitor and act upon each one immediately.

The introduction of distributed control systems (DCS) changed the traditional alarm systems. It becomes so easy to add new alarms for instruments linked to a DCS, leading to an alarm overload on the operating console of the DCS. Operators are overloaded with hundred of alarms that may not be relevant and where in the event of a serious incident, can cause an alarm flooding (interfering with the operator’s ability to understand and respond correctly to the situation).

### What is an Alarm system?
An Alarm system is a system designed to help the operator by drawing his attention towards plant conditions requiring timely assessment or action.

### Why is Alarm management Important?

Alarm management refers to the processes and practices for determining, documenting, designing, monitoring, and maintaining alarm messages from process automation and safety systems.

Alarm management systems are necessary to prevent operator information overload by reducing the number of alarms and assist in the detection of the cause of the alarm event to ensure safe and speedy rectification of the problem.

Accident investigations have revealed that poor alarm system performance contributed to a significant number of industrial accidents.
The top 4 major accidents in the history are: 

• Three Mile Island - 1979

• Piper Alpha - 1988

• Milford Haven Refinery - 1994

• Buncefield Oil Storage - 2005

### Guideline, Regulations and Standards

A distinguishing between Guideline and Standard/Or Regulation shall be etablished beforehand. 

A standard specifies uniform uses of specific technologies or configurations, while a guideline provides general guidance, and additional advice and support for policies, standards or procedures. Below are the main guideline and standards used for Alarm management.

1. **Guideline**

**EEMUA 191 - Alarm Systems - A Guide to Design, Management and Procurement published by the Engineering Equipment and Material Users Association (EEMUA).**

It is primarily concerned with alarm systems provided for people operating industrial processes. These include alarm systems in industries such as chemical manufacture, power generation, oil and gas extraction and refining and others.

2. **Standards**

**ANSI/ISA 18.2 Management of Alarm Systems in the Process Industries published by the international society of automation (ISA).**

This standard specifies general principles and processes for the lifecycle management of alarm systems based on programmable electronic controller and computer-based human-machine interface (HMI) technology for facilities in the process industries. It covers all alarms presented to the operator through the control system, which includes alarms from basic process control systems, annunciator panels, packaged systems (e.g., fire and gas systems, and emergency response systems), and safety instrumented systems.

**IEC 62682 Management of Alarm Systems in the Process Industries** (based on ANSI/ISA 18.2 )

This standard was written as an extension of the existing ISA 18.2-2009 standard which utilized numerous industry alarm management guidance documents in its development such as EEMUA 191.

3. **Technical Report**

**ISA-TR18.2.5-2012** (helps understand and use ANSI/ISA 18.2  / also an excellent resource for interpreting alarm metrics and common causes.)


# Design of Alarm Management system

### Core Principles

- **Usability :** It ensures that the design of the alarm system can adapt to the needs of the user and operate within the constraints of the user
- **Safety :** EEMUA 191 states that "the contribution of alarm system to protecting the safety of people, the environment, and plant equipment should be clearly identified".
- **Performance monitoring :** According to the EEMUA Guideline, the performance of the alarm system should be assessed during design and commissioning to ensure that it is usable and effective under all operating conditions.
- **Investment in engineering :** EEMUA states that alarm systems should be engineered to suitably high standards in a structured methodology


### What's a good Alarm ?

- Each alarm should alert, inform and guide.
- Every alarm should be relevant to the operator.
- Every alarm should have a defined response.
- Alarms shall be designed in a way that allows the operator a sufficient time to carry out a defined response (taking into account the human limitation).

### Alarm System Lifecycle

The lifecycle of an alarm is system as presented in the ISA 18.2 Standard is as below and it covers the alarm system from its specification through design to operation and finally to its eventual decommissioning :
<img width="495" align="center" alt="image" src="https://user-images.githubusercontent.com/43297808/151704192-8238dd10-2cfa-4dc7-9197-4735b8198595.png">

[image source] (https://www.isa.org/intech-home/2018/march-april/features/alarm-management-life-cycle)

1. **Philosophy/Company Standard**

The Alarm management philosophy document (the company’s standard) establishes the guidelines for how to address all aspects of alarm management, and include (but not limited to):

- Definition of what an alarm should be
- Definitions of alarm system performance targets
- Dictionary of terms and abbreviations to be used in alarm messages
- Guidance on content and structure of alarm response definitions (e.g. procedures, task aids, etc.)
- Guidance on interpreting patterns of alarms

2. **Alarm Rationalisation**

Alarm rationalization is a key stage in the alarm management lifecycle defined in ISA-18.2. It's goal is to establish the optimum set of alarms needed to keep the process safe and within normal operating limits. The alarm rationalisation is a process where team of plant stakeholders review, establish, and document that each alarm meets the standard for being an alarm as set up in a company’s alarm philosophy documents.
This assessment of alarms is done by examining the actual alarm system configuration and detailed analysis of alarm history and requires the follow information: 

**Alarm configuration**
- Alarm priorities.
- Alarm thresholds.
- Alarm messages.

**Alarm history**
- Basic alarm rates.
- Identification of most frequent alarms.
- Multiple alarms.
- Standing alarms.
- Location of plant incidents.

**Historical data (digital and analogue)**
- Identification of the cause.
- Indication of what changes could be made.

**System capability**
- Alarm displays.
- Alarm priorities.
- Audible alarm sounders and outputs.
- Alarm inhibiting and hiding.

# Alarm Issues

