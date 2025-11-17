
### ✅ **Arduino Starter Kit Numbered Checklist**

---

# 🔌core boards & interfaces

### 🧠 1. Core Board (ສ່ວນຫົວໃຈ)
<img src="Pasted image 20251028222355.png" width="400">



**Core Boards & Interfaces ຂອງ Arduino Uno Board** ແມ່ນສ່ວນທີ່ເປັນ “ຫົວໃຈ” ແລະ “ຈຸດເຊື່ອມຕໍ່” ທີ່ໃຫ້ບອດສາມາດຮັບຂໍ້ມູນ, ປະມວນຜົນ, ແລະສົ່ງຂໍ້ມູນອອກໄດ້.  
ສາມາດແບ່ງອອກໄດ້ເປັນ 2 ພາກໃຫຍ່ໆ: **(1) Core Board** ແລະ **(2) Interfaces.**

ແມ່ນສ່ວນທີ່ໃຊ້ໃນການປະມວນຜົນແລະຄວບຄຸມການເຮັດວຽກທັງໝົດ:

#### 🔹 (1.1) Microcontroller (ATmega328P)

- ແມ່ນ “ສະຫມອງ” ຂອງບອດ Arduino Uno.
    
- ທຳໜ້າທີ່ປະມວນຜົນຄຳສັ່ງຈາກຊອບແວ (sketch/program).
    
- ມີສ່ວນສຳຄັນພາຍໃນເຊັ່ນ:
    
    - **Flash Memory (32 KB)** — ໃຊ້ເກັບໂປຣແກຣມ
        
    - **SRAM (2 KB)** — ໃຊ້ໃນການປະມວນຜົນຊົ່ວຄາວ
        
    - **EEPROM (1 KB)** — ບັນທຶກຂໍ້ມູນແບບຖາວອນ
        
    - **Clock Speed 16 MHz** — ເຮັດໃຫ້ບອດປະມວນຜົນໄດ້ໄວ
        

#### 🔹 (1.2) Voltage Regulator

- ຮັບໄຟຈາກ USB ຫຼື Adapter (7–12V)
    
- ປັບໃຫ້ເຫມາະສົມກັບບອດ (5V ແລະ 3.3V)
    

#### 🔹 (1.3) Crystal Oscillator

- ຄວບຄຸມຄວາມໄວໃນການປະມວນຜົນ (16 MHz)
    
- ເຮັດໃຫ້ໂປຣແກຣມເຮັດວຽກຢ່າງຖືກຕ້ອງຕາມເວລາ
    

#### 🔹 (1.4) Power Supply Section

- ສາມາດໃຊ້ໄຟຈາກ:
    
    - USB (5V)
        
    - Adapter (7–12V)
        
    - ແລະມີ pin 3.3V, 5V, GND ໃຫ້ໃຊ້
        

---

### ⚙️ 2. Interfaces (ສ່ວນເຊື່ອມຕໍ່)

ແມ່ນສ່ວນທີ່ໃຫ້ບອດສາມາດຕິດຕໍ່ກັບອຸປະກອນອື່ນໆໄດ້:

#### 🔸 (2.1) Digital I/O Pins (0–13)

- ມີ 14 pins
    
- ໃຊ້ໄດ້ທັງ input ແລະ output
    
- pins 0 ແລະ 1 ສຳລັບ serial communication (RX, TX)
    

#### 🔸 (2.2) Analog Input Pins (A0–A5)

- ຮັບຄ່າຈາກອຸປະກອນຈັບສັນຍານ analog (ເຊັ່ນ sensor)
    
- ປ່ຽນຄ່າ analog → digital (ADC 10-bit)
    

#### 🔸 (2.3) Power Pins

- 3.3V, 5V — ຈ່າຍໄຟໃຫ້ sensor / module
    
- GND — ຕໍ່ດິນ
    
- Vin — ຮັບໄຟຈາກ Adapter
    

#### 🔸 (2.4) USB Interface

- ໃຊ້ເຊື່ອມກັບຄອມພິວເຕີ ເພື່ອ upload code ແລະສົ່ງຂໍ້ມູນ Serial Monitor
    
- ຜ່ານຊິບ **ATmega16U2** (ແປ USB ↔ Serial)
    

#### 🔸 (2.5) Reset Button

- ໃຊ້ reset ໂປຣແກຣມໃຫ້ເລີ່ມໃໝ່
    

#### 🔸 (2.6) ICSP Header

- ສຳລັບໂປຣແກຣມເຂົ້າ microcontroller ໂດຍກົງ (In-Circuit Serial Programming)
    

#### 🔸 (2.7) TX / RX LEDs

- TX — ເມື່ອສົ່ງຂໍ້ມູນ
    
- RX — ເມື່ອຮັບຂໍ້ມູນ
    
- ຊ່ວຍໃຫ້ເຫັນການສື່ສານຂອງ serial
    

---

### 🔍 ສະຫຼຸບສັ້ນໆ:

| ສ່ວນ               | ໜ້າທີ່                 |
| ------------------ | ---------------------- |
| ATmega328P         | ປະມວນຜົນ (CPU)         |
| ATmega16U2         | ແປ USB ↔ Serial        |
| Crystal Oscillator | ຄວບຄຸມເວລາ             |
| Voltage Regulator  | ຄວບຄຸມໄຟຟ້າ            |
| Digital Pins       | ຮັບ/ສົ່ງສັນຍານ Digital |
| Analog Pins        | ຮັບຄ່າ Analog          |
| Power Pins         | ຈ່າຍໄຟ                 |
| USB Port           | ໂອນຂໍ້ມູນກັບຄອມ        |
| Reset Button       | ຣີເຊັດບອດ              |

ຮູບອຸປະກອນແບບ Schematic Diagram :

<img src="Pasted image 20251028222836.png" width="700">

ຕົວຢ່າງການນຳໃຊ້: Blink LED: ໃຊ້ຂາ Digital Output ເພື່ອຄວບຄຸມການເປີດ-ປິດໄຟ LED ເປັນຈັງຫວະ

2.Breadboards
<img src="Pasted image 20251028224652.png" width=""600>


**Breadboard (ແບຣດບອດ)** ແມ່ນອຸປະກອນພື້ນຖານທີ່ນັກອິເລັກໂຕນິກ ຫຼື ນັກຮຽນທີ່ຝຶກ Arduino ທຸກຄົນຕ້ອງໃຊ້!  
ມັນຊ່ວຍໃຫ້ສາມາດ “ຕໍ່ວົງຈອນ” ໄດ້ໂດຍ **ບໍ່ຕ້ອງບັດ (solder)** — ສະດວກໃນການທົດລອງ ແລະ ແກ້ໄຂວົງຈອນໄດ້ງ່າຍ.

---

## 🔹 1. ຄວາມໝາຍຂອງ Breadboard

> Breadboard ແມ່ນກະດານທີ່ມີຮູເຈາະຫຼາຍຮູ (ຮູເຫັນເປັນຕາຕະລາງ) ສຳລັບໃສ່ຂາຂອງອຸປະກອນໄຟຟ້າ (resistor, LED, sensor, IC, ແລະສາຍ jumper)  
> ພາຍໃນກະດານຈະມີແຜ່ນໂລຫະຊຶ່ງເຊື່ອມຮູໃຫ້ຕໍ່ກັນໄດ້.

---

## 🔹 2. ໂຄງສ້າງຂອງ Breadboard

ສ່ວນໃຫຍ່ຈະແບ່ງອອກເປັນ 3 ພາກໃຫຍ່:

### 🟦 (1) Power Rails (ດ້ານຂ້າງ)

- ມັກຈະມີສັນຍາລັກ “+” ແລະ “–”
    
- ສຳລັບຈ່າຍໄຟໃຫ້ວົງຈອນ
    
    - “+” = 5V ຫຼື 3.3V
        
    - “–” = GND
        
- ຮູໃນແຕ່ລະແຖວຂອງ power rail ຈະເຊື່ອມກັນໃນແນວຕັ້ງ
    

### 🟩 (2) Terminal Strips (ສ່ວນກາງ)

- ຈະແບ່ງເປັນສອງຂ້າງ (ຊ້າຍ/ຂວາ)
    
- ແຕ່ລະແຖວມີ 5 ຮູ ເຊື່ອມກັນໃນແນວນອນ
    
- ເຮັດໜ້າທີ່ເປັນຈຸດຕໍ່ຂອງຂາອຸປະກອນ (ເຊັ່ນຂາ LED, Resistor, IC)
    
- ກາງບອດມັກຈະມີ “ຮ່ອງກາງ” ເພື່ອໃຫ້ໃສ່ IC ໄດ້ພອດດີ (ແຕ່ລະຂ້າງຈະບໍ່ເຊື່ອມກັນ)
    

### 🟥 (3) Gap (ຮ່ອງກາງ)

- ແຍກຂອງຂາຊ້າຍ-ຂວາອອກເພື່ອໃສ່ IC ໃນກາງ
    
- ຂາຂອງ IC ທີ່ຢູ່ຄົບກັນຈະບໍ່ຕໍ່ກັນ ເຮັດໃຫ້ສາມາດຕໍ່ວົງຈອນໄດ້ຢ່າງປອດໄພ
    

---

## 🔹 3. ການເຊື່ອມຕໍ່ຂ້າງໃນ (ສຳຄັນຫຼາຍ)

ຄິດງ່າຍໆແບບນີ້:

```
Power rail:  | + + + + + + |    (ແນວຕັ້ງ)
               | - - - - - - |

Terminal strips:
   A B C D E   |   F G H I J
  1 o o o o o  |  o o o o o
  2 o o o o o  |  o o o o o
     (ແຕ່ລະແຖວ 5 ຮູ ເຊື່ອມກັນໃນແນວນອນ)
```

- ຮູ A–E ແຖວ 1 ຈະເຊື່ອມກັນ
    
- ຮູ F–J ແຖວ 1 ຈະເຊື່ອມກັນ
    
- ແຕ່ຮູລະຫວ່າງ “E” ແລະ “F” ຈະ **ບໍ່ເຊື່ອມກັນ**
    

---

## 🔹 4. ຂໍ້ດີຂອງ Breadboard

✅ ບໍ່ຕ້ອງບັດສາຍ  
✅ ທົດລອງວົງຈອນໄດ້ໄວ  
✅ ແກ້ໄຂ ຫຼື ປ່ຽນອຸປະກອນໄດ້ງ່າຍ  
✅ ເຫມາະສຳລັບຝຶກ Arduino, ESP32, sensor ແລະວົງຈອນພື້ນຖານ

---

## 🔹 5. ຂໍ້ສັງເກດ

⚠️ Breadboard ບໍ່ເໝາະກັບວົງຈອນທີ່ໃຊ້ໄຟສູງ (ເຊັ່ນ 12V ຂຶ້ນໄປ) ຫຼື ມີກະແສຫຼາຍ  
⚠️ ຕ້ອງລະວັງການສັບສາຍ “+” ແລະ “–”

---

ຮູບອຸປະກອນແບບ Schematic Diagram :

<img src="Pasted image 20251028225022.png" witdth="600">


ຕົວຢ່າງການນຳໃຊ້: ສ້າງວົງຈອນໄຟ LED ກະພິບໂດຍການວາງ LED, ຕົວຕ້ານທານ, ແລະ ສາຍເຊື່ອມຕໍ່ກັບ Arduino Uno.

3.USB Cable
<img src="Pasted image 20251028225318.png" width="500">

---

## 🔌 **1. USB Cable ແມ່ນຫຍັງ**

**USB cable** (ສາຍຊື່ອມຕໍ່ຂໍ້ມູນແລະໄຟຟ້າ) ແມ່ນສາຍທີ່ໃຊ້  
**ເຊື່ອມຕໍ່ລະຫວ່າງ Arduino Board ແລະ ຄອມພິວເຕີ**  
ເພື່ອໃຫ້ບອດສາມາດ:

- 💾 **ຮັບໂປຣແກຣມ** ຈາກ Arduino IDE
    
- 🔋 **ຮັບໄຟຟ້າ 5V** ຈາກຄອມພິວເຕີ
    
- 💬 **ສື່ສານຂໍ້ມູນ** ລະຫວ່າງບອດ ແລະ ຄອມພິວເຕີ (Serial Communication)
    

---

## ⚙️ **2. ປະເພດຂອງສາຍທີ່ Arduino Uno ໃຊ້**

ສໍາລັບ **Arduino Uno R3 (ຮຸ່ນທີ່ນິຍົມສຸດ)**  
ຈະໃຊ້ສາຍຊະນິດນີ້ 👇

### 🔹 **USB Type-A to USB Type-B**

- ປາຍດ້ານໜຶ່ງ: **Type-A** (ຮູບຫົວສີ່ຫຼ່ຽມບາງ) — ເສັບເຂົ້າຄອມພິວເຕີ
    
- ອີກປາຍໜຶ່ງ: **Type-B** (ຫົວໃຫຍ່ຮູບສີ່ຫຼ່ຽມ) — ເສັບເຂົ້າ Arduino Uno
    

🧩 ຮູບຫົວສາຍນີ້ຄ້າຍກັບທີ່ໃຊ້ກັບເຄື່ອງພິມ (Printer Cable)

---

## ⚡ **3. ໜ້າທີ່ຂອງສາຍ USB**

|ໜ້າທີ່|ອະທິບາຍ|
|---|---|
|**Power Supply (ຈ່າຍໄຟ)**|ຈ່າຍໄຟ 5V ໃຫ້ບອດ Arduino|
|**Data Transfer (ສົ່ງຂໍ້ມູນ)**|ສົ່ງ/ຮັບຂໍ້ມູນລະຫວ່າງຄອມ ↔ ບອດ|
|**Upload Code (ອັບໂຫລດໂປຣແກຣມ)**|ນຳໃຊ້ໃນການສົ່ງໂປຣແກຣມຈາກ Arduino IDE|
|**Serial Communication (ສື່ສານ Serial)**|ໃຊ້ກັບ Serial Monitor ເພື່ອສະແດງຜົນຫຼືຂໍ້ມູນ|

---

## 🔍 **4. ສະຫຼຸບງ່າຍໆ**

- ສາຍ USB ແມ່ນທັງ “ສາຍໄຟ” ແລະ “ສາຍຂໍ້ມູນ”
    
- ຈໍາເປັນສໍາລັບການໃຊ້ Arduino Uno
    
- ບໍ່ຈຳເປັນຕ້ອງໃຊ້ Adapter ຖ້າເຊື່ອມຜ່ານ USB
    

---

#### 🧵 Wiring & Connectors

4.Jumper wires (male-to-male)
<img src="Pasted image 20251028230130.png" width="500">

## 🔌 **Jumper Wires (male-to-male)

**Jumper wire** ແມ່ນສາຍສັ້ນໆ ທີ່ໃຊ້ເພື່ອ **ເຊື່ອມຕໍ່ວົງຈອນດ້ວຍກັນ** ໂດຍບໍ່ຕ້ອງໃຊ້ການບັດບັງຫຼືບັດລວມໃດໆ.  
ມັນເປັນອຸປະກອນພື້ນຖານທີ່ໃຊ້ຮ່ວມກັບ **Breadboard** ແລະ **Arduino** ເພື່ອຕໍ່ສາຍວົງຈອນທົດລອງ.

---

## 🧩 **Male-to-Male ແມ່ນແນວໃດ?**

- “**Male**” ໝາຍເຖິງປາຍທີ່ເປັນເຂັມ (ມີເຫຼັກສຽບອອກມາ)
    
- “**Male-to-Male**” ໝາຍເຖິງສາຍທີ່ມີເຂັມທັງສອງຂ້າງ
    

➡ ນັ້ນກໍ່ຄື ສາຍທີ່ສາມາດ **ເສີບລົງ Breadboard ໄດ້ທັງສອງດ້ານ**  
ແລະມັກໃຊ້ເພື່ອເຊື່ອມລະຫວ່າງ  
👉 **Breadboard ↔ Arduino Board**

---

## ⚙️ **ໜ້າທີ່ຂອງ Jumper Wires (Male-to-Male)**

|ໜ້າທີ່|ອະທິບາຍ|
|---|---|
|🔋 **ເຊື່ອມສາຍໄຟຟ້າ**|ນໍາໄຟຟ້າຈາກ Arduino ໄປຫາ Breadboard|
|🧠 **ເຊື່ອມສັນຍານ**|ສົ່ງສັນຍານລະຫວ່າງຂາຂອງອຸປະກອນຕ່າງໆ|
|🧩 **ຊ່ວຍທົດລອງວົງຈອນ**|ໃຊ້ຕໍ່ວົງຈອນຊົ່ວຄາວ ໂດຍບໍ່ຕ້ອງບັດສາຍ|

---

## 🧠 **ປະເພດອື່ນຂອງ Jumper Wires**

|ປະເພດ|ລາຍລະອຽດ|
|---|---|
|🔹 **Male-to-Male**|ເຊື່ອມ Breadboard ↔ Breadboard / Breadboard ↔ Arduino|
|🔹 **Male-to-Female**|ເຊື່ອມ Breadboard ↔ Sensor / Module|
|🔹 **Female-to-Female**|ເຊື່ອມ Module ↔ Module|

---

## 🧩 **ຕົວຢ່າງ: ຕໍ່ LED ກັບ Arduino Uno**

### 🎯 ຈຸດປະສົງ:

ໃຫ້ **LED ຕິດ–ດັບ** ຕາມໂຄດທີ່ຢູ່ໃນ Arduino IDE

---

### 🔧 ອຸປະກອນທີ່ໃຊ້:

1. Arduino Uno Board
    
2. Breadboard
    
3. LED 1 ດວງ
    
4. Resistor 220Ω
    
5. Jumper wires (male-to-male) 3 ສາຍ
    

---

### ⚙️ **ວິທີຕໍ່ວົງຈອນ:**

1. ນໍາ **Jumper wire** ສາຍໜຶ່ງ  
    ➜ ຕໍ່ຈາກ **Pin 13** ຂອງ Arduino → ຂາບວກ (Anode) ຂອງ LED ຜ່ານ Resistor
    
2. ນໍາ **Jumper wire** ອີກສາຍ  
    ➜ ຕໍ່ຈາກ **GND (Ground)** ຂອງ Arduino → ຂາລົບ (Cathode) ຂອງ LED
    
