# Open questions


## General

## Wireless Communication

## GNSS

**In a GNSS, satellites broadcast crucial information to the users:**
1. **Identify the crucial pieces of information that satellites broadcast to users.
List the essential data elements transmitted by GNSS satellites to receivers.**
2. **Explain how these pieces of information are utilized by a receiver.
Describe how the receiver utilizes satellite signals to calculate its position, velocity, and time (PVT)**

**Difference between Jamming and spoofing in GNSS, how they influence the PVT , what is more harmful and why?**

**Describe meaconing compare work other type of GNSS ATTACKS.**

**Interference detection methods can vary in their approaches within GNSS receivers.**
   1. List some interference detection methods used in GNSS receivers. (2 points)
      - Identify at least two different methods used for interference detection.
   2. Briefly describe each interference detection method. (4 points)
      - Provide a concise explanation of how each method detects interference within GNSS receivers.
      - Discuss the advantages or limitations of each method (e.g. in terms of effectiveness and implementation complexity).

**Explain in general detection and mitigation techniques for interference signals in both domain. Explain in detail mitigation technique in frequency domain and in time domain**

**Describe the mitigation techniques (at least 3) of GNSS spoofing and the relative leves in which they act.**

**List and describe some possible spoofing countermeasures for satellite navigation systems. (3 points). 
Identify at least three spoofing countermeasures.
Briefly describe how each countermeasure works.
Explain the effectiveness of each countermeasure in mitigating spoofing attacks.
Specify the levels of a satellite navigation system at which these countermeasures can be implemented. (3 points)
Identify the different levels within a satellite navigation system.
For each of the countermeasures mentioned above, indicate the level(s) at which they can be applied.**

**What are the effects of a spoofing attack on a GNSS receiver? (2 pts) How can a receiver fail or fail to respond to a spoofing attack? (2 pts) Possible disruptions of the attack? (2 pts)**

**In a GNSS, satellites broadcast crucial information to the users.**
   1. Identify the crucial pieces of information that satellites broadcast to users. (2 points) 
      - List the essential data elements transmitted by GNSS satellites to receivers.
   2. Explain how these pieces of information are utilized by a receiver. (4 points) 
      - Describe how the receiver utilizes satellite signals to calculate its position, velocity, and time (PVT).**

**Describe the effect of pseudorange errors on the Position, Velocity, and Time (PVT) solution and explain the role of the Dilution of Precision factor (e.g., GDOP, HDOP).**
1. Explain the effect of pseudorange errors on the Position, Velocity, and Time (PVT) solution.
(3 points)
Describe how errors in the measurement of pseudoranges from GNSS satellites affect the accuracy
of the PVT solution.
2. Discuss the role of the Dilution of Precision (DOP) factor in GNSS positioning. (3 points)
Define what Dilution of Precision (DOP) factors (e.g., GDOP, HDOP) represent in GNSS.
Discuss the relationship between DOP values and the accuracy and reliability of the PVT solution.
Provide examples of scenarios where high and low DOP values impact GNSS performance.

## WLAN - wifi

**Power saving mode in 802.11 + attack**

**Consider a setup in which 2 STA (STA-1 and STA-2) are connected to the same WLAN managed by an AP. A third device (ETH-1) is connected with Ethernet technology. For each setup, describe and justify the expected goodput in the following cases:**

- **Scenario 1 (3 points): Both STA-1 and STA-2 use 802.11g on the ISM band, ETH-1 uses Fast Ethernet technology with a physical link capacity of 100Mb/s**

    1. STA-1 sends data to ETH-1 using UDP
    2. STA-1 sends data to ETH-1 using TCP
    3. STA-1 sends data to STA-2 using UDP
    4. STA-1 sends data to STA-2 using TCP

- **Scenario 2 (2 points): What changes if STA-1 now connects to the same WLAN but using the 5GHz band? Again, consider the cases**

   1. STA-1 sends data to ETH-1 using UDP
   2. STA-1 sends data to ETH-1 using TCP
   3. STA-1 sends data to STA-2 using UDP
   4. STA-1 sends data to STA-2 using TCP

- **Scenario 3 (1 point), what changes if now both STA-1 (on 5GHz band) and STA-2 (on 2.4GHz band) upgrade their technology to using 802.11ax (WiFi 6)?**

   1. STA-1 sends data to ETH-1 using UDP
   2. STA-1 sends data to ETH-1 using TCP
   3. STA-1 sends data to STA-2 using UDP
   4. STA-1 sends data to STA-2 using TCP



**Consider UDP header of 8B, TCP header of 20B, IP header of 20B, Ethernet header c’ of 38B.**


**Describe the frames exchanged by an STA and an AP to inform the STA about the SSID of the AP; what kind of attack exploits this mechanism?**
**Descrive step For OPEN AUTH sydtem when the Ap communicate EESID and when not**

**Describe the sequence of messages that an STA and an AP exchange during association and authentication processes in an open system(?) in the following cases:
case 1 - AP broadcasts beacon messages (2 points)
case 2 - ESSID is hidden, AP does not broadcast WLAN EISS in beacons (2 points)
(enumerate the steps)
which types of attacks do these mechanisms allow? (2 points)**

