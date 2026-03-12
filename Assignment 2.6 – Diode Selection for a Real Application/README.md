# 12 V Input Protection Diode

For the protection circuit, the 1N4007 rectifier diode was selected. This diode is commonly used in power circuits because it has suitable voltage and current ratings and is inexpensive and widely available.

The 1N4007 diode has a maximum reverse voltage rating of 1000 V. Since the circuit operates at only 12 V, this provides a very large safety margin and ensures the diode will not break down under normal conditions.

The maximum forward current rating of the diode is approximately 1 A. In the simulated circuit, the load current is much smaller than this value, so the diode can safely conduct the required current without overheating.

Another advantage of the 1N4007 is its low cost and high availability. It is one of the most commonly used rectifier diodes and can easily be purchased from electronics suppliers worldwide.

In the LTspice simulation, when the input voltage is positive, the diode becomes forward biased and allows current to flow through the circuit. If the input polarity is reversed, the diode becomes reverse biased and blocks the current. This prevents damage to the connected electronics.

Because of its high voltage rating, sufficient current capacity, and low cost, the 1N4007 is a suitable choice for a simple 12 V DC input protection circuit.
