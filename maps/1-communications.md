# Communications

CNS stands for Communications, Navigation, and Surveillance (Aviation)
- This is the fundamental technological infrastructure and operational framework used to guide, track, and manage aircraft.

| Component | Primary Function | Core Technologies Used |
| :--- | :--- | :--- |
| Communications | Transmitting information between aircraft, air traffic control (ATC), and airline operations. | • VHF / HF Radio: Traditional voice communications.<br>• CPDLC: Controller-Pilot Data Link Communications (text-based messaging).<br>• SATCOM: Satellite communication for oceanic/remote areas. |
| Navigation | Determining the aircraft’s current position and guiding it safely along a specific flight path. | • GNSS / GPS: Satellite-based positioning.<br>• Ground Beacons: VOR (VHF Omnidirectional Range), DME (Distance Measuring Equipment), and ILS (Instrument Landing System) for precise runway approaches. |
| Surveillance | Allowing ATC to monitor and track the real-time position and altitude of all aircraft in the airspace. | • Primary/Secondary Radar: Traditional ground radar tracking.<br>• ADS-B: Automatic Dependent Surveillance-Broadcast (aircraft broadcast their precise GPS position to ground stations and other planes). |

Or simply:
- **Communications**: Voice and digital exchanges between pilots and air traffic control (ATC) via VHF, UHF, HF, or satellite links.
- **Navigation**: Systems (such as GNSS/GPS) that help pilots determine and maintain an accurate, reliable aircraft position and flight path.
- **Surveillance**: Ground-based radar (cooperative/non-cooperative) or satellite-based tracking (like ADS-B) that allows ATC to monitor aircraft positions in real time.

In Other words:
1. **Communications (C)**: *Where VCCS lives* - This is the most critical pillar for your immediate focus. You need to understand how a controller's voice gets from their headsets to the sky.
- Ground-to-Air (G/A): High-frequency (HF) and Very High Frequency (VHF) radios used to talk to pilots. Your VCCS interfaces directly with these radios.
- Ground-to-Ground (G/G): Telephone and data lines connecting one control tower to a neighboring country's tower (e.g., Manila talking to Taipei).
- The Core Connection: The VCCS is the "switchboard" that ties the G/A radios and G/G telephones into one touchscreen panel for the controller.

2. **Navigation (N)**: *How planes know where they are* - You don't need to know the deep physics of these, but you must know they exist because VCCS systems often display status alerts for them.
- Ground Beacons (VOR/DME/ILS): Land-based antennas that shoot signals into space so planes can track routes and land blindly in heavy fog.
- Satellite Navigation (GNSS/GPS): Modern space-based tracking.

3. **Surveillance (S)**: *how controllers see the planes* - This is crucial because the VCCS heavily interacts with the surveillance display.
- Radar (Primary & Secondary): Systems that sweep the sky to find aircraft.
- ADS-B (Automatic Dependent Surveillance-Broadcast): Modern systems where planes constantly broadcast their exact GPS location to ground towers.
- The Core Connection: A controller looks at a Surveillance radar screen to see a plane, and then use the VCCS to talk to that specific plane.

--- 

VCS stands for Voice Communication System; it is the whole system that connects controllers to pilots and to each other.
> It is also referred to as ***VCCS*** or ***Voice Communication Control System***.
- This is often described as the "lifeline" of an air traffic controller, the VCS is the specialized hardware and software routing switch that sits inside an Air Traffic Control (ATC) tower or center. It consolidates all the different radio frequencies and telepohone lines into a single touchscreen panel at the controller's desk.


**The system and its parts**
| Term | Meaning | Plain version |
| :--- | :--- | :--- |
| VCS | Voice Communication System | The whole system that connects controllers to pilots and to each other |
| CWP | Controller Working Position | The controller’s desk: screen, panel, headset |
| PTT | Push-To-Talk | The press-to-transmit action that keys the radio |
| Voice switch | Core of the VCS | Routes every call and radio session |
| Radio gateway | Converts between network and radio | The bridge between the IP network and the actual radio |
| Recorder | Captures all voice | For incident investigation, legally required |
| Supervision / management | Monitors and configures the system | Tells technicians what’s healthy or failing |

