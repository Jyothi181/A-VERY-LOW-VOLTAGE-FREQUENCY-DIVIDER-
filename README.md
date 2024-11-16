# A-Very-Low-Voltage-Frequency-Divider
A very low voltage frequency divider in folded MOS current mode logic with complementary n-type and p-type flipflops

- **Technology :** 45nm
- **Tools :** Tanner EDA

# Table of Contents
- Introduction
- Current mode logic (CML)
- MCML
- Folded MOS Current Mode Logic (FCM-CML) 
- Key Features
- Complementary flip-flops
- Low Voltage
- Schematics
- Results
- Future Scope

# Introduction

A frequency divider by 16 in Folded MCML using complementary p-type and n-type flip flops is proposed. This architecture is able to operate with a low supply voltage compared to MCML based architectures. As the scaling of the transistors are reducing gradually, the proposed circuit is able to work under Deep Sub-micron technology. By using complementary types of flip flops, there is also a reduction of common mode problems and minimum power dissipation. In this, the control of the clock is also achieved by using constant current source.The propagation delay is also reduced. Due to these advantages, these are mostly used at high frequency applications, clock generators, phase locked loop circuits and radio applications.



# Current mode logic (CML)

The basic principle of CML is that current from a constant current generator is steered between two alternate paths depending on whether a logic zero or logic one is being represented. Typically, the generator is connected to the two sources of a pair of differential FETs with the two paths being their two drains. Bipolar equivalents operate in the same way, with the output being taken from the collectors of the BJT transistors. The fast operation of CML circuits is mainly due to their lower output voltage swing compared to the static CMOS circuits as well as the very fast current switching taking place at the input differential pair transistors. One of the primary requirements of a current-mode logic circuit is that the current bias transistor must remain in the saturation region in order to maintain a constant current.

# MCML
With MOS transistors, it is known as MCML. CMOS rail to rail is used for low static power dissipation whereas for high frequencies, CML is preferred. Due to the reduced output voltage swing, this topology can operate faster with lower power. The reference logic family is, therefore, the MOS current mode logic (MCML) that allows higher maximum speed than standard CMOS logic and could even provide lower power consumption at frequencies that are still suitable for CMOS.

# Folded MOS Current Mode Logic (FCM-CML) 
It is a type of digital logic design that combines the advantages of current mode logic with the benefits of folded structures.

## Key Features

- **Current Mode Operation:** FCM-CML operates using current rather than voltage, which can lead to faster switching speeds and improved noise margins.

- **Folded Structure:** The folded aspect refers to the configuration of the transistors, allowing for a more compact design. This typically involves the use of complementary pairs of MOSFETs arranged to optimize performance and reduce power consumption.
  
- **High Speed:** The use of current mode logic allows for rapid signal transitions, making FCM-CML suitable for high-speed applications.

- **Reduced Power Consumption:** By minimizing switching power and optimizing the use of bias currents, FCM-CML circuits can be more power-efficient compared to traditional voltage-mode logic.

- **Differential Signaling:** FCM-CML often employs differential signaling, which improves immunity to noise and enhances the signal integrity.

- FCM-CML is an effective design approach that balances speed, power efficiency, and noise resilience, making it suitable for modern electronic systems.

![image](https://github.com/user-attachments/assets/960c2535-1557-413f-9adf-9b1bf59f20d5)

***Figure 1: FMCML D-Latch***

# Complementary flip-flops 
Complementary flip-flops are often used in frequency dividers for several key reasons. Flip-flops (such as those using both PMOS and NMOS transistors) can switch faster than single-type flip-flops. This characteristic is crucial for high-speed applications. They can achieve lower static power consumption since only one type of transistor is conducted at any time, minimizing the short-circuit current that occurs during switching. Complementary designs help mitigate issues related to signal degradation and improve noise margins. This results in more reliable operation, especially at high frequencies. They produce complementary outputs, which can be advantageous for further stages of digital logic, reducing the need for additional inverters and improving overall circuit efficiency. Using complementary flip-flops allows for straightforward implementation of divide-by-2 or more complex frequency division without needing additional circuitry to handle signal inversion. Overall, the complementary nature of these flip-flops enhances performance, efficiency, and reliability in frequency divider applications.

# Low Voltage

Low voltage is often used in frequency dividers for several reasons. Lower voltages reduce dynamic power consumption, which is crucial in battery-operated devices and low-power applications. Operating at lower voltages minimizes heat generation, enhancing reliability and extending the lifespan of the components. Many modern digital circuits and systems, especially in CMOS technology, are designed to operate at low voltage levels. This ensures compatibility and allows for integration with other low-voltage components. Lower voltage levels can improve noise margins in some applications, making the circuits less susceptible to noise and improving signal integrity. 


![image](https://github.com/user-attachments/assets/5e6b7d26-a506-47e5-a3d4-653a5a0e0c91)

***Figure 2: Proposed Frequency divider architecture***

![image](https://github.com/user-attachments/assets/83e07b8a-873d-4809-906a-a598f88dc16b)

***Figure 3: Topology of a) n-type b) p-type D flip flop in Folded MCML logic style***

![image](https://github.com/user-attachments/assets/fb3eab5e-9f58-4990-a263-ccaee3837a27)

# Schematics

***Figure 4: Schematic of n-type flip flop***

![image](https://github.com/user-attachments/assets/a855727e-dd79-46d3-b77e-a770c62c6b85)

***Figure 5: Schematic of p-type flip flop***


# Results

![image](https://github.com/user-attachments/assets/1a03735b-e7ab-4f0b-be46-a38306eef87e)

***Figure 6: Schematic of proposed frequency divider in FMCML***

![image](https://github.com/user-attachments/assets/947aa59f-f3c6-4241-945c-9ef572d26485)

***Figure 7: Output of proposed frequency divider in FMCML***

# Future Scope
Further we can approach multi-folded (MF) MCML that generalizes the FMCML topology idea, thus allowing a minimum power supply equal to a single-level MCML (i.e., the MCML inverter) regardless of the number of inputs.





