# UART Communication in Verilog

This is a simple UART (Universal Asynchronous Receiver and Transmitter) project written in Verilog. It includes:
- A transmitter module
- A receiver module
- A testbench to simulate the communication

This project is based on the paper:  
**"Design and Implementation of UART Serial Communication on FPGA Using Verilog"**  
Link: [IJEAT Paper](https://www.ijeat.org/wp-content/uploads/papers/v9i5/E1135069520.pdf)

---

## 📂 Files

- `transmitter.v`: Sends 8-bit data serially with start and stop bits.
- `receiver.v`: Receives the serial data and converts it back to 8-bit format.
- `serial_communication_test.v`: Testbench that connects transmitter and receiver and verifies the communication.

---

## ⚙️ UART Basics

- Baud Rate: 9600 bps
- Data Bits: 8
- Start Bit: 1
- Stop Bit: 1
- No Parity

UART is used to send data one bit at a time over a single wire (TX), and receive on another wire (RX).

---

## ▶️ How to Simulate

1. Open ModelSim or Vivado.
2. Add all `.v` files to your project.
3. Set `serial_communication_test.v` as the top module.
4. Run the simulation.
5. You’ll see that the data sent by the transmitter is received correctly by the receiver.

---

## 📷 Waveform Example



---

## ✅ What I Learned

- How UART works
- How to write simple Verilog modules
- How to simulate a digital design with a testbench

---

## 🔧 Future Work

- Make the baud rate configurable
- Add a real FPGA board implementation
- Use FIFO for better data handling

---

## 🙋‍♂️ Author

**Prateek Rajput** – Beginner in Digital Design and Verilog.

---

