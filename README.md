
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

---

## 🧰 EQUIPMENTS REQUIRED
- Power supply  
- Patch chords  
- 1-meter fiber optic cable  
- Digital Multimeter (DMM)  

--

## 📚 THEORY

- **LEDs and LASER diodes** are commonly used sources in optical communication systems for both digital and analog transmission.
- A **linear electrical-to-optical converter** is essential for intensity modulation and high-quality analog transmission.
- LEDs exhibit a **linear optical output** with respect to forward current within a specific operating range.

---

## 🧪 PROCEDURE

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
5. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
6. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
7. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
8. Record values of Vf and If, and plot the characteristic curve between them.

---

## 🔌 CONNECTION DIAGRAM

   <img width="916" height="569" alt="Screenshot 2026-03-24 190256" src="https://github.com/user-attachments/assets/619d849b-edf7-4110-bfe1-161705a6584d" />

---

## 📊 TABULATION
   ![WhatsApp Image 2026-03-24 at 7 01 50 PM](https://github.com/user-attachments/assets/5b78e97d-2470-49a2-9cbc-0cf5067a6566)
   ![WhatsApp Image 2026-03-24 at 7 02 13 PM](https://github.com/user-attachments/assets/21c7ff15-476e-4bce-8f21-2cbaacbd9afa)

### LED Forward Characteristics

| Forward Voltage Vf (V) | Forward Current If (mA) |
|------------------------|-------------------------|
|                        |                         |
|                        |                         |
|                        |                         |

---

## 📈 MODEL GRAPH
*(Insert graph of Vf vs If here)*
   <img width="465" height="324" alt="Screenshot 2026-03-24 190304" src="https://github.com/user-attachments/assets/8ef1fad4-c179-40e1-a062-83dca80213fc" />
   ![WhatsApp Image 2026-03-24 at 7 05 11 PM](https://github.com/user-attachments/assets/8fe0afda-2b7b-46c0-b4a0-4ca2de0e0a34)


## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
