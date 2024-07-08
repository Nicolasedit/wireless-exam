# Quiz or closed questions

## Cryptography

**What is a stream cipher?**

**Which of the following defines a cipher text attack?**

**what is known plaintext attack**

**Classification of wireless network, adhoc/infrastructure, fixed/mobile, wwan/wlan**

**Which of the following best defines asymmetric encryption?**
- [ ] A cipher that encrypts data in fixed-size blocks, each block processed independently with a key.
- [ ] A cipher that uses a single key for both encryption and decryption.
- [x] A cipher that uses a pair of keys (public and private) for encryption and decryption to ensure secure communication between parties.
- [x] A cipher that uses different keys for encryption and decryption, ensuring secure communication between parties.
- [ ] None of the other options.

**Associate the correct definition to the following security mechanisms**
- **Access Control**: Determines and enforce the access rights of the entity depending on the authenticated identityProvides confidentiality for either data or traffic flow information
- **Encipherment**: Provides confidentiality for either data or traffic flow information
- **Traffic Padding**: Protects against traffic analysis attacks by adding non essential data to network communicationsAssures data integrity, origin, time, and destination about data communicated between two or more entities
- **Notarization**: Assures data integrity, origin, time, and destination about data communicated between two or more entities

**Associate the correct definition of the following Security Services:**
- **Non-repudiation:** Assurance that someone cannot deny the validity of something.
- **Confidentiality:** Ensuring that information is accessible only to those authorized to have access.
- **Availability:** Ensuring that authorized users have access to information and associated assets when required.
- **Integrity:** Maintaining and assuring the accuracy and completeness of data over its entire lifecycle.

**What is the key difference between a monoalphabetic and a polyalphabetic cipher?**
- [ ] The method of rearranging the order of letters.
- [ ] The use of multiple keys for encryption.
- [ ] The length of the plaintext that can be encrypted.
- [x] The complexity of the substitution pattern used.
- [ ] None of the other options.


## Signals and basics

**In digital Communication system which type of waveforms are propagated in the channel?**

**Order the elements in the transmission chain (encoder, modulator, channel etc.)**

**Why the definition of the bandwidth 3db**

**PSK modulation - about the energy level of symbols and saturation level of a power amplifier**

**Put the building blocks of a digital communication system in the correct order:**
TX --> Encoder --> Modulator  --> Channel  --> Demodulator  --> Decoder  --> RX

**A digital communication system uses a 2-PAM modulation with rectangular pulses and a given average energy per symbol ***E_s***. What happens if we adopt instead a 4-PAM modulation, using the same basic pulse and average energy per symbol ***E_s***?**
- [ ] The bitrate decreases, but the system becomes more robust to errors.
- [x] The bitrate increases, but the system becomes more error prone.
- [ ] The bandwidth efficiency increases resulting in a generally larger bandwidth of the transmitted signals.
- [ ] The bandwidth efficiency decreases resulting in a generally larger bandwidth of the transmitted signals.
- [ ] None of the other options.

## GNSS

**How can a spoofing attack be detected?**

**Why is monitoring the GNSS spectrum alone often insufficient for comprehensive spoofing detection?**
- [ ] Spectrum monitoring is too slow to detect real-time attacks.
- [x] It only detects changes in signal strength and frequency, not the content or integrity of the signals.
- [x] Spoofers can closely mimic legitimate signal parameters, making detection challenging.
- [ ] It cannot differentiate between different types of interference.
- [ ] None of the other options.

**Which of the following is generally ***NOT*** an effective spoofing detection method?**
- [ ] Implement cryptographic authentication to verify the authenticity of GNSS signals, ensuring they originate from legitimate satellites.
- [ ] Cross-checking GNSS data with other navigation systems like inertial navigation sensors or signals from multiple GNSS constellations (GPS, GLONASS, Galileo, BeiDou) and frequencies.
- [ ] Use antennas that can determine the direction of incoming signals, allowing the receiver to distinguish between legitimate and spoofed signals based on direction.
- [ ] Monitor the strength of GNSS signals. Sudden increases in signal strength can indicate spoofing attempts.
- [x] Monitor the frequency spectrum in the GNSS band. Frequency spikes generally indicate the presence of a spoofer in that band.


**Why is it important to receive signals in Line-of-Sight to build profitable pseudoranges?**
- [x] Because line-of-sight signals are not delayed by reflections. Multipath can cause the receiver to calculate a longer travel time, leading to erroneous pseudorange calculations.
- [x] Because Line-of-sight signals travel the shortest and most direct path from the satellite to the receiver. This ensures that the signal strength is higher and minimal attenuation is experienced leading to a higher signal-to-noise ratio.
- [ ] Because satellites in line-of-sight yield to better geometrical conditions to estimate the position and therefore to a lower GDOP.
- [ ] Because measurements performed in line-of-sight maintain synchronization between the user and the satellite.
- [ ] None of the other options.


