### Embedded firmware and hardware

I'm an electrical and computer engineering student at UC Davis, graduating in June 2027. I write embedded C firmware for STM32 and CC3200 microcontrollers. I also lay out boards in KiCad and write Verilog.

Right now I work on the CubeSat's flight software and the rover's electronics at [Space and Satellite Systems](https://github.com/Space-and-Satellite-Systems-UC-Davis).

#### Selected projects

- [**IntelliSat**](https://github.com/Space-and-Satellite-Systems-UC-Davis/IntelliSat): flight software for our club's CubeSat, on an STM32L476. I wrote a C monitor that streams 50 sensor channels over UART, and a fix for SPI transfers that reported success after a timeout.
- [**BalanceBot**](https://github.com/ChenSiyun1234/BalanceBot-STM32-CC3200): a self-balancing robot. I ported the balancing controller to an STM32F103, where it runs at 100 Hz from the IMU interrupt, and wrote the motor driver.
- [**FieldVision**](https://github.com/ChenSiyun1234/FieldVision): Grand Prize at Hack the Harvest 2026, a USDA NASS hackathon. I built the model that tells silage corn from grain corn using public satellite data.
- [**FPGA matrix accelerator**](https://github.com/ChenSiyun1234/eec180-fpga-matrix-accelerator): signed 8x8 matrix multiply in Verilog. Scaling from one to four MAC units took it from 513 to 134 clock cycles in ModelSim.
- [**NMOS LDO board**](https://github.com/ChenSiyun1234/nmos-ldo-board): a 1.0 V, 1 A regulator designed around a power NMOS and an op amp, on a four-layer KiCad board, with ngspice and thermal simulation.
- [**Rover drivebase**](https://github.com/ChenSiyun1234/rover-drivebase-sim): a MuJoCo simulation of a six-wheel rocker-bogie rover with wheel control, suspension and electrical limits.

More: a [CC3200 balancing cart](https://github.com/ChenSiyun1234/cc3200-balancing-cart) with bare-metal firmware and 27 host unit tests in CI, a [force-limited insertion axis](https://github.com/ChenSiyun1234/insertion-axis-force-sim), [CMOS inverters measured against LTspice](https://github.com/ChenSiyun1234/cmos-inverter-characterization) and a [small Unix shell in C++](https://github.com/ChenSiyun1234/unix-shell-cpp).

I'm looking for new-grad firmware and embedded roles starting in July 2027. You can reach me on [LinkedIn](https://www.linkedin.com/in/siyun-chen-691122342).