3. ນໍາ **Jumper wire ອີກສາຍ**  
    ➜ ເຊື່ອມລະຫວ່າງ Breadboard ໃຫ້ກະແສໄຟເຂົ້າຫາ LED ຢ່າງຖືກທາງ
    

---

### 🧠 **ໂຄດທີ່ໃຊ້ (ໃນ Arduino IDE):**

```cpp
int ledPin = 13;

void setup() {
  pinMode(ledPin, OUTPUT);
}

void loop() {
  digitalWrite(ledPin, HIGH); // LED ຕິດ
  delay(1000);               // ລໍຖ້າ 1 ວິນາທີ
  digitalWrite(ledPin, LOW);  // LED ດັບ
  delay(1000);               // ລໍຖ້າ 1 ວິນາທີ
}
```

---

### 💡 **ຜົນທີ່ໄດ້:**

LED ຈະ **ຕິດ 1 ວິນາທີ ແລ້ວດັບ 1 ວິນາທີ** ຊໍ້າໆ  
ເຮັດໃຫ້ເຫັນຊັດໆວ່າ Jumper wire ຊ່ວຍໃຫ້ການເຊື່ອມຕໍ່ລະຫວ່າງ Breadboard ແລະ Arduino ງ່າຍແລະສະດວກຫຼາຍ.

---

ສະຫຼຸບງ່າຍໆ 🧷

> **Jumper Wire (Male-to-Male)** ແມ່ນສາຍທີ່ມີເຂັມທັງສອງດ້ານ, ໃຊ້ເພື່ອເຊື່ອມຕໍ່ລະຫວ່າງ Breadboard ແລະ Arduino ຢ່າງສະດວກແລະວ່ອງໄວ.

---

5.Jumper wires (male-to-female)

<img src="Pasted image 20251028230312.png" width="500">


---

## 🔌 **Jumper Wire (Male-to-Female) ແມ່ນຫຍັງ?**

**Jumper wire** ປະເພດນີ້ຈະມີ:

- ຂາໜຶ່ງເປັນ **Male (ເຂັມ)**
    
- ອີກຂາໜຶ່ງເປັນ **Female (ຮູຮັບ)**
    

ໃຊ້ເພື່ອ **ເຊື່ອມຕໍ່ອຸປະກອນຫຼືໂມດູນທີ່ມີຂາເປັນເຂັມ (Male pin)** ເຊັ່ນ Sensor, Module, ຫຼືຂາຂອງ Arduino.

---

## ⚙️ **ວິທີນໍາໃຊ້**

- ປາຍ **Male** ➜ ເສີບລົງ **Breadboard**
    
- ປາຍ **Female** ➜ ເສີບໃສ່ **ຂາ Pin ຂອງ Sensor / Module**
    

---

## 🧠 **ປະໂຫຍດຂອງ Male-to-Female Jumper Wires**

|ຈຸດດີ|ອະທິບາຍ|
|---|---|
|🔹 ສະດວກໃນການເຊື່ອມ Sensor|ເຊັ່ນ Ultrasonic, DHT11, ຫຼືອຸປະກອນອື່ນໆ|
|🔹 ບໍ່ຈໍາເປັນບັດສາຍ|ເພີ່ມ–ຖອດອຸປະກອນງ່າຍ|
|🔹 ເຊື່ອມຕໍ່ກັບ Breadboard ໄດ້|ດ້ານ male ເສີບລົງ breadboard ໄດ້ເລີຍ|

---

## 🧩 **ຕົວຢ່າງນ້ອຍໆ: ເຊື່ອມ Sensor DHT11 (ວັດອຸນຫະພູມ) ກັບ Arduino Uno**

### 🎯 ຈຸດປະສົງ:

ເຊື່ອມ Sensor DHT11 ເພື່ອອ່ານອຸນຫະພູມແລະຄວາມຊຸ່ມ

---

### 🔧 ອຸປະກອນ:

- Arduino Uno
    
- DHT11 Sensor (ຂາ 3 ຂາ: VCC, DATA, GND)
    
- Jumper wires (male-to-female) 3 ສາຍ
    

---

### ⚙️ **ວິທີຕໍ່ສາຍ:**

|DHT11|Arduino Uno|
|---|---|
|VCC|5V|
|DATA|Pin 2|
|GND|GND|

🧵 ນໍາ Jumper Wire (male-to-female) ມາຕໍ່:

- ຂາ **Female** ຕໍ່ກັບ **Sensor DHT11**
    
- ຂາ **Male** ເສີບລົງ Breadboard ແລ້ວເຊື່ອມໄປຫາ Arduino
    

---

ດັ່ງນັ້ນ 👇

> **Jumper wire (male-to-female)** ເປັນສາຍທີ່ໃຊ້ເຊື່ອມອຸປະກອນທີ່ມີຂາເຂັມ (ຢ່າງ Sensor)** ເຂົ້າກັບ Breadboard ຫຼື Arduino ໄດ້ຢ່າງສະດວກ.

---

6.Jumper wires (female-to-female)
<img src="Pasted image 20251028230431.png" width="500">

---

## 🔌 **Jumper Wire (Female-to-Female) ແມ່ນຫຍັງ?**

**Jumper wire (female-to-female)** ແມ່ນສາຍທີ່ມີ **ຮູຮັບ (female)** ທັງສອງປາຍ.  
ຮູຮັບນີ້ສາມາດໃຫ້ **ເຂັມຂອງອຸປະກອນສອດເຂົ້າໄດ້**.

ສ່ວນໃຫຍ່ໃຊ້ເພື່ອ  
👉 ເຊື່ອມຕໍ່ **ໂມດູນ – ໂມດູນ**,  
👉 ຫຼື **ໂມດູນ – Arduino (ຜ່ານຂາເຂັມ)**

---

## ⚙️ **ຄຸນສົມບັດຂອງ Female-to-Female Jumper Wire**

|ຄຸນສົມບັດ|ອະທິບາຍ|
|---|---|
|🔹 ມີຮູຮັບທັງສອງຂ້າງ|ສາມາດສຽບໃສ່ຂາເຂັມ (male pin) ຂອງອຸປະກອນໄດ້|
|🔹 ສະດວກໃນການເຊື່ອມອຸປະກອນພາຍນອກ|ເຊັ່ນ ເຊື່ອມບອດ Sensor ໄປຫາບອດອື່ນ|
|🔹 ປອດໄພ|ບໍ່ມີເຂັມໂລຫະອອກມາ ຈຶ່ງລົດຄວາມສຽງຈາກການຊອດວົງ|

---

## 🧩 **ຕົວຢ່າງການນໍາໃຊ້ນ້ອຍໆ**

### 🎯 ຈຸດປະສົງ:

ເຊື່ອມຕໍ່ **Module Bluetooth HC-05** ກັບ **Arduino Uno**

---

### 🔧 ອຸປະກອນທີ່ໃຊ້:

- Arduino Uno
    
- Bluetooth Module HC-05
    
- Jumper Wires (female-to-female) 4 ສາຍ
    

---

### ⚙️ **ວິທີຕໍ່ສາຍ:**

|HC-05|Arduino Uno|
|---|---|
|VCC|5V|
|GND|GND|
|TXD|Pin 0 (RX)|
|RXD|Pin 1 (TX)|

🧵 ນໍາ **Jumper Wire (female-to-female)** ຕໍ່ໂດຍ:

- ຂາ **Female** ທັງສອງດ້ານເສີບໃສ່ **ຂາເຂັມ** ຂອງ HC-05 ແລະ Arduino
    

---

### 💡 **ຜົນທີ່ໄດ້:**

ບອດ Arduino ສາມາດສື່ສານຜ່ານ Bluetooth ໄດ້ ໂດຍໃຊ້ Jumper wires (female-to-female) ເປັນຕົວເຊື່ອມສາຍສັນຍານ.

---

ສະຫຼຸບງ່າຍໆ 🧷

> **Jumper wire (female-to-female)** ແມ່ນສາຍທີ່ມີຮູຮັບທັງສອງຂ້າງ, ໃຊ້ເພື່ອເຊື່ອມອຸປະກອນທີ່ມີຂາເຂັມ (Male pins) ຢ່າງສະດວກແລະປອດໄພ.

---

7.9V Battery Connector
<img src="Pasted image 20251028230531.png" width="500">

---

## 🔌 **9V Battery Connector ແມ່ນຫຍັງ?**

**9V Battery Connector** ຫຼື **ສາຍຕໍ່ຖ່ານ 9 ໂວນ**  
ແມ່ນສາຍທີ່ໃຊ້ເຊື່ອມຕໍ່ລະຫວ່າງ  
👉 **ຖ່ານ 9V (Battery)** ແລະ  
👉 **ບອດ Arduino** (ຫຼືອຸປະກອນອື່ນໆ)

ເພື່ອ **ຈ່າຍໄຟຟ້າໃຫ້ບອດ** ໃນກໍລະນີທີ່ບໍ່ໄດ້ເຊື່ອມກັບຄອມພິວເຕີ.

---

## ⚙️ **ສ່ວນປະກອບຂອງ 9V Battery Connector**

1. 🔴 **ສາຍສີແດງ** → ຄົງຄ່າ **ບວກ (+)**
    
2. ⚫ **ສາຍສີດໍາ** → ຄົງຄ່າ **ລົບ (−)**
    
3. 🪫 **ຫົວຕໍ່ Battery Clip** → ໄວ້ເຊື່ອມກັບຖ່ານ 9V
    
4. 🔌 **ຫົວ DC Jack (2.1mm)** → ເຊື່ອມໄປທີ່ **Arduino’s Power Jack**
    

---

## ⚡ **ວິທີນໍາໃຊ້ກັບ Arduino Uno**

1. ເອົາຖ່ານ 9V ໃສ່ກັບ **Battery Connector**
    
2. ເຊື່ອມຫົວ **DC Jack** ເຂົ້າກັບ **Power Jack** ຂອງ Arduino (ຢູ່ມຸມຊ້າຍລຸ່ມຂອງບອດ)
    
3. Arduino ຈະໄດ້ຮັບໄຟຟ້າ 9V ຜ່ານ **Voltage Regulator** ຂອງບອດ ແລະປ່ຽນເປັນ 5V ສໍາລັບຊິບຫຼັກ.
    

---

## 🧠 **ສິ່ງທີ່ຄວນຮູ້**

|ຫົວຂໍ້|ອະທິບາຍ|
|---|---|
|⚠️ **ຢ່າຕໍ່ກັບ 5V Pin ໂດຍກົງ!**|ເພາະ 9V ສູງເກີນ ອາດເຮັດໃຫ້ບອດເສຍ|
|✅ **ຕໍ່ຜ່ານ Power Jack ຫຼື Vin**|ເປັນວິທີທີ່ຖືກຕ້ອງ ເພື່ອໃຫ້ຊິບ Regulator ຈັດການແຮງດັນໃຫ້ພອດ|
|🔋 **ສາມາດນໍາໃຊ້ທົດແທນ USB**|ໃນກໍລະນີທີ່ບໍ່ມີຄອມພິວເຕີ|

---

## 🧩 **ຕົວຢ່າງນ້ອຍໆ**

ຖ້າເຮົາເຮັດໂຄງງານ Arduino ໃນພາກສະໜາມ (ບໍ່ມີຄອມພິວເຕີ)  
ເຮົາສາມາດໃຊ້

> 🔋 **9V Battery + Connector** ເພື່ອຈ່າຍໄຟໃຫ້ Arduino  
> ບອດຈະເຮັດວຽກຕໍ່ໄປໄດ້ໂດຍບໍ່ຕ້ອງເຊື່ອມ USB.

---

ສະຫຼຸບງ່າຍໆ 🧷

> **9V Battery Connector** ແມ່ນສາຍຕໍ່ທີ່ໃຊ້ເຊື່ອມຖ່ານ 9V ເຂົ້າກັບ Arduino ເພື່ອຈ່າຍໄຟໃຫ້ບອດເມື່ອບໍ່ໄດ້ເຊື່ອມຜ່ານ USB.

---

#### 💡 Basic Components

8.LEDs (Red: 5, Yellow: 5, Blue: 5, RGB: 1)
<img src="Pasted image 20251028230719.png" width="500">

---

## 💡 **LED ແມ່ນຫຍັງ?**

**LED (Light Emitting Diode)** ແມ່ນຫຼອດໄຟຂະໜາດນ້ອຍທີ່ປ່ອຍແສງອອກເມື່ອມີໄຟຟ້າໄຫຼຜ່ານ.  
ມັນເປັນອຸປະກອນພື້ນຖານທີ່ນິຍົມໃຊ້ໃນໂຄງງານ Arduino ເພື່ອ:

- ແສດງຜົນ (ຢ່າງເຊັ່ນ “ON/OFF”)
    
- ສົ່ງສັນຍານສະແດງສະຖານະ
    
- ໃຊ້ປະດັບຫຼືຈໍາລອງໄຟຈະລາຈອນ 🚦
    

---

## 🟥🟨🟦 **ຈໍານວນແລະສີ**

|ສີ|ຈໍານວນ|ຄວາມໝາຍ|
|---|---|---|
|🔴 ແດງ|5|ມັກໃຊ້ເປັນໄຟສະແດງ “ON”, “Error”, “Stop”|
|🟡 ເຫຼືອງ|5|ໃຊ້ເປັນ “Warning” ຫຼື “Processing”|
|🔵 ຟ້າ|5|ໃຊ້ເປັນ “Status” ຫຼື “Bluetooth/Signal”|
|🌈 RGB|1|ສາມາດປ່ຽນໄດ້ຫຼາຍສີໂດຍຄວບຄຸມຄ່າ **R (Red)**, **G (Green)**, **B (Blue)**|

---

## ⚙️ **ໂຄງສ້າງຂອງ LED**

LED ທົ່ວໄປຈະມີ 2 ຂາ:

1. ➕ **Anode (ຂາຍາວ)** — ຕໍ່ໄປທີ່ **ຂົວບວກ (5V ຫຼື Output Pin)**
    
2. ➖ **Cathode (ຂາສັ້ນ)** — ຕໍ່ໄປທີ່ **GND (ຂົວລົບ)**
    

👉 ຄວນໃສ່ **Resistor (220Ω – 330Ω)** ຕໍ່ອະນຸກັບ LED ເພື່ອປ້ອງກັນບໍ່ໃຫ້ໄຫຼໄຟຫຼາຍເກີນ.

---

## 🧩 **ຕົວຢ່າງການນໍາໃຊ້ນ້ອຍໆ**

### 🔹 ຕົວຢ່າງ: ໄຟ LED ເວລາກົດປຸ່ມ

```cpp
int buttonPin = 2;
int ledPin = 13;
int buttonState = 0;

void setup() {
  pinMode(buttonPin, INPUT);
  pinMode(ledPin, OUTPUT);
}

void loop() {
  buttonState = digitalRead(buttonPin);
  if (buttonState == HIGH) {
    digitalWrite(ledPin, HIGH); // ເປີດໄຟ
  } else {
    digitalWrite(ledPin, LOW);  // ປິດໄຟ
  }
}
```

💡 ເມື່ອກົດປຸ່ມ ໄຟ LED ຈະຕິດ  
ປ່ອຍປຸ່ມ ໄຟຈະດັບ

---

## 🌈 **ຕົວຢ່າງການໃຊ້ RGB LED**

```cpp
int redPin = 9;
int greenPin = 10;
int bluePin = 11;

void setup() {
  pinMode(redPin, OUTPUT);
  pinMode(greenPin, OUTPUT);
  pinMode(bluePin, OUTPUT);
}

void loop() {
  analogWrite(redPin, 255);   // ແດງ
  analogWrite(greenPin, 0);
  analogWrite(bluePin, 0);
  delay(1000);

  analogWrite(redPin, 0);
  analogWrite(greenPin, 255); // ຂຽວ
  delay(1000);

  analogWrite(redPin, 0);
  analogWrite(greenPin, 0);
  analogWrite(bluePin, 255);  // ຟ້າ
  delay(1000);
}
```

---

## 🧠 **ສະຫຼຸບງ່າຍໆ**

> **LEDs (Red, Yellow, Blue, RGB)** ແມ່ນຫຼອດໄຟນ້ອຍໆ ທີ່ໃຊ້ສະແດງຜົນ ຫຼື ສະຖານະຂອງໂຄງງານ Arduino, ແລະ RGB LED ສາມາດປ່ຽນສີໄດ້ຫຼາຍສີໂດຍການປັບຄ່າຄວາມແຮງຂອງແຕ່ລະສີ.

---
**ຮູບອຸປະກອນແບບ Schematic Diagram:**

<img src="Pasted image 20251028230826.png"width="500">



9.RGB module

<img src="Pasted image 20251028231329.png"width="500">

---

## 💡 **RGB Module ແມ່ນຫຍັງ?**

**RGB Module** ແມ່ນ LED ປະກອບມາດເປັນ 3 ສີຫຼັກ:

- **R (Red)**
    
- **G (Green)**
    
- **B (Blue)**
    

✅ ສາມາດປ່ຽນສີໄດ້ຫຼາຍສີໂດຍການຄວບຄຸມຄ່າ **ຄວາມແຮງຂອງແຕ່ລະສີ (PWM)**

---

## ⚙️ **ວິທີນໍາໃຊ້ RGB Module ກັບ Arduino**

### 🔧 **ອຸປະກອນທີ່ໃຊ້**

- Arduino Uno
    
- RGB Module (Common Cathode / Common Anode)
    
- Jumper wires (male-to-male ຫຼື male-to-female ຂຶ້ນກັບການต่อ)
    
- Resistors 220Ω ຕໍ່ຂາ LED ທຸກສາຍ
    

---

### 🔌 **ຕົວຢ່າງການຕໍ່ສາຍ (Common Cathode)**

|RGB Module|Arduino Uno|
|---|---|
|R (Red)|Pin 9|
|G (Green)|Pin 10|
|B (Blue)|Pin 11|
|GND|GND|

💡 **ຄວນໃສ່ Resistor 220Ω ຕໍ່ແຕ່ລະສາຍ LED** ເພື່ອປ້ອງກັນບໍ່ໃຫ້ LED ໄຫຼໄຟຫຼາຍເກີນ.

