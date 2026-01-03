# BikeToKey

[日本語](README.md) | English

A universal tool to convert fitness bike exercise data into keyboard input

## 📖 What is this?

BikeToKey is a Node-RED project that automatically generates keyboard input based on the pedaling speed of a BLE fitness bike.

Simply pedal the bike to control games and applications on your computer. It works with any software that accepts keyboard input.

### Features

- 🚴 Detects bike RPM and converts it to key input
- 🎮 Works with any app that accepts keyboard input
- 🔧 Freely customizable key mappings and speed settings
- 📡 Wireless via Bluetooth connection

## 🎯 Use Cases

### Minecraft Education Edition (Default Configuration)

This project is configured for Minecraft Education Edition by default.

**Behavior:**
- Fast pedaling (>55rpm): Sprint (W + Ctrl keys)
- Normal pedaling (1-55rpm): Walk forward (W key)
- Stopped (<1rpm): Stop (release keys)

**How to use:**
1. Turn on the bike
2. Launch Minecraft and enter a world
3. Click [Start] button in Node-RED
4. Pedal the bike

## 🛠️ Requirements

### Hardware
- FTMS-compatible BLE fitness bike
- PC with Bluetooth 4.0 or higher

### Software
- Node.js
- Node-RED

## 📚 Technical Details

- **FTMS (Fitness Machine Service)**: Bluetooth standard protocol (UUID: 1826)
- **Indoor Bike Data**: Retrieves data like RPM (UUID: 2ad2)
- **RobotJS**: Keyboard input simulation

Available data: Speed, RPM, Distance, Power, Calories, Elapsed Time

## 🧠 Moving to Focus

Some children with ADHD traits can focus better when moving their bodies rather than sitting still.

Research in the United States has shown that physical movement (fidgeting) enhances concentration in children with ADHD ([NPR Education](https://www.npr.org/sections/ed/2015/05/14/404959284/fidgeting-may-help-concentration-for-students-with-adhd), [UC Davis](https://health.ucdavis.edu/news/headlines/does-fidgeting-help-people-with-adhd-focus-/2024/10)). Movement awakens the brain and increases blood flow to the prefrontal cortex.

BikeToKey leverages this "focus while moving" characteristic, enabling natural exercise while engaging in digital activities.

## 📄 License

MIT License

## 👤 Author

mming
