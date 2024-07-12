# SI-2024-CUBESAT-AP
📡 Repository for Summer Internship 2024 "Intro To Cube-sat and Satellite Communication"
# CUBESAT
![Alen-Space-CubeSat-Constelation-LO](https://github.com/user-attachments/assets/5e1dc05c-5c20-4b62-8361-d1efca199d8d)
- A CubeSat is a miniature spacecraft with a volume of from 1 to 3 liters and a mass from 1 to 3 kg. California Polytechnic State University and Stanford University developed the CubeSat specifications to help universities worldwide
to perform space science and exploration. CubeSats provide an opportunity for students to learn about satellites and
engineering.
### ATTRIBUTES
- Small Size: CubeSats are typically small, cubic-shaped satellites with standardized dimensions. The most common sizes are 1U (10 cm x 10 cm x 10 cm), 2U, and 3U, although larger configurations exist (e.g., 6U, 12U).     (<img align="right" width="300" height="180" src="https://github.com/user-attachments/assets/c877e2d0-ab1d-44e3-9abe-8b42f1d342c0">

- Modularity: They are built using standardized components and interfaces, making them highly modular and easy to assemble. This modularity allows for cost-effective manufacturing and rapid deployment.

- Low Cost: CubeSats are relatively inexpensive compared to traditional satellites, making them accessible to universities, research institutions, and even some commercial entities.

- Educational and Research Purposes: CubeSats are often used for educational purposes, providing students and researchers with hands-on experience in satellite design, development, and operation. They also facilitate scientific research in various disciplines such as Earth observation, space weather monitoring, and technology demonstration.                    (<img align="right" width="300" height="180" src="https://github.com/user-attachments/assets/d1d0163e-8d7c-43c8-9e46-4ad5e734b34e">

- Short Development Cycles: Due to their small size and standardized components, CubeSats can be developed and launched relatively quickly compared to larger satellites.
### CUBESAT LAYOUT

- A CubeSat typically follows a standardized layout that adheres to the CubeSat specification, which allows for easier integration and deployment. Here are the key components and their typical arrangements:

  - Structure: CubeSats are built around a cubical frame, usually 10 cm × 10 cm × 10 cm (1U) in size. Larger CubeSats (2U, 3U, etc.) are multiples of this base unit.

  - Payload: This is the primary purpose of the CubeSat mission, such as a scientific instrument, a technology demonstration, or a communications payload.

  - Avionics: This includes the onboard electronics for controlling the satellite, managing power, handling communications, and data processing. Avionics typically include:

  - Computer: Controls satellite operations and data handling.
  - Power System: Manages power generation (solar panels) and distribution (batteries).
  - Attitude Determination and Control System (ADCS): Controls satellite orientation using reaction wheels, magnetorquers, or reaction control thrusters.
  - Communications System: Transmits and receives data to/from ground stations using antennas.
  - Thermal Control: Components are thermally managed to ensure they operate within their temperature limits. This can involve passive methods (insulation, coatings) and active methods (heaters, heat pipes).

  - Sensors: These can include sun sensors, star trackers, magnetometers, and others depending on the mission requirements.          (<img align="right" width="500" height="450" src="https://github.com/user-attachments/assets/f8fff9fa-b416-46d9-9f6c-ed6b6517c236">

  - Deployment Mechanism: Used to release the CubeSat into space from a deployment vehicle or the International Space Station.

  - Antennas: Used for communication with ground stations and possibly for scientific measurements.

  - Propulsion System (optional): Some CubeSats include small propulsion systems for orbital maneuvers or deorbiting.

  - Integration of Components: The components are carefully integrated to maximize use of space and ensure they function together properly in the confined CubeSat structure.

  - Interfaces: CubeSats have standardized mechanical, electrical, and communication interfaces to facilitate integration with launch vehicles and ground stations.

  ### CUBESAT DISPENSER SYSTEM
 -  A CubeSat dispenser system is crucial for deploying CubeSats into orbit from a launch vehicle. Here’s an overview of how a typical CubeSat dispenser system works:

   - Purpose: The dispenser system securely holds and releases CubeSats into space at the designated deployment altitude and conditions.

   - Integration: CubeSats are typically integrated into the dispenser on the ground before launch. They are often stacked in a row or configured in a specific arrangement based on the dispenser’s design.

   - Launch Vehicle Interface: The dispenser system interfaces with the launch vehicle's payload adapter or deployment mechanism. It is securely mounted within the payload fairing or deployer bay of the rocket.

   - Deployment Mechanism: There are different deployment mechanisms depending on the dispenser design:

     - Spring-Based Deployment: CubeSats are typically held in place with springs that provide the necessary force to eject them into space when released.
     - Pneumatic or Mechanical Release: Some dispensers use pneumatic or mechanical systems to release CubeSats.
     - Pusher Plates: In some cases, pusher plates are used to mechanically push CubeSats out of the dispenser.          (<img align="right" width="500" height="500" src="https://github.com/user-attachments/assets/288f7c73-94da-460f-97d5-66c4520e3e16">

- Ejection Dynamics: The dispenser system ensures that CubeSats are ejected with a controlled velocity and orientation to prevent collisions with the launch vehicle or other CubeSats.

- Electrical and Communication Interfaces: The dispenser may provide electrical connections and antennas for CubeSats that require power and communication through the launch vehicle.

- Deployment Sequence: CubeSats are deployed in a predefined sequence either simultaneously or one-by-one, depending on mission requirements and deployment strategy.

- Deployment Confirmation: Once deployed, the dispenser system may have sensors or telemetry to confirm successful release and deployment of each CubeSat.

- Safety and Reliability: Dispenser systems are designed with safety and reliability in mind to ensure that CubeSats are deployed without issues that could compromise their mission objectives.

- Examples of CubeSat dispenser systems include the P-POD (Poly-Picosatellite Orbital Deployer) and other proprietary or custom designs developed by various aerospace companies and institutions.

### DEVELOPMENT PROCESS OVERVIEW
The development of a CubeSat typically follows several key phases, each essential for ensuring its successful deployment and mission performance:

1. *Conceptualization and Mission Definition*:
   - *Mission Definition*: Identify the mission objectives, scientific goals, or technology demonstration aims.
   - *Conceptual Design*: Determine the basic configuration and size of the CubeSat (e.g., 1U, 2U, 3U) based on payload requirements and mission objectives.
   - *Feasibility Study*: Assess the technical feasibility and potential challenges associated with achieving the mission goals.

2. *Preliminary Design Phase (Phase A)*:
   - *System Requirements*: Define detailed mission and system requirements, including subsystems like power, communication, attitude control, and payload.
   - *Preliminary Design*: Develop initial designs and concepts for the CubeSat structure, subsystems, and integration approach.
   - *Concept Review*: Conduct a review to evaluate the feasibility of the preliminary design and make adjustments as necessary.

3. *Detailed Design Phase (Phase B)*:
   - *Detailed Design*: Refine the design based on feedback from Phase A. Develop detailed specifications and plans for each subsystem and component.
   - *Manufacturing Plans*: Prepare detailed manufacturing plans for all CubeSat components, considering space-grade materials and fabrication techniques.
   - *Testing Plans*: Develop plans for environmental testing (thermal vacuum, vibration, radiation) to validate the CubeSat's design and ensure it can withstand the harsh conditions of space.

4. *Manufacturing, Integration, and Testing Phase (Phase C)*:
   - *Component Manufacturing*: Manufacture and procure all necessary components and subsystems according to the detailed design specifications.
   - *Integration*: Assemble the CubeSat, integrating all subsystems and components into the final structure.
   - *Testing*: Perform rigorous testing including functional tests, subsystem tests, and environmental tests to verify the CubeSat's performance and readiness for space.

5. *Launch Preparation and Operations Phase (Phase D)*:
   - *Launch Campaign*: Coordinate with launch service providers to secure a launch opportunity and integrate the CubeSat with the launch vehicle.
   - *Pre-launch Checks*: Conduct final checks and preparations to ensure the CubeSat is ready for launch.
   - *Launch*: Deploy the CubeSat into its intended orbit from the launch vehicle.

6. *Operations and Data Analysis Phase (Phase E)*:
   - *Commissioning*: Activate and configure the CubeSat in orbit, ensuring all systems are functioning correctly.
   - *Mission Operations*: Operate the CubeSat from ground control, monitor its health, and execute the mission plan to collect data or perform experiments.
   - *Data Analysis*: Analyze data collected by the CubeSat to assess mission success and achieve scientific or technological objectives.

7. *Mission Conclusion and Post-Mission Phase (Phase F)*:
   - *Decommissioning*: If necessary, plan for the safe decommissioning or deorbiting of the CubeSat at the end of its mission.
   - *Data Dissemination*: Archive mission data and prepare final reports or publications summarizing mission achievements and findings.
   - *Lessons Learned*: Conduct a review to identify lessons learned and areas for improvement in future CubeSat missions.


![CubeSat_Development_Process_Timeline](https://github.com/user-attachments/assets/1f81d304-960d-49ac-af13-a60f6ad4ab5b)
### MINIMAL PAYLOAD
A minimal payload refers to the essential and streamlined set of instruments and subsystems carried by a CubeSat or small satellite mission. It is designed to achieve specific scientific or technological goals with minimal complexity and cost. Typically, a minimal payload configuration includes a primary instrument (such as a camera or spectrometer), basic avionics for satellite control and data handling, a simple power system (solar panels and batteries), a straightforward communication system, and a standard CubeSat structure.        (<img align="right" width="500" height="500" src="https://github.com/user-attachments/assets/04a9c08a-9465-4613-ba27-16fa7d9d543d"> This approach allows for cost-effective space missions, faster development timelines, and focused scientific or educational objectives, making CubeSats accessible to a broader range of users including educational institutions, startups, and small research organizations.           
### CUBESAT ARCHITECTURE
CubeSat architecture refers to the structural and functional design of CubeSats, which are standardized small satellites primarily used for scientific, educational, and technology demonstration purposes. The architecture of a CubeSat typically includes several key components and characteristics:

1. **Structure**:
   - CubeSats are based on a cubic structure, with a standard size of 10 cm × 10 cm × 10 cm (1U). Larger CubeSats can be multiples of this size (e.g., 2U, 3U, 6U).
   - The structure provides mechanical support for all internal components and ensures the satellite's structural integrity during launch and in orbit.

2. **Payload**:
   - The payload is the primary scientific or technological instrument carried by the CubeSat. It can include cameras, spectrometers, magnetometers, radiation detectors, and other sensors depending on the mission objectives.
   - The payload is typically housed within the CubeSat structure and interfaces with the satellite's avionics and power systems.

3. **Avionics**:
   - Avionics encompass the electronic systems necessary for controlling the CubeSat's operations. This includes:
     - **Onboard Computer**: Manages satellite functions, data processing, and communication with ground stations.
     - **Power System**: Regulates power distribution from solar panels and batteries to ensure continuous operation.
     - **Attitude Determination and Control System (ADCS)**: Controls the orientation of the CubeSat using reaction wheels, magnetorquers, or other mechanisms.
     - **Communication System**: Facilitates communication between the CubeSat and ground stations using antennas and radio transceivers.

4. **Power System**:
   - CubeSats typically use solar panels to generate electrical power from sunlight. This power is stored in rechargeable batteries to supply energy during eclipses or when solar panels are not exposed to sunlight.

5. **Communication System**:
   - CubeSats communicate with ground stations using radio frequencies allocated for satellite communication. This system includes antennas for transmitting data collected by the payload and receiving commands from Earth.

6. **Thermal Control**:
   - Thermal management is crucial to ensure that components operate within their temperature limits in the extreme conditions of space. This can include passive methods (insulation, coatings) and active methods (heaters, heat pipes).         (<img align="right" width="500" height="500" src="https://github.com/user-attachments/assets/9f4a0d0b-2246-4b63-833a-4f1877b57ed1">

7. **Deployment Mechanism**:
   - CubeSats are typically deployed from a dispenser or deployer system onboard a launch vehicle or the International Space Station (ISS). This mechanism ensures the CubeSat is safely released into its designated orbit.

8. **Interfaces and Standards**:
   - CubeSats adhere to standardized interfaces and specifications to ensure compatibility with launch vehicles, deployment systems, and ground stations. This includes mechanical, electrical, and communication interfaces.

9. **Mission-Specific Adaptations**:
   - Depending on the mission requirements, CubeSat architecture may include additional subsystems such as propulsion for orbital maneuvers or specialized sensors for specific scientific investigations.

CubeSat architecture emphasizes modularity, scalability, and standardization, allowing for cost-effective development and deployment of small satellites for a wide range of space missions. These satellites have democratized access to space exploration and provided valuable opportunities for scientific research and technological innovation worldwide.

# BASIC DIGITAL MODULATION
- Digital modulation techniques are methods used to encode digital data onto analog carrier signals for transmission in communication systems.
 ### BASIC BANDPASS MODULATION
 - Bandpass modulation refers to a type of modulation technique where the baseband signal (which contains the information to be transmitted) is modulated onto a carrier signal that is within a specific frequency band. This carrier signal is usually centered around a higher frequency compared to the baseband signal. Bandpass modulation is essential in many communication systems to efficiently utilize the available frequency spectrum and ensure that signals can be transmitted over long distances with minimal interference.
 - Key Characteristics of Bandpass Modulation:
     - Frequency Spectrum: Bandpass modulation techniques utilize carrier signals within specific frequency bands allocated for transmission.

     - Bandwidth Efficiency: Techniques like SSB and VSB are designed to minimize bandwidth usage while transmitting essential information effectively.

     - Signal-to-Noise Ratio (SNR): Bandpass modulation helps in achieving better SNR compared to baseband techniques, particularly in long-distance communication.

     - Interference Mitigation: By using specific frequency bands, bandpass modulation reduces the likelihood of interference from adjacent channels or other sources.

Bandpass modulation techniques are integral to modern communication systems, offering flexibility, efficiency, and robustness in transmitting information over various types of communication channels, from radio waves to optical fibers. Their use ensures reliable and effective transmission of data, voice, and video signals across different applications and industries.
- These techniques are crucial in modern telecommunications for efficiently and reliably transmitting digital information over various transmission media. Here are some commonly used digital modulation techniques:

1. Amplitude Shift Keying (ASK)
   - Description: ASK modulates the amplitude of a carrier signal to represent digital data.
   - Operation: Different amplitude levels correspond to different digital symbols (e.g., 0 and 1).
   - Applications: Simple and used in applications where bandwidth efficiency is not critical, such as low-cost communication systems.     (<img align="right" width="500" height="500" src="https://github.com/user-attachments/assets/dee767d3-4007-4b4f-a4ea-4da6705d8803">
2. Frequency Shift Keying (FSK)
   - Description: FSK modulates the frequency of the carrier signal to convey digital data.
   - Operation: Different frequencies represent different digital symbols.
   - Applications: Used in applications requiring moderate bandwidth efficiency, such as radio communications and data modems.      
3. Phase Shift Keying (PSK)
   - Description: PSK modulates the phase of the carrier signal to encode digital data.
   - Operation: Different phase shifts represent different digital symbols.
   - Variants:
       - Binary Phase Shift Keying (BPSK): Two phase shifts (0° and 180°) represent binary symbols (0 and 1).
       - Quadrature Phase Shift Keying (QPSK): Four phase shifts (0°, 90°, 180°, 270°) represent two bits per symbol.
   - Applications: Used in satellite communication, Wi-Fi, and digital television.

 

