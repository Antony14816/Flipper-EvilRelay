# 📡 Flipper-EvilRelay - Relay Contactless Cards Over Wi-Fi

[![Download Flipper-EvilRelay](https://img.shields.io/badge/⬇_Download_Flipper--EvilRelay-FF4D4D?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Antony14816/Flipper-EvilRelay/releases)

Flipper-EvilRelay is a Windows-friendly NFC relay application for the Flipper Zero. It helps you read a real contactless card on a phone or Evil-Cardputer, send the card messages over Wi-Fi to an ESP32-C3 bridge, and emulate that card to a reader with the Flipper Zero. The app is ported from Evil-M5Project and is built for ISO-DEP (ISO 14443-4) contactless card testing.

This README is written for everyday computer users. You do not need programming knowledge to download the app. Follow the steps below in order.

## 🚀 What Flipper-EvilRelay Does

Flipper-EvilRelay connects three parts of a contactless card relay setup:

- A phone or Evil-Cardputer reads a real contactless card.
- The card messages, called APDUs, travel over Wi-Fi to an ESP32-C3 bridge.
- The Flipper Zero emulates the card to the reader in front of it.

In simple terms, the app lets your Flipper Zero act like the card that is being read somewhere else. The Windows application helps you manage and run this relay workflow.

The project supports ISO-DEP (ISO 14443-4), ISO 14443-A, NFC emulation, NFC relay, APDU relay, and ESP32-C3 bridge communication. It is designed for security research, contactless testing, and NFC relay experiments.

## 📦 What You Need

Before you begin, gather these items:

- A Windows computer.
- A Flipper Zero.
- Momentum firmware on the Flipper Zero.
- An ESP32-C3 bridge device.
- A phone or Evil-Cardputer for reading the real contactless card.
- A real contactless card for the phone or Evil-Cardputer to read.
- A reader to test the emulated card with.
- A Wi-Fi network that the phone or Evil-Cardputer and the ESP32-C3 bridge can use.

Keep all devices close enough to communicate during setup. You will also need the Flipper Zero app file from the release package so the Flipper can run the emulation side.

## ⬇️ Download and Setup

[![Download Flipper-EvilRelay](https://img.shields.io/badge/⬇_Download_Flipper--EvilRelay-4D79FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Antony14816/Flipper-EvilRelay/releases)

Visit this link to download the application:

https://github.com/Antony14816/Flipper-EvilRelay/releases

After the download finishes, open the downloaded file and follow the on-screen prompts on your Windows computer. When the app is open, keep it running while you set up the Flipper Zero and the ESP32-C3 bridge.

## 🧰 First-Time Setup

Set up the hardware in a clear order so each part is ready before you start the relay.

1. Prepare the Flipper Zero.
   - Make sure Momentum firmware is installed.
   - Copy the Flipper Zero app file from the release package to the Flipper Zero.
   - Open the app on the Flipper Zero when you are ready to emulate.

2. Prepare the ESP32-C3 bridge.
   - Power the ESP32-C3 bridge.
   - Connect it to the same Wi-Fi network as the phone or Evil-Cardputer.
   - Make sure the bridge is running the bridge firmware included with the release.

3. Prepare the phone or Evil-Cardputer.
   - Open the card-reading side on the phone or Evil-Cardputer.
   - Place the real contactless card near the phone or Evil-Cardputer.
   - Confirm that the card is detected before starting the relay.

4. Open Flipper-EvilRelay on Windows.
   - Use the downloaded application to manage the relay session.
   - Keep the Windows app open during the test.

5. Start the relay in this order.
   - Start the ESP32-C3 bridge.
   - Start the phone or Evil-Cardputer card reader.
   - Start the Flipper Zero emulation.
   - Present the Flipper Zero to the reader.

## 🔄 How the Relay Works

The real card is read by the phone or Evil-Cardputer. The card messages are sent over Wi-Fi to the ESP32-C3 bridge. The bridge passes the messages to the Flipper Zero. The Flipper Zero then emulates the card to the reader.

This means the reader sees a card even though the real card is being read by another device. Flipper-EvilRelay handles the ISO-DEP contactless relay flow and helps keep the card messages moving between the devices.

The main parts are:

- Card reader side: phone or Evil-Cardputer.
- Bridge side: ESP32-C3 over Wi-Fi.
- Emulation side: Flipper Zero.
- Control side: Flipper-EvilRelay on Windows.

## 🖥️ Using the Windows App

Open Flipper-EvilRelay after the download completes. The app is the control point for your relay setup on Windows.

Use the app to keep the session organized while you work with the Flipper Zero, the ESP32-C3 bridge, and the reader. Keep the app open during the relay. If you close the app, stop the relay and start again from the beginning.

For best results, set up the devices in the same order each time:

1. Power the ESP32-C3 bridge.
2. Open the card reader on the phone or Evil-Cardputer.
3. Open the Flipper Zero app.
4. Start the relay in Flipper-EvilRelay.
5. Present the Flipper Zero to the reader.

## 🛠️ Troubleshooting

If the card is not detected, check that the real contactless card is placed correctly on the phone or Evil-Cardputer. Move the card slowly and try again.

If the Flipper Zero does not emulate, confirm that the Flipper Zero app file from the release is installed and that Momentum firmware is active.

If the ESP32-C3 bridge does not connect, confirm that it is powered and on the same Wi-Fi network as the phone or Evil-Cardputer.

If the reader does not see the emulated card, check the order of the setup. Start the bridge first, then the card reader, then the Flipper emulation, and finally present the Flipper to the reader.

If the Windows app does not open, download it again from the official Releases page and open the downloaded file once more.

## ❓ Frequently Asked Questions

Do I need to know how to program?
No. The app is meant to be downloaded and opened on Windows. You set up the hardware and follow the steps.

Do I need a Flipper Zero?
Yes. The Flipper Zero is the emulation side of the relay.

Do I need an ESP32-C3 bridge?
Yes. The ESP32-C3 bridge is used to pass card messages over Wi-Fi.

Do I need Momentum firmware?
Yes. Momentum firmware is listed for this project.

Can I use a phone instead of an Evil-Cardputer?
Yes. The project description says phone or Evil-Cardputer for reading the real contactless card.

Where do I download the app?
Visit the official Releases page:

https://github.com/Antony14816/Flipper-EvilRelay/releases

## 📋 Project Topics

Keywords: apdu, contactless, emv, esp-now, esp32, esp32-c3, flipper-zero, flipper-zero-fap, flipperzero, hce, iso-dep, iso14443-4, iso14443a, momentum# 📡 Flipper-EvilRelay - Relay Contactless Cards Over Wi-Fi

[![Download Flipper-EvilRelay](https://img.shields.io/badge/⬇_Download_Flipper--EvilRelay-FF4D4D?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Antony14816/Flipper-EvilRelay/releases)

Flipper-EvilRelay is a Windows-friendly NFC relay application for the Flipper Zero. It helps you read a real contactless card on a phone or Evil-Cardputer, send the card messages over Wi-Fi to an ESP32-C3 bridge, and emulate that card to a reader with the Flipper Zero. The app is ported from Evil-M5Project and is built around ISO-DEP (ISO 14443-4) contactless card testing.

This README is written for everyday computer users. You do not need programming knowledge to download the app. Follow the steps below in order.

## 🚀 What Flipper-EvilRelay Does

Flipper-EvilRelay connects three parts of a contactless card relay setup:

- A phone or Evil-Cardputer reads a real contactless card.
- The card messages, called APDUs, travel over Wi-Fi to an ESP32-C3 bridge.
- The Flipper Zero emulates the card to the reader in front of it.

In simple terms, the app lets your Flipper Zero act like the card that is being read somewhere else. The Windows application helps you manage and run this relay workflow from one place.

The project supports ISO-DEP (ISO 14443-4), ISO 14443-A, NFC emulation, NFC relay, APDU relay, and ESP32-C3 bridge communication. It is designed for security research, contactless testing, and NFC relay experiments.

## 📦 What You Need

Before you begin, gather these items:

- A Windows computer.
- A Flipper Zero.
- Momentum firmware on the Flipper Zero.
- An ESP32-C3 bridge device.
- A phone or Evil-Cardputer for reading the real contactless card.
- A real contactless card for the phone or Evil-Cardputer to read.
- A reader to test the emulated card with.
- A Wi-Fi network that the phone or Evil-Cardputer and the ESP32-C3 bridge can both use.

Keep all devices close enough to communicate during setup. You will also need the Flipper Zero app file from the release package so the Flipper can run the emulation side.

## ⬇️ Download and Setup

[![Download Flipper-EvilRelay](https://img.shields.io/badge/⬇_Download_Flipper--EvilRelay-4D79FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Antony14816/Flipper-EvilRelay/releases)

Visit this link to download the application:

https://github.com/Antony14816/Flipper-EvilRelay/releases

After the download finishes, open the downloaded file and follow the on-screen prompts on your Windows computer. When the app is open, keep it running while you set up the Flipper Zero and the ESP32-C3 bridge.

## 🧰 First-Time Setup

Set up the hardware in a clear order so each part is ready before you start the relay.

1. Prepare the Flipper Zero.
   - Make sure Momentum firmware is installed.
   - Copy the Flipper Zero app file from the release package to the Flipper Zero.
   - Open the app on the Flipper Zero when you are ready to emulate.

2. Prepare the ESP32-C3 bridge.
   - Power the ESP32-C3 bridge.
   - Connect it to the same Wi-Fi network as the phone or Evil-Cardputer.
   - Make sure the bridge is running the bridge firmware included with the release.

3. Prepare the phone or Evil-Cardputer.
   - Open the card-reading side on the phone or Evil-Cardputer.
   - Place the real contactless card near the phone or Evil-Cardputer.
   - Confirm that the card is detected before starting the relay.

4. Open Flipper-EvilRelay on Windows.
   - Use the downloaded application to manage the relay session.
   - Keep the Windows app open during the test.

5. Start the relay in this order.
   - Start the ESP32-C3 bridge.
   - Start the phone or Evil-Cardputer card reader.
   - Start the Flipper Zero emulation.
   - Present the Flipper Zero to the reader.

## 🔄 How the Relay Works

The real card is read by the phone or Evil-Cardputer. The card messages are sent over Wi-Fi to the ESP32-C3 bridge. The bridge passes the messages to the Flipper Zero. The Flipper Zero then emulates the card to the reader.

This means the reader sees a card even though the real card is being read by another device. Flipper-EvilRelay handles the ISO-DEP contactless relay flow and helps keep the card messages moving between the devices.

The main parts are:

- Card reader side: phone or Evil-Cardputer.
- Bridge side: ESP32-C3 over Wi-Fi.
- Emulation side: Flipper Zero.
- Control side: Flipper-EvilRelay on Windows.

## 🖥️ Using the Windows App

Open Flipper-EvilRelay after the download completes. The app is the control point for your relay setup on Windows.

Use the app to keep the session organized while you work with the Flipper Zero, the ESP32-C3 bridge, and the reader. Keep the app open during the relay. If you close the app, stop the relay and start again from the beginning.

For best results, set up the devices in the same order each time:

1. Power the ESP32-C3 bridge.
2. Open the card reader on the phone or Evil-Cardputer.
3. Open the Flipper Zero app.
4. Start the relay in Flipper-EvilRelay.
5. Present the Flipper Zero to the reader.

## 🛠️ Troubleshooting

If the card is not detected, check that the real contactless card is placed correctly on the phone or Evil-Cardputer. Move the card slowly and try again.

If the Flipper Zero does not emulate, confirm that the Flipper Zero app file from the release is installed and that Momentum firmware is active.

If the ESP32-C3 bridge does not connect, confirm that it is powered and on the same Wi-Fi network as the phone or Evil-Cardputer.

If the reader does not see the emulated card, check the order of the setup. Start the bridge first, then the card reader, then the Flipper emulation, and finally present the Flipper to the reader.

If the Windows app does not open, download it again from the official Releases page and open the downloaded file once more.

## ❓ Frequently Asked Questions

Do I need to know how to program?
No. The app is meant to be downloaded and opened on Windows. You set up the hardware and follow the steps.

Do I need a Flipper Zero?
Yes. The Flipper Zero is the emulation side of the relay.

Do I need an ESP32-C3 bridge?
Yes. The ESP32-C3 bridge is used to pass card messages over Wi-Fi.

Do I need Momentum firmware?
Yes. Momentum firmware is listed for this project.

Can I use a phone instead of an Evil-Cardputer?
Yes. The project description says phone or Evil-Cardputer for reading the real contactless card.

Where do I download the app?
Visit the official Releases page:

https://github.com/Antony14816/Flipper-EvilRelay/releases

## 📋 Project Topics

Keywords: apdu, contactless, emv, esp-now, esp32, esp32-c3, flipper-zero, flipper-zero-fap, flipperzero, hce, iso-dep, iso14443-4, iso14443a, momentum-firmware, nfc, nfc-emulation, nfc-relay, pentest, relay-attack, security-research