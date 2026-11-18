### Firmware, boards and control loops

I study electrical and computer engineering at UC Davis. I like the place where code meets hardware, and the bugs that only show up on the real thing. My balancing cart once sped up when I pushed it, because one sign in the velocity loop was wrong.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/trace-dark.svg">
  <img src="assets/trace-light.svg" width="100%" alt="A balance loop settling after a push.">
</picture>

These days I work on the rover's electronics and the CubeSat's flight software with [Space and Satellite Systems](https://github.com/Space-and-Satellite-Systems-UC-Davis).

#### Things I've built

- [**FieldVision**](https://github.com/ChenSiyun1234/FieldVision) tells silage corn from grain corn using public satellite data. It won the Grand Prize at Hack the Harvest 2026.
- [**IntelliSat**](https://github.com/Space-and-Satellite-Systems-UC-Davis/IntelliSat) is the flight software for our club's CubeSat. My C monitor streams 50 sensor channels over UART.
- [**Rover drivebase**](https://github.com/ChenSiyun1234/rover-drivebase-sim) is a six-wheel rocker-bogie rover simulated in MuJoCo.
- [**BalanceBot**](https://github.com/ChenSiyun1234/BalanceBot-STM32-CC3200) is a robot that stays up, with a 100 Hz balance loop on an STM32F103.
- [**Matrix accelerator**](https://github.com/ChenSiyun1234/eec180-fpga-matrix-accelerator) multiplies signed 8x8 matrices in Verilog. I took it from 513 to 134 clock cycles.
- [**NMOS LDO board**](https://github.com/ChenSiyun1234/nmos-ldo-board) puts out 1.0 V at 1 A from discrete parts on a four-layer KiCad board.

Also on the shelf: a [CC3200 balancing cart](https://github.com/ChenSiyun1234/cc3200-balancing-cart), a [force-limited insertion axis](https://github.com/ChenSiyun1234/insertion-axis-force-sim), [CMOS inverters measured against LTspice](https://github.com/ChenSiyun1234/cmos-inverter-characterization) and a [small Unix shell](https://github.com/ChenSiyun1234/unix-shell-cpp).

[LinkedIn](https://www.linkedin.com/in/siyun-chen-691122342)
