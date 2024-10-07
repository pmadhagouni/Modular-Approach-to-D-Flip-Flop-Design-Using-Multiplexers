# **Modular-Approach-to-D-Flip-Flop-Design-Using-Multiplexers**
* Designed a D Flip Flop using Swing Restored Pass–Transistor Logic and Lean integration with pass transistor (Single–rail pass
transistor logic).
* Used single-rail pass transistor logic to optimize circuit design, resulting reduced power consumption and improved performance.
* Employed swing restoration methods to maintain signal integrity and minimize voltage degradation in logic levels.
* Conducted extensive simulations using software tools (e.g., LTSpice, Cadence) to validate circuit functionality and timing
parameters.

![image](https://github.com/user-attachments/assets/354f4f1e-4352-4454-b2bf-f7b4e14b74d0)

D flip-flop (DFF) is a type of flip-flop circuit that stores a single bit of data. It is used to store a value that can be either a logic 0 or a logic 1, and it can be used for various purposes such as storage, synchronization, and sequencing of digital signals.

The D flip-flop has a single input, known as the data (D) input, which is used to set the value of the flip-flop. The output of the flip-flop, known as the Q output, represents the stored value of the flip-flop.

Our design is quite like the master-slave D flip-flop is made up of two D flip-flops, a master flip-flop, and a slave flip-flop, which are triggered on different phases of the clock signal to improve the reliability of the output.

* The condition we are given is that the clock should run at 1.5 GHz.
* Converting it to the time we have a clock period of 0.66ns with a pulse width of 0.33ns.
* T = 1/f = 1 / (1.5 *109) = 0.66 ns.

![image](https://github.com/user-attachments/assets/3dec7ca5-f2d9-4445-940e-42849b82e4b8)

The operation of the D flip-flop is controlled by a clock input, which is used to trigger the flip-flop to store the value on the D input. When the clock input is high, the D input is sampled and stored in the flip-flop, and the Q output reflects the stored value. When the clock input is low, the flip-flop holds the stored value and does not change its state

![image](https://github.com/user-attachments/assets/862e2b8a-fe5c-4cd4-a8ba-7b455b33359b)

The total area of LEAP + PPL = 3960 x 180 =
712800 nM2 or 712.800 uM2.
