# Bulls and Cows Game on FPGA

A hardware implementation of the classic **Bulls and Cows** game, designed to run on an FPGA board (Nexys A7).

## 🛠️ Technologies

- **HDL:** Verilog
- **Platform:** Nexys A7 FPGA
- **Tools:** Vivado Design Suite

## 🎮 How It Works

- The player guesses a 4-digit secret number.
- For each guess, the system returns:
  - 🐂 **Bulls:** Correct digit in the correct position.
  - 🐄 **Cows:** Correct digit in the wrong position.
- The game continues until the player finds the correct number.

## 🚀 Features

- Fully synthesizable Verilog design.
- Real-time input handling through FPGA buttons/switches.
- Output via 7-segment displays and LEDs.

## 📦 Project Structure

- `/src`: HDL source files
- `/constraints`: FPGA constraint files (XDC)
- `/docs`: Documentation and block diagrams

## ⚙️ Setup

1. Clone the repo.
2. Open the project with **Vivado**.
3. Generate the bitstream.
4. Upload it to the **Nexys A7** FPGA.
5. Play!

## 💡 Notes

- This is a pure hardware implementation—no software involved.
- Designed for educational purposes to demonstrate digital design and finite state machines.

## 🤝 Contributors

- [Seu Nome Aqui]

## 📜 License

MIT License.
