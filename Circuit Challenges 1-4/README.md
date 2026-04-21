# Circuit Challenges README

## Overview

In this project, I completed selected circuit challenges from the “Resistors, LEDs, and More” slides. Specifically, I built and tested **Circuit Challenge 1, Circuit Challenge 3, and Circuit Challenge 4** using a breadboard, LEDs, resistors, push buttons, and other components.

Images of my circuits are included in this repository. To demonstrate original work, each image includes my name written on paper next to the circuit.

---

## Circuit Challenge 1 – Bright Bright Lights

### Objective

The goal was to light **4 LEDs at maximum brightness** without burning them out, and ensure that removing one LED does not turn off the others.

### What I Did

Initially, LEDs wired in **series** caused dim lighting and dependency (if one LED was removed, all turned off). To fix this:

* I rewired the circuit using a **parallel configuration**.
* Each LED had its **own path** from Vcc to ground.
* I added a **200Ω resistor in series with each LED** to limit current and prevent damage.

### Result

* All 4 LEDs lit at full brightness.
* Removing one LED did **not** affect the others.
* This demonstrated how **parallel circuits provide independent paths for current**.

---

## Circuit Challenge 3 – Turn the Lights Off

### Objective

Design a circuit where:

* LEDs are **ON by default**
* Pressing a button turns the corresponding LED **OFF**

### What I Did

* I connected each LED in a standard circuit with a resistor so it stays ON.
* I added a **push button in parallel with each LED**.
* When the button is pressed, it creates a **short circuit path (low resistance)** directly to ground.

### Explanation

* Current always follows the path of least resistance.
* When the button is pressed, current bypasses the LED and flows through the button instead.
* This causes the LED to turn OFF.

### Result

* LEDs stayed ON normally.
* Pressing a button immediately turned OFF the corresponding LED.
* This demonstrated the concept of **short circuits and current redirection**.

---

## Circuit Challenge 4 – Color the Rainbow

### Objective

Use a **tri-color LED (RGB)** to create multiple colors by controlling each channel:

* Red: controlled by a push button
* Green: controlled by a push button + light dependent resistor (LDR)
* Blue: controlled by a push button + potentiometer

### What I Did

* Connected the **common ground** of the tri-color LED.
* For each color channel:

  * Added a **200Ω resistor** for current limiting.
* Red channel:

  * Connected directly to a push button (on/off control).
* Green channel:

  * Added an **LDR** to vary brightness based on light.
* Blue channel:

  * Used a **10K potentiometer** to manually adjust brightness.

### Result

* I could mix colors by activating different channels.
* Brightness of green changed with light exposure.
* Blue intensity adjusted smoothly using the potentiometer.
* Combining colors produced various outputs (including white).

### Key Learning

* RGB LEDs create colors through **additive color mixing**.
* Variable resistors allow **dynamic control of current and brightness**.

---

## Proof of Work

* All circuit images uploaded in this repository include:

  * My **handwritten name**
  * The **physical circuit setup**
* This confirms the work was completed independently.

---

## Conclusion

Through these challenges, I learned:

* The difference between **series and parallel circuits**
* How to safely use **resistors with LEDs**
* How **current behaves in different paths**
* How to control circuits using **buttons and variable components**

These exercises helped build a strong foundation in basic electronics and circuit design.
