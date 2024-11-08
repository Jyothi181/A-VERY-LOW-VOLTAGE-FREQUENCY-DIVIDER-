# A-VERY-LOW-VOLTAGE-FREQUENCY-DIVIDER
A very low voltage frequency divider in folded MOS current mode logic with complementary n-type and p-type flipflops

Technology : 45nm
Tools : Tanner EDA
# Introduction
Over the past few years, the surpassing advancements in Integrated system technologies is there is a major solid growth in using micro circuitry devices. In this digital world, electronic devices like computers mostly use registers for multi purposes. In this paper, a static frequency divider based on folded MOS current mode logic (FMCML) is presented. The design is based on alternating FMCML flip-flops with complementary pMOS or nMOS input differential pairs since common-mode problems arise by using only one type of FMCML flip-flops. We propose a different approach: input and output common-mode levels of each divide-by-2 (DIV2) block are made compatible by alternating complementary FMCML DFF stages, thus avoiding any additional stage in between. A modeling strategy to analyze the dependence of propagation delay and power consumption on the bias currents is introduced. We demonstrate that the behavior of the FMCML is different both from the one of the conventional MCML DFF (D-type Flip-Flop) and from FMCML DFF. In this paper, the design was implemented using 45nm Technology in Tanner EDA.


# Current mode logic (CML)
CML or source-coupled logic (SCL), is a digital design style used both for logic gates and for board-level digital signalling of digital data . The basic principle of CML is that current from a constant current generator is steered between two alternate paths depending on whether a logic zero or logic one is being represented. Typically, the generator is connected to the two sources of a pair of differential FETs with the two paths being their two drains. Bipolar equivalents operate in the same way, with the output being taken from the collectors of the BJT transistors.

# Folded MOS Current Mode Logic (FCM-CML)
It is a type of digital logic design that combines the advantages of current mode logic with the benefits of folded structures.

