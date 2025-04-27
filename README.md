# Formal Specification and Verification of the IETF MUD Protocol
The **Manufacturer Usage Description (MUD)** is an IETF standard designed to enhance the security and manageability of IoT devices with limited computational capabilities, such as smart home devices, sensors, and cameras.

Due to their constrained nature, these devices often lack sophisticated security mechanisms, making them attractive targets for cyberattacks.
To address this issue, MUD establishes a framework that allows IoT devices to declare their expected behavior and security requirements to the network infrastructure.
Based on this information, the network enforces a whitelist-based policy, restricting device communication to only predefined and authorized interactions.

This report focuses on:

- Developing a comprehensive threat model,

- Identifying potential vulnerabilities,

- Assessing their impact on the protocol’s security.

Following the threat analysis, the **formal verification** of the protocol will be conducted using ProVerif, ensuring that it meets the specified security requirements and is resilient to potential attacks.

The objective is to provide a structured security analysis of MUD and verify its effectiveness in protecting IoT networks.
