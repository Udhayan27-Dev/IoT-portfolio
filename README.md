# IoT Portfolio Website · Udhayan

An end-to-end documentation portfolio showcasing bare-metal **Embedded Rust** (`no_std`) and **ESP32-C3** (RISC-V) Internet of Things projects, cloud integrations, and automation systems.

## Live Website
- **GitHub Pages:** [https://udhayan27-dev.github.io/IoT-portfolio/](https://udhayan27-dev.github.io/IoT-portfolio/)

---

## Projects Featured

All projects are consolidated in the main repository: [**https://github.com/Udhayan27-Dev/IoT_Task1**](https://github.com/Udhayan27-Dev/IoT_Task1)

1. **[Task 1: ESP32-C3 Web Server & HTML LED Control](task-1.html)**
   - *Tech:* Embedded Rust (`no_std`), `esp-hal`, `esp-radio`, `embassy-net`, Port 80 HTTP server
   - *Code:* [https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task1-web-control](https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task1-web-control)

2. **[Task 2: Adafruit IO Dashboard & Async MQTT Relay Control](task-2.html)**
   - *Tech:* Custom async MQTT 3.1.1 packet parser, `critical-section` Mutex, Active-LOW 230V AC Relay
   - *Code:* [https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task2-adafruit-mqtt](https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task2-adafruit-mqtt)

3. **[Task 3: Voice Assistant & Cloud Automation](task-3.html)**
   - *Tech:* Google Assistant + IFTTT Webhooks + Adafruit IO MQTT with sub-second voice actuation
   - *Code:* [https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task3-voice-automation](https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task3-voice-automation)

4. **[Task 4: Firebase IoT Monitoring Dashboard](task-4.html)**
   - *Tech:* Real-time DHT11 & LDR sensor streaming, Firebase Realtime Database, Firebase Authentication
   - *Code:* [https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task4-firebase-dashboard](https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task4-firebase-dashboard)

5. **[Task 5: Firebase Logging, Automation & Data Export](task-5.html)**
   - *Tech:* Autonomous ambient LDR threshold switching, timestamped RTDB audit logs, history charts, CSV export
   - *Code:* [https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task5-logging-automation](https://github.com/Udhayan27-Dev/IoT_Task1/tree/main/task5-logging-automation)

---

## Repository Structure

```
├── index.html            # Portfolio overview and hardware rig summary
├── task-1.html           # Task 1 documentation with embedded demo video & photos
├── task-2.html           # Task 2 documentation with circuit diagrams & photos
├── task-3.html           # Task 3 documentation with real voice video demo
├── task-4.html           # Task 4 documentation with Firebase dashboard screenshots
├── task-5.html           # Task 5 documentation with history charts & CSV generator
├── assets/
│   ├── style.css         # Clean, responsive portfolio stylesheet
│   └── img/              # UI screenshots and architecture assets
└── evidence/             # Real laboratory photos and MP4 video demonstrations
```

---

## Enabling GitHub Pages

1. Navigate to your repository settings: **Settings &gt; Pages**.
2. Under **Build and deployment &gt; Branch**, select `main` and root `/`.
3. Click **Save**. GitHub Pages will deploy the live portfolio at `https://udhayan27-dev.github.io/IoT-portfolio/`.
