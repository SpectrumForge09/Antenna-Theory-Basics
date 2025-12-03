# Equivalent Circuit of Antenna

- Before discussing about the antenna, let us consider an example where there is a communication system and it wants to transfer data to other devices.  
  The conduction of information in communication systems can either be done through:

## COMMUNICATION SYSTEMS
- **Transmission Lines**
- **Electromagnetic Radiation**

---

## What are Transmission Lines?

- In low-frequency circuits, we use ordinary wires for connections and usually don’t bother much about their effects.
- But at high frequencies, the same wire cannot be used in the same way.

  **Analogy:**  
  If a 2-year-old tries to hit me, I can withstand the effect and it doesn’t bother me much. This is because of the difference in sizes between me and the child.  
  But if another 20-year-old tries to hit me, that bothers me because my size and his size are comparable.

- Likewise, in low-frequency systems:
  - The wavelength of the waves travelling in the wire and the dimensions of the wire are **not comparable**.

- But in the case of high frequency:
  - The wavelength becomes **comparable to the wire dimensions**  
  - **λ = c / f** → As frequency (**f**) increases, wavelength (**λ**) decreases.


- This leads to a phenomenon known as the **skin effect**, where:
  - The current in the wire is pushed towards the surface of the conductor.
  - The current will not be able to efficiently transmit through the entire cross-section of the wire.

- **Transmission lines are nothing but the high-frequency model of a wire.**

---

## Role of Antennas in Communication

- Coming back to our discussion, apart from transmission lines (for conduction of information), **electromagnetic radiation** could also be used.
- **Antennas are nothing but tools for creating such electromagnetic radiation.**
- The main task for antenna designers is to control **how the currents should flow in the antenna** so that the **radiation shape (radiation pattern)** will be in the desired form.
<p align="center">
  <img src="skin-effect.jpg" width="400">
  <br>
  <em>Figure 1: Skin Effect in Conductors</em>
</p>


---

## Antenna as a Transition Device
<p align="center">
  <img src="Screenshot 2025-12-02 162514.png" width="400">
  <br>
  <em>Figure 2: Antenna as a transition device</em>
</p>

-	The above figure depicts the equivalent circuit of an antenna. where the source is represented by an ideal generator, the transmission line is represented by a line with characteristic impedance Zc, and the antenna is represented by a load ZA [ZA =  (RL + Rr) + jXA] connected to the transmission line.
- The antenna can be modeled as a **transition device**.
- The current and voltage which pass through the wire are converted into **electromagnetic radiation**, and the antenna aids in this conversion.
- Hence, while discussing antenna parameters, there will essentially be **two perspectives**:
  - The **circuit perspective**
  - The **radiation perspective**

---

## Equivalent Circuit of an Antenna
<p align="center">
  <img src="Screenshot 2025-12-02 203403.png" width="400">
  <br>
  <em>Figure 2: Antenna as a transition device</em>
</p>

- The equivalent circuit of an antenna consists of:
  - A **source** represented by an ideal generator.
  - A **transmission line** represented by a line with characteristic impedance \( Z_c \).
  - An **antenna load** connected to the transmission line:

  \[
  Z_A = (R_L + R_r) + jX_A
  \]

- Where:
  - \( R_L \) represents **conduction and dielectric losses**.
  - \( R_r \) represents the **radiation resistance**, which is a measure of how much power is radiated by the antenna.
  - \( X_A \) represents the **imaginary part of the antenna impedance** associated with stored reactive energy.

- **Standing wave patterns** are the result of constructive or destructive interference between:
  - The incoming wave, and
  - The reflected wave in the transmission line.

- These standing waves represent **storage of energy**, which is undesirable because:
  - We do not want to store energy.
  - We want the energy to be **radiated efficiently**.

- Therefore, **impedance matching between the antenna and the transmission line is essential** to avoid energy being stored in the system and to ensure maximum radiation.
