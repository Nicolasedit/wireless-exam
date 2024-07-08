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


**Associate the correct definition of the following Security Services:**
- **Non-repudiation:** Assurance that someone cannot deny the validity of something.
- **Confidentiality:** Ensuring that information is accessible only to those authorized to have access.
- **Availability:** Ensuring that authorized users have access to information and associated assets when required.
- **Integrity:** Maintaining and assuring the accuracy and completeness of data over its entire lifecycle.


## Signals and basics

**In digital Communication system which type of waveforms are propagated in the channel?**

**Order the elements in the transmission chain (encoder, modulator, channel etc.)**

**Why the definition of the bandwidth 3db**

**PSK modulation - about the energy level of symbols and saturation level of a power amplifier**

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


**Are the clocks of Satellite and receiver synchronized?**

**What is broadcasted by the satellite**

**Do Out-Of-Band interferences affect GNSS?**

**Which of the following is a common indicator of a GNSS spoofing attack?**
- [ ] A gradual decrease in signal strength over time
- [ ] Enhanced accuracy and reliability of GNSS signals
- [ ] Sudden and significant deviations in position, velocity or time calculations
- [ ] None of the others
- [ ] Discrepancies between GNSS-based positions and those from alternative navigation systems (e.g., inertial navigation systems)

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


