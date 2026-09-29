# Siyun Chen

I'm an Electrical Engineering and Computer Engineering student at UC Davis, graduating in June 2027. I'm looking for new-grad firmware and embedded roles.

## What I work on

Mostly firmware in C for STM32 and CC3200 microcontrollers. I also do PCB layout in KiCad and digital design in Verilog. I like bugs that only show up on real hardware, like a velocity loop with the wrong sign.

## Projects

- **[CC3200 self-balancing cart](https://github.com/ChenSiyun1234/cc3200-balancing-cart)**: bare-metal C firmware that started as my EEC 172 final project. I later moved its fault rules into a module with 27 host unit tests and CI.
- **[BalanceBot](https://github.com/ChenSiyun1234/BalanceBot-STM32-CC3200/blob/main/STM32/Robot/ax_control.c)**: I ported a vendor's 100 Hz balancing controller to an STM32F103. I wrote the motor driver and the Bluetooth commands around it.
- **[Satellite sensor monitor](https://github.com/Space-and-Satellite-Systems-UC-Davis/IntelliSat/pull/117)**: I wrote a sensor monitor in C for my club's STM32L476 flight software. It streams 50 sensor channels as CSV over UART.
- **[Rover control board layout](https://github.com/SSS-Controls/Rover_Contest-Electrical_Subteam/tree/S_C/single_board/images)**: I completed a four-layer KiCad layout of the rover's STM32 control board, routing six motor/encoder channels and the 3.3 V/5 V power.
- **[FPGA matrix accelerator](https://github.com/ChenSiyun1234/eec180-fpga-matrix-accelerator)**: a signed 8x8 matrix multiply in Verilog (EEC 180). Going from one to four MAC units cut it from 513 to 134 clock cycles in ModelSim.
- **[CMOS inverter characterization](https://github.com/ChenSiyun1234/cmos-inverter-characterization)**: CD4007 inverters measured against LTspice (EEC 111 lab). Two PMOS in parallel raised the switching point by 178 mV; LTspice predicted 205 mV.

## Skills

C, C++, Python, Verilog · STM32 (Cortex-M3/M4), CC3200, FreeRTOS, I2C, UART, PWM · KiCad, LTspice, ModelSim · Git, GitHub Actions, unit testing (Unity, pytest) · oscilloscope, ADALM2000

## Contact

[LinkedIn](https://www.linkedin.com/in/siyun-chen-691122342) · 200533csy@gmail.com