**What is broadcasted by the satellite**

**Is out-of-band interference detrimental for GNSS signals? Why?**
- [ ] Yes. GNSS frequency bands are reserved only in the country that owns each system (e.g., the US for GPS, the EU for Galileo), therefore, other signal transmissions can freely interfere with those bands in most regions.
- [ ] No. GNSS frequency bands are reserved, and no other signal transmission interferes with those bands.
- [ ] No. GNSS signals are generally very weak; however, the use of spread spectrum codes makes them invulnerable to interference.
- [ ] None of the other options.
- [X] Yes. Since GNSS signals are generally very weak, strong out-of-band spillovers of powerful signals can interfere with the GNSS band.

**Which of the following is a common indicator of a GNSS spoofing attack?**
- [ ] A gradual decrease in signal strength over time
- [ ] Enhanced accuracy and reliability of GNSS signals
- [ ] Sudden and significant deviations in position, velocity or time calculations
- [ ] None of the others
- [ ] Discrepancies between GNSS-based positions and those from alternative navigation systems (e.g., inertial navigation systems)


**Are the user and satellite clock synchronized in a GNSS?**
- [ ] None of the other options.
- [ ] Yes, but there is a constant time-invariant offset.
- [ ] Yes, always.
- [ ] No, never. Neither before nor after the user position estimation.
- [X] Not really. However, the user clock can be considered synchronized after the
continuous estimation of the user clock bias which is time-varying.

**What is the minimum number of satellite signals that a GNSS receiver needs to track to correctly solve the positioning problem?**
- [ ] 1
- [ ] 2
- [ ] 3
- [x] 4
- [ ] None of the other options.


**Assume a radionavigation system which, like a GNSS, is based on signal travelling time measurements between transmitters and receiver. What is the difference between a pseudorange and a range measurement for such a system?**
- [ ] No difference, they are equivalent definitions.
- [x] A pseudorange is a range affected by an offset caused by the lack of synchronization.
- [ ] A pseudorange is a range measurement when such measurement is obtained through a signal.
- [ ] A pseudorange is a range affected by an unsolvable measurement error.
- [ ] None of the other options.


## WLAN / wifi

**Two devices connected in Wi-Fi without RTS/CTS assumed to collide, order what happened (and there where a series of steps like A sends, B, sends, DATA(A) collide with DATA(B) etc,)**

**Sort the exchanged messages to connect to an AP**

**Algorithm used in OWE**

**How WEP key management ic compared to WPA/WPA2**

**why not csma/ cd in wifi**

**authentication service - in the context of wireless networks**

**CDMA networks - why is power control important?**

**Purpose of DIFS in wifi networks**

**802.11 network - using ISM BW range, how many independent channels can be used?**

**Which wifi protocols are considered secure? (wpa with tkip, wpa2, wep, wpa3 )**

**Definition of authenticator supplicant port server authentication**

**Consider the maximum goodput one could reach with the following technologies. Put the following options in order from the HIGHEST to the LOWEST:**
1. 801.11n RTS/CTS disabled, UDP + IP
2. 801.11n RTS/CTS disabled, TCP + IP
3. 801.11n RTS/CTS enabled, UDP + IP
4. 801.11n RTS/CTS enabled, TCP + IP
5. Fast Ethernet, 100Mb/s
6. 802.11g RTS/CTS disabled, UDP + IP
7. 802.11g RTS/CTS disabled, TCP + IP
8. 802.11g RTS/CTS enabled, UDP + IP
9. 802.11g RTS/CTS enabled, TCP + IP


**Associate the correct definition for the following attacks in a WLAN:**
- **WEP Password cracking** → Leverage the reusage of Initialization Vector to create a collision and then break the RC4 key.
- **NAV attack**: → An attack where the attacker manipulates the frame duration value to prevent other devices from accessing the channel.
- **Rouge Access Point**: → A fake AP that impersonates the real AP.
- **De-authentication attack**: → The attacker sends forged de-authentication frames to force a STA to repeat the connection process.
- **Chopchop attack** → The process to recover the plaintext content of a frame by replaying a portion of the original frame.


**Which of the following information would an attacker require to mount a de-authentication attack against one specific STA in a WLAN?**
- [x] The AP MAC address
- [x] The STA MAC address
- [x] The WLAN channel
- [ ] The WLAN ESSID
- [ ] None of the other options.



**Why in 802.11 there are two destination mac addresses?**
- [x] The first indicates the AP that has to receive the frame. The second indicates the interface of the router that frame is destined to.
- [ ] To correctly identify the STA sending the frame.
- [ ] For anonymisation.
- [ ] For error correction.
- [ ] None of the other options.

**Consider the case a STA would like to transmit a frame to the AP. No other transmissions are present. RTS/CTS are disabled. Put in the correct order over time the sequence of events that would occur:**
1. A waits for DIFS time
2. A sends the DATA(A) frame
3. AP receives the DATA(A) frame
4. AP waits for SIFS time
5. AP sends ACK(A)
6. The transmission is completed

**Why in 802.11 there are two destination mac addresses?**
- [ ] In case there are multiple APs, to indicate the two APs that should receive and process the frame.
- [ ] For error correction
- [ ] For anonymisation
- [X] None of the other options.
- [ ] To correctly identify the STA sending the frame 

**What type of encryption does OWE use to secure data in transit?**
- [X] Diffie-Hellman key exchange to establish a shared secret.
- [ ] Asymmetric encryption using RSA keys.
- [ ] Symmetric key encryption with a pre-shared key.
- [ ] None of the other options.
- [ ] Static encryption keys manually configured by the user.

**Consider two STA, A and B, that belong to a WLAN managed by an AP. RTS/CTS are DISABLED.
A and B wake up at the same time to send a data frame, creating thus a collision.
Put in the right sequence the frames and events that could occur in time.**
1. A wait for DIFS and sends a DATA(A) frame 
2. B wait for DIFS and sends a DATA(B) frame 
3. DATA(A) collides with DATA(B) 
4. A and B wait for the AP's ACK 
5. Neither A nor B received the ACK, so they backoff 
6. A wait 10ms and tries to retransmit DATA(A) 
7. B wait 20ms and listen to the channel, sensing its busy with DATA(A) transmission
8. AP receives DATA(A)
9. AP sends an ACK to A

**Consider two STA, A and B, that belong to a WLAN managed by an AP. RTS/CTS are ENABLED.
A and B wake up at the same time to send a data frame, creating thus a collision.
Put in the right sequence the frames and events that could occur in time.**
1. A sends a RTS
2. B sends a RTS
3. RTS sent by A collides with RTS sent by B
4. A waits 10ms and tries to retransmit the RTS
5. B waits 20ms and tries to retransmit the RTS
6. AP receives the RTS from A and sends a CTS(A)
7. A and B receive the CTS(AP)
8. A sends a DATA frame while B defers its transmission
9. AP sends an ACK to A

**Why in a WLAN it is not sufficient to use the CSMA-CD protocol used in Ethernet?**

- [x] It will be impossible to detect an eventual collision by the transmitter because the transmitted signal power would be much stronger than the received signal power.
- [x] The WLAN transmitter can either transmit or receive, making it impossible to detect collisions when they occur.
- [ ] CSMA-CD requires a bidirectional channel to work. In WLAN there is only one single shared channel.
- [ ] CSMA-CD requires an additional channel to signal collisions.
- [ ] None of the other options

**Which of the following are effective defenses against deauthentication attacks in WiFi networks?**
- [ ] Disabling encryption to improve performance.
- [x] Honour only de-authentication requests that have the same physical layer properties of other messages sent by such a STA.
- [x] Honour de-authentication requests only from STAs that remain idle for the next 15 seconds.
- [x] Ignoring de-authentication frames entirely.
- [ ] None of the other options.


## WPAN / Bluetooth

**How does Bluetooth Classic handle privacy concerns compared to Bluetooth LE?**
- [ ] Bluetooth Classic uses encryption keys for all data transmissions.
- [ ] Bluetooth Classic limits the number of devices that can connect simultaneously.
- [ ] Bluetooth Classic randomizes MAC addresses for improved privacy.
- [ ] Bluetooth Classic does not have any privacy features.
- [ ] None of the other options.

**What is bluesnarfing?**

**Which security services does Bluetooth support?**
- [x] Authorization
- [x] Confidentiality
- [x] Authentication
- [ ] Notarization
- [ ] None of the other options.


**How prevent MITM on Bluetooth Secure Simple Pairing?**

**Which multiple access mechanism BT uses?**

**What is Bluetooth LE Privacy Feature?**
- [ ] A feature that encrypts all data transmitted over Bluetooth Low Energy (LE).
- [x] A feature that generates random MAC addresses for advertising packets.
- [ ] A feature that hides the Bluetooth device from unauthorized scanning.
- [ ] A feature that restricts the range of Bluetooth connections to improve privacy.
- [ ] None of the other options.


**What is pairing in Bluetooth technology? Select one:**
- [ ] A method for managing power consumption in Bluetooth devices.
- [X] The process of establishing a Bluetooth connection between two devices. 
- [ ] A mechanism for securely storing Bluetooth device information for future connections.
- [ ] None of the other options.
- [ ] A protocol for encrypting Bluetooth data transmissions.

