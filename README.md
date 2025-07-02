# LED Voltmeter using IC 741

This project presents an LED-based voltmeter built with **741 operational amplifiers** used as voltage comparators. The circuit visually displays increasing voltage levels by lighting up LEDs sequentially. A voltage divider network provides reference thresholds, while a potentiometer adjusts the input voltage. This is a simple and effective analog project to understand comparator-based voltage indication.

Developed as a course project for **ECT 301 – Linear Integrated Circuits** at **NSS College of Engineering, Palakkad** (APJ Abdul Kalam Technological University).

---

## ⚙️ How It Works

- A potentiometer adjusts the input voltage fed to 741 ICs.
- A resistor voltage divider sets threshold voltages.
- Each op-amp compares the input voltage with its threshold.
- When the input exceeds the threshold, it switches on a specific pair of LEDs.
- The LEDs light up in sequence as the voltage increases.

---

## 🔩 Components Used

- 4 × 741 Op-Amp ICs (U1–U4)
- 100kΩ Potentiometer (RV1)
- Resistors: R1–R9 (voltage divider + current limiting)
- LEDs: D1–D8
- Power Supplies: 13V input (B1), 15V reference (B2)

---

## 📄 Project Report

📥 [Download Full Report (PDF)](1.docs/voltmeter_project_report.pdf)

---

## 👨‍💻 Contributors

- Sariga R 
- Sharan Krishnan M 
- Suhair K 
  
 NSS College of Engineering,palakkad
---

## 🛠️ Tools Used

- Breadboard and discrete components
- Optional: Proteus (for testing/visual output)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
