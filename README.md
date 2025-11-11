# CPU Simulator

This project is a simple CPU simulation written in **C++**.  
It models registers, memory, a control unit, and an arithmetic logic unit (ALU),  
using classes to represent hardware components.

## 🧠 Features
- Register and memory simulation  
- Control signal logic using bit masks  
- ALU with flag handling (zero, carry, negative)  
- File-based microcode loading (`CTRL_LSB.bin` and `CTRL_MSB.bin`)  
- Console input/output emulation  

## ⚙️ Requirements
- Windows OS (uses `windows.h` and `conio.h`)
- C++17 or later compiler (e.g. MinGW or MSVC)

## 🧩 Build Instructions
```bash
g++ main.cpp -o cpu_sim
./cpu_sim

🧾 Notes

To simulate ROM, ensure you have ROM.bin, CTRL_LSB.bin, and CTRL_MSB.bin in the same directory.

Press Home to reset, End to quit during simulation.


📄 License

This project is released under the MIT Licens
