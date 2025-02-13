# 🔌 Embedded Systems Lab: ADC & DAC Configuration  

## 📌 Overview  
This project is part of an **Embedded Systems Lab** 🛠️ where we configure an **Analog-to-Digital Converter (ADC) 🎛️** and **Digital-to-Analog Converter (DAC) 🔄** using a microcontroller board. The setup includes adjusting a **potentiometer 🎚️** and modifying a **jumper (bygel) ⚡** to enable proper signal conversion.  

## 🛠️ Hardware Setup  
1️⃣ **Potentiometer Placement**:  
   - Insert the **potentiometer 🎚️** into the **header next to the headphone jack 🎧**.  

2️⃣ **ADC Jumper Adjustment**:  
   - Lift the **ADC-labeled jumper 🔌** and reposition it so that it connects to only **one pin** (as shown in the image).  

## 🎯 Functionality  
✅ The **potentiometer** adjusts the **input signal** to the **ADC**.  
✅ The **ADC** reads the **analog voltage** and converts it into a **digital signal**.  
✅ The **DAC** outputs the processed **digital signal** back as an **analog voltage**.  

## 💻 Software Implementation  
🔹 The **microcontroller** reads ADC values **periodically**.  
🔹 The values are processed and can be **sent to peripherals** (e.g., LED matrix 💡, audio output 🔊).  
🔹 The **DAC** converts the **digital signal** back into an **analog output**.  

## 🚀 Usage  
📥 **Upload the firmware** to the microcontroller.  
🎚️ **Rotate the potentiometer** and observe changes in output.  
📊 **Analyze signal processing** using an oscilloscope or serial monitor.  

---

✨ **Contributors**  
👤 Tousif Dewan  

📜 **License**  
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
