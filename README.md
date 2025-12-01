# ARIGALA LAVANYA
# 212222060019
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

In optical fiber communication system, electrical signal is first converted into optical signal with the help of E / O conversion device as LED. After this optical signal is transmitted through optical fiber, it is retrieved in its original electrical form with the help O / E conversion device as photo detector.

Different technologies employed in chip fabrication lead to significant variation in parameters for the various emitter diodes. All the emitters distinguish themselves in offering high output power coupled into the plastic fiber. Data sheets for LEDs usually specify electrical and optical characteristics, out of which are important peak wavelength of emission, conversion efficiency (usually specified in terms of power launched in optical fiber for specified forward current), optical rise and fall ties which put the limitation on operating frequency, maximum forward current through LED and typical forward voltage across LED.

Photodetectors usually comes in variety of forms like photoconductive, photovoltaic, transistor type output and diode type output. Here also characteristics to be taken into account are response time of the detector which puts the limitation on the operating frequency, wavelength sensitivity and responsively. LED’s and LASER diodes are the commonly used sources in optical communication systems, whether the system transmits digital or analog signal. It is therefore, often necessary to use linear electrical to optical converter to allow its use in intensity modulation & high quality analog transmission systems. LED's have a linear optical output with relation to the forward current over a certain region of operation. Numerical aperture refers to the maximum angle at the light incident on the fiber end is totally internally reflected and is transmitted properly along the Fiber. The cone formed by the rotations of this angle along the axis of the Fiber is the cone of acceptance of the Fiber. The light ray should strike the fiber end within its cone of acceptance; else it is refracted out of the fiber core.
---

## PROCEDURE

Refer to the block diagram and make the following connections. Keep all switch faults in OFF position. Slightly unscrew the cap of LED SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the 1-meter fiber into the cap. Now tighten the cap by screwing it back. Slightly unscrew the cap of Photo Diode SFH250V. Do not remove the cap from the connector. Once the cap is loosened, insert the other end of fiber into the cap. Now tighten the cap by screwing it back. Keep the jumpers JP1 short for +12v, JP2 towards sine wave, JP3 short for +12 v & JP4 towards TX1on FCL-01. Keep switch SW2 in VI position on FCL-01. Connect voltmeter and current meter as per the polarities shown in the block diagram. Switch on the power supply. Keep the potentiometer P3 in its maximum position (anti-clockwise rotation). P3 is used to control current flowing through the LED. Keep the potentiometer P4 in its fully clockwise rotation.P4 is used to control bias voltage of the LED. To get the IV characteristics of LED, rotate P3 slowly and measure forward current and corresponding forward voltage. Take number of such readings for various current values and plot IV characteristics graph for the LED. • For each reading taken above, find out the power, which is product of I and V. This is the electrical power supplied to the LED. Data sheets for the LED specify optical power coupled into plastic fiber when forward current was 10 mA as 200 mW. This means that the electrical power at 10 mA current is converted into 200 mW of optical energy. Hence the efficiency of the LED comes out to be approx. 1.15%. • With this efficiency assumed, find out optical power coupled into plastic optical fiber for each of the reading. Plot the graph of forward current v/s output optical power of the LED. • Similarly measure the current at the detector. • Plot the graph of receiver current v/s output optical power of the LED. • Perform the above procedure again for all the combinations of Transmitter & Receiver.

<img width="532" height="247" alt="518106384-441834c8-3f2d-4cc7-98cf-873d39446e08" src="https://github.com/user-attachments/assets/d9cc0326-77e6-4d95-94a2-ce1760288ca4" />

<img width="573" height="230" alt="518106625-d2054527-cd33-447e-ab79-70ef813a5c72" src="https://github.com/user-attachments/assets/5f1a644c-ee4e-42a1-b5e4-099a8a5d86d1" />

<img width="576" height="267" alt="518106821-0292fd01-507f-4a13-ad05-9e8652c21f8f" src="https://github.com/user-attachments/assets/f96894bf-f256-48a5-b77f-55d3151add60" />



## Block Diagram
<img width="527" height="222" alt="515628394-bb7cdd3c-0c96-4c90-bd3e-0464f3f28f04" src="https://github.com/user-attachments/assets/75a03798-9f07-4ade-84a8-6087e0ea70df" />


### Connection Diagram
Setting up an Analog Link


<img width="571" height="122" alt="515628523-50281445-d044-48e2-809a-f65bd0f2eb65" src="https://github.com/user-attachments/assets/5535eef3-61b0-4436-a4ed-b6b921900dcb" />

*(Insert connection diagram here)*

---

## TABULATION  
**Transmission through Analog Link**
![515630019-ea280b11-3042-43c9-b0c4-44923306974c](https://github.com/user-attachments/assets/f4f57eb8-f6e9-42fa-8dc5-518d6fa7e843)




---

## MODEL GRAPH
![515630165-01a5a04a-c230-4511-b52a-cf4de3f19e94](https://github.com/user-attachments/assets/5aa94417-8b29-4b38-88c1-6bbbb64d63e1)

![517866184-e1c41a2b-61d0-4664-a7bb-73e5457b95f6](https://github.com/user-attachments/assets/b2cd0043-04dd-4f52-8d71-fdd1fb8dc594)


---

## RESULT
The transmitted and received waveforms for the 660 nm fiber link matched closely, confirming faithful analog and digital signal transfer. Output amplitude decreased with increasing frequency, showing the fiber link’s frequency-dependent response. The calculated –3 dB point confirms the bandwidth of the 660 nm analog/digital fiber optic link.


*(Summarize observations and conclusions here)*
