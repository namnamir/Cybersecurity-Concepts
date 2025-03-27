# NIST 800-160: Cyber Resiliency

NIST SP 800-160 focuses on the property of **cyber resiliency**, which is defined as the ability to:
- *Anticipate*: Predict and prepare for adverse conditions, stresses, attacks, or compromises.
- *Withstand*: Resist and endure adverse conditions or attacks.
- *Recover*: Restore functionality and operations after an adverse event.
- *Adapt*: Adjust to changing conditions and learn from past experiences.

## Levels of Cyber Resiliency
Cyber resiliency can be applied at multiple levels, including:
- **System Elements**: Individual components of a system.
- **Systems**: Entire systems or subsystems.
- **Missions or Business Functions**: Specific organizational objectives or tasks.
- **System-of-Systems**: Interconnected systems supporting broader functions.
- **Organizations, Sectors, and Regions**: Larger-scale entities or geographic areas.
- **The Nation or Transnational Missions/Business Functions**: National or global operations.

## Purpose of Cyber Resiliency
From an enterprise risk management perspective, cyber resiliency aims to reduce mission, business, organizational, or sector risks associated with potentially compromised cyber resources.

## Types of Systems Addressed in NIST 800-160
The document identifies considerations for engineering the following types of systems that depend on cyber resources:
1. **General-purpose or Multi-use Systems**: Examples include enterprise information technology (EIT), shared services, or common infrastructures.
2. **Dedicated or Special-purpose Systems**: Examples include security-dedicated or security-purposed systems.
3. **Large-scale Processing Environments**: Systems designed for high-volume data processing.
4. **Cyber-physical Systems (CPS)**: Systems that integrate computation, networking, and physical processes.
5. **Internet of Things (IoT) or Network of Things (NoT) Devices**: Devices interconnected via the internet or other networks.
6. **Systems-of-Systems**: Examples include critical infrastructure systems (CIS).

# Fundamentals

Cyber resiliency focuses on ensuring systems can withstand, recover from, and adapt to adverse conditions, whether caused by adversarial or non-adversarial threats. This is achieved through a combination of goals, objectives, techniques, and design principles.

**Key Concepts:**
1. **Goals and Objectives**: Define the **“what”** of cyber resiliency—what properties and behaviors are essential for resilient systems.
2. **Techniques and Design Principles**: Define the **“how”**—the methods and approaches to achieve or improve resiliency.
3. **Constructs**: Address both adversarial and non-adversarial threats from cyber and non-cyber sources.
4. **Engineering Practices**: Use methods, processes, and analytical techniques to design solutions that meet stakeholder requirements and protection needs.

## Cyber Resiliency Engineering Framework

The framework includes goals, objectives, techniques, implementation approaches, and design principles. These constructs can be applied at various levels, such as systems, organizations, or sectors.

![NIST 800-160 | Cyber Resiliency Framework](img/tobeputlater.png)

### Cyber Resiliency Goals

Cyber resiliency goals provide a foundation for risk management decisions across different levels of an organization. The four primary goals are:

1. **Anticipate**: Predict and prepare for potential threats or adverse conditions.
2. **Withstand**: Resist and endure attacks or adverse conditions.
3. **Recover**: Restore functionality after an adverse event.
4. **Adapt**: Adjust to changing conditions and learn from past experiences.

![NIST 800-160 | Cyber Resiliency Goals](img/tobeputlater.png)

### Cyber Resiliency Objectives

Cyber resiliency objectives are specific outcomes systems should achieve to meet stakeholder needs. These objectives can be tailored to reflect organizational missions or operational concepts.

#### Objectives and Descriptions
- **Prevent or Avoid**: Preclude successful attacks or adverse conditions.
- **Prepare**: Maintain realistic courses of action for anticipated adversity.
- **Continue**: Maximize the duration and viability of essential functions during adversity.
- **Constrain**: Limit damage from adverse events.
- **Reconstitute**: Restore as much functionality as possible after adversity.
- **Understand**: Maintain awareness of dependencies and resource status.
- **Transform**: Modify workflows and processes to handle adversity effectively.
- **Re-Architect**: Redesign system architectures to address adversity and environmental changes.

### Cyber Resiliency Techniques and Approaches

The framework identifies 14 techniques to achieve cyber resiliency. These techniques are interdependent and can address both adversarial and non-adversarial threats.

