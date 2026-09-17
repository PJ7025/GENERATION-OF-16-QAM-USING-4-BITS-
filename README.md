# GENERATION-OF-16-QAM-USING-4BITS

Generation of 16-QAM Using 4 Bits 16-QAM (16-Quadrature Amplitude Modulation) is a digital modulation technique in which 4 input bits are transmitted per symbol

**16-QAM (16-Quadrature Amplitude Modulation)is a digital modulation technique in which **4 input bits are transmitted per symbol. Since four bits can produce (2^4=16) different combinations, 16-QAM uses 16 distinct constellation points.

In this project, a 4-bit binary sequence such as **1011** is divided into two 2-bit groups. The first pair controls the **In-phase (I)** component, while the second pair controls the **Quadrature (Q)** component. Each pair is converted into one of four amplitude levels, typically \(-3,-1,+1,+3\).

The I and Q components modulate two carrier signals that are **90° out of phase**:


s(t)=I\cos(2\pifct)+Q\sin(2\pifct)

The project simulates the complete generation of the QAM waveform using **Python in Google Colab** and displays the digital input, I component, Q component, modulated waveform, and **16-QAM constellation diagram**. The concept can also be implemented in hardware using **AD633 analog multiplier ICs**, where the I and Q signals are multiplied with their respective carriers and then summed to generate the QAM output.

*Aim*

//To generate a 16-QAM signal using a 4-bit binary input and observe its I and Q components, modulated waveform, and constellation diagram using Python simulation//

*Result*

//The 16-QAM signal was successfully generated for a 4-bit input. The four input bits were mapped into I and Q amplitude levels, and the corresponding constellation point and QAM-modulated waveform were obtained//