---

### 🧩 **ຕົວຢ່າງໂຄ້ດ Arduino (PWM)**

```cpp
int redPin = 9;
int greenPin = 10;
int bluePin = 11;

void setup() {
  pinMode(redPin, OUTPUT);
  pinMode(greenPin, OUTPUT);
  pinMode(bluePin, OUTPUT);
}

void loop() {
  analogWrite(redPin, 255);   // ແດງ
  analogWrite(greenPin, 0);
  analogWrite(bluePin, 0);
  delay(1000);

  analogWrite(redPin, 0);
  analogWrite(greenPin, 255); // ຂຽວ
  analogWrite(bluePin, 0);
  delay(1000);

  analogWrite(redPin, 0);
  analogWrite(greenPin, 0);
  analogWrite(bluePin, 255);  // ຟ້າ
  delay(1000);

  // ຜົນສີປະກອບ
  analogWrite(redPin, 128);
  analogWrite(greenPin, 128);
  analogWrite(bluePin, 0);    // ເປັນເຫຼືອງ
  delay(1000);
}
```

💡 **ผลลัพธ์:**  
RGB Module ສາມາດປ່ຽນສີໄດ້ຫຼາຍສີ, ສາມາດສ້າງຄວາມສົດໃສ, ແລະແສງສະຫຼຸບຜົນຂອງພາບ LED ໄດ້ງ່າຍ.

---

💡 **ເຫັນຊັດໆ:**

- **Red, Green, Blue pins** → PWM ຄວບຄຸມຄ່າໄຟ
    
- **GND / VCC** → ຕໍ່ພາຍໃນ (Common Cathode = GND, Common Anode = VCC)
    
- **Resistor** → ປ້ອງກັນ LED ເສຍ
    

---
**ຮູບອຸປະກອນແບບ Schematic Diagram:**

<img src="Pasted image 20251028231459.png"width="500">

10.Resistors (220Ω, 1kΩ, 10kΩ)
<img src="Pasted image 20251028231706.png"width="500">

## 💡 **Resistor ແມ່ນຫຍັງ?**

**Resistor** ແມ່ນອຸປະກອນອີເລັກໂທນິກ ທີ່ປ້ອງກັນໄຟຟ້າໄຫຼເກີນ, ເພື່ອ:

- ຄວບຄຸມການໄຫຼຂອງໄຟ
    
- ປ້ອງກັນອຸປະກອນອື່ນໆ ເຊັ່ນ LED, Sensor
    
- ໃນໂຄງງານ Arduino ເຮັດໜ້າທີ່ສຳຄັນຫຼາຍ 💡
    

---

## ⚙️ **ປະເພດຂອງ Resistors ທີ່ໃຊ້ບ່າງ**

|ຄ່າ|ການນໍາໃຊ້ຕົວຢ່າງ|
|---|---|
|220Ω|ເຊື່ອມຕໍ່ LED ເພື່ອຈຸດໄຟໄຫຼໄດ້ຖືກຂະໜາດ|
|1kΩ|ຕໍ່ກັບ Push Button, Pull-up / Pull-down ພາຍໃນ Arduino|
|10kΩ|ຕໍ່ສຳລັບ Sensors, Potentiometer, Voltage Divider, Pull-up / Pull-down ທີ່ຕ້ອງຄ່າຄວາມຕ່າງແຮງຕ່ຳ|

---

## 🧩 **ຕົວຢ່າງນ້ອຍໆ**

### 🔹 ຕໍ່ LED ກັບ Arduino

```cpp
int ledPin = 13;

void setup() {
  pinMode(ledPin, OUTPUT);
}

void loop() {
  digitalWrite(ledPin, HIGH); // ເປີດ LED
  delay(1000);
  digitalWrite(ledPin, LOW);  // ປິດ LED
  delay(1000);
}
```

💡 **Resistor 220Ω** ໃຊ້ຕໍ່ອະນຸກັບ LED ເພື່ອປ້ອງກັນການໄຫຼໄຟຫຼາຍເກີນ.

---

### 🔹 ຕໍ່ Push Button ກັບ Arduino (Pull-down)

```cpp
int buttonPin = 2;
int ledPin = 13;

void setup() {
  pinMode(buttonPin, INPUT);
  pinMode(ledPin, OUTPUT);
}

void loop() {
  int buttonState = digitalRead(buttonPin);
  digitalWrite(ledPin, buttonState);
}
```

💡 **Resistor 10kΩ** ເຊື່ອມລົບພາຍໃນ (GND) ເພື່ອ Pull-down ປ້ອງການລອຍສັນຍານ.

---

### 🧠 **ເຫັນຊັດໆ**

- **220Ω** → LED, ໄຟສະແດງ
    
- **1kΩ** → Push Button, Pull-up / Pull-down ທີ່ຄ່າກາງ
    
- **10kΩ** → Sensors, Voltage Divider, Pull-up / Pull-down ຄ່າສູງ
    

---

💡 **ສະຫຼຸບ:**  
Resistors ເປັນສາຍສຳຄັນຫຼາຍ ໃນໂຄງງານ Arduino ເພື່ອຄວບຄຸມໄຟ, ປ້ອງກັນ LED ແລະອຸປະກອນອື່ນໆ.

---
**ຮູບອຸປະກອນແບບ Schematic Diagram:**

<img src="Pasted image 20251028231935.png"width="300">


11.8. Push Buttons (x4 with Lids )
<img src="Pasted image 20251028232144.png"width="500">

---

## 🔘 **Push Button ແມ່ນຫຍັງ?**

**Push Button** ແມ່ນປຸ່ມກົດໄດ້ ແລະສາມາດສະແດງສັນຍານ **ON / OFF** ສຳລັບ Arduino.

- ຕິດແປ Normally Open (NO)** ຫຼື **Normally Closed (NC)**
    
- ກົດ = ໄຟ **ON**, ປ່ອຍ = ໄຟ **OFF**
    

**ຕົວຢ່າງ:**

- ກົດເພື່ອເປີດ LED
    
- ກົດເພື່ອສົ່ງສັນຍານເຄື່ອງມື
    

---

## 🛡️ **“With Lids” ແມ່ນຫຍັງ?**

- Lids ຫຼື **ຝາປຸ່ມ**
    
- ສາມາດເຊື່ອມກັບຂາມື ແລະກົດງ່າຍ
    
- ປ້ອງກັນຜູ້ໃຊ້ກົດຜິດປຸ່ມ ຫຼື ລົດຄວາມເສຍຫາກຕິດຕໍ່ຜິດ
    

---

## ⚙️ **ວິທີນໍາໃຊ້ Push Button ກັບ Arduino**

### 🔧 **ອຸປະກອນທີ່ໃຊ້**

- Arduino Uno
    
- Push Buttons x4
    
- Jumper Wires
    
- Resistors 10kΩ (Pull-down)
    

---

### 🔌 **ຕົວຢ່າງการต่อสาย (Pull-down)**

|Push Button|Arduino Uno|
|---|---|
|One pin|Pin 2|
|Other pin|GND ผ่าน Resistor 10kΩ|

> ສາມາດເພີ່ມ Push Buttons ເພື່ອຄວບຄຸມຫຼາຍ LED ຫຼື Module ຕໍ່ໄດ້

---

### 🧩 **ຕົວຢ່າງโค้ດ Arduino**

```cpp
int buttonPin = 2; 
int ledPin = 13; 
int buttonState = 0;

void setup() {
  pinMode(buttonPin, INPUT);
  pinMode(ledPin, OUTPUT);
}

void loop() {
  buttonState = digitalRead(buttonPin);  // ອ່ານຄ່າປຸ່ມ
  if(buttonState == HIGH) {
    digitalWrite(ledPin, HIGH);  // ເປີດ LED
  } else {
    digitalWrite(ledPin, LOW);   // ປິດ LED
  }
}
```

💡 ເມື່ອກົດປຸ່ມ LED ຈະຕິດ, ປ່ອຍປຸ່ມ LED ຈະດັບ

---

## 🧠 **ສະຫຼຸບງ່າຍໆ**

> **Push Buttons (x4 with Lids)** ເປັນປຸ່ມກົດສາມາດນໍາໃຊ້ຄວບຄຸມ Arduino ໄຟ LED, Module ຫຼືສັນຍານອື່ນໆ. Lids ຊ່ວຍໃຫ້ກົດງ່າຍ ແລະປ້ອງກັນຄວາມຜິດພາດ.

---

12.Potentiometer (5kΩ)

<img src="Pasted image 20251028232231.png"width="500">

---

## 🎚️ **Potentiometer ແມ່ນຫຍັງ?**

**Potentiometer** ຫຼື **POT** ແມ່ນອຸປະກອນທີ່ປ່ຽນ **ຄ່າຄວາມຕ່າງກຽວກັບອິນພຸດ (Voltage / Resistance)** ໄດ້

- ມັນເປັນ **ຕົວປັບໝຸນ ເພື່ອເຮັດให้ output voltage ແຕກຕ່າງກັນ
    
- ມັກໃຊ້ຄວບຄຸມ LED, Servo, Motor, หรือ Analog Input ຂອງ Arduino
    

---

## ⚙️ **ຄຸນສົມບັດ**

|ສິ່ງ|ອະທິບາຍ|
|---|---|
|ຄ່າ 5kΩ|ຄ່າຄວາມຕ່າງຕໍ່ຂາຍາວໃນພາຍໃນ Pot|
|3 ຂາ|ປາກເຊື່ອມທັງສາມຂາ: **VCC**, **GND**, **Vout**|
|หมุนได้|ປ່ຽນ Output Voltage ລະຫວ່າງ 0–5V ສຳລັບ Arduino|

---

## 🔌 **ວິທີນໍາໃຊ້ Potentiometer ກັບ Arduino**

### 🔧 **ອຸປະກອນທີ່ໃຊ້**

- Arduino Uno
    
- Potentiometer 5kΩ
    
- Jumper wires
    

---

### 🔌 **การต่อสาย**

|Potentiometer Pin|Arduino Pin|
|---|---|
|Left (VCC)|5V|
|Right (GND)|GND|
|Middle (Vout)|A0 (Analog Input)|

---

### 🧩 **ตัวอย่างโค้ด Arduino**

```cpp
int potPin = A0;       // Analog pin
int ledPin = 9;        // PWM pin for LED
int potValue = 0;

void setup() {
  pinMode(ledPin, OUTPUT);
  Serial.begin(9600);
}

void loop() {
  potValue = analogRead(potPin);          // ອ່ານຄ່າ potentiometer
  int brightness = map(potValue, 0, 1023, 0, 255); // ແປງຄ່າ 0-1023 ເປັນ 0-255
  analogWrite(ledPin, brightness);        // ປັບຄວາມສະຫວ່າງ LED
  Serial.println(potValue);
  delay(100);
}
```

💡 **ຜົນລັບ:**  
ໝຸນ potentiometer → LED ສະຫວ່ງ/ມືດ ຕາມຄ່າທີ່ໝຸນ 🟢🔴🔵

---

## 🧠 **ສະຫຼຸບງ່າຍໆ

> **Potentiometer (5kΩ)** ເປັນຕົວປັບຄ່າແຮງດັນ/ຄວາມຕ້ານທານ ສາມາດໃຊ້ປັບ **ຄວາມສະຫວ່າງ LED, ຄວາມໄວມໍເຕີ້, ຫຼືອ່ານຄ່າຜ່ານ Analog Input ຂອງ Arduino** ໄດ້ງ່າຍແລະສະດວກ

---

**ຮູບອຸປະກອນແບບ Schematic Diagram:**
<img src="Pasted image 20251028232329.png"width="500">

13.Active Buzzer
<img src="Pasted image 20251028232612.png"width="500">

## 🔊 **Active Buzzer ແມ່ນຫຍັງ?**

**Active Buzzer** ແມ່ນອຸປະກອນສຽງ ທີ່ສາມາດ **ສົ່ງເສຽງໄດ້ເອງ** ເມື່ອມີໄຟຟ້າຜ່ານ

- ບໍ່ຈຳເປັນຕ້ອງໃຊ້ PWM ຫຼື signal frequency
    
- ສົມບູນເລີຍ ສໍາລັບ **ແຈ້ງເຕືອນ / Alarm / Notification**
    

**ແຕ່ຫຼາຍເວລາມັນມີ Active ແລະ Passive:**

- **Active Buzzer** → ເສຽງໄດ້ເອງ, ເພີ່ມໄຟ DC ແຕ່ພຽງພັດ
    
- **Passive Buzzer** → ຕ້ອງໃຊ້ PWM ຫຼື signal frequency ເພື່ອເສຽງ
    

---

## ⚙️ **ສ່ວນປະກອບ**

|ສ່ວນ|ອະທິບາຍ|
|---|---|
|+ (Positive)|ຕໍ່ເຂົ້າ **Pin Output ຂອງ Arduino**|
|- (Negative)|ຕໍ່ເຂົ້າ **GND**|

---

## 🔌 **ການນຳໃຊ້ກັບ Arduino**

|Buzzer Pin|Arduino Pin|
|---|---|
|+|Pin 8|
|-|GND|

> ບໍ່ຈຳເປັນຕ້ອງໃຊ້ resistor ເນື່ອງຈາກ Active Buzzer ກິນໄຟນ້ອຍ (~5V)

---

## 🧩 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
int buzzer = 8;

void setup() {
  pinMode(buzzer, OUTPUT);
}

void loop() {
  digitalWrite(buzzer, HIGH);  // ເປີດເສຽງ
  delay(500);
  digitalWrite(buzzer, LOW);   // ປິດເສຽງ
  delay(500);
}
```

💡 **ຜົນລັບ:**

- Buzzer ສົ່ງເສຽງ **ເປັນຈຸດ** 0.5 ວິນາທີ เปิด/ปิด ຊໍ້າ
    
- ສາມາດນໍາໃຊ້ເປັນ **Alarm, Button Feedback, Notification** ງ່າຍໆ
    

---

## 🧠 **ສະຫຼຸບງ່າຍໆ**

> **Active Buzzer** ແມ່ນອຸປະກອນສົ່ງເສຽງ ທີ່ເສຽງໄດ້ເອງ
> 
> - ຕໍ່ **Pin Output + GND** ກັບ Arduino
>     
> - ບໍ່ຈຳເປັນຕ້ອງใช้ PWM
>     
> - ເໝາະສໍາລັບ **ແຈ້ງເຕືອນ, Alarm, Notification**
>     

**ຮູບອຸປະກອນແບບ Schematic Diagram:**

<img src="Pasted image 20251028232648.png"width="500">

14.Passive Buzzer

<img src="Pasted image 20251028232822.png"width="500">

---

## 🔔 **Passive Buzzer ແມ່ນຫຍັງ?**

**Passive Buzzer** ແມ່ນອຸປະກອນສົ່ງເສຽງ ແຕ່ຈະ **ບໍ່ສາມາດສ້າງເສຽງໄດ້ເອງ** ເມື່ອມີໄຟ DC ຜ່ານ.  
ມັນຈຳເປັນຕ້ອງໃຊ້ **ຄວາມຖີ່ສັນຍານ (PWM signal)** ເພື່ອສ້າງເສຽງ.

> 🧠 ງ່າຍໆຄື:
> 
> - **Active Buzzer** → ໃຫ້ໄຟກໍສົ່ງເສຽງໄດ້ເອງ
>     
> - **Passive Buzzer** → ຕ້ອງໃຫ້ Arduino ສ້າງຄວາມຖີ່ເພື່ອເສຽງ
>     

---

## ⚙️ **ຄຸນສົມບັດ**

|ສ່ວນ|ອະທິບາຍ|
|---|---|
|+ (Positive)|ຕໍ່ເຂົ້າ **Pin Output (PWM)** ຂອງ Arduino|
|- (Negative)|ຕໍ່ເຂົ້າ **GND**|
|ໄຟເຂົ້າ|3.3V – 5V|
|ເສຽງປ່ຽນໄດ້|ສ້າງເສຽງຕ່າງໆຕາມຄວາມຖີ່|

---

## 🔌 **ການຕໍ່ກັບ Arduino**

|Passive Buzzer Pin|Arduino Pin|
|---|---|
|+ (Positive)|Pin 9 (PWM)|
|- (Negative)|GND|

---

## 🧩 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
int buzzer = 9;

void setup() {
  pinMode(buzzer, OUTPUT);
}

void loop() {
  tone(buzzer, 1000); // ເສຽງ 1000 Hz
  delay(500);
  noTone(buzzer);     // ປິດເສຽງ
  delay(500);
}
```

💡 **ຜົນລັບ:**  
Passive Buzzer ຈະສົ່ງເສຽງ 1000 Hz ເປັນເວລາ 0.5 ວິນາທີ ແລ້ວຢຸດ 0.5 ວິນາທີ

---

## 🎶 **ຕົວຢ່າງເພີ່ມເຕີມ: ເຮັດເພງນ້ອຍໆ**

```cpp
int buzzer = 9;

void setup() {
  pinMode(buzzer, OUTPUT);
}

void loop() {
  tone(buzzer, 262); // ສຽງ C
  delay(300);
  tone(buzzer, 294); // ສຽງ D
  delay(300);
  tone(buzzer, 330); // ສຽງ E
  delay(300);
  noTone(buzzer);
  delay(1000);
}
```

🎵 **ຜົນລັບ:** ຈະໄດ້ເພງສັ້ນໆ “ດົງ ໂດ ເມ”

---

## 🧠 **ສະຫຼຸບງ່າຍໆ**

> **Passive Buzzer** ແມ່ນອຸປະກອນສົ່ງເສຽງທີ່ຕ້ອງໃຊ້ Arduino ສ້າງຄວາມຖີ່ (tone) ເພື່ອໃຫ້ມັນເສຽງ.
> 
> - ເຮັດເພງໄດ້, ແຈ້ງເຕືອນໄດ້
>     
> - ເຊື່ອມງ່າຍ: **Pin PWM + GND**
>     
> - ເສຽງປ່ຽນໄດ້ຕາມຄ່າ frequency
>     

---
**ຮູບອຸປະກອນແບບ Schematic Diagram:**

<img src="Pasted image 20251028232648.png"width="500">

