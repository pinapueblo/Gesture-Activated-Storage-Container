# 🤖 Gesture-Activated Smart Storage Container

A low-cost, contactless storage container prototype built with an Arduino Uno, ultrasonic sensor, and servo motor. When a hand is detected near the lid, the servo motor opens the trash can using a clever DIY linkage made from floss and cardboard.

---

## 🛠️ Features

- 🖐️ Detects nearby hand gestures using an HC-SR04 ultrasonic sensor
- 🔄 Automatically opens lid via servo motor
- 📦 Built entirely from everyday materials (cardboard + floss)
- 💡 Runs on Arduino Uno with minimal components
- 🧪 Great for prototyping smart home or hygiene-focused devices

---

## 🔌 Hardware Used

| Component           | Description                  |
|--------------------|------------------------------|
| Arduino Uno         | Microcontroller              |
| HC-SR04             | Ultrasonic distance sensor   |
| SG90 Servo Motor    | Used to open lid             |
| Mini breadboard     | For easy wiring              |
| Tooth floss & cardboard | For mechanical linkage |
| Jumper wires        | For connections              |

---

## 🧠 How It Works

1. The ultrasonic sensor continuously checks for an object (like a hand) within a set distance.
2. When an object is detected (e.g. within 20 cm), it triggers the servo motor.
3. The servo pulls on a piece of tooth floss connected to the lid, opening the trash can.
4. After a short delay, the servo returns to its original position, closing the lid.
