# ESP32 Blinking LED 💡  

This is a simple **ESP32 LED blinking** project that demonstrates basic **GPIO control** using Arduino IDE. The LED connected to **GPIO 2** (or the built-in LED on some ESP32 boards) will blink **on and off every 500ms**.  

## ✨ Features  
- ⚡ **Basic LED Blinking** – A great starting point for ESP32 beginners.  
- 🔌 **Uses GPIO 2** – Works with most ESP32 dev boards.  
- 🕹️ **Easily Adjustable** – Change blink timing by modifying `delay()` values.  

---

## 🛠️ Hardware Requirements  
- **ESP32 Dev Board**  
- **LED + Resistor (Optional)** (if using an external LED)  
- **USB cable & computer** (to upload code)  

---
## 📜 Code Overview:

void setup() {
  // put your setup code here, to run once:
pinMode(2,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(2,HIGH);
delay(500);

digitalWrite(2,LOW);

delay(500);
}