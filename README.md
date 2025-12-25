# Binary Frequency Shift Keying (BFSK) Modulation and Demodulation Kit

A hardware-based implementation of **Binary Frequency Shift Keying (BFSK)** that demonstrates the **generation, transmission, and recovery of digital data** using two distinct carrier frequencies. This project is designed as an **educational digital communication kit** to visualize BFSK modulation and demodulation in real time.

---

## 🎯 Key Features

* Hardware realization of **BFSK modulation & demodulation**
* Two carrier frequencies representing binary `0` and `1`
* **PLL-based demodulation** for accurate frequency detection
* Clear visualization of:
  * Input binary signal
  * Carrier waves
  * BFSK modulated signal
  * Demodulated output
* Suitable for **lab experiments and demonstrations**

---

## 🛠️ Components Used

* IC **741** – Operational Amplifier
* **BC547** (NPN) & **BC557** (PNP) Transistors
* **NE565 PLL IC** – Frequency detection and demodulation
* Resistors & Capacitors
* Potentiometer (frequency tuning)
* Signal generators & CRO (for testing and visualization)
* PCB / Veroboard

---

## 🧠 Working Principle

1. **Carrier Generation**

   * Two sine wave generators produce different frequencies:

     * One for binary `1`
     * One for binary `0`

2. **Binary Input Signal**

   * A square wave represents digital data.

3. **BFSK Modulation**

   * The binary input controls which carrier frequency is transmitted.
   * Frequency switching forms the BFSK waveform.

4. **Demodulation**

   * The received BFSK signal is fed into a **PLL (NE565)**.
   * The PLL locks onto the input frequency and converts it into a voltage.
   * A comparator regenerates the original binary data.

---

## 📊 Observed Outputs

* Square wave (input binary data)
* Two carrier sine waves (different frequencies)
* BFSK modulated signal
* Demodulated digital output

All signals are verified using an oscilloscope.

---

## 📁 Files Included

* `BFSK-Simulation.pdsprj` – Complete BFSK modulator & demodulator schematic
* `Kit-Hardware.jpg` – Hardware kit setup
* `Report.pdf` – Detailed project report with theory and results

---

## 💡 Applications

* Digital communication systems
* Low-speed data modems
* Telemetry and remote data transmission
* RFID and satellite communication
* Educational communication labs

---

## 🚀 Future Improvements

* Implementation using **microcontroller / DSP**
* Comparison with **ASK, PSK, and FSK**
* Noise performance analysis (BER vs SNR)
* Software simulation using MATLAB or Simulink