# 📟 Displays & Output

15.16x2 LCD display
<img src="Pasted image 20251028233040.png"width="500">

---

## 🧾 **16x2 LCD Display ແມ່ນຫຍັງ?**

**LCD (Liquid Crystal Display) 16x2** ແມ່ນຈໍສະແດງຂໍ້ຄວາມທີ່ສາມາດສະແດງໄດ້

- **16 ຕົວອັກສອນ** ຕໍ່ແຖວ
    
- **2 ແຖວ** (ລວມແລ້ວ 32 ຕົວອັກສອນ)
    

ຈໍປະເພດນີ້ເຮັດວຽກໂດຍໃຊ້ **Controller HD44780** ຊຶ່ງ Arduino ຮອງຮັບໂດຍກົງ

---

## ⚙️ **ຄຸນສົມບັດຫຼັກ**

|ລາຍການ|ອະທິບາຍ|
|---|---|
|ຈຳນວນຕົວອັກສອນ|16 ຕົວອັກສອນ x 2 ແຖວ|
|ແຮງດັນ|5V|
|Controller|HD44780|
|ຄວາມສາມາດ|ສະແດງຂໍ້ຄວາມ, ຕົວເລກ, ສັນຍາລັກ|
|ການປັບຄວາມສະຫວ່າງ|ຜ່ານ Potentiometer|

---

## 🧩 **ຈຳນວນຂາທັງໝົດ 16 Pins**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|1|VSS|ຕໍ່ກັບ GND|
|2|VDD|ຕໍ່ກັບ +5V|
|3|V0|ປັບຄວາມຄົມຊັດ (ຜ່ານ Potentiometer)|
|4|RS|Register Select (ຄວບຄຸມໂໝດຂໍ້ຄວາມ/ຄໍາສັ່ງ)|
|5|RW|Read/Write (ປົກກະຕິຕໍ່ GND)|
|6|E|Enable (ເຮັດໃຫ້ LCD ເຮັດວຽກ)|
|7–14|D0–D7|Data Pins|
|15|LED+|ໄຟສ່ອງຈໍ (Backlight +)|
|16|LED-|ໄຟສ່ອງຈໍ (Backlight -)|

> ⚠️ ໃນການນໍາໃຊ້ທົ່ວໄປ ມັກໃຊ້ແຕ່ D4–D7 (4-bit mode) ເພື່ອປະຫຍັດຂາ Arduino

---

## 🔌 **ການຕໍ່ແບບພື້ນຖານ**

|LCD|Arduino Uno|
|---|---|
|VSS|GND|
|VDD|5V|
|V0|Potentiometer (ກາງ)|
|RS|Pin 12|
|RW|GND|
|E|Pin 11|
|D4|Pin 5|
|D5|Pin 4|
|D6|Pin 3|
|D7|Pin 2|
|A (LED+)|5V|
|K (LED-)|GND|

---

## 🧠 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
#include <LiquidCrystal.h>

LiquidCrystal lcd(12, 11, 5, 4, 3, 2);

void setup() {
  lcd.begin(16, 2);           // ກຳນົດຈໍ 16x2
  lcd.print("Hello, Arduino!"); // ສະແດງຂໍ້ຄວາມແຖວທຳອິດ
  lcd.setCursor(0, 1);        // ເລື່ອນໄປແຖວທີ 2
  lcd.print("LCD 16x2 Test");
}

void loop() {
}
```

💡 **ຜົນລັບ:**  
ຈໍ LCD ຈະສະແດງຄຳວ່າ

```
Hello, Arduino!
LCD 16x2 Test
```

---

## 🧠 **ສະຫຼຸບງ່າຍໆ**

> **LCD 16x2** ແມ່ນຈໍສະແດງຂໍ້ຄວາມທີ່ໃຊ້ງ່າຍ ແລະເໝາະສໍາລັບການສະແດງຂໍ້ມູນຕ່າງໆໃນ Arduino Project.
> 
> - ສະແດງໄດ້ 2 ແຖວ, ແຖວລະ 16 ຕົວອັກສອນ
>     
> - ຕໍ່ງ່າຍ, ມີຟັງຊັນໃນ Library `LiquidCrystal` ພ້ອມໃຊ້
>     
> - ເຫມາະສໍາລັບຂໍ້ຄວາມ, ສະຖານະ, ຄ່າວັດຕ່າງໆ
>     

---
**ຮູບອຸປະກອນແບບ Schematic Diagram:**

<img src="Pasted image 20251028233141.png"width="300">


16.I2C Serial Adapter board module
<img src="Pasted image 20251028233302.png"width="500">

---

## 🧾 **I2C Serial Adapter Board Module ແມ່ນຫຍັງ?**

ໂມດູນ **I2C Serial Adapter** ແມ່ນບອດນ້ອຍໆ ທີ່ຊ່ວຍໃຫ້ເຮົາເຊື່ອມຕໍ່ **LCD 16x2** ກັບ Arduino ໄດ້ງ່າຍຂຶ້ນ  
ໂດຍປົກກະຕິ LCD ຈະໃຊ້ຂາຫຼາຍ (ປະມານ 12–16 ຂາ) ແຕ່ຖ້າໃຊ້ I2C Module ຈະໃຊ້ພຽງແຕ່ **2 ຂາສັນຍານ** (SDA ແລະ SCL) ເທົ່ານັ້ນ! 😄

---

## ⚙️ **ຫນ້າທີ່ຫຼັກ**

- ປ່ຽນການສື່ສານຈາກ **parallel (ຫຼາຍຂາ)** ເປັນ **serial (2 ຂາ)**
    
- ຊ່ວຍປະຫຍັດຂາຂອງ Arduino
    
- ມີ Potentiometer ໃຫ້ປັບຄວາມຄົມຊັດຂອງຈໍ LCD
    
- ມີ jumper ສຳລັບເປີດ/ປິດ backlight
    
- ມີ IC **PCF8574** ໃຊ້ຄວບຄຸມ LCD ຜ່ານ I2C
    

---

## 🧩 **ຂາທີ່ສຳຄັນ (4 Pins)**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|GND|Ground|ຕໍ່ກັບ GND ຂອງ Arduino|
|VCC|Power|ຕໍ່ກັບ +5V|
|SDA|Data|ຕໍ່ກັບ SDA ຂອງ Arduino (A4)|
|SCL|Clock|ຕໍ່ກັບ SCL ຂອງ Arduino (A5)|

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|I2C Module|Arduino Uno|
|---|---|
|GND|GND|
|VCC|5V|
|SDA|A4|
|SCL|A5|

ພາຍຫຼັງຈາກນັ້ນ ນຳໂມດູນນີ້ໄປເສຽບກັບຈໍ **LCD 16x2** (ມີຮູຮອງພອດກັນແລ້ວ)

---

## 💻 **ຕົວຢ່າງໂຄດພ້ອມ Library**

### 🔹 ຕ້ອງຕິດຕັ້ງ Library:

- `LiquidCrystal_I2C`
    
- `Wire`
    

### 🔹 ຕົວຢ່າງໂຄດ:

```cpp
#include <Wire.h>
#include <LiquidCrystal_I2C.h>

LiquidCrystal_I2C lcd(0x27, 16, 2); // 0x27 ແມ່ນທີ່ຢູ່ I2C (ອາດແຕກຕ່າງ)

void setup() {
  lcd.init();          // ເລີ່ມການເຮັດວຽກ LCD
  lcd.backlight();     // ເປີດໄຟສ່ອງຈໍ
  lcd.setCursor(0, 0);
  lcd.print("Hello I2C LCD!");
  lcd.setCursor(0, 1);
  lcd.print("Arduino Uno");
}

void loop() {
}
```

---

## 🧠 **ຜົນດີຂອງການໃຊ້ I2C Module**

✅ ປະຫຍັດຂາ Arduino (ໃຊ້ແຕ່ 2 ຂາ)  
✅ ຕໍ່ງ່າຍ ແລະ ເຮັດວຽກໄດ້ທັນທີ  
✅ ສາມາດໃຊ້ກັບ LCD ຫຼາຍຈໍໄດ້ (ຜ່ານ I2C address)  
✅ ປັບຄວາມຄົມຊັດ ແລະ ໄຟສ່ອງຈໍໄດ້

---

## 📦 **ສະຫຼຸບງ່າຍໆ**

> 🔹 **I2C Serial Adapter Board Module** ແມ່ນອຸປະກອນຊ່ວຍໃຫ້ການເຊື່ອມຕໍ່ LCD 16x2 ກັບ Arduino ເປັນໄປຢ່າງງ່າຍດາຍ  
> 🔹 ໃຊ້ພຽງແຕ່ 4 ສາຍ (GND, VCC, SDA, SCL)  
> 🔹 ມີຄວາມຍືດຫຍຸ່ນ ແລະ ເຮັດໃຫ້ໂປຣເຈັກດູສະອາດຂຶ້ນ

---

**ຮູບອຸປະກອນແບບ Schematic Diagram:**
<img src="Pasted image 20251028233401.png"width="500">

17.7-segment display (Common Cathode +)
<img src="Pasted image 20251104131848.png"width="400">


---

## 🧾 **7-Segment Display ແມ່ນຫຍັງ?**

**7-Segment Display** ແມ່ນຈໍສະແດງຕົວເລກທີ່ປະກອບດ້ວຍ **LED 7 ດວງ** ແລະບາງຄັ້ງມີຈຸດທົດສະນິຍົມ (**DP**) ເພີ່ມອີກ 1 ດວງ.  
ແຕ່ລະດວງແທນດ້ວຍຕົວອັກສອນ **a, b, c, d, e, f, g**  
ເມື່ອເຮົາເປີດດວງໄຟແຕ່ລະຕຳແໜ່ງ ມັນຈະສະແດງເປັນຕົວເລກ 0–9 ຫຼືຕົວອັກສອນ A–F ໄດ້.

---

## 💡 **ປະເພດຂອງ 7-Segment Display**

1. **Common Cathode (CC)** 👉 ຂາລົບ (Cathode) ທັງໝົດຖືກຮວບເຂົ້າດ້ວຍກັນ ແລະຕໍ່ກັບ GND
    
    - ຈະເຮັດໃຫ້ຫຼັງຈາກນັ້ນປ້ອນ **5V (HIGH)** ໃຫ້ຂາ a, b, c... ເພື່ອເຮັດໃຫ້ດວງໄຟນັ້ນໆຕິດ
        
2. **Common Anode (CA)** 👉 ຂາບວກທັງໝົດຖືກຮວບເຂົ້າດ້ວຍກັນ ແລະຕໍ່ກັບ +5V
    
    - ຈະເຮັດໃຫ້ຂາ a, b, c... ຕ້ອງຮັບຄ່າ **LOW (0V)** ເພື່ອໃຫ້ດວງໄຟຕິດ
        

---

## ⚙️ **ຂາຂອງ 7-Segment Display (ປົກກະຕິ 10 Pins)**

|ຂາ|ຊື່|ໜ້າທີ່|
|---|---|---|
|1|e|ໄຟດວງ e|
|2|d|ໄຟດວງ d|
|3|DP|ຈຸດທົດສະນິຍົມ|
|4|c|ໄຟດວງ c|
|5|g|ໄຟດວງ g|
|6|Common Cathode|ຕໍ່ກັບ GND|
|7|b|ໄຟດວງ b|
|8|a|ໄຟດວງ a|
|9|f|ໄຟດວງ f|
|10|Common Cathode|ຕໍ່ກັບ GND|

> ⚠️ ບາງແບບອາດຈະຈັດຂາບໍ່ຄືກັນ — ກວດດ້ວຍ datasheet ກ່ອນໃຊ້

---

## 🔌 **ການຕໍ່ກັບ Arduino (Common Cathode)**

|7-Segment|Arduino Uno|ຜ່ານຕົວຕ້ານ (220Ω)|
|---|---|---|
|a|2|✅|
|b|3|✅|
|c|4|✅|
|d|5|✅|
|e|6|✅|
|f|7|✅|
|g|8|✅|
|DP|9|(ຖ້າຈໍາເປັນ)|
|CC|GND|❌ (ຕໍ່ກັບດິນໂດຍກົງ)|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
int a = 2;
int b = 3;
int c = 4;
int d = 5;
int e = 6;
int f = 7;
int g = 8;

void setup() {
  pinMode(a, OUTPUT);
  pinMode(b, OUTPUT);
  pinMode(c, OUTPUT);
  pinMode(d, OUTPUT);
  pinMode(e, OUTPUT);
  pinMode(f, OUTPUT);
  pinMode(g, OUTPUT);
}

void loop() {
  // ສະແດງເລກ 0
  digitalWrite(a, HIGH);
  digitalWrite(b, HIGH);
  digitalWrite(c, HIGH);
  digitalWrite(d, HIGH);
  digitalWrite(e, HIGH);
  digitalWrite(f, HIGH);
  digitalWrite(g, LOW);
  delay(1000);

  // ສະແດງເລກ 1
  digitalWrite(a, LOW);
  digitalWrite(b, HIGH);
  digitalWrite(c, HIGH);
  digitalWrite(d, LOW);
  digitalWrite(e, LOW);
  digitalWrite(f, LOW);
  digitalWrite(g, LOW);
  delay(1000);
}
```

---

## 🔍 **ຜົນລັບ**

👉 ຈໍ 7-segment ຈະສະແດງຕົວເລກ **0** ແລະຫຼັງຈາກ 1 ວິນາທີ ຈະປ່ຽນເປັນ **1**

---

## 🧠 **ສະຫຼຸບງ່າຍໆ**

> 🔹 **7-Segment Display (Common Cathode)** ແມ່ນອຸປະກອນສະແດງຕົວເລກດ້ວຍ LED 7 ດວງ  
> 🔹 ຕໍ່ຂາ Common ກັບ GND  
> 🔹 ຈຸດໄຟແຕ່ລະດວງໂດຍປ້ອນ HIGH ຈາກ Arduino  
> 🔹 ຕ້ອງໃຊ້ຕົວຕ້ານ (220Ω) ປ້ອງກັນກະແສເກີນ

---

**ຮູບອຸປະກອນແບບ Schematic Diagram:**
<img src="Pasted image 20251104131925.png"width="500">

18.4-Digit 7-Segment Display

<img src="Pasted image 20251028233646.png"width="500">

---

# 🔢 **4-Digit 7-Segment Display ແມ່ນຫຍັງ?**

**4-Digit 7-Segment Display** ແມ່ນໂຕສະແດງຜົນທີ່ມີ **4 ຕົວເລກ** (digit) ແຕ່ລະຕົວເລກມີ **7 segment** ສຳລັບສ້າງຮູບຕົວເລກ 0–9  
ບາງອັນຍັງມີ **ເມັດຈຸດ (dot)** ຢູ່ຂ້າງລຸ່ມ (DP)

ມັນເຫມາະສຳລັບ:

- ໂຊວເວລາ (clock)
    
- ນັບຈຳນວນ (counter)
    
- ວັດຄ່າ sensor
    
- ສະແດງອຸນຫະພູມ, ແຮງດັນ, ຄວາມໄວ
    

---

# 🛠️ **ວິທີເຮັດວຽກ**

4 digit ນີ້ **ບໍ່ໄດ້ສະແດງພ້ອມກັນທຸກຕົວຕະຫຼອດ**  
ແຕ່ Arduino ຈະເຮັດ “Multiplexing”  
👉 ສະຫຼັບສະແດງ digit 1 → digit 2 → digit 3 → digit 4 ດ້ວຍຄວາມໄວສູງ ຈົນເຮົາເບິ່ງເປັນແບບຕໍ່ເນື່ອງ

---

# 🔌 **ປະເພດ**

4-digit ແບ່ງເປັນ 2 ປະເພດ:

### **1) Common Cathode (CC)**

ຂາລົບ (–) ຂອງທຸກ digit ຖືກຮວບເຂົ້າກັນ

### **2) Common Anode (CA)**

ຂາບວກ (+) ຮວບກັນ

> ກ່ອນຕໍ່ວົງຈອນ ຕ້ອງຮູ້ກ່ອນວ່າເປັນ CC ຫຼື CA

---

# 🧩 **ຂາຂອງມັນ (ຕົວຢ່າງ)**

ຈະມີປະມານ 12–16 ຂາ:

### **Segment Pins (A–G, DP)**

- A
    
- B
    
- C
    
- D
    
- E
    
- F
    
- G
    
- DP (decimal point)
    

### **Digit Control Pins**

- D1 (digit 1)
    
- D2
    
- D3
    
- D4
    

Arduino ຕ້ອງເປີດ/ປິດ digit ແຕ່ລະອັນ

---

# 📚 **ຕົວຢ່າງໂຄດ Arduino (ໂຊວ “1234”)**

```cpp
int segA = 2;
int segB = 3;
int segC = 4;
int segD = 5;
int segE = 6;
int segF = 7;
int segG = 8;

int d1 = 9;
int d2 = 10;
int d3 = 11;
int d4 = 12;

void setup() {
  pinMode(segA, OUTPUT);
  pinMode(segB, OUTPUT);
  pinMode(segC, OUTPUT);
  pinMode(segD, OUTPUT);
  pinMode(segE, OUTPUT);
  pinMode(segF, OUTPUT);
  pinMode(segG, OUTPUT);

  pinMode(d1, OUTPUT);
  pinMode(d2, OUTPUT);
  pinMode(d3, OUTPUT);
  pinMode(d4, OUTPUT);
}

void showNumber(int num) {
  // ກຳນົດ segment ຕາມຕົວເລກ
  switch(num) {
    case 1: digitalWrite(segB,1); digitalWrite(segC,1); break;
    case 2: /* ... */ break;
    case 3: /* ... */ break;
    case 4: /* ... */ break;
  }
}

void loop() {
  digitalWrite(d1, LOW);
  showNumber(1);
  delay(5);

  digitalWrite(d1, HIGH);
  digitalWrite(d2, LOW);
  showNumber(2);
  delay(5);

  digitalWrite(d2, HIGH);
  digitalWrite(d3, LOW);
  showNumber(3);
  delay(5);

  digitalWrite(d3, HIGH);
  digitalWrite(d4, LOW);
  showNumber(4);
  delay(5);

  digitalWrite(d4, HIGH);
}
```