**Describe and sketch the sequences of messages a STA and an AP exchange during the initial Association and Authentication process in an Open System. Consider both the case in which**
   1. The AP broacasts the beacon messages (2 points)
   2. The ESSID is hidden and the AP does not broadcast the WLAN ESSIS in the beacons (2 points).

   What type of attacks such mechanisms allow? (2 points)  
   To describe the timeline, you can use a numbered list and state who sends what to who, or which computations a device does with some information:
   1. STA sends frame XXX to AP
   2. AP sends frama YYY to broadcast
   3. STA extracts ZZZ from YYY and computes KKK, YYY, LLL
   4. ...




## WPAN - Bluetooth

**Secure simple pairing + MITM attack**

**Differences between BT BR/EDR and BLE (frequencies, FEC/ARQ, …)**

**Which are the privacy features offered by Bluetooth? Which attack they offer protection to?
How is the problem solved using the IRK?
Describe in details how the IRK is used to provide resolvable private addresses**

**What are the 4 association modes in Bluetooth and what capabilities a device must have to support them( in general ); Why they are used? For every association mode, tell which capabilities a device must have to support them (for Numerical comparison the devices must have these capabilities and so on and so forth)**

**Bluetooth modes OOB, Just works, passkey entry, numeric comparison and hardware required to use them**

**Describe the 4 states of a Bluetooth device (standby, advertiser, scanner, initiator and master/slave) (3 points) and prove an example with all the steps, A sends frame to B, B sends broadcast to A, A extract YYYY, ZZZZ from XXX to get GGGG etc (3 points)**

**Explain the main design goals for the BT technology and the technical constraints that guided the design (2 pts). Describe BT network topologies and the role of nodes in each scenario (2 pts).  
Describe the physical layer com mechanisms implemented in BT BR/EDR and the differences since BLE was introduced: which frequency range does it use, which multiple access scheme does it use, which FEC/ARQ mechanism it provides etc. (2 pts)**

**Describe the Bluetooth association models and the mechanisms implemented to support the different capabilities a device could have. (3 points)  
What is the goal of implementing such association models? (1 point)  
what are the minimum hardware capabilities two devices must have to support each of the four association models? (2 points)**

**Explain the main design goals for the Bluetooth technology and the technical constraints that guided the design, and the Bluetooth network topologies and the role of nodes in each scenario.(2 points). Describe the physical layer communication mechanisms implemented in Bluetooth BR/EDR and the differences since BLE was introduced: which frequency range does it use, which multiple access scheme does it use, which FEC/ARQ mechanism it provides, etc. (4 points)** 

The main goal for Bluetooth technology was to create a wireless cable rather than a wireless network. It is designed to be ubiquitous, inexpensive, and close range (<10m).

In the Bluetooth protocol, we always have a master device and a slave device, forming a piconet. There can be a maximum of 7 devices in a single piconet, and we can create scatternets by connecting piconets with each other. Communication between piconets can occur via a device that acts as a slave in one piconet and a master in another, or via a device that acts as a master in one and a slave in another. A device CANNOT be a master in both piconets. Within master-slave communications, the master decides when the slaves should communicate with it, and slave devices cannot communicate directly with each other.

The physical layer communication mechanism is implemented using FHSS (Frequency Hopping Spread Spectrum), which involves dividing the general channel into smaller channels and using a pattern (or a pre-specified one) to jump (hop) from one channel to another. This is done to prevent or at least complicate sniffing attacks. There is a special version of FHSS called Adaptive FHSS, where devices use statistical algorithms to choose which channels to hop on based on the least busy ones. However, if all devices use this mode, they will consequently hop to the same channels, making them busier and reducing overall communication effectiveness.

The frequency band used for both BR/EDR and BLE ranges from 2.4GHz to 2.485GHz, which is typically very busy. The two versions use a different number of channels: BR/EDR uses 79 channels, hopping every 1600ms, while BLE uses 40 channels, of which 37 are reserved for data. Because this frequency band is very busy, ARQ (Automatic Repeat reQuest) and FEC (Forward Error Correction) mechanisms are implemented. 

ARQ uses ACK (acknowledgment) and NACK (negative acknowledgment) messages to ensure the correct reception of messages, which is especially important given the busy frequency. 

FEC directly influences efficiency and can be implemented in two ways: 1/3 efficiency, where each message is sent over the channel 3 times, and 2/3 efficiency, where for every 10 bits of data, 5 bits of error correction codes are sent, capable of correcting 1-bit errors and detecting 2-bit errors.

**Explain the main design goals for the Bluetooth technology and the technical constraints that guided the design, and the Bluetooth network topologies and the role of nodes in each scenario. (2 points).
Describe the physical layer communication mechanisms implemented in Bluetooth BR/EDR and the
differences since BLE was introduced: which frequency range does it use, which multiple access scheme does
it use, which FEC/ARQ mechanism it provides, etc. (4 points)**

## WWAN - mobile
