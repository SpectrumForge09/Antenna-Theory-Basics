# Introduction to Antenna Theory

- An antenna is defined by Webster’s Dictionary as **“a usually metallic device (as a rod or wire) for radiating or receiving radio waves.”**
- Long story short, an antenna acts like a **transceiver** (a device which transmits as well as receives).
- The following are a set of questions that one could encounter at the beginning stage of exploring antennas:
  - If a wire acts like an antenna, why does a straight wire not radiate?
  - What is the need of an antenna and the purpose of learning about it?
  - How does an antenna radiate electromagnetic waves?
  - Is an antenna a source of energy or just a converter?
  - Can a wire always act as an antenna?
- At the end of this discussion, the reader will be able to have clarity about a couple of questions from this set, and the remaining will be cleared as the course proceeds further.
- It is worthy to note that an antenna is just another engineering structure to be studied and not something **“ALIEN”** as perceived by most while first dealing with antennas.

---

## 1. If a wire acts like an antenna, why not a straight wire radiates?

### Discussion:

To understand this, let us consider three cases:

### CASE 1: Straight Wire with DC (No Radiation)
- Consider a perfectly straight infinite wire carrying DC current.
- Charges move with constant velocity (since DC).
- No acceleration (since DC).
- No charge build-up anywhere (since straight wire – no discontinuity).
- These are the main requirements for radiation to occur, but since all the cases are defied here, there is **no radiation**.
- **Application:** This is why power transmission lines don’t act like radio transmitters even though they are very long.

---

### CASE 2: Straight Wire with AC but Electrically Short (Almost No Radiation)
- Its length ≪ Wavelength ( \( l \ll \lambda \) ).
- Charges do accelerate back and forth (since AC).
- But the charge separation is extremely small (since electrically short).
- The fields produced by tiny segments almost cancel each other, and as a result most people conclude that a straight wire won’t radiate.
- But the fact is straight wires do have **very weak radiation**.

---

### CASE 3: Straight Wire with Proper Length (Strong Radiation)
- When the length is equal to \( \lambda/2 \) (note: here \( \lambda \) corresponds to the wavelength of the wave which is being transmitted or received).
- Current is sinusoidally distributed (since length = \( \lambda/2 \)).
- Charges pile up at the ends alternately (since finite length).
- This creates a **time-varying electric dipole**.
- Thus, when one end is positive, the other end is negative and vice versa.
- This acts like a **half-wave dipole antenna**.

---

### Inference:

It is inferred that for a conductor, the following are needed for radiation:

- Time-varying current (AC) must flow.
- Charges must undergo acceleration.
- A time-varying dipole moment must exist.
- The structure should have **finite electrical length**.
- The fields must **not cancel each other** (net field component must exist).

