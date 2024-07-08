# Quiz or closed questions

## General

**What is a stream cipher?**

**Which of the following defines a cipher text attack?**

**what is known plaintext attack**

**Classification of wireless network, adhoc/infrastructure, fixed/mobile, wwan/wlan**

**What is Asymmetric encryption**

**Associate the correct definition to the following security mechanisms**
Access Control: Determines and enforce the access rights of the entity depending on the authenticated identityProvides confidentiality for either data or traffic flow information
Encipherment: Provides confidentiality for either data or traffic flow information
Traffic Padding: Protects against traffic analysis attacks by adding non essential data to network communicationsAssures data integrity, origin, time, and destination about data communicated between two or more entities
Notarization: Assures data integrity, origin, time, and destination about data communicated between two or more entities


## Wireless Communication

**In digital Communication system which type of waveforms are propagated in the channel?**

**Order the elements in the transmission chain (encoder, modulator, channel etc.)**

**Why the definition of the bandwidth 3db**

**PSK modulation - about the energy level of symbols and saturation level of a power amplifier**

**Put the building blocks of a digital communication system in the correct order:**
TX --> Encoder --> Modulator  --> Channel  --> Demodulator  --> Decoder  --> RX

## GNSS
**How can a spoofing attack be detected?**

**Why monitoring GNSS spectrum is insufficient for spoofing detection?**

**GNSS - Why is line of sight to satellites important to have correct pseudorange calculations?**

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

**GNSS difference between range and pseudorange**


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

**Maximum goodput that can be reached with this technology from 1 to 9**
1. 802.11n, RTS/CTS enabled, UDP+IP
2. 802.11n, RTS/CTS disabled, UDP+IP
3. 802.11g, RTS/CTS enabled, UDP+IP
4. 802.11g, RTS/CTS disabled, UDP+IP
5. 802.11n, RTS/CTS enabled, TCP+IP
6. 802.11g, RTS/CTS disabled, TCP+IP
7. 802.11g, RTS/CTS enabled, TCP+IP
8. 802.11n, RTS/CTS disabled, TCP+IP
9. Fast ethernet 100 Mbps

**WLAN attacks**
- [ ] WEP
- [ ] NAV
- [ ] ROGUE AP
- [ ] DEAUTH
- [ ] CHOP-CHOP

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

## WPAN / Bluetooth

**How does Bluetooth Classic handle privacy concerns compared to Bluetooth LE?**
- [ ] Bluetooth Classic uses encryption keys for all data transmissions.
- [ ] Bluetooth Classic limits the number of devices that can connect simultaneously.
- [ ] Bluetooth Classic randomizes MAC addresses for improved privacy.
- [ ] Bluetooth Classic does not have any privacy features.
- [ ] None of the other options.

**What is bluesnarfing?**

**BT secure services**

**How prevent MITM on Bluetooth Secure Simple Pairing?**

**Which multiple access mechanism BT uses?**

**Bluetooth Privacy Feature**

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
- [X] The VLR is a temporary database that stores information about subscribers currently roaming in the coverage area, while the HLR is a permanent database that contains detailed subscriber information and is maintained by the subscriber's home network.
- [ ] The VLR handles billing and account information for roaming subscribers, while the HLR manages encryption keys and authentication data.
- [ ] The VLR stores the IMSI and Ki keys, while the HLR stores the subscriber's phonebook and SMS messages.
- [ ] The VLR is responsible for managing voice call routing, while the HLR handles data transmission services.
- [ ] None of the other options.

**Describe device authentication in GSM (completare l’immagine con le parti date.)**

![gsm_auth](GSM_auth.png)

**4G networks - techniques used to enhance security**

**GSM Authentication**

**Wifi rate adaptation**

**Handover (mobile)**

**What are the advantages and disadvantages of having small or larger cells in mobile networks?**
- [ ] Small cells are more expensive to deploy and maintain compared to larger cells, which are cheaper and more energy-efficient.
- [ ] None of the other options.
- [ ] Small cells are only suitable for urban areas, while larger cells can only be used in rural areas.
- [ ] Small cells reduce interference and improve signal quality, whereas larger cells are prone to higher levels of interference and degraded signal quality.
- [X] Small cells provide higher capacity and better coverage in dense areas but may require more frequent handovers as users move, while larger cells cover wider areas with fewer handovers but might have lower capacity in dense environments.
