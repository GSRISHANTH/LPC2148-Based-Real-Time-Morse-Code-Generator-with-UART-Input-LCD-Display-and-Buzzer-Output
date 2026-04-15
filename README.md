LPC2148-Based-Real-Time-Morse-Code-Generator-with-UART-Input-LCD-Display-and-Buzzer-Output
Real-time embedded Morse Code Generator using LPC2148 microcontroller, designed and simulated in Proteus. Accepts UART (Virtual Terminal) input, converts alphanumeric characters into Morse code, displays output on a 16x2 LCD, and generates audio signals via a buzzer.
LPC2148 Morse Code Generator

Overview
This project is a real-time Morse Code Generator built using the LPC2148 microcontroller and simulated in Proteus. It takes input characters through a UART-based Virtual Terminal, converts them into Morse code, displays the output on a 16x2 LCD, and produces corresponding sound signals using a buzzer.

The project demonstrates key embedded system concepts such as UART communication, LCD interfacing, and timing-based signal generation.

 Features
- Accepts input via UART (Virtual Terminal)
- Converts A–Z and 0–9 into Morse code
- Displays Morse output on LCD
- Generates audio signals using buzzer
- Real-time processing
- Fully simulated in Proteus

 Technologies Used
- LPC2148 Microcontroller (ARM7)
- Embedded C
- Keil µVision
- Proteus Simulation

 Components Used
- LPC2148 Microcontroller
- 16x2 LCD (4-bit mode)
- Buzzer
- Virtual Terminal (UART)

Pin Configuration

| Component | LPC2148 Pin |
|----------|------------|
| LCD RS   | P1.16      |
| LCD EN   | P1.17      |
| LCD D4–D7 | P1.18–P1.21 |
| Buzzer   | P0.25      |


Working
1. User enters a character in the Virtual Terminal  
2. LPC2148 receives the input via UART  
3. The input is converted into Morse code  
4. Morse code is displayed on the LCD  
5. Buzzer generates sound:
   - Dot → Short beep  
   - Dash → Long beep  

 Simulation
The entire system is designed and tested in Proteus using a Virtual Terminal for input. The LCD shows Morse code output, and the buzzer simulates audio signals.

Applications
- Morse code communication systems  
- Embedded systems learning  
- Signal encoding systems  

 Future Improvements
- Add support for special characters  
- Implement Morse code decoding  
- Deploy on real hardware  
- Add speed control for signals

Author
G Srishanth


 License
This project is licensed under the MIT License.