---

# 🎯 **ໃຊ້ທຳຫຍັງໄດ້?**

✅ ນາລິກາ (Clock)  
✅ ເຄື່ອງນັບ Counter  
✅ ມາດວັດອຸນຫະພູມ  
✅ ສະແດງຄ່າ sensor  
✅ ປ້ອນຂໍ້ມູນເປັນເລກ 4 ຕົວ

---

**ຮູບອຸປະກອນແບບ Schematic Diagram:**

<img src="Pasted image 20251028233747.png"width="500">


19.8x8 Dot Matrix display

<img src="Pasted image 20251028233824.png"width="500">

---

## 🧾 **8x8 Dot Matrix Display ແມ່ນຫຍັງ?**

**8x8 Dot Matrix** ແມ່ນຈໍທີ່ປະກອບດ້ວຍ **ຫຼອດ LED ທັງໝົດ 64 ດວງ (8 ແຖວ × 8 ຖັນ)**  
ແຕ່ລະດວງສາມາດເປີດຫຼືປິດໄດ້ເພື່ອສ້າງຮູບຮ່າງ ຫຼື ຕົວອັກສອນ.  
ຕົວຢ່າງ: ສາມາດສະແດງເປັນໂຕເລກ, ໂຕອັກສອນ, ຫຼື ຮູບໃບຫົວໜ້າຍິ້ມ 😊

---

## ⚙️ **ປະເພດຂອງ Dot Matrix**

ມີ 2 ປະເພດຫຼັກໆ:

1. **Common Cathode (CC)** → ຂາລົບ (GND) ຂອງແຕ່ລະແຖວຖືກຮວບໄວ້ຮ່ວມກັນ
    
2. **Common Anode (CA)** → ຂາບວກ (+V) ຂອງແຕ່ລະແຖວຖືກຮວບໄວ້ຮ່ວມກັນ
    

ໃນແຕ່ລະແບບຈະມີການເຊື່ອມຕໍ່ຂາທີ່ຕ່າງກັນນິດໜ່ອຍ, ແຕ່ຫຼັກການເຮັດວຽກເຫມືອນກັນ.

---

## 🧩 **ໂຄງສ້າງພາຍໃນ**

ຈໍຈະມີ:

- **8 ແຖວ (Row)** → ຄວບຄຸມຂອງແຕ່ລະແຖວ LED
    
- **8 ຖັນ (Column)** → ຄວບຄຸມຂອງແຕ່ລະຖັນ
    

ທັງໝົດຈະມີ **16 ຂາ** (8 ຂາສໍາລັບ Row + 8 ຂາສໍາລັບ Column)

ຫຼັກການເຮັດວຽກຄື:

> ເມື່ອເຮົາປ້ອນສັນຍານ “1” ໃຫ້ Column ແລະ “0” ໃຫ້ Row (ຫຼືກັນຂ້າມ ຂຶ້ນກັບປະເພດ) → ຫຼອດໃນຈຸດນັ້ນຈະຕິດ.

---

## 💡 **ຕົວຢ່າງການເຮັດວຽກ**

ຖ້າເຮົາຢາກໃຫ້ຕິດຫຼອດທີ່ແຖວ 2 ແລະຖັນ 3  
→ ເຮົາຈະສົ່ງ:

- Row 2 = LOW
    
- Column 3 = HIGH  
    (ໃນຮູບແບບ Common Cathode)
    

---

## ⚡ **ການຄວບຄຸມດ້ວຍ Arduino**

ເພາະຈໍມີຫຼອດທັງ 64 ດວງ ຈຶ່ງບໍ່ສາມາດໃຊ້ຂາ Arduino ໄດ້ທັງໝົດ  
ພວກເຮົາຈຶ່ງໃຊ້ **IC Driver MAX7219** ຫຼື **HT16K33** ເພື່ອຄວບຄຸມມັນງ່າຍຂຶ້ນ.

---

## 🔌 **ການຕໍ່ສາຍກັບ MAX7219**

|Pin MAX7219|Arduino|
|---|---|
|VCC|5V|
|GND|GND|
|DIN|11|
|CS|10|
|CLK|13|

> ຈາກນັ້ນເຮົາສາມາດຄວບຄຸມຈໍ 8x8 ໄດ້ດ້ວຍພຽງ 3 ຂາເທົ່ານັ້ນ!

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino ສະແດງໃບຫົວໜ້າຍິ້ມ 😊**

```cpp
#include <LedControl.h>

// DIN=11, CLK=13, CS=10
LedControl lc = LedControl(11, 13, 10, 1);

byte smile[8] = {
  B00111100,
  B01000010,
  B10100101,
  B10000001,
  B10100101,
  B10011001,
  B01000010,
  B00111100
};

void setup() {
  lc.shutdown(0, false);   // ເປີດຈໍ
  lc.setIntensity(0, 8);   // ຄວາມສວ່າງ 0–15
  lc.clearDisplay(0);      // ລ້າງຈໍ

  for (int i = 0; i < 8; i++) {
    lc.setRow(0, i, smile[i]);  // ສະແດງແຕ່ລະແຖວ
  }
}

void loop() {
}
```

---

## 🌈 **ຜົນດີຂອງ 8x8 Dot Matrix**

✅ ສາມາດສະແດງຮູບ, ຕົວເລກ, ແລະ ຕົວອັກສອນ  
✅ ຕໍ່ຮວມຫຼາຍຈໍເພື່ອເຮັດເປັນຈໍຍາວໄດ້ (ປ້າຍໄຟແຈ້ງເຕືອນ)  
✅ ໃຊ້ພຽງ 3 ຫຼື 4 ຂາກັບ MAX7219

---

## 🧠 **ສະຫຼຸບງ່າຍໆ**

> 🔹 **8x8 Dot Matrix** ແມ່ນຈໍສະແດງທີ່ມີ 64 ຫຼອດ LED  
> 🔹 ໃຊ້ຫຼັກການສະຫຼັບສັນຍານ Row/Column ເພື່ອໃຫ້ໄຟຕິດໃນຈຸດທີ່ຕ້ອງການ  
> 🔹 ເມື່ອໃຊ້ຄູ່ກັບ **MAX7219** ຈະຄວບຄຸມໄດ້ງ່າຍ ແລະ ປະຫຍັດຂາ Arduino

---

**ຮູບອຸປະກອນແບບ Schematic Diagram:
<img src="Pasted image 20251028233916.png"width="500">

# 📡 Sensors & Input Modules

20.Temperature and humidity sensor (DHT11)

<img src="Pasted image 20251028234034.png"width="500">

---

## 🌡️ **DHT11 ແມ່ນຫຍັງ?**

**DHT11** ແມ່ນຕົວຈັບຄ່າ **ອຸນຫະພູມ (Temperature)** ແລະ **ຄວາມຊຸ່ມ (Humidity)** ໃນອາກາດ  
ມັນແມ່ນຊິບທີ່ນິຍົມໃຊ້ໃນໂຄງການ Arduino, ESP32, Raspberry Pi ແລະອຸປະກອນ IoT ຕ່າງໆ.

---

## ⚙️ **ຄຸນນະສົມບັດທີ່ສໍາຄັນ**

|ລາຍການ|ຄ່າ|
|---|---|
|ຊ່ວງອຸນຫະພູມ|0°C – 50°C|
|ຄວາມຖືກຕ້ອງອຸນຫະພູມ|±2°C|
|ຊ່ວງຄວາມຊຸ່ມ|20% – 90% RH|
|ຄວາມຖືກຕ້ອງຄວາມຊຸ່ມ|±5% RH|
|ໄຟທີ່ໃຊ້|3V – 5V DC|
|ອັດຕາການອ່ານຂໍ້ມູນ|ປະມານ 1 ຄັ້ງ/ວິນາທີ|

---

## 🔌 **ການຕໍ່ຂາກັບ Arduino**

DHT11 ມີ 4 ຂາ (ບາງແບບມີ 3 ຂາ ຂຶ້ນກັບຮູບແບບ):

|ຂາ|ຊື່|ໜ້າທີ່|
|---|---|---|
|1|VCC|ໃຫ້ໄຟ 3.3V ຫຼື 5V|
|2|DATA|ຂາສົ່ງຂໍ້ມູນອອກໄປຫາ Arduino|
|3|NC|(ບໍ່ໃຊ້)|
|4|GND|ຕໍ່ກັບດິນ|

> 💡 ໃສ່ **resistor 10kΩ** ລະຫວ່າງ VCC ແລະ DATA ເພື່ອຊ່ວຍດຶງສັນຍານ (pull-up resistor)

---

## 🧩 **ການຕໍ່ກັບ Arduino Uno**

|DHT11 Pin|Arduino Uno|
|---|---|
|VCC|5V|
|DATA|Pin 2|
|GND|GND|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino ອ່ານຄ່າອຸນຫະພູມແລະຄວາມຊຸ່ມ**

```cpp
#include "DHT.h"

#define DHTPIN 2      // ຂາທີ່ຕໍ່ກັບ DATA
#define DHTTYPE DHT11 // ລະບຸຊື່ເ຋ັນເຊີ

DHT dht(DHTPIN, DHTTYPE);

void setup() {
  Serial.begin(9600);
  dht.begin();
}

void loop() {
  float humidity = dht.readHumidity();
  float temperature = dht.readTemperature();

  Serial.print("Humidity: ");
  Serial.print(humidity);
  Serial.print(" %  |  ");

  Serial.print("Temperature: ");
  Serial.print(temperature);
  Serial.println(" °C");

  delay(2000); // ອ່ານຄ່າທຸກ 2 ວິນາທີ
}
```

---

## 🧠 **ຫຼັກການເຮັດວຽກ**

- ສ່ວນຄວາມຊຸ່ມຈັບຈາກ **capacitive humidity sensor**
    
- ສ່ວນອຸນຫະພູມຈັບຈາກ **thermistor**
    
- ຊິບພາຍໃນຈະແປງຄ່າເປັນດິຈິຕອນ ແລະສົ່ງອອກຜ່ານ DATA pin ໃຫ້ Arduino
    

---

## 🌈 **ຂໍ້ດີ**

✅ ໃຊ້ງ່າຍ  
✅ ລາຄາຖືກ  
✅ ບໍ່ຈໍາເປັນການຕັ້ງຄ່າຊັບຊ້ອນ  
✅ ເໝາະສໍາລັບໂຄງການອາກາດ, Smart Home, ແລະ IoT

---

## ⚠️ **ຂໍ້ຈໍາກັດ**

❌ ບໍ່ຖືກຕ້ອງຫຼາຍ (ທົ່ວໄປ ±5%)  
❌ ອ່ານຄ່າໄດ້ຊ້າ (1 ຄັ້ງ/ວິນາທີ)  
❌ ບໍ່ເໝາະສໍາລັບສະພາບອາກາດທີ່ຊຸ່ມຫຼາຍ

---

## 🔍 **ສະຫຼຸບງ່າຍໆ**

> 🌡️ **DHT11** ແມ່ນຕົວຈັບຄ່າອຸນຫະພູມແລະຄວາມຊຸ່ມ  
> 🔌 ຕໍ່ງ່າຍ ໃຊ້ພຽງ 1 ຂາຂໍ້ມູນ (DATA)  
> 🧩 ສາມາດໃຊ້ກັບ Arduino, ESP32, Raspberry Pi  
> ✅ ເໝາະສໍາລັບໂຄງການຝຶກຮຽນ ຫຼື ສ້າງສະຖານີວັດອາກາດນ້ອຍໆ

---

**ຮູບອຸປະກອນແບບ Schematic Diagram:
<img src="Pasted image 20251028234120.png"width="500">

21.LM35 Temperature Sensor

<img src="Pasted image 20251028234257.png"width="300">

---

## 🌡️ **LM35 Temperature Sensor ແມ່ນຫຍັງ?**

**LM35** ແມ່ນເ຋ັນເຊີວັດອຸນຫະພູມແບບ **Analog Sensor** ທີ່ສາມາດວັດອຸນຫະພູມໄດ້ຢ່າງແມ່ນຍຳ.  
ມັນຈະໃຫ້ຄ່າສັນຍານແຮງດັນອອກ (Voltage Output) ຕາມຄ່າອຸນຫະພູມທີ່ວັດໄດ້.

---

## ⚙️ **ຄຸນສົມບັດທົ່ວໄປ**

|ລາຍການ|ລາຍລະອຽດ|
|---|---|
|ຊ່ວງອຸນຫະພູມ|0°C – 150°C|
|ຄວາມແມ່ນຍຳ|±0.5°C|
|ຄ່າສັນຍານອອກ|10 mV / °C (ເຊັ່ນ 25°C = 250 mV)|
|ໄຟເຂົ້າ|4V – 20V|
|ປະເພດສັນຍານ|Analog Output|

---

## 🧩 **ຂາຂອງ LM35**

|ຂາ|ຊື່|ໜ້າທີ່|
|---|---|---|
|1|VCC|ໃຫ້ໄຟ 5V ຫຼື 3.3V|
|2|VOUT|ຂາອອກສັນຍານ (Analog Output)|
|3|GND|ຕໍ່ກັບ Ground|

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|LM35 Pin|Arduino Pin|
|---|---|
|VCC|5V|
|VOUT|A0|
|GND|GND|

---

## 🧠 **ຫຼັກການເຮັດວຽກ**

> LM35 ຈະສົ່ງຄ່າແຮງດັນອອກຕາມອຸນຫະພູມ:
> 
> - 0°C = 0.00V
>     
> - 25°C = 0.25V
>     
> - 100°C = 1.00V
>     

Arduino ຈະອ່ານຄ່າ Analog ຈາກ LM35 ແລ້ວແປງເປັນອຸນຫະພູມໃນ °C.

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
int sensorPin = A0; 
float temp;  

void setup() {
  Serial.begin(9600);
}

void loop() {
  int sensorValue = analogRead(sensorPin);     // ອ່ານຄ່າ Analog
  float voltage = sensorValue * (5.0 / 1023.0); // ແປງເປັນໄຟຟ້າ
  temp = voltage * 100;                        // 10mV = 1°C
  Serial.print("Temperature: ");
  Serial.print(temp);
  Serial.println(" °C");
  delay(1000);
}
```

---

## 🔍 **ຜົນລັບ**

- ຄ່າອຸນຫະພູມຈະຖືກສະແດງອອກໃນ Serial Monitor
    
- ຕົວຢ່າງ:
    
    ```
    Temperature: 28.50 °C
    Temperature: 29.00 °C
    ```
    

---

## 💡 **ຈຸດເດັ່ນ**

- ໃຊ້ງານງ່າຍ ແລະ ແມ່ນຍຳ
    
- ບໍ່ຕ້ອງການການປັບແຕ່ງ
    
- ເໝາະສຳລັບໂຄງການວັດອຸນຫະພູມທົ່ວໄປ
    

---

22.Tilt sensor (x2)
<img src="Pasted image 20251028234403.png"width="500">

---

## ⚖️ **Tilt Sensor ແມ່ນຫຍັງ?**

**Tilt Sensor** ແມ່ນອຸປະກອນສັນຍານທີ່ເຮັດວຽກເພື່ອກວດສອບມຸມການເງື່ອນໄຂ ຫຼື **ການເເງ່ງ**

- ເມື່ອ Tilt Sensor ເເງ່ເກີນມາກເຮັດໃຫ້ສັນຍານອອກ (HIGH)
    
- ເມື່ອຢູ່ຕົງ ຫຼື ບໍ່ເເງ່ ສັນຍານຈະເປັນ (LOW)
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

- Voltage: 3V – 5V
    
- Type: Digital Output (HIGH/LOW)
    
- ຂนาด: ຂອງເຫຼັ້ນອຸປະກອນນ້ອຍ, ເຮັດໃຫ້ສາມາດເຊື່ອມກັບ Arduino ໄດ້ງ່າຍ
    

---

## 🧩 **ຂາຂອง Tilt Sensor**

ໂຕຢ່າງ Tilt Sensor 2 ขา:

|ຂາ|ຊື່|ໜ້າທີ່|
|---|---|---|
|1|VCC|ໄຟ 5V ຫຼື 3.3V|
|2|GND / OUT|ຂາອອກ Digital → ຕໍ່ເຂົ້າ Arduino|

> ເຫັນໄດ້ວ່າ Tilt Sensor ສາມາດໃຊ້ເພື່ອກວດມຸມ ການເເງ່ ຫຼື ການຫຼວງໄປມາ ເຫມາກັບໂຄງການ **alarm, robot balance, security switch**

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|Tilt Sensor Pin|Arduino Pin|
|---|---|
|VCC|5V|
|OUT|D2 (Digital)|
|GND|GND|

> 💡 ບາງເທື່ອ ອາດເປັນ Pull-down resistor 10kΩ ເພື່ອໃຫ້ຄ່າ LOW ຈາກ Sensor ຢ່າງແນ່ນອນ

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
int tiltPin = 2;  // ຂາທີ່ເຊື່ອມ Tilt Sensor
int tiltState = 0;

void setup() {
  pinMode(tiltPin, INPUT);
  Serial.begin(9600);
}

void loop() {
  tiltState = digitalRead(tiltPin); // ອ່ານຄ່າອອກ HIGH/LOW

  if (tiltState == HIGH) {
    Serial.println("Tilt detected!");
  } else {
    Serial.println("No tilt.");
  }

  delay(500);
}
```

---

## 🔍 **ຜົນລັບ**

- HIGH → Tilt / ເເງ່
    
- LOW → ບໍ່ເເງ່ / ຢູ່ຕົງ
    
- ສາມາດໃຊ້ກັບ **Arduino, ESP32** ເພື່ອເຮັດ **alarm, robot balance, safety switch**
    

---

## 🌈 **ຂໍ້ດີ**

✅ ອ່ານຄ່າງ່າຍ  
✅ ແມ່ນ Digital Sensor → ບໍ່ຕ້ອງປັບຄ່າ  
✅ ຂາຂອນ້ອຍ → ຕໍ່ໄດ້ຫຼາຍກັບ Arduino

---

**ຮູບອຸປະກອນແບບ Schematic Diagram:
<img src="Pasted image 20251028234507.png"width="500">
23.Photoresistor (LDRs x3)

