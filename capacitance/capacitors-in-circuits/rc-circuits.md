# RC Circuits

Oftentimes, capacitors and resistors are found together in "RC" (resistor + capacitor) circuits that are useful for time-based electronic devices like traffic lights, windshield wipers, camera flashes. This is because variables like **voltage, charge, and current change with time** in RC circuits.

![RC circuit diagram. when switch is closed to "a," capacitor starts CHARGING through the resistor. when switch is closed to "b," capacitor starts DISCHARGING.](<../../.gitbook/assets/image (9).png>)

Based off this, we can easily write the equation ![](<../../.gitbook/assets/image (10).png>)However, reader beware!! Current and charge vary in the circuit, so we can't _literally_ use this equation.&#x20;

## Charging a Capacitor&#x20;

As we know, capacitors **start off with 0 charge and 0 voltage** **across them** in a circuit. Because of this, they also start off with the maximum amount of current. Therefore, the following graphs would make sense:&#x20;

![](<../../.gitbook/assets/image (14).png>)![](<../../.gitbook/assets/image (12).png>)

Charge on the capacitors increases within time, whereas current decreases over time until eventually no current passes through & the voltage across = emf of battery. Note: since q is proportional to V, **the graph of **_**V vs. Time**_** would look like **_**q vs. Time**_. It's worth observing that the graph for current is undergoing _exponential decay._

![](<../../.gitbook/assets/image (5).png>)

* **ε = emf of battery**, or the max difference in potential
* **Cε** = **Q0**, or the **MAXIMUM charge** that'd be generated in the capacitor
* t is the time passed; RC is the time constant. As -t/RC gets bigger, **e^-t/RC approaches 0**, making **q approach Q0 over time**.

![](<../../.gitbook/assets/image (4).png>)

* using i = dq/dt (change in amt of charge over time), we see that the **current across the capacitor approaches 0**, since it's proportional to e^-t/RC

![](<../../.gitbook/assets/image (6).png>)

* very similar to the charge equation --> just dividing it by C using the q = CV relationship (see "Capacitors")

#### Time Constant (**τ = RC)**&#x20;

A unit of time we use for RC circuits is τ (tau).  **τ = resistance \* capacitance = RC** --> makes sense b/c the smaller the resistance, the quicker the capacitor gets charged.

t(total) = the total time it takes to charge/discharge a capacitor. It takes around **5 time constants** for the capacitor to **fully charge** and **fully discharge**. t(total)/τ = 5 in most cases.

## Discharging a Capacitor

now, we look at another situation: the capacitor is already charged to V0 and Q0 (full potential & charge), and is now _discharging_ with a flick of the switch_._ we set t = 0 back again.&#x20;

We expect the opposite to happen: charge and voltage would decrease over time (exponential decay), whereas current would increase. Indeed:



## Summary

![all the equations in one table!](<../../.gitbook/assets/image (3).png>)