## WWAN / mobile

**What is Stingray vulnerability?**

**Which of the following are 2G vulnerabilities?**

**Ss7 vulnerability**

**Purpose of paging and location are in mobile network**

**What is the difference between the Visitor Location Register (VLR) and the Home Location Register (HLR) in GSM networks?**
- [x] The VLR is a temporary database that stores information about subscribers currently roaming in the coverage area, while the HLR is a permanent database that contains detailed subscriber information and is maintained by the subscriber's home network.
- [ ] The VLR handles billing and account information for roaming subscribers, while the HLR manages encryption keys and authentication data.
- [ ] The VLR is responsible for managing voice call routing, while the HLR handles data transmission services.
- [ ] The VLR stores the IMSI and Ki keys, while the HLR stores the subscriber's phonebook and SMS messages.
- [ ] None of the other options.

**Describe device authentication in GSM (completare l’immagine con le parti date.)**

![gsm_auth](GSM_auth.png)

**4G networks - techniques used to enhance security**

**GSM Authentication**

**Wifi rate adaptation**

**What is the primary purpose of handover in mobile networks?**
- [ ] To encrypt voice and data transmissions for secure communication.
- [ ] To seamslessy transfer an active call or data session from one mobile teriminal to another.
- [ ] To manage billing and account information for mobile subscribers when they move between to Base Stations.
- [ ] To increase the data transmission speed betwen mobile devices.
- [x] None of the other options.

**What are the main components involved in the GSM authentication process?**
- [x] SIM card, Authentication Center (AuC), and Home Location Register (HLR).
- [ ] Mobile Equipment (ME), Visitor Location Register (VLR), and Base Transceiver Station (BTS).
- [ ] Mobile Station (MS), Base Station Subsystem (BSS), and Network Switching Subsystem (NSS).
- [ ] Mobile Management Entity (MME), Serving Gateway (SGW), and Packet Data Network Gateway (PGW).
- [ ] None of the other options.

**What is the primary purpose of rate adaptation in WiFi networks?**
- [ ] To adjust the transmission power of devices based on network conditions.
- [ ] To select the optimal data rate for transmitting data over the wireless channel based on the AP transmitter power.
- [ ] To select the optimal data rate for transmitting data over the wireless channel based on the distance from the AP.
- [ ] To adjust the transmission power of devices dynamically.
- [x] None of the others.

**Which of the following statements about PSK modulation is TRUE?**
- [ ] Since each symbol has a different energy level, operating close to the saturation region of a power amplifier does not cause distortion, resulting in efficient use of the amplifier.
- [ ] Since each symbol has a different energy level, operating close to the saturation region of a power amplifier causes distortion, resulting in a larger probability of error.
- [ ] Since all the symbols have the same energy, operating close to the saturation region of a power amplifier causes distortion, resulting in a larger probability of error.
- [x] Since all the symbols have the same energy, operating close to the saturation region of a power amplifier does not cause distortion, resulting in efficient use of the amplifier.
- [ ] None of the other options.


**What are the advantages and disadvantages of having small or larger cells in mobile networks?**
- [ ] Small cells are more expensive to deploy and maintain compared to larger cells, which are cheaper and more energy-efficient.
- [ ] None of the other options.
- [ ] Small cells are only suitable for urban areas, while larger cells can only be used in rural areas.
- [ ] Small cells reduce interference and improve signal quality, whereas larger cells are prone to higher levels of interference and degraded signal quality.
- [X] Small cells provide higher capacity and better coverage in dense areas but may require more frequent handovers as users move, while larger cells cover wider areas with fewer handovers but might have lower capacity in dense environments.

**Which of the following technologies are used in 4G networks to enhance security?**
- [x] Advanced Encryption Standard (AES) for data encryption.
- [x] Non-Access Stratum (NAS) security for signaling protection.
- [ ] Implementation of advanced firewall technologies at the network core.
- [ ] Temporary Mobile Subscriber Identity (TMSI) for user anonymity.
- [ ] None of the other options.

**What is the difference between the IMSI and the TMSI in mobile networks?**

- [ ] The IMSI identifies the mobile device, while the TMSI identifies the subscriber's location area.
- [ ] The IMSI is a randomly generated number used for secure authentication, while the TMSI is a fixed identifier stored on the SIM card.
- [ ] None of the other options.
- [x] The IMSI is a unique identifier assigned to a mobile subscriber by the home network, while the TMSI is a temporary identifier used to protect the subscriber's identity during communications with the network.
- [ ] The IMSI is used for billing and account management, while the TMSI is used for data encryption.