<img src="Pasted image 20251028234745.png"width="500">

---

## 💡 **Photoresistor (LDR) ແມ່ນຫຍັງ?**

**Photoresistor** ຫຼື **LDR (Light Dependent Resistor)** ແມ່ນຕົວຕ້ານຄ່າຄວາມຕໍ່ຕ້ານຂອງອິນໄລຄ່າສາງສີ (Resistance)**

- ເມື່ອມີແສງສູງ → Resistance ຈະນ້ອຍ
    
- ເມື່ອມີແສງນ້ອຍ / ມືດ → Resistance ຈະຫຼາຍ
    

> ສາມາດນຳໃຊ້ເພື່ອກວດສອບຄວາມສວ່າງ, ຕັ້ງ light sensor, automatic night light, alarm, robot vision ฯลฯ

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Resistance ພາຍໃນ|1 kΩ – 10 MΩ (ຂື້ນກັບຄວາມສວ່າງ)|
|Voltage ໃຊ້|3V – 5V|
|ປະເພດ|Analog Sensor|

---

## 🧩 **ການຕໍ່ສາຍງ່າຍໆ ກັບ Arduino**

LDR ຈະເຊື່ອມເປັນ **Voltage Divider** ກັບ Resistor ຄ່າສ່ວນໃດໜຶ່ງ (ເຊັ່ນ 10kΩ)

**ໂຄງສ້າງ:**

```
5V ── LDR ── A0 ── Resistor ── GND
```

- A0 → Analog Input Arduino
    
- ຄ່າອະນາຄານຈະອ່ານຄ່າ Analog ຕາມແສງ
    

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino ອ່ານ LDR**

```cpp
int LDRPin = A0; 
int LDRValue = 0;

void setup() {
  Serial.begin(9600);
}

void loop() {
  LDRValue = analogRead(LDRPin);  // ອ່ານຄ່າ LDR
  Serial.print("LDR Value: ");
  Serial.println(LDRValue);

  delay(500);
}
```

> 💡 ຄ່າອອກຈາກ `analogRead()` ຈະເປັນ 0–1023
> 
> - 0 → ແສງສວ່າງສູງ
>     
> - 1023 → ມືດ / ແສງນ້ອຍ
>     

---

## 🌈 **ຂໍ້ດີ**

✅ ເປັນ Analog Sensor → ອ່ານໄດ້ຕໍ່ເນື່ອງ  
✅ ເໝາະສໍາລັບ Light Detection, Automatic Lighting, Alarm  
✅ ຂານ້ອຍ, ຕໍ່ງ່າຍ ແລະ ຖືກ

---

## 🔍 **ຫຼັກການເຮັດວຽກ**

1. LDR ແມ່ນຕົວຕ້ານຄ່າຄວາມຕໍ່ຕ້ານທີ່ພາຍໃນຈະປ່ຽນຕາມແສງ
    
2. ເຊື່ອມເປັນ **Voltage Divider** ເພື່ອໄດ້ຄ່າ Analog
    
3. Arduino ຈະອ່ານແລະແປງເປັນຄ່າຄວາມສວ່າງ/ແສງ
    

---

24.PIR sensor
<img src="Pasted image 20251028234823.png"width="500">

---

## 👀 **PIR Sensor ແມ່ນຫຍັງ?**

**PIR Sensor** ຫຼື **Passive Infrared Sensor** ແມ່ນອຸປະກອນກວດສອບ **ການເຄື່ອນໄຫວຂອງຄົນ ຫຼື ສັດ** ຜ່ານການຈັບອາກາກໄຟໄຫຼເຊິ່ງມາຈາກແສງອີນເຟຣດ (Infrared Radiation) ທີ່ສ່ວນຮ່າງກາຍປ່ຽນໄດ້.

- **Passive** ຫຼັກແມ່ນວ່າ Sensor ບໍ່ສົ່ງແສງ IR ໃຫ້ຄົນເພື່ອກວດສອບ, ມັນຈະພຽງແຕ່ອ່ານແສງ IR ທີ່ມາຈາກສັດ/ຄົນ.
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ລາຍລະອຽດ|
|---|---|
|Voltage ໃຊ້|3.3V – 5V|
|Output|Digital (HIGH/LOW)|
|Detection Range|~5m – 7m|
|Detection Angle|~110°|
|Response Time|~2s – 5s|

---

## 🧩 **ຂາຂອງ PIR Sensor**

|ຂາ|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|VCC|ໃຫ້ໄຟ 5V|
|OUT|Output|Digital Signal → HIGH = Motion Detected, LOW = No Motion|
|GND|Ground|ຕໍ່ກັບ GND Arduino|

> ບາງເທື່ອມີເປັນ **3 pins** ບໍ່ມີ Jumper ເພີ່ມ

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|PIR Pin|Arduino Pin|
|---|---|
|VCC|5V|
|OUT|D2 (Digital)|
|GND|GND|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
int pirPin = 2;  // ຂາທີ່ເຊື່ອມ PIR
int pirState = 0;

void setup() {
  pinMode(pirPin, INPUT);
  Serial.begin(9600);
}

void loop() {
  pirState = digitalRead(pirPin);

  if (pirState == HIGH) {
    Serial.println("Motion Detected!");
  } else {
    Serial.println("No Motion.");
  }

  delay(500);
}
```

---

## 🔍 **ຜົນລັບ**

- HIGH → ເຄື່ອນໄຫວຖືກຈັບ
    
- LOW → ບໍ່ມີການເຄື່ອນໄຫວ
    
- ເຫມາະສໍາລັບ **Alarm, Auto Light, Security System**
    

---

## 🌈 **ຂໍ້ດີ**

✅ ອ່ານຄ່າ Digital ງ່າຍ  
✅ ເໝາະສໍາລັບ Security / Automation  
✅ ມີ Detection Range ສູງ (~5–7m)

---

25.Ultrasonic module

<img src="Pasted image 20251028235032.png"width="500">

---

## 🌀 **Ultrasonic Module ແມ່ນຫຍັງ?**

**Ultrasonic Module** ຫຼື **HC-SR04** ແມ່ນອຸປະກອນສັນຍານດິຈິຕອນ ສາມາດວັດ **ລະດັບລະດັບອອກຈາກອະຈາງຫຼັກໄວ້ໄດ້** (Distance) ຜ່ານການສົ່ງສັນຍານ **Ultrasonic Sound Waves**

- ສົ່ງຄຳສັນຍານຄວາມຖືກຕ້ອງສູງສຸດ (~40 kHz)
    
- ເມື່ອສັນຍານສົ່ງອອກ → ກະທົບກັບວັດຖຸ → ຮັບກັບ Echo → ຄ່າລະດັບລະດັບອອກ
    

> ເປັນ Sensor ທີ່ນິຍົມໃຊ້ໃນ **robot obstacle detection, distance measurement, automatic door, water level sensing**

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|5V DC|
|Current|15 mA|
|Measuring Range|2 cm – 400 cm|
|Accuracy|±3 mm|
|Frequency|40 kHz|

---

## 🧩 **ຂາຂອง HC-SR04**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|VCC|ໃຫ້ 5V|
|Trig|Trigger|ສົ່ງຄຳສັນຍານ Ultrasound|
|Echo|Echo|ຮັບຄຳສັນຍານ Ultrasound|
|GND|Ground|ຕໍ່ກັບ GND Arduino|

> 💡 **Trigger** → ສົ່ງ Pulse 10 µs → Module ຈະສົ່ງ Ultrasonic  
> **Echo** → Module ສົ່ງ HIGH Pulse → Arduino ຈະອ່ານເວລາ (duration) → ຄຳນວນລະດັບ

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|HC-SR04 Pin|Arduino Pin|
|---|---|
|VCC|5V|
|Trig|D9|
|Echo|D10|
|GND|GND|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino ອ່ານ Ultrasonic Module**

```cpp
const int trigPin = 9;
const int echoPin = 10;
long duration;
float distance;

void setup() {
  pinMode(trigPin, OUTPUT);
  pinMode(echoPin, INPUT);
  Serial.begin(9600);
}

void loop() {
  digitalWrite(trigPin, LOW);
  delayMicroseconds(2);
  
  digitalWrite(trigPin, HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin, LOW);
  
  duration = pulseIn(echoPin, HIGH); // ອ່ານ Pulse
  distance = (duration * 0.034) / 2; // ຄຳນວນເປັນ cm
  
  Serial.print("Distance: ");
  Serial.print(distance);
  Serial.println(" cm");
  
  delay(500);
}
```

---

## 🔍 **ຜົນລັບ**

- `distance` → ຄ່າລະດັບລະດັບອອກໃນ cm
    
- ສາມາດນໍາໃຊ້ເພື່ອ **obstacle detection, robot navigation, automatic water level**
    

---

## 🌈 **ຂໍ້ດີ**

✅ ລະດັບຄ່າຖືກ  
✅ ໄກ່ການອ່ານງ່າຍ  
✅ ເໝາະສໍາລັບໂຄງການ Robot & Automation

---

26.Sound Sensor
<img src="Pasted image 20251028235130.png"width="500">

---

## 🎵 **Sound Sensor ແມ່ນຫຍັງ?**

**Sound Sensor** ແມ່ນອຸປະກອນທີ່ສາມາດຈັບ **ເສຍງ** ຫຼື **vibration ຂອງສຽງ** ທີ່ມາຈາກສິ່ງຕ່າງໆ ແລະແປງເປັນ **Digital Signal (HIGH/LOW)** ຫຼື **Analog Value** ເພື່ອ Arduino ອ່ານ.

- ຕົວຢ່າງສຳລັບ: clap detection, sound level measurement, voice-activated project
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|3.3V – 5V|
|Output|Digital (HIGH/LOW) & Analog|
|Sensitivity|Adjustable via potentiometer|
|Module Type|KY-038 / LM393 sound sensor|

---

## 🧩 **ຂາຂອง Sound Sensor Module**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|VCC|ໄຟ 5V|
|GND|GND|Ground|
|DO|Digital Output|HIGH → sound detected, LOW → no sound|
|AO|Analog Output|0–5V (ຄ່າສຽງທີ່ຈະອ່ານ)|

> ບາງເທື່ອ ມີ potentiometer ຢູ່ເພື່ອປັບ **sensitivity**

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|Sensor Pin|Arduino Pin|
|---|---|
|VCC|5V|
|GND|GND|
|DO|D3 (Digital)|
|AO|A0 (Analog)|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino (Digital Output)**

```cpp
int soundPin = 3; 
int soundState = 0;

void setup() {
  pinMode(soundPin, INPUT);
  Serial.begin(9600);
}

void loop() {
  soundState = digitalRead(soundPin); 

  if (soundState == HIGH) {
    Serial.println("Sound Detected!");
  } else {
    Serial.println("No Sound.");
  }

  delay(200);
}
```

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino (Analog Output)**

```cpp
int soundAnalogPin = A0; 
int soundValue = 0;

void setup() {
  Serial.begin(9600);
}

void loop() {
  soundValue = analogRead(soundAnalogPin); // 0-1023
  Serial.print("Sound Level: ");
  Serial.println(soundValue);

  delay(200);
}
```

---

## 🔍 **ຜົນລັບ**

- Digital → HIGH/LOW → ຈັບວ່າມີเสียงຫຼືບໍ່
    
- Analog → ວັດຄວາມສູງຂອງเสียง
    
- ເຫມາສໍາລັບ **clap switch, sound level indicator, voice-activated system**
    

---

## 🌈 **ຂໍ້ດີ**

✅ ອ່ານຄ່າ Digital/Analog ງ່າຍ  
✅ Sensitivity ປັບໄດ້  
✅ ເໝາະສໍາລັບ automation ແລະ project ທີ່ເຊື່ອງກັບเสียง

---

27.Water sensor

<img src="Pasted image 20251028235256.png"width="500">

---

## 💧 **Water Sensor ແມ່ນຫຍັງ?**

**Water Sensor** ແມ່ນອຸປະກອນທີ່ສາມາດກວດສອບ **ການມີນ້ຳ / ລະດັບນ້ຳ** ແລະສາມາດສົ່ງ **Signal Digital / Analog** ໄປຫາ Arduino.

- ຕົວຢ່າງ: water leak detection, rain sensor, water level alarm
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|3.3V – 5V|
|Output|Digital (HIGH/LOW) & Analog|
|Sensitivity|Adjustable via potentiometer|
|Type|Water Level / Water Detection Module|

---

## 🧩 **ຂາຂອง Water Sensor Module**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|VCC|ໄຟ 5V|
|GND|GND|Ground|
|DO|Digital Output|HIGH → Water detected, LOW → No water|
|AO|Analog Output|0–5V → level of water conductivity|

> ບາງເທື່ອມີ **potentiometer** ໃຫ້ປັບ sensitivity ຄວາມຕັ້ງຄ່າ detection

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|Sensor Pin|Arduino Pin|
|---|---|
|VCC|5V|
|GND|GND|
|DO|D4 (Digital)|
|AO|A1 (Analog)|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino (Digital Output)**

```cpp
int waterPin = 4; 
int waterState = 0;

void setup() {
  pinMode(waterPin, INPUT);
  Serial.begin(9600);
}

void loop() {
  waterState = digitalRead(waterPin);

  if (waterState == HIGH) {
    Serial.println("Water Detected!");
  } else {
    Serial.println("No Water.");
  }

  delay(500);
}
```

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino (Analog Output)**

```cpp
int waterAnalogPin = A1; 
int waterLevel = 0;

void setup() {
  Serial.begin(9600);
}

void loop() {
  waterLevel = analogRead(waterAnalogPin); // 0-1023
  Serial.print("Water Level Value: ");
  Serial.println(waterLevel);

  delay(500);
}
```

---

## 🔍 **ຜົນລັບ**

- Digital → HIGH/LOW → ຈັບວ່າມີນ້ຳຫຼືບໍ່
    
- Analog → ອ່ານຄ່າ conductivity / water level
    
- ເຫມາສໍາລັບ **water leak alarm, rain detection, water level monitoring**
    

---

## 🌈 **ຂໍ້ດີ**

✅ ອ່ານຄ່າ Digital/Analog ງ່າຍ  
✅ Sensitivity ປັບໄດ້  
✅ ເໝາະສໍາລັບ **Automation & Safety Project**

---

28.Flame sensor
<img src="Pasted image 20251028235339.png"width="500">

---

## 🔥 **Flame Sensor ແມ່ນຫຍັງ?**

**Flame Sensor** ແມ່ນອຸປະກອນທີ່ສາມາດຈັບ **ສະພາບແສງໄຟຟ້າ (Infrared Light) ຈາກການໄຟໄໝເພື່ອກວດສອບເພື່ອກັນໄຟໄໝ**

- ສາມາດນຳໃຊ້ໃນ **fire alarm, robot fire detection, safety system**
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|3.3V – 5V|
|Output|Digital (HIGH/LOW) & Analog|
|Detection Range|~0.1 – 1 m|
|Detection Angle|~60°|

---

## 🧩 **ຂາຂອง Flame Sensor Module**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|VCC|ໃຫ້ 5V|
|GND|GND|Ground|
|DO|Digital Output|HIGH → Flame Detected, LOW → No Flame|
|AO|Analog Output|0–5V → Flame intensity level|

> ບາງເທື່ອມີ **potentiometer** ເພື່ອປັບ sensitivity detection

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|Sensor Pin|Arduino Pin|
|---|---|
|VCC|5V|
|GND|GND|
|DO|D5 (Digital)|
|AO|A2 (Analog)|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino (Digital Output)**

```cpp
int flamePin = 5; 
int flameState = 0;

void setup() {
  pinMode(flamePin, INPUT);
  Serial.begin(9600);
}

void loop() {
  flameState = digitalRead(flamePin);

  if (flameState == HIGH) {
    Serial.println("Flame Detected!");
  } else {
    Serial.println("No Flame.");
  }

  delay(500);
}
```

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino (Analog Output)**

```cpp
int flameAnalogPin = A2;
int flameLevel = 0;

void setup() {
  Serial.begin(9600);
}

void loop() {
  flameLevel = analogRead(flameAnalogPin); // 0-1023
  Serial.print("Flame Intensity: ");
  Serial.println(flameLevel);

  delay(500);
}
```

---

## 🔍 **ຜົນລັບ**

- Digital → HIGH/LOW → ຈັບວ່າມີໄຟໄໝຫຼືບໍ່
    
- Analog → ວັດຄ່າ intensity ຂອງ flame
    
- ເຫມາສໍາລັບ **fire alarm, safety detection, robot fire sensing**
    

---

## 🌈 **ຂໍ້ດີ**

✅ ອ່ານຄ່າ Digital/Analog ງ່າຍ  
✅ Sensitivity ປັບໄດ້  
✅ Detection range ~1 m → ເໝາະສໍາລັບ automation & safety project

---

29.RFID module

<img src="Pasted image 20251028235451.png"width="500">

---

## 📛 **RFID Module ແມ່ນຫຍັງ?**

**RFID Module** ແມ່ນອຸປະກອນທີ່ໃຊ້ສົ່ງແລະຮັບ **Radio Frequency Signal** ເພື່ອຈຳແທນ **ID card / RFID tag** ແລະເກັບຂໍ້ມູນຂອງ tag ລົງຄອມພິວເຕີ/Arduino.

- ສາມາດນຳໃຊ້ໃນ **Access Control, Attendance System, Inventory Tracking**
    

> ໂຄງການນິຍົມ: RFID reader (RC522) + RFID card / key fob

---

## ⚙️ **ຄຸນນະສົມບັດ (RC522 Module)**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|3.3V – 5V|
|Communication|SPI Interface|
|Operating Frequency|13.56 MHz|
|Read Range|~2–5 cm|
|Protocol|ISO/IEC 14443A/MIFARE|

---

## 🧩 **ຂາຂອง RC522 Module**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|VCC|3.3V – 5V|
|GND|GND|Ground|
|RST|Reset|Reset module|
|SDA|SS|SPI Slave Select|
|MOSI|Master Out|Data to module|
|MISO|Master In|Data from module|
|SCK|Clock|SPI Clock|

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno (SPI)**

|RC522 Pin|Arduino Pin|
|---|---|
|VCC|3.3V|
|GND|GND|
|RST|D9|
|SDA|D10|
|MOSI|D11|
|MISO|D12|
|SCK|D13|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino (ອ່ານ Tag ID)**

```cpp
#include <SPI.h>
#include <MFRC522.h>

