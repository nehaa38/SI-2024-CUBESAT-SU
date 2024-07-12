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

   
![CubeSat_Development_Process_Timeline](https://github.com/user-attachments/assets/34d15efc-cc3b-458e-bae7-9789397a7f23)
