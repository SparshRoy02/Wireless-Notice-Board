## Wireless Notice Board 
A **Wireless Notice Board** system designed using **Arduino UNO**, **Bluetooth module (HC-05)**, and **16×2 LCD display**.

This system allows users to **send messages wirelessly from a mobile phone** and display them **instantly on an electronic notice board**.

### Abstract
Notice boards are widely used in **educational institutions, hospitals, offices, and public places**. Traditional **paper-based notice boards** consume time, effort, and paper.

This project introduces a **wireless electronic notice board** that uses **Bluetooth communication** to receive messages from a mobile device and display them on an LCD screen.

It is **paperless, cost-effective, and environment-friendly**, making it suitable for modern communication systems.

### Objectives
- To design a **wireless message display system**
- To reduce **paper usage and manual effort**
- To enable **real-time message updates**
- To improve **communication efficiency** in public places

### Components Used
| Component | Description |
|----------|-------------|
| Arduino UNO | Microcontroller (**ATmega328P**) |
| HC-05 Bluetooth Module | **Wireless serial communication** |
| LCD 16×2 | **Message display** |
| Jumper Wires | Circuit connections |
| Breadboard | Prototyping |
| Power Supply | USB / External |


### Circuit Connections
| Arduino Pin | Connected To | Description |
|------------|--------------|-------------|
| D2 | HC-05 TX | **Bluetooth data receive** |
| D3 | HC-05 RX | **Bluetooth data transmit** |
| D4–D9 | LCD Pins | **LCD data & control lines** |
| 5V | VCC | Power supply |
| GND | GND | Common ground |


### Arduino Code
The Arduino program:
- Reads **message from Bluetooth**
- Displays **scrolling text on LCD**
- Updates display **only when message changes**

### How to Run the Project
1. Install **Arduino IDE**
2. Connect **Arduino UNO** to PC
3. Upload the code 
4. Power the circuit
5. Pair mobile phone with **HC-05**
6. Send message using **Bluetooth terminal app**
7. Message appears on **LCD display** 

### Advantages
- **Wireless communication**
- **Paperless system**
- **Low cost**
- **Easy to operate**
- **Environment friendly**

### Future Scope
- **GSM / Wi-Fi based notice board**
- **Mobile application integration**
- **Multiple display panels**
- **Local language support**
- **Cloud-based message updates**

### Conclusion
The **Wireless Notice Board using Arduino and Bluetooth** presents an efficient and practical solution for **displaying messages wirelessly in real time**. By integrating **Arduino** with a **Bluetooth module** and **LCD display**, the system eliminates the need for manual updates and enables **instant communication**. The implementation of **automatic message updating** and **scrolling display** enhances readability and usability.

Overall, the project demonstrates the effective use of **embedded systems and serial communication** to solve real-world problems in a **cost-effective and scalable manner**. It is well-suited for applications in **educational institutions, offices, and public places**, and provides a strong foundation for future enhancements such as **IoT-based communication systems**.
