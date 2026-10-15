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


