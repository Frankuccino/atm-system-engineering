# ATM System Engineering
> [!NOTE]
> This is my personal system engineering document and series going through the technologies related to air traffic management.

> **Objective**
> [!IMPORTANT]
> This document will serve as my long-term system engineering skill acquisition, mastery, and knowledge sharing for anyone who's interested in the aviation industry as a system engineer.

If you have any questions or suggestions, feel free to contact me via [![LinkedIn](https://raw.githubusercontent.com/CLorant/readme-social-icons/main/small/filled/linkedin.svg)](https://www.linkedin.com/in/frank-angelo-malubag/)


## ATM stands for Air Traffic Management which includes:

- Air Traffic Services (ATS):
    - Air Traffic Control (ATC): separation and sequencing, split into tower, approach, and area control
    - Flight Information Service (FIS): information useful for safe and efficient flights
    - Alerting Service: notifying search and rescue when an aircraft needs help
- Airspace Management (ASM): designing and allocating airspace (routes, sectors, restricted or military areas) so it’s used efficiently
- Air Traffic Flow Management (ATFM): balancing demand against capacity, so sectors and airports don’t get overloaded

What it depends on (this is where system engineers work most):

- CNS: Communications (voice, data link), Navigation (ILS, VOR, GNSS), Surveillance (radar, ADS-B, multilateration)
- ATM automation: flight data processing, radar data processing, controller working positions, safety nets (conflict alerts, short-term alerts)
- AIM (Aeronautical Information Management): NOTAMs, charts, aeronautical data, AMHS messaging
- MET: weather data feeding controllers and planners
- SAR: search and rescue coordination

Suggested priority for you, given Company is mainly voice, messaging, and information systems:

1. Communications: VCS, VoIP, radio, ED-136/137/138
2. AIM and messaging: AMHS, AFTN, SWIM, AIXM
3. ATS fundamentals: how ATC actually works operationally
4. Surveillance and automation: ASTERIX, flight and radar data processing
5. Safety and assurance: SMS, RAMS, ED-153
6. Navigation: lower priority unless your team supports it
7. ASM and ATFM: conceptual understanding is enough at first


### 1. High Priority (Core Communication & Messaging Infrastructure)

• Communications: Focus on VCS (Voice Communication Systems), VoIP, Radio integration, and compliance with ED-136 / ED-137 / ED-138 standards (particularly IP-based ATM interoperability).
• AIM and Messaging: Focus on AMHS, legacy AFTN, and modern data exchange formats/frameworks like SWIM and AIXM.

### 2. Medium Priority (Operational Context & Data Processing)

• ATS Fundamentals: Operational understanding of how ATC works, sector handoffs, and terminal vs. en-route environments.
• Surveillance and Automation: Understanding radar/flight data processing frameworks, specifically the ASTERIX data exchange format.

### 3. Lower / Conceptual Priority (Frameworks & Domain Context)

• Safety and Assurance: High-level awareness of SMS, RAMS, and software assurance guidelines like ED-153.
• Navigation (Navaids): Kept as a lower priority unless a specific project or assignment demands it.
• ASM and ATFM: Conceptual and architectural understanding of airspace and traffic flow management.
