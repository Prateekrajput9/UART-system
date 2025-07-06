# UART Communication in Verilog

This project demonstrates a basic UART (Universal Asynchronous Receiver and Transmitter) communication system using Verilog. It includes a transmitter, a receiver, and a testbench to simulate data transmission and reception between them.

---

## 📂 Files Included

- `transmitter.v` – Sends 8-bit parallel data serially with start and stop bits.
- `receiver.v` – Receives serial data and converts it back to 8-bit parallel format.
- `serial_communication_test.v` – A testbench that simulates the entire UART communication.

---

## ⚙️ Project Details

- **Data Bits**: 8
- **Start Bit**: 1
- **Stop Bit**: 1
- **Baud Rate**: 9600 bps (assumed timing in simulation)
- **Clock**: Fixed simulation clock (no separate baud rate generator module)

---

## 📘 About the Design

This project is based on concepts described in the paper:  
**"Design and Implementation of UART Serial Communication on FPGA Using Verilog"**  
🔗 [Read Paper (IJEAT)](https://www.ijeat.org/wp-content/uploads/papers/v9i5/E1135069520.pdf)

While the paper describes a more modular hardware-ready architecture (with a separate baud rate generator and state machines), this project is a simplified simulation version for learning and beginner practice.

---

## ▶️ How to Simulate

1. Open **Vivado**, **ModelSim**, or any Verilog simulator.
2. Add the three `.v` files to your project.
3. Set `serial_communication_test.v` as the top module.
4. Run the simulation.
5. Observe UART transmission on `tx` and reception on `rx_data`.

---

## ✅ What I Learned

- How UART serial communication works (start bit, data bits, stop bit)
- How to implement transmitter and receiver logic in Verilog
- How to write and run a Verilog testbench to simulate communication

---

## 🛠️ Future Improvements

- Add a separate Baud Rate Generator module 
- Improve timing accuracy for real FPGA implementation
- Add parity bit support and configurable baud rate

---

## 🙋‍♂️ Author

**Prateek rajput** – Digital Design and Verilog HDL

---