#define SS_PIN 10
#define RST_PIN 9

MFRC522 mfrc522(SS_PIN, RST_PIN);

void setup() {
  Serial.begin(9600);
  SPI.begin();
  mfrc522.PCD_Init();
  Serial.println("Scan your RFID card:");
}

void loop() {
  if (!mfrc522.PICC_IsNewCardPresent()) return;
  if (!mfrc522.PICC_ReadCardSerial()) return;

  Serial.print("Card UID: ");
  for (byte i = 0; i < mfrc522.uid.size; i++) {
    Serial.print(mfrc522.uid.uidByte[i] < 0x10 ? "0" : "");
    Serial.print(mfrc522.uid.uidByte[i], HEX);
    Serial.print(" ");
  }
  Serial.println();
  mfrc522.PICC_HaltA();
}
```

---

## 🔍 **ຜົນລັບ**

- Arduino ຈະອ່ານ **UID ของ Tag**
    
- ສາມາດນໍາໃຊ້ສໍາລັບ **Access Control, Attendance System, Inventory**
    

---

## 🌈 **ຂໍ້ດີ**

✅ อ่าน Tag ID ງ່າຍ  
✅ ใช้ SPI Interface → ຄ່ານ້ອຍ, Response เร็ว  
✅ เหมาะกับ **security & automation projects**

---

30.RFID tag
<img src="Pasted image 20251104135810.png"width="500">

---

## 🆔 **RFID Tag ແມ່ນຫຍັງ?**

**RFID Tag** ແມ່ນອຸປະກອນໃນຮູບແບບ **Card, Key Fob, Sticker** ຫຼື Chip ຂ້າງໃນ ທີ່ສາມາດ **เก็บข้อมูล ID แบบไม่ต้องใช้สาย**

- RFID Tag ຈະສົ່ງ **รหัสประจำตัว (UID)** ໄປໃຫ້ **RFID Reader**
    
- Tag ຈະ **ບໍ່ຕ້ອງໃຊ້ແບັດເຕີລີ້** (Passive Tag) ເພາະ Reader ຈະຈ່າຍພະລັງງານແບບໄຟຟ້າກະແສຕ່ຳ
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

| ລາຍການ       | ຄ່າ                             |
| ------------ | ------------------------------- |
| Type         | Passive / Active (ມີແບັດເຕີລີ່) |
| Frequency    | 13.56 MHz (MIFARE)              |
| Read Range   | 2–5 cm (Passive)                |
| Data Storage | UID / small memory              |
| Shape        | Card, Key Fob, Sticker          |

---

## 🧩 **ວິທີໃຊ້ RFID Tag ກັບ Module RC522**

1. ນຳ Tag ມາ **ສະແກນ** ໃດ້ **RFID Reader (RC522)**
    
2. Reader ຈະອ່ານ **UID ຂອງ Tag**
    
3. Arduino ຈະປະມວນຜົນ **UID** → ເຮັດ Automation / Access Control
    

---

## 💻 **ตัวอย่างการใช้งาน**

```cpp
#include <SPI.h>
#include <MFRC522.h>

#define SS_PIN 10
#define RST_PIN 9

MFRC522 mfrc522(SS_PIN, RST_PIN);

void setup() {
  Serial.begin(9600);
  SPI.begin();
  mfrc522.PCD_Init();
  Serial.println("Scan your RFID Tag:");
}

void loop() {
  if (!mfrc522.PICC_IsNewCardPresent()) return;
  if (!mfrc522.PICC_ReadCardSerial()) return;

  Serial.print("Tag UID: ");
  for (byte i = 0; i < mfrc522.uid.size; i++) {
    Serial.print(mfrc522.uid.uidByte[i] < 0x10 ? "0" : "");
    Serial.print(mfrc522.uid.uidByte[i], HEX);
    Serial.print(" ");
  }
  Serial.println();
  mfrc522.PICC_HaltA();
}
```

> ເມື່ອ Arduino ອ່ານ Tag → Serial Monitor ຈະສະແດງ **UID ຂອງ Tag**

---

## 🔍 **ປະໂຫຍດຂອງ RFID Tag**

- ໃຊ້ໃນການ **ເປີດປະຕູອັດຕະໂນມັດ**
    
- ໃຊ້ໃນ **attendance system / inventory tracking**
    
- ເຮັດວຽກແບບ **ບໍ່ຕ້ອງສຳພັດ** ແລະ **ອ່ານໄດ້ໄວ**
    

---

31.Infrared receiver
<img src="Pasted image 20251028235710.png"width="500">

---

## 📡 **Infrared Receiver ແມ່ນຫຍັງ?**

**IR Receiver** ຫຼື **Infrared Receiver Module** ແມ່ນອຸປະກອນທີ່ສາມາດຮັບ **ສັນຍານ Infrared (IR) ຈາກ Remote Control / IR LED** ແລະແປງເປັນ **Digital Signal** ທີ່ Arduino ອ່ານໄດ້

- ມັນສາມາດນໍາໃຊ້ໃນ **TV Remote Control, Robot IR Control, Home Automation**
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|3.3V – 5V|
|Output|Digital (HIGH/LOW)|
|Compatible|Most IR Remote Controls|
|Pin Count|3 Pins (VCC, GND, OUT)|

---

## 🧩 **ຂາຂອງ IR Receiver Module**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|VCC|ໄຟ 5V|
|GND|GND|Ground|
|OUT|Output|Digital Signal → HIGH/LOW|

> ເຫັນວ່າ Module ຈະມີ **3 ຂາ** ງ່າຍໃນການຕໍ່ກັບ Arduino

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|IR Receiver Pin|Arduino Pin|
|---|---|
|VCC|5V|
|GND|GND|
|OUT|D7 (Digital)|

---

## 💻 **ຕົວຢ່າງໂຄ້ດ Arduino (ອ່ານ IR Remote)**

```cpp
#include <IRremote.h>

const int RECV_PIN = 7;
IRrecv irrecv(RECV_PIN);
decode_results results;

void setup() {
  Serial.begin(9600);
  irrecv.enableIRIn(); // ເລີ່ມອ່ານ IR
}

void loop() {
  if (irrecv.decode(&results)) {
    Serial.println(results.value, HEX); // ສະແດງລະຫັດ IR
    irrecv.resume(); // ອ່ານຄັ້ງຕໍ່ໄປ
  }
}
```

---

## 🔍 **ຜົນລັບ**

- Arduino ຈະອ່ານ **ລະຫັດຂອງປຸ່ມ IR Remote**
    
- ສາດມາດໃຊ້ສັ່ງ **ສັ່ງງານອຸປະກອນ, ຄວບຄຸມຫຸ່ນຍົນ, ເປີດ/ປິດໄຟ**
    

---

## 🌈 **ຂໍ້ດີ**

✅ ອ່ານລະຫັດ IR ຈາກລີໂໝດໄດ້ງ່າຍ  
✅ ໃຊ້ Digital Signal → ປະມວນຜົນໄວ  
✅ ເໝາະສຳຫຼັບ **Home Automation & Robot Control**

---

# 🎮 Remote & Control

32.Infrared remote control
<img src="Pasted image 20251028235826.png"width="500">

---

## 📱 **Infrared Remote Control ແມ່ນຫຍັງ?**

**IR Remote Control** ແມ່ນອຸປະກອນສົ່ງ **ສັນຍານແສງ Infrared (IR)** ໄປຫາ **IR Receiver Module**

- ສາມາດໃໍ້ **ສັ່ງງານອຸປະກອນ** ໄດ້ເຊັ່ນ TV, Robot, Home Automation
    
- ປຸ່ມແຕ່ລະປຸ່ມຈະສົ່ງ **ສະເພາະລະຫັດ (Unique Hex Code)** ໄປຍັງ IR Receiver
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

| ລາຍການ      | ຄ່າ                               |
| ----------- | --------------------------------- |
| Voltage     | 3V – 5V (ໃຊຸ້ຖ່ານ AAA / CR2025)   |
| Signal Type | Infrared (IR)                     |
| Output      | ส่งรหัสรหัส Hex ໄປຍັງ IR Receiver |
| Range       | ~5–10 m                           |
| Frequency   | 38 kHz (ທົ່ວໄປ)                   |

---

## 🧩 **ວິທີໃຊ້**

1. ກດປຸ່ມເທິງ IR Remote
    
2. IR LED ຈະສົ່ງ **ສັນຍານແສງ IR**
    
3. IR Receiver Module ຮັບສັນຍານ → ແປງເປັນ Digital Signal → Arduino ອ່ານ
    
4. Arduino ປະມວນຜົນລະຫັດຜ່ານ → ທຳ Action ຕາມທີ່ຕັ້ງໄວ້
    

---

## 💻 **ตัวอย่างการใช้งานกับ Arduino**

ใช้ร่วมกับ **IR Receiver Module**:

```cpp
#include <IRremote.h>

const int RECV_PIN = 7; // ຂາ IR Receiver
IRrecv irrecv(RECV_PIN);
decode_results results;

void setup() {
  Serial.begin(9600);
  irrecv.enableIRIn(); // ເລີ່ມອ່ານ IR
}

void loop() {
  if (irrecv.decode(&results)) {
    Serial.print("Button Code: ");
    Serial.println(results.value, HEX); // ສະແດງລະຫັດ Hex ຂອງປຸ່ມ
    irrecv.resume(); // ອ່ານລະຫັດຄັ້ງຕໍ່ໄປ
  }
}
```

> Arduino ຈະສາມາດ **ຮັບລະຫັດປຸ່ມ** ແລະນຳໄປສັ່ງງານອຸປະກອນ ເຊັ່ນ ເປີດ/ປິດ LED, ຄວບຄຸມມໍເຕີ້ ຫຼື robot

---

## 🔍 **ຂໍ້ດີຂອງ IR Remote**

- ໃຊ້ງານງ່າຍແລະບໍ່ມີສາຍ
    
- ສາດມາດສັ່ງງານຫຼາຍອຸປະກອນໄດ້
    
- ໃຊ້ຮ່ວມກັບ **IR Receiver Module** ແລະ Arduino ເພື່ອເຮັດ **Home Automation ຫຼື Robot Control**
    

---

33.Joystick module
<img src="Pasted image 20251028235920.png"width="500">

---

## 🎮 **Joystick Module ແມ່ນຫຍັງ?**

**Joystick Module** ແມ່ນອຸປະກອນ input ທີ່ໃຊ້ກວດຄວາມຄວາມເຄື່ອນໄຫວທາງ X/Y ແລະກວດການກົດປຸ່ມ (SW button)

- ສາມາດນຳໃຊ້ໃນ **robot control, game controller, menu navigation**
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|5V|
|Output|Analog (X/Y axes) & Digital (SW button)|
|Range|0–1023 (Analog)|
|Pins|5 pins: VCC, GND, VRx, VRy, SW|
|Type|2-axis with push button|

---

## 🧩 **ຂາຂອง Joystick Module**

| Pin | ຊື່    | ໜ້າທີ່                                |
| --- | ------ | ------------------------------------- |
| VCC | VCC    | 5V                                    |
| GND | GND    | Ground                                |
| VRx | X-axis | Analog Output → Arduino A0            |
| VRy | Y-axis | Analog Output → Arduino A1            |
| SW  | Switch | Digital Output → Arduino D2 (ກົດປຸ່ມ) |

> ເຄື່ອນ Joystick → ປ່ຽນຄ່າ Analog ຂອງ VRx / VRy  
> ກົດ Joystick → Digital HIGH/LOW ຂອງ SW

---

## 🔌 **ການຕໍ່ກັບ Arduino Uno**

|Joystick Pin|Arduino Pin|
|---|---|
|VCC|5V|
|GND|GND|
|VRx|A0|
|VRy|A1|
|SW|D2|

---

## 💻 **ຕົວຢ່າງໂຄ້ດ Arduino (ອ່ານ Joystick)**

```cpp
int VRx = A0;
int VRy = A1;
int SW = 2;

void setup() {
  Serial.begin(9600);
  pinMode(SW, INPUT_PULLUP);
}

void loop() {
  int xValue = analogRead(VRx);
  int yValue = analogRead(VRy);
  int buttonState = digitalRead(SW);

  Serial.print("X: "); Serial.print(xValue);
  Serial.print(" | Y: "); Serial.print(yValue);
  Serial.print(" | Button: "); Serial.println(buttonState);

  delay(200);
}
```

---

## 🔍 **ຜົນລັບ**

- Analog → ຄ່າການເຄື່ອນທີ່ X/Y (0–1023)
    
- Digital → ຕວດສອບປຸ່ມກົດ Joystick
    
- ສາມາດໃຊ້ **ຄວບຄຸມຫຸ່ນຍົນ, ເກມ, ເມນູ LCD**
    

---

## 🌈 **ຂໍ້ດີ**

✅ 2-axis + ປຸ່ມໃນຕົວ 
✅ ອ່ານ Analog / Digital ງ່າຍ  
✅ ເໝາະສຳຫຼັບ **robot control, game controller, menu navigation**

---

**ຮູບອຸປະກອນແບບ Schematic Diagram:**
<img src="Pasted image 20251028235939.png"width="500">

34.4x4 Matrix Keyboard Module
<img src="Pasted image 20251029000044.png"width="500">

---

## ⌨️ **4x4 Matrix Keypad Module ແມ່ນຫຍັງ?**

**4x4 Matrix Keypad** ແມ່ນຄິບບອດທີ່ມີ **4 ແຖວ × 4 ຄອລຳ = 16 ປຸ່ມ**

- ໃຊ້ເພື່ອ **ປ່ອນຕົວເລກ / ຄໍາສັ່ງ / password**
    
- ໂມດູນນີ້ຈະ **ສົ່ງສັນຍານ Digital ໄປເຖິງ Arduino** ເພື່ອກວດສອບປຸ່ມທີ່ກົດ
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|5V|
|Pins|8 pins (R1–R4, C1–C4)|
|Type|Digital Input|
|Layout|4x4 matrix → 16 ປຸ່ມ|
|Protocol|Row-Column scanning|

---

## 🧩 **ຂາຂອງ 4x4 Keypad Module**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|R1|Row 1|ເຊື່ອມກັບ Arduino Digital Pin|
|R2|Row 2|-|
|R3|Row 3|-|
|R4|Row 4|-|
|C1|Col 1|ເຊື່ອມກັບ Arduino Digital Pin|
|C2|Col 2|-|
|C3|Col 3|-|
|C4|Col 4|-|

> Arduino ຈະ **scan row ແລະ column** ເພື່ອກວດສອບປຸ່ມທີ່ກົດ

---

## 🔌 **ການເຊື່ອມກັບ Arduino Uno (ຕົວຢ່າງ)**

|Keypad Pin|Arduino Pin|
|---|---|
|R1|D9|
|R2|D8|
|R3|D7|
|R4|D6|
|C1|D5|
|C2|D4|
|C3|D3|
|C4|D2|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino (ໃຊ້ Keypad Library)**

```cpp
#include <Keypad.h>

const byte ROWS = 4;
const byte COLS = 4;

char keys[ROWS][COLS] = {
  {'1','2','3','A'},
  {'4','5','6','B'},
  {'7','8','9','C'},
  {'*','0','#','D'}
};

byte rowPins[ROWS] = {9,8,7,6};
byte colPins[COLS] = {5,4,3,2};

Keypad keypad = Keypad(makeKeymap(keys), rowPins, colPins, ROWS, COLS);

void setup(){
  Serial.begin(9600);
}

void loop(){
  char key = keypad.getKey();
  if (key){
    Serial.print("Key Pressed: ");
    Serial.println(key);
  }
}
```

---

## 🔍 **ຜົນລັບ**

- Arduino ຈະອ່ານປຸ່ມທີ່ກົດ ແລະສະແດງໃນ Serial Monitor
    
- ໃຊ້ **ປ່ອນລະຫັດ, ຕົວເລກ, ຄໍາສັ່ງ**
    
- ເໝາະສໍາລັບ **Security Access, Menu Navigation, Calculator Projects**
    

---

## 🌈 **ຂໍ້ດີ**

✅ 16 ປຸ່ມແຕ່ໃຊ້ພຽງ 8 ขา Arduino  
✅ ໃຊ້ງານງ່າຍໂດຍ Keypad Library  
✅ ເໝາະສໍາລັບ **password system, robot control, calculator projects**

**ຮູບອຸປະກອນແບບ Schematic Diagram:**
<img src="Pasted image 20251029000115.png"width="500">


35.Relay module

<img src="Pasted image 20251029000230.png"width="500">

---

## 🔌 **Relay Module ແມ່ນຫຍັງ?**

**Relay Module** ແມ່ນ **switch ອັດໂຕ** ທີ່ Arduino ຫຼື microcontroller ສາມາດ **ຄວບຄຸມວົງຈອນໄຟຟ້າແຮງສູງ** ໄດ້

- Arduino → ສັນຍານ LOW/HIGH → Relay → ເປີດ/ປິດ **ໄຟບ້ານ, ມໍເຕີ, ປັ້ນນ້ຳ**
    
- ເຮັດໃຫ້ **Arduino ຄວບຄຸມອຸປະກອນ AC ຫຼື DC ທີ່ໃຊ້ກຳລັງສູງ** ໄດ້ຢ່າງປອດໄພ
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|5V (Arduino)|
|Output|Normally Open (NO), Normally Closed (NC), Common (COM)|
|Max Load|10A 250VAC / 10A 30VDC|
|Input Signal|Digital HIGH/LOW|
|Type|Single-channel / Multi-channel (1, 2, 4, 8)|

---

## 🧩 **ຂາຂອງ Relay Module**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|VCC|5V ຈາກ Arduino|
|GND|GND|Ground|
|IN|Signal|Digital Input ຈາກ Arduino|
|NO|Normally Open|ປິດ → ເປີດເມື່ອ relay ON|
|NC|Normally Closed|ເປີດ → ປິດເມື່ອ relay ON|
|COM|Common|ຂາເຊື່ອມວົງຈອນໂຫຼດ|

> Relay ຈະ **ເຮັດວຽກໂດຍໃຊ້ສັນຍານ Digital 5V** ຈາກ Arduino → ກະຕຸ້ນໃຫ້ switch ເປີດ/ປິດວົງຈອນໄຟຟ້າແຮງສູງ

---

## 🔌 **ການເຊື່ອມກັບ Arduino Uno (Single-Channel)**

|Relay Pin|Arduino Pin|
|---|---|
|VCC|5V|
|GND|GND|
|IN|D8|
|NO|ເຊື່ອມໂຫຼດ (+)|
|COM|ເຊື່ອມໂຫຼດ (-) / Ground|

> ໂຫຼດຕົວຢ່າງ: ໄຟ, ມໍເຕີ, ປັ້ນນ້ຳ

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
int relayPin = 8;

void setup() {
  pinMode(relayPin, OUTPUT);
}

void loop() {
  digitalWrite(relayPin, HIGH); // ເປີດໂຫຼດ
  delay(2000);
  digitalWrite(relayPin, LOW);  // ປິດໂຫຼດ
  delay(2000);
}
```