#### Techniques:
1. **Adaptive Response**: Implement agile courses of action to manage risks.
2. **Analytic Monitoring**: Continuously monitor and analyze system behaviors.
3. **Contextual Awareness**: Maintain awareness of mission posture and threats.
4. **Coordinated Protection**: Ensure protection mechanisms work cohesively.
5. **Deception**: Mislead or confuse adversaries.
6. **Diversity**: Use heterogeneity to minimize common vulnerabilities.
7. **Dynamic Positioning**: Relocate functionality or resources dynamically.
8. **Non-Persistence**: Retain resources only as needed.
9. **Privilege Restriction**: Limit privileges based on user attributes and environmental factors.
10. **Realignment**: Align resources with mission needs and reduce risks.
11. **Redundancy**: Provide multiple protected instances of critical resources.
12. **Segmentation**: Separate system elements based on criticality and trustworthiness.
13. **Substantiated Integrity**: Verify the integrity of critical system elements.
14. **Unpredictability**: Introduce randomness to reduce predictability.

![NIST 800-160 | Cyber Resiliency Techniques and Implementation Approach](img/tobeputlater.png)

### Cyber Resiliency Design Principles

Design principles guide systems engineers and architects in making decisions to enhance resiliency. These principles include:
- **Minimize Attack Surfaces**: Reduce opportunities for adversaries to exploit vulnerabilities.
- **Ensure Trustworthiness**: Build systems that can be trusted even under adverse conditions.
- **Promote Agility**: Enable systems to adapt quickly to changing environments.

### Relationship Among Cyber Resiliency Constructs

The constructs—goals, objectives, techniques, and design principles—are interconnected and relate to risk management. Systems engineers use these constructs to analyze solutions in terms of their impact on risk and specific threat events.

![NIST 800-160 | Relationship between Cyber Resiliency Constructs](img/tobeputlater.png)

## Cyber Resiliency in the System Life Cycle

This section outlines how cyber resiliency concepts and framework constructs are applied across the system life cycle stages. It addresses differences in security and cyber resiliency terminology and how goals, objectives, techniques, and design principles influence key stages.

![NIST 800-160 | System Life Cycle Processes and Stages](img/tobeputlater.png)

### Life Cycle Stages and Cyber Resiliency Constructs

1. **Concept Stage**
   - Prioritize and tailor objectives based on the system's concept of use.
   - Align design principles with other disciplines and limit applicable techniques.
   - Identify cyber resiliency concerns for production, integration, validation, and supply chain management.
2. **Development Stage**
   - Apply design principles to shape system architecture and prioritize objectives.
   - Analyze and define cyber resiliency solutions using techniques and approaches.
   - Verify solutions for effectiveness and compatibility with trustworthiness.
3. **Production Stage**
   - Implement and evaluate cyber resiliency solutions in stressed environments.
   - Address production, integration, validation, and supply chain concerns.
4. **Utilization Stage**
   - Monitor the effectiveness of solutions in operational environments.
   - Adapt processes and reprioritize objectives to address environmental changes.
5. **Support Stage**
   - Revisit objectives and constraints based on monitoring results.
   - Modify or upgrade capabilities to align with operational, threat, and technical changes.
6. **Retirement Stage**
   - Address vulnerabilities introduced during system decommissioning.
   - Ensure disposal processes do not compromise cyber resiliency objectives.

### Role of Cyber Resiliency Constructs in Life Cycle Stages

| **Life Cycle Stage** | **Key Activities**                                                                 |
|-----------------------|-----------------------------------------------------------------------------------|
| **Concept**           | Prioritize objectives, align design principles, and identify applicable techniques. |
| **Development**       | Apply design principles, define solutions, and verify effectiveness.             |
| **Production**        | Implement and evaluate solutions, address supply chain concerns.                 |
| **Utilization**       | Monitor effectiveness, adapt processes, and reprioritize objectives.             |
| **Support**           | Modify or upgrade capabilities, revisit objectives and constraints.              |
| **Retirement**        | Address vulnerabilities and ensure secure disposal processes.                    |


## Risk Management and Cyber Resiliency

Organizations manage risks related to systems with cyber resources as part of a broader portfolio, including financial, reputational, and operational risks. Cyber resiliency solutions primarily aim to reduce mission, business, and operational risks but may also influence other risk types (e.g., financial or schedule risks).

### Key Considerations for Risk Management
- **Impact of Solutions**: Assess how proposed solutions affect organizational risk tolerance and strategy.
- **Dynamic Environment**: Address risks associated with evolving technologies, processes, and threat landscapes.
- **Adaptation Goals**: Ensure solutions align with the "Adapt" goal by addressing changes in attack surfaces, dependencies, and operational procedures.

### Questions to Guide Risk Management
- How does each step in a transition plan affect the attack surface?
- Are new attack vectors introduced? How will they be mitigated?
- Does this step increase complexity or instability? How will those risks be managed?
- What dependencies exist on other programs or initiatives? How will risks be addressed if objectives are not met?
- What new or modified operational procedures are assumed? How will they be resourced?
- How will cyber resiliency objectives continue to be achieved amidst changes?