**Types of voice**
| Term | Meaning |
| :--- | :--- |
| Air-ground (A/G) | Controller to pilot, over radio |
| Ground-ground (G/G) | Controller to controller, over telephone lines |
| Direct access (DA) | One touch calls a specific counterpart (hotline) |
| Indirect access (IA) | Dial a number, like a phone call |
| VHF / UHF | The radio frequency bands used for air-ground voice |

**Protocols and technology**
| Term | Meaning | Job |
| :--- | :--- | :--- |
| VoIP | Voice over IP | Carrying voice as data packets over a network |
| SIP | Session Initiation Protocol | Sets up, manages, and ends calls (the signaling) |
| RTP | Real-time Transport Protocol | Carries the actual audio packets |
| G.711 | A voice codec | Encodes speech with little compression and low delay |
| Codec | Coder-decoder | Converts audio to digital data and back |
| Latency | Delay | Time for audio to travel end to end |
| Jitter | Variation in delay | Packets arriving at uneven intervals |
| Packet loss | Dropped packets | Missing chunks of audio |
| QoS | Quality of Service | Network rules that prioritize voice traffic |

**Terminologies found would reviewing this document and their deep-dives:**

1. GNSS & GPS:
- GNSS: Global Navigation Satellite Systems - this represents the broad umbrella of space-based infrastructure that provide global positioning, navigation, and timing (PNT).
- PNT: Positioning, Navigation, and Timing - The collective framework of three independent core capabilities; knowing where youare, how to get somewhere else, and what exact time it is.
> While **GNSS** is the primary space-based delivery mechanism for PNT, PNT itself represents the actual utility consumed by global digital, financial, and physical infrastructure.

**Three Pillars of PNT:**
    1. **Positionning**: The ability to accurately and precisely determine geographic coordinates (latitude, longitude, and altitude) or orientation relative to a standard geodetic reference frame like WGS84 
    2. **Navigation**: The dynamic process of determining a current versus desired position and calculating real-time corrections to speed, course, and heading to guide a user or autonomous asset safely from point A to point B
    3. **Timing**: The acquisition and maintenance of ultra-precise time synchronization referenced to Coordinated Universal Time (UTC) down to the nanosecond level. Though least visible to everyday consumers, timing is arguably the most critical component of the triad

- GPS: Global Positioning System this is specifically the pioneer GNSS constellation operated by the United States. A single satellite constellation owned and operated by the United States government. Typically **31 operational satellites.** High risk of signal loss or delay in urban canyons, valleys, or dense trees.
- GNSS: The overarching term that encompasses all global and regional constellations. Over **120+ satellites** combined across multiple nations. High resilience; if one constellation is blocked, the receiver automatically switches to another.

**The Global Core Constellations of GNSS**
> A standard, modern multi-GNSS receiver does not just talk to the U.S. network. It tracks data simultaneously from four major worldwide networks.
1. GPS (United States): The historical pioneer, fully deployed 1993/1994.
2. GLONASS (Russia): A 24-satellite constellation optimized heavily for high-latitude tracking.
3. Galileo (European Union): A highly precise civil-controlled network utilizing advanced frequency channels.
4. BeiDou (China): The largest constellation in orbit, utilizing over 40 satellites for massive coverage density.
> *Note: Regional augmentation systems like Japan's QZSS and India's NavIC also tie into GNSS architectures to reinforce positioning over specific hemispheres.*

Global Navigation Systems orbit at an altitude of roughly 19,000 to 24,000 kilometers (Medium Earth Orbit). This altitude is a mathematical sweet spot; it allows the satellites to circle the Earth about twice a day, moving relative to the ground so a handful of satellites can sweep the entire planet continuously.

There are 3 Main Altitudes and different kind of technologies:
1. Low Earth Orbit (LEO):
    - Typical Altitude: 160-2000km
    - Speed: ~28,000 km/h
    - Time to Orbit Earth: 90-120 minutes
2. Medium Earth Orbit (MEO): **These are where GNSS are positioned**
3. Geostationary Orbit (GEO):




