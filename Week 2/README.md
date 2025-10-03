Learning SoC Design with BabySoC
---

When I first heard about System on Chip (SoC) it sounded me difficult. But after reading more Then I realized it’s just like having a small computer inside a single chip. Instead of many separate parts everything (CPU, memory, input/output) is put together in one place. That’s why SoCs are used in phones, tablets, watches and many smart devices they save space, use less power and work faster.

What is an SoC?
---

A System on Chip is a tiny chip that has:

* CPU (processor) → Works like the brain and runs instructions.

* Memory → Stores data both temporary and permanent.

* Peripherals → Extra parts like timers, GPIOs, DAC, ADC and etc.

* Interconnect → The 'wires' inside the chip that connect everything.

Since all of this is inside one chip, SoCs are small, efficient and cheaper than building with many separate components.

Why BabySoC is useful for learning
---

Real SoCs like Apple’s A-series or Snapdragon are huge and complex. But BabySoC is a small easy-to-understand version made for students.

It has only three important blocks:

* RVMYTH CPU (processor) → Runs basic programs.

* PLL (Phase Locked Loop) → Makes a clean and stable clock so everything works together.

* DAC (Digital to Analog Converter) → Changes digital signals into analog signals like audio or video.

This simple setup is enough to learn how chips work without getting lost in advanced details.

Why we do functional modeling first
---

Before jumping into actual chip design we first test the idea using functional modeling. Think of it like making a draft or a practice run.

In BabySoC, this helps to:

* Check if the CPU instructions are working.

* Make sure the PLL gives the right clock signal.

* See if the DAC produces the correct output.

After this, we can move on to detailed design and physical layout.

My takeaway
---

For me, BabySoC is like a starter kit for understanding SoCs. It’s small, simple and shows the key ideas clearly:

* A chip is like a mini computer.

* The PLL keeps timing stable.

* The DAC connects digital systems to the analog world.

By playing with BabySoC, I can slowly build knowledge about how modern chips are made.

This is my current understanding of SoC design and BabySoC.
