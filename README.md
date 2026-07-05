🔐 ESP32 Smart Door Lock System

An IoT-based Smart Door Lock System developed using **ESP32**, **4x4 Matrix Keypad**, **16x2 I2C LCD**, and a **Servo Motor**. The system allows users to unlock the door by entering the correct password through the keypad. The LCD displays system status and the servo motor acts as the door lock mechanism.

---

## 🚀 Features

- 🔑 Password-based door unlocking
- 📟 4x4 Matrix Keypad for password entry
- 📺 16x2 I2C LCD for user messages
- 🔒 Servo Motor for door lock/unlock
- ❌ Incorrect password detection
- 🔄 Automatic lock after unlocking

---

## 🛠️ Components Used

- ESP32 Development Board
- 4x4 Matrix Keypad
- 16x2 I2C LCD Display
- Servo Motor (SG90)
- Jumper Wires

---

## 💻 Software Used

- Arduino IDE
- Wokwi Simulator

---

## 📂 Project Structure

```
ESP32-Smart-Door-Lock/
│── code.ino
│── README.md
│── circuit.png
```

---

## ▶️ How It Works

1. Power on the ESP32.
2. Enter the password using the keypad.
3. The LCD prompts for password entry.
4. If the password is correct:
   - Servo rotates to unlock the door.
   - LCD displays **Access Granted**.
5. If the password is incorrect:
   - LCD displays **Access Denied**.
   - Door remains locked.

---

## 🔗 Wokwi Simulation

👉 **Simulation Link:**  
https://wokwi.com/projects/468694252587365377

---

## 📜 License

This project is for educational and learning purposes.

---

## 👨‍💻 Author

** Suru Vishal**

Electronics and Communication Engineering (ECE)