---

## 🔍 **ຜົນລັບ**

- Relay ຈະ **ເປີດ/ປິດອຸປະກອນໄຟຟ້າ** ຕາມສັນຍານ Arduino
    
- ໃຊ້ **ຄວບຄຸມ AC ຫຼື DC load ສູງ** ໂດຍປອດໄພ
    

---

## 🌈 **ຂໍ້ດີ**

✅ Arduino ຄວບຄຸມອຸປະກອນແຮงສູງໄດ້  
✅ ປອດໄພ, ບໍ່ຕ້ອງເຊື່ອມ Arduino ກັບ AC ໂດຍຕົວຈິງ  
✅ ໃຊ້ໄດ້ທັງ **ບ້ານອັດໂຕ, ມໍເຕີ, ປັ້ນນ້ຳ, ໂຄມໄຟ**

---

# ⚙️ Motors & Drivers

36.Servo motor

<img src="Pasted image 20251029000343.png"width="500">

---

## 🤖 **Servo Motor ແມ່ນຫຍັງ?**

**Servo Motor** ແມ່ນ **ມະນຸດຈິກ** ທີ່ຄວບຄຸມ **ການຫຸ່ນອອກ** ຢ່າງເຖິງການ

- ສາມາດ **ຫຸ່ນໄປຫາມຸມທີ່ກຳນົດ (0–180°)** ຫຼື **ຫຸ່ນຕໍ່ເນື່ອງ**
    
- ໃຊ້ໃນ **ຫົວໜ້າໂຣບອດ, กล้อง Pan-Tilt, RC Car, ລະບົບບ້ານອັດໂຕ**
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|4.8 – 6V|
|Current|~500 mA (ບໍ່ເຮັດໜ້າທຸກ)|
|Rotation|0–180° (ມາດຕະຖານ)|
|Control|PWM signal (Pulse Width Modulation)|
|Type|Standard / Continuous Rotation|

---

## 🧩 **ຂາຂອງ Servo Motor**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|+5V|ເຊື່ອມກັບແຫຼ່ງຈ່າຍໄຟ 5V|
|GND|GND|ເຊື່ອມກັບ Ground|
|Signal|PWM|ເຊື່ອມກັບຂາ Arduino Digital Pin (ເຊັ່ນ D9)|

> Arduino ສົ່ງ **ສັນຍານ PWM** → Servo ຈະຫຸ່ນໄປທີ່ມຸມທີ່ກຳນົດ

---

## 🔌 **ການເຊື່ອມກັບ Arduino Uno (ຕົວຢ່າງ)**

|Servo Pin|Arduino Pin|
|---|---|
|VCC|5V|
|GND|GND|
|Signal|D9|

> ຖ້າ Servo ໃຫຍ່ ຄວນໃຊ້ **ແຫຼ່ງຈ່າຍໄຟພາຍນອກ** ເພື່ອປ້ອງກັນ Arduino ໂດຍການ overload

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
#include <Servo.h>

Servo myservo;  // ສ້າງອັບເຈັກ Servo

void setup() {
  myservo.attach(9); // ເຊື່ອມ Signal ຂາ D9
}

void loop() {
  myservo.write(0);   // ຫຸ່ນໄປ 0°
  delay(1000);
  myservo.write(90);  // ຫຸ່ນໄປ 90°
  delay(1000);
  myservo.write(180); // ຫຸ່ນໄປ 180°
  delay(1000);
}
```

---

## 🔍 **ຜົນລັບ**

- Servo ຈະ **ຫຸ່ນໄປຫາມຸມທີ່ກຳນົດ**
    
- ໃຊ້ໃນ **robot arm, กล้อง Pan-Tilt, RC car, ລະບົບບ້ານອັດໂຕ**
    

---

## 🌈 **ຂໍ້ດີ**

✅ ຄວບຄຸມມุมຢ່າງແນ່ນອນ (0–180°)  
✅ ຕິດຕັ້ງງ່າຍ, ຄວບຄຸມ PWM ຜ່ານ Arduino  
✅ ເໝາະສໍາລັບ **robot, RC car, camera mount, home automation**

37.Stepper motor
<img src="Pasted image 20251029000434.png"width="500">

---

## 🌀 **Stepper Motor ແມ່ນຫຍັງ?**

**Stepper Motor** ແມ່ນ **ມໍເຕີທີ່ຫຸ່ນເປັນຂັ້ນໆ (step)**

- ໃຊ້ເພື່ອ **ຄວບຄຸມມຸມການຫຸ່ນຢ່າງແນ່ນອນ**
    
- ຫຸ່ນເປັນ **step ຕໍ່ step** ແທນການຫຸ່ນຕໍ່ເນື່ອງເຫັນເຫັນຄົນມໍເຕີທົ່ວໄປ
    
- ໃຊ້ໃນ **3D printer, CNC machine, robot arm, camera slider**
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|5V–12V (ຂຶ້ນຢູ່ກັບມໍເຕີ)|
|Current|100–500 mA ຕໍ່ phase|
|Step Angle|1.8° / 0.9° (ຂຶ້ນຢູ່ກັບມໍເຕີ)|
|Control|Digital Pulse / Step Signal|
|Type|Unipolar / Bipolar|

---

## 🧩 **ຂາຂອງ Stepper Motor**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|Coil A|-|ເຊື່ອມກັບ Driver|
|Coil A'|-|ເຊື່ອມກັບ Driver|
|Coil B|-|ເຊື່ອມກັບ Driver|
|Coil B'|-|ເຊື່ອມກັບ Driver|

> Stepper Motor **ບໍ່ເຊື່ອມກັບ Arduino ໂດຍກົງ**  
> ແຕ່ຈະຕ້ອງໃຊ້ **Driver (ເຊັ່ນ ULN2003, A4988, DRV8825)**

---

## 🔌 **ການເຊື່ອມກັບ Arduino (ຕົວຢ່າງ)**

|Stepper Pin|Arduino Pin|
|---|---|
|IN1|D8|
|IN2|D9|
|IN3|D10|
|IN4|D11|
|VCC|5V–12V (Driver)|
|GND|GND|

> Driver ຈະ **ຮັບສັນຍານ digital ຈາກ Arduino** → ກະຕຸ້ນ Coil ຂອງ Stepper

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino (ໃຊ້ Stepper Library)**

```cpp
#include <Stepper.h>

const int stepsPerRevolution = 200; // Step ຕໍ່ການຫຸ່ນ 1 ລອບ (1.8°/step)

Stepper myStepper(stepsPerRevolution, 8, 10, 9, 11);

void setup() {
  myStepper.setSpeed(60); // ຄວາມໄວ 60 RPM
}

void loop() {
  myStepper.step(stepsPerRevolution);   // ຫຸ່ນ 1 ລອບ
  delay(1000);
  myStepper.step(-stepsPerRevolution);  // ຫຸ່ນກັບ 1 ລອບ
  delay(1000);
}
```

---

## 🔍 **ຜົນລັບ**

- Stepper Motor ຈະ **ຫຸ່ນເປັນ step ຕາມສັນຍານຈາກ Arduino**
    
- ຄວບຄຸມ **ມຸມ, ຄວາມໄວ, ການຫຸ່ນໄປ-ກັບ** ໄດ້ແນ່ນອນ
    

---

## 🌈 **ຂໍ້ດີ**

✅ ຫຸ່ນໄດ້ແນ່ນອນ ແບບ step by step  
✅ ຄວບຄຸມມຸມ ແລະ ຄວາມໄວໄດ້ຕາມຕ້ອງການ  
✅ ເໝາະສໍາລັບ **robot, CNC, 3D printer, camera slider**

**ຮູບອຸປະກອນແບບ Schematic Diagram:**
<img src="Pasted image 20251029000509.png"width="500">


38.Stepper motor driver board

<img src="Pasted image 20251029000617.png"width="500">

---

## 🔌 **Stepper Motor Driver Board ແມ່ນຫຍັງ?**

**Stepper Motor Driver Board** ແມ່ນ **ບອດຄວບຄຸມ Stepper Motor**

- ຮັບ **ສັນຍານ digital ຈາກ Arduino**
    
- ກະຕຸ້ນ **Coil ຂອງ Stepper Motor** ໃຫ້ຫຸ່ນເປັນ step
    
- ເຮັດໃຫ້ **Stepper Motor ຫຸ່ນໄດ້ແນ່ນອນ ແລະປອດໄພ** ຈາກ Arduino
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|5V–12V (ຂຶ້ນຢູ່ກັບ Stepper)|
|Current|0.5–2A (ຂຶ້ນຢູ່ກັບ Driver)|
|Input|Digital Pulse / Step Signal|
|Output|Coil A, Coil B (Stepper Motor)|
|Type|ULN2003, A4988, DRV8825 (ຕ່າງກັນຕາມຍີ່ຫໍ້)|

---

## 🧩 **ຂາຂອງ Stepper Driver Board**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|5V–12V|ເຊື່ອມກັບ Power Supply ພາຍນອກ|
|GND|GND|ເຊື່ອມກັບ Ground|
|IN1/STEP|Step / Pulse|ຮັບສັນຍານຈາກ Arduino|
|IN2/DIR|Direction|ກຳນົດທິດທາງຫຸ່ນ|
|OUT1–OUT4|Coil A / B|ສົ່ງກຳລັງອອກຫາ Stepper Motor|

> Driver Board ເຮັດໃຫ້ **Arduino ຄວບຄຸມ Stepper Motor ໄດ້ງ່າຍແລະປອດໄພ**

---

## 🔌 **ການເຊື່ອມກັບ Arduino (ຕົວຢ່າງ A4988)**

|Driver Pin|Arduino Pin|
|---|---|
|VDD|5V|
|GND|GND|
|STEP|D3|
|DIR|D4|
|ENABLE|D5 (optional)|
|OUT1–OUT4|ເຊື່ອມກັບ Coil Stepper Motor|
|VMOT|8–12V Power Supply ສໍາລັບ Stepper Motor|

---

## 💻 **ຕົວຢ່າງໂຄດ Arduino**

```cpp
#define STEP_PIN 3
#define DIR_PIN 4

void setup() {
  pinMode(STEP_PIN, OUTPUT);
  pinMode(DIR_PIN, OUTPUT);
  digitalWrite(DIR_PIN, HIGH); // ກຳນົດທິດທາງ
}

void loop() {
  digitalWrite(STEP_PIN, HIGH);
  delayMicroseconds(500);
  digitalWrite(STEP_PIN, LOW);
  delayMicroseconds(500);
}
```

---

## 🔍 **ຜົນລັບ**

- Stepper Motor ຈະ **หมุนเป็น step ຕາມ STEP และ DIR**
    
- ຄວບຄຸມ **มุม, ความเร็ว, ทิศทาง** ได้แม่นยำ
    

---

## 🌈 **ຂໍ້ດີ**

✅ ຄວບຄຸມ Stepper Motor ໄດ້ແນ່ນອນ  
✅ ລົດພາລະກິດການກະຕຸ້ນຂອງ Arduino  
✅ ເໝາະສໍາລັບ **robot, CNC, 3D printer, camera slider**

---

**ຮູບອຸປະກອນແບບ Schematic Diagram:**
<img src="Pasted image 20251029000702.png"width="500">
# 🧠 ICs & Modules

39.Real-time Clock Module DS1302

<img src="Pasted image 20251029000850.png"width="500">

---

## ⏰ **Real-time Clock Module DS1302 ແມ່ນຫຍັງ?**

**DS1302 RTC Module** ແມ່ນ **ມູດຄວາມເວລາຈິງເທົ່າ (Real-time Clock)**

- ສາມາດ **ບັນທຶກວັນ, ເດືອນ, ປີ, ຊົ່ວໂມງ, ນາທີ, ວິນາທີ**
    
- ໃຊ້ຮ່ວມກັບ **Arduino ຫຼື Microcontroller**
    
- ມີ **Backup battery (CR2032)** ເພື່ອບັນທຶກຂໍ້ມູນເວລາ ເມື່ອປິດໄຟ
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|5V|
|Interface|3-wire Serial (CLK, DAT, RST)|
|Battery Backup|CR2032|
|Accuracy|±2 min/month|
|Function|Time & Date keeping (seconds, minutes, hours, day, date, month, year)|

---

## 🧩 **ຂາຂອງ DS1302 Module**

|Pin|ຊື່|ໜ້າທີ່|
|---|---|---|
|VCC|VCC|ເຊື່ອມ 5V ຈາກ Arduino|
|GND|GND|Ground|
|CLK|Serial Clock|ສັນຍານນາທີຈາກ Arduino|
|DAT|Data|ສັນຍານຂໍ້ມູນຂາເຂົ້າ-ອອກ|
|RST|Reset|ກຳນົດເລີ່ມໃໝ່ / Enable|

> Module ຈະ **ສົ່ງສັນຍານเวลา** ໃຫ້ Arduino ພາຍນໃນ 3-wire Serial

---

## 🔌 **ການເຊື່ອມກັບ Arduino Uno**

|DS1302 Pin|Arduino Pin|
|---|---|
|VCC|5V|
|GND|GND|
|CLK|D2|
|DAT|D3|
|RST|D4|

---

## 💻 **ຕົວຢ່າງโค้ດ Arduino (ใช้ DS1302 Library)**

```cpp
#include <DS1302.h>

const int CLK = 2;
const int DAT = 3;
const int RST = 4;

DS1302 rtc(CLK, DAT, RST);

void setup() {
  Serial.begin(9600);
  rtc.halt(false);
  rtc.writeProtect(false);

  // ຕັ້ງວັນເດືອນ/ປີ ເມື່ອຄວາມຈິງເລີ່ມເວລາ
  rtc.setDOW(SUNDAY);
  rtc.setTime(12, 0, 0); // 12:00:00
  rtc.setDate(1, 11, 2025); // 1/11/2025
}

void loop() {
  Serial.print(rtc.getDOWStr());
  Serial.print(" ");
  Serial.print(rtc.getDateStr());
  Serial.print(" ");
  Serial.println(rtc.getTimeStr());
  delay(1000);
}
```

---

## 🔍 **ຜົນລັບ**

- Arduino ຈະ **ອອກຂໍ້ມູນເວລາແລະວັນທີ** ຢູ່ Serial Monitor
    
- ຂໍ້ມູນຈະ **ຖືກບັນທຶກໄວ້ໃນ Battery Backup** ເມື່ອໄຟຖືກປິດ
    

---

## 🌈 **ຂໍ້ດີ**

✅ ຕິດຕັ້ງງ່າຍ  
✅ ຈິງເວລາ ບໍ່ຫາຍໄປເມື່ອໄຟປິດ  
✅ ເໝາະສໍາລັບ **ນັດເວລາ, ນາທີບັນທຶກ, ລະບົບປອດຄວາມປອດໄພ, ບ້ານອັດໂຕ**

---

40.74HC595 Chip
<img src="Pasted image 20251029000930.png"width="500">

---

## 💾 **74HC595 ແມ່ນຫຍັງ?**

**74HC595** ແມ່ນ **ຊິບ Shift Register 8-bit Serial-in, Parallel-out**

- ໃຊ້ເພື່ອ **ຂະຫຍາຍຈຳນວນຂາ Digital ຂອງ Arduino**
    
- ອະນຸຍາດໃຫ້ **Arduino ຄວບຄຸມ 8 output ດ້ວຍ 3 ຂາ** (Serial Data, Clock, Latch)
    
- ເຮັດໃຫ້ **LED, 7-segment, Relay ແລະ Module ຫຼາຍໆ** ຄວບຄຸມໄດ້ງ່າຍ ແລະປອດໄພ
    

---

## ⚙️ **ຄຸນນະສົມບັດ**

|ລາຍການ|ຄ່າ|
|---|---|
|Voltage|2–6V|
|Output|8 parallel outputs|
|Input|Serial Data In|
|Control|Shift Clock (SH_CP), Latch Clock (ST_CP)|
|Max Current|35 mA ຕໍ່ output|
|Type|Shift Register 8-bit|

---

## 🧩 **ຂາຂອງ 74HC595**

|Pin|Name|Function|
|---|---|---|
|DS|Data Serial In|ຮັບຂໍ້ມູນ Serial ຈາກ Arduino|
|SH_CP|Shift Clock|ສັນຍານຄວາມໄວເພື່ອ shift data|
|ST_CP|Latch Clock|ອອກຄ່າຈາກ shift register ໄປອອກເປັນ output|
|Q0–Q7|Parallel Out|ສົ່ງອອກສຳລັບ LED / Relay / Module|
|MR|Master Reset|ລ້າງຂໍ້ມູນໃນ shift register|

---

## 🔌 **ປະໂຫຍດ**

✅ ຂยายຈຳນວນ output ດ້ວຍ Arduino ຈິດເພາະ  
✅ ເຮັດໃຫ້ **LED, 7-segment, Relay ແລະ Module ຫຼາຍໆ** ຄວບຄຸມໄດ້ງ່າຍ  
✅ ປອດໄພ ແລະປອດຈາກການຕ້ອງການขา output ຫຼາຍໆ

---
**ຮູບອຸປະກອນແບບ Schematic Diagram:**
<img src="Pasted image 20251029000949.png"width="500">
