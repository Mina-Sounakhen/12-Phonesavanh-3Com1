
## ບົດລາຍງານອຸປະກອນ Arduino Starter Kit

### 1. Arduino Uno board


**Arduino Uno** ແມ່ນແຜງໄມໂຄຣຄອນໂທນເລີ (Microcontroller Board) ແບບ open-source ທີ່ສ້າງຂຶ້ນເທິງຊິບ **ATmega328P**
ມັນເຮັດໜ້າທີ່ເປັນສະໝອງຫຼັກສຳລັບໂຄງການເອເລັກໂຕຣນິກ, ອະນຸຍາດໃຫ້ຜູ້ໃຊ້ສາມາດຂຽນໂປຣແກຣມ ແລະ ໂຕ້ຕອບກັບໂລກພາຍນອກ.

ເຮັດວຽກໂດຍການອ່ານການປ້ອນຂໍ້ມູນ (ເຊັ່ນ: ແສງຈາກເຊັນເຊີ ຫຼື ການກົດປຸ່ມ) ແລະ ປ່ຽນເປັນການສົ່ງອອກ (ເຊັ່ນ: ການເປີດໄຟ LED ຫຼື ການເດີນຂອງມໍເຕີ) , ໂດຍອີງຕາມຄໍາສັ່ງ (sketch) ທີ່ບັນທຶກໄວ້ໃນໜ່ວຍຄວາມຈຳຂອງມັນ.

![example.jpg](./photo/Arduino%20Uno%20board.png)

Arduino Uno board  * **Digital Pins (0-13):** ໃຊ້ສຳລັບການປ້ອນຂໍ້ມູນ/ສົ່ງອອກແບບດິຈິຕອລ (ON/OFF). Pins 3, 5, 6, 9, 10, ແລະ 11 ຮອງຮັບ PWM (Pseudo-Analog). * **Analog Pins (A0-A5):** ໃຊ້ສຳລັບການອ່ານຄ່າອະນາລັອກ (ຕົວຢ່າງ: ຈາກເຊັນເຊີອຸນຫະພູມ). * **Power Pins (GND, 5V, 3.3V):** ໃຊ້ສຳລັບການເຊື່ອມຕໍ່ກັບພື້ນດິນ ແລະ ການສະໜອງພະລັງງານໃຫ້ອຸປະກອນອື່ນ. * **Etc...:** Microcontroller: ATmega328P, ໂວນເຮັດວຽກ: 5V, ຄວາມໄວໂມງ: 16 MH

![example.jpg](./photo/schemetic%20Arduino%20Uno%20board.png)**ໃຊ້ໃນການສ້າງລະບົບໄຟສັນຍານຈາລະຈອນແບບງ່າຍດາຍ (Simple Traffic Light System)** 

---

### 2. Breadboards

**Breadboard** ແມ່ນແຜງພລາສຕິກທີ່ມີຮູ, ໃຊ້ສຳລັບການສ້າງແບບຈຳລອງ (prototype) ວົງຈອນເອເລັກໂຕຣນິກຊົ່ວຄາວ. ມັນຊ່ວຍໃຫ້ສາມາດເຊື່ອມຕໍ່ອຸປະກອນຕ່າງໆໄດ້ໂດຍບໍ່ຈຳເປັນຕ້ອງມີການເຊື່ອມ.

ພາຍໃນ breadboard, ແຖວຂອງຮູຖືກເຊື່ອມຕໍ່ທາງດ້ານໄຟຟ້າ: * **ລາງພະລັງງານ (Power Rails):** ແຖວຕາມລວງຍາວທັງໝົດ (ປົກກະຕິແມ່ນໝາຍດ້ວຍ + ແລະ -) ແມ່ນເຊື່ອມຕໍ່ກັນ. * **ລາງວົງຈອນ (Component Area):** ຫ້າຮູໃນແຕ່ລະຖັນຕາມລວງນອນຖືກເຊື່ອມຕໍ່ກັນ. ທ່ານສາມາດໃສ່ສາຍ ຫຼື ສ່ວນປະກອບຕ່າງໆເຂົ້າໄປໃນຮູເຫຼົ່ານີ້ເພື່ອເຮັດໃຫ້ວົງຈອນສົມບູນ.

![example.jpg](./photo/Breadboards.png)


**ຕົວຢ່າງການນໍາໃຊ້:** **ການສ້າງວົງຈອນ LED ແລະ Resistor ເທິງ Breadboard (Wiring an LED on a Breadboard)**

---
### 3.USB cable

**ສາຍ USB (USB Cable)** ແມ່ນໃຊ້ສຳລັບເຊື່ອມຕໍ່ Arduino Uno ກັບຄອມພິວເຕີ. ປົກກະຕິແລ້ວມັນຈະເປັນສາຍປະເພດ **USB A ຫາ USB B** (ສຳລັບ Uno).

ສາຍ USB ເຮັດສອງໜ້າທີ່ຫຼັກຄື: * **ພະລັງງານ (Power):** ມັນສະໜອງພະລັງງານ 5V ໃຫ້ກັບ Arduino Uno ຈາກຄອມພິວເຕີ. * **ຂໍ້ມູນ (Data):** ມັນສ້າງຊ່ອງທາງການສື່ສານແບບ serial ເພື່ອອັບໂຫລດລະຫັດຈາກຄອມພິວເຕີໄປຫາ Arduino ແລະ ສົ່ງຂໍ້ມູນ serial ກັບຄືນໄປຫາຄອມພິວເຕີ (Serial Monitor).

![example.jpg](./photo/USB%20cable.png)
**ຕົວຢ່າງການໃຊ້ງານ: ການອັບໂຫລດໂຄງການ "Blink" ໄປຫາ Arduino Uno**

---
### 4. Jumper wires (male-to-male)

**ສາຍ Jumper wires (Male-to-Male)**  ແມ່ນສາຍທີ່ມີເຂັມປັກຢູ່ທັງສອງສົ້ນ. ມັນຖືກນໍາໃຊ້ເພື່ອສ້າງການເຊື່ອມຕໍ່ທາງດ້ານໄຟຟ້າຊົ່ວຄາວລະຫວ່າງສອງຈຸດໃນວົງຈອນ.

ພວກມັນຖືກໃຊ້ໂດຍສະເພາະເພື່ອເຊື່ອມຕໍ່: * **ຈຸດຕ່າງໆໃນ Breadboard:** ເຂັມປັກເໝາະກັບຮູຂອງ breadboard. * **Arduino Pins ກັບ Breadboard:** ເຊັ່ນ: ເຊື່ອມຕໍ່ Pin ດິຈິຕອລຂອງ Arduino ກັບຈຸດໃນ breadboard.

ມີຫຼາຍສີ ແລະ ຫຼາຍຄວາມຍາວ, ໃຊ້ສຳລັບການເຊື່ອມຕໍ່ສັນຍານ ແລະ ພະລັງງານພາຍໃນ breadboard.
![example.jpg](./photo/Jumper%20wires%20(male-to-male).png)

**ໃຊ້ໃນການເຊື່ອມຕໍ່ GND ແລະ 5V ຂອງ Arduino ໄປຫາລາງພະລັງງານຂອງ Breadboard**

---
### 5. Jumper wires (male-to-female)

**ສາຍ Jumper wires (Male-to-Female)**  ມີເຂັມປັກຢູ່ສົ້ນໜຶ່ງ (Male) ແລະ ຫົວເຊື່ອມຕໍ່ແບບເຕົ້າສຽບຢູ່ອີກສົ້ນໜຶ່ງ (Female).

ພວກມັນມີປະໂຫຍດຢ່າງຍິ່ງສຳລັບ: * **ການເຊື່ອມຕໍ່ Breadboard ກັບ Pin headers ຂອງ Module:** ປາຍ Female ທີ່ເປັນເຕົ້າສຽບສາມາດສຽບເຂົ້າໄປໃນເຂັມປັກ (pins) ຂອງເຊັນເຊີ ຫຼື ໂມດູນໄດ້ໂດຍກົງ. * **ການເຊື່ອມຕໍ່ Arduino Pin Headers ກັບ Breadboard:** ປາຍ Female ສຽບໃສ່ Pin ຂອງ Arduino, ແລະ ປາຍ Male ສຽບໃສ່ Breadboard.

ຖືກໃຊ້ເພື່ອຂະຫຍາຍສາຍເຊື່ອມຕໍ່ຈາກແຜງວົງຈອນອອກໄປຫາ breadboard

![example.jpg](./photo/Jumper%20wires%20(male-to-female).png)**ຕົວຢ່າງການນຳໃຊ້​: ການເຊື່ອມຕໍ່ເຊັນເຊີ DHT11 (ມີ Pin Header) ໄປຫາ Arduino Uno**

---
### 6. Jumper wires (female-to-female)

**ສາຍ Jumper wires (Female-to-Female)** ແມ່ນສາຍທີ່ມີຫົວເຊື່ອມຕໍ່ແບບເຕົ້າສຽບຢູ່ທັງສອງສົ້ນ. ມັນຖືກໃຊ້ເພື່ອສ້າງການເຊື່ອມຕໍ່ລະຫວ່າງເຂັມປັກສອງອັນ (male pins).

ພວກມັນຖືກໃຊ້ໂດຍສະເພາະສຳລັບການເຊື່ອມຕໍ່: * Pin Headers ຂອງ Module ຫາ Pin Headers ຂອງ Module: ເຊັ່ນ: ເຊື່ອມຕໍ່ Pin ຂອງເຊັນເຊີໂດຍກົງກັບ Pin ຂອງ Arduino (ໂດຍບໍ່ຜ່ານ breadboard). * ການເຊື່ອມຕໍ່ລະຫວ່າງ Arduino/Raspberry Pi: ໃຊ້ສຳລັບການເຊື່ອມຕໍ່ແບບ point-to-point.

ຖືກໃຊ້ເພື່ອຂະຫຍາຍສາຍເຊື່ອມຕໍ່ຈາກແຜງວົງຈອນອອກໄປຫາ breadboard

![example.jpg](./photo/Jumper%20wires%20(female-to-female).png)


**ໃຊ້ກັບການເຊື່ອມຕໍ່ເຊັນເຊີ Ultrasonic (HC-SR04) ກັບ Arduino**

---
### 7. 9V Battery Connector

**9V Battery Connector** ແມ່ນອຸປະກອນທີ່ເຊື່ອມຕໍ່ແບັດເຕີຣີ 9 ໂວນເຂົ້າກັບປລັກສຽບໄຟ DC (DC barrel jack) ຂອງ Arduino Uno.

ມັນອະນຸຍາດໃຫ້ Arduino Uno ໄດ້ຮັບພະລັງງານຈາກແບັດເຕີຣີ 9V, ເຮັດໃຫ້ໂຄງການສາມາດໃຊ້ງານໄດ້ໂດຍບໍ່ຈຳເປັນຕ້ອງເຊື່ອມຕໍ່ກັບຄອມພິວເຕີ ຫຼື ແຫຼ່ງພະລັງງານອື່ນໆ.

**Pins:** ເສັ້ນລວດສີແດງ (+) ເຊື່ອມຕໍ່ກັບຈຸດໃຈກາງຂອງປລັກ DC, ແລະ ສີດໍາ (-) ເຊື່ອມຕໍ່ກັບດ້ານນອກ. * **Etc...:** ໂວນປ້ອນຂໍ້ມູນນີ້ (9V) ຖືກຄວບຄຸມລົງມາເປັນ 5V ໂດຍເຄື່ອງຄວບຄຸມໂວນໃນ Arduino.

![example.jpg](./photo/9V%20Battery%20Connector.png)
**ໃຊ້ໃນການໃຫ້ພະລັງງານແກ່ໂຄງການທີ່ໃຊ້ງານຢູ່ (Standalone Project Power Supply)**

---
### 8. LEDs (Red: 5, Yellow: 5, Blue: 5, RGB: 1)

**LED (Light Emitting Diode)** ແມ່ນອຸປະກອນ semiconductor ທີ່ປ່ອຍແສງເມື່ອກະແສໄຟຟ້າໄຫຼຜ່ານມັນໃນທິດທາງທີ່ຖືກຕ້ອງ. ຊຸດປະກອບມີສີແດງ, ສີເຫຼືອງ, ສີຟ້າ, ແລະ LED RGB (ສາມສີໃນອັນດຽວ)

LED ເຮັດວຽກເປັນໄດໂອດ; ໄຟຟ້າຕ້ອງໄຫຼຈາກຂາ **Anode (+) ຫາ Cathode (-)**. ພວກມັນປ່ອຍແສງເປັນສີທີ່ແຕກຕ່າງກັນຕາມວັດສະດຸ semiconductor ທີ່ໃຊ້. LED RGB ມີສີ່ຂາ, ແຕ່ລະຂາສຳລັບສີແດງ, ສີຂຽວ, ສີຟ້າ, ແລະ ຂາທົ່ວໄປ (common)

**ຂາ Anode (+):** ຂາຍາວ, ເຊື່ອມຕໍ່ກັບ 5V (ຜ່ານ Resistor). * **ຂາ Cathode (-):** ຂາສັ້ນ, ເຊື່ອມຕໍ່ກັບ Ground (GND). ຕ້ອງໃຊ້ Resistor (ເຊັ່ນ: 220Ω) ໃນຊຸດເພື່ອຈຳກັດກະແສໄຟຟ້າ ແລະ ປ້ອງກັນບໍ່ໃຫ້ LED ໄໝ້.

![example.jpg](./photo/LEDs%20(Red%205,%20Yellow%205,%20Blue%205,%20RGB%201).png)



**ໃຊ້ໃນການຄວບຄຸມຄວາມສະຫວ່າງຂອງ LED ດ້ວຍ PWM (Fade LED)** 

---

### 9. RGB module

**RGB Module** ແມ່ນໂມດູນທີ່ບັນຈຸ LED RGB, ເຊິ່ງສາມາດຜະລິດແສງສີຕ່າງໆໄດ້ໂດຍການປະສົມຄວາມເຂັ້ມຂອງສີແດງ (Red), ສີຂຽວ (Green), ແລະ ສີຟ້າ (Blue). ມັນມີຕົວຕ້ານທານທີ່ຈຳກັດກະແສໄຟຟ້າໃນຕົວ

ໂດຍການໃຊ້ **Pulse Width Modulation (PWM)** ຈາກ Arduino ເພື່ອຄວບຄຸມລະດັບຄວາມເຂັ້ມແສງຂອງ LED ແຕ່ລະສີ (R, G, B), ມັນສາມາດຜະລິດສີທີ່ແຕກຕ່າງກັນໄດ້ເຖິງ 16 ລ້ານສີ. ມັນມັກຈະເປັນແບບ **Common Cathode** (GND ທົ່ວໄປ) ຫຼື **Common Anode** (VCC ທົ່ວໄປ)

**Pins:** R (Red), G (Green), B (Blue), ແລະ VCC (Common Anode) ຫຼື GND (Common Cathode).ຕ້ອງເຊື່ອມຕໍ່ກັບ Pin ຂອງ Arduino ທີ່ຮອງຮັບ PWM (~) ເພື່ອຄວບຄຸມສີ.
![example.jpg](./photo/RGB%20module.png)
![example.jpg](./photo/schemetic%20RGB%20module.png)**ໃຊ້ໃນການສະແດງການປ່ຽນແປງສີແບບສຸ່ມ (Rainbow Fading Effec**

---
### 10. Resistors (220Ω, 1kΩ, 10kΩ)

**Resistor** ແມ່ນອຸປະກອນເອເລັກໂຕຣນິກສອງຂາທີ່ອອກແບບມາເພື່ອຕ້ານການໄຫຼຂອງກະແສໄຟຟ້າໃນວົງຈອນ. ຊຸດປະກອບມີ 220Ω, 1kΩ (1,000Ω), ແລະ 10kΩ (10,000Ω)

ພວກມັນຖືກໃຊ້ສຳລັບ: * **ການຈຳກັດກະແສໄຟຟ້າ:** (ເຊັ່ນ: 220Ω ຖືກໃຊ້ກັບ LED ເພື່ອປ້ອງກັນບໍ່ໃຫ້ມັນໄໝ້). * **Pull-up/Pull-down:** (ເຊັ່ນ: 10kΩ ຖືກໃຊ້ກັບປຸ່ມກົດ) ເພື່ອກຳນົດສະຖານະເລີ່ມຕົ້ນຂອງສັນຍານດິຈິຕອລ. * **Voltage Divider:** ສອງ Resistor ຖືກໃຊ້ຮ່ວມກັນເພື່ອຫຼຸດໂວນລົງ

**ກຳນົດຄ່າ:** ໂດຍໃຊ້ **ແຖບສີ** (Color Codes) ທີ່ຖືກພິມຢູ່ເທິງຕົວຕ້ານທານ42. ຫົວໜ່ວຍວັດແທກແມ່ນ **Ohm ($\Omega$)**43.
![example.jpg](./photo/Resistors%20(220Ω,%201kΩ,%2010kΩ).png)
**ການໃຊ້ Resistor 10kΩ ເປັນ Pull-down ກັບ Push Button**

---

### 11. Push Buttons (x4 with Lids)

**Push Button** ແມ່ນສະວິດຊົ່ວຄາວທີ່ປິດ ຫຼື ເປີດວົງຈອນໃນຂະນະທີ່ມັນຖືກກົດ ແລະ ກັບຄືນສູ່ສະຖານະເດີມເມື່ອຖືກປ່ອຍ.

ມັນເຮັດວຽກໂດຍການປ່ຽນແປງສະຖານະຂອງການປ້ອນຂໍ້ມູນດິຈິຕອລຂອງ Arduino. ໂດຍປົກກະຕິແລ້ວມັນຈະຖືກໃຊ້ໃນການເຊື່ອມຕໍ່ແບບ **Pull-down** (ໃຫ້ຄ່າ LOW ເມື່ອບໍ່ຖືກກົດ) ຫຼື **Pull-up** (ໃຫ້ຄ່າ HIGH ເມື່ອບໍ່ຖືກກົດ)

**Pins:** ມີ 4 Pins, ສອງຄູ່ຂອງ Pin ທີ່ກົງກັນຂ້າມຖືກເຊື່ອມຕໍ່ເຂົ້າກັນເມື່ອບໍ່ຖືກກົດ, ແລະ ທັງ 4 Pin ເຊື່ອມຕໍ່ກັນເມື່ອຖືກກົດ. ຝາປິດ (Lids) ຖືກໃຊ້ເພື່ອເຮັດໃຫ້ການກົດງ່າຍຂຶ້ນ ແລະ ສວຍງາມຂຶ້ນ.

![example.jpg](./photo/Push%20Buttons%20(x4%20with%20Lids).png)
![example.jpg](./photo/schemetic%20Push%20Buttons%20(x4%20with%20Lids).png)**ໃຊ້ໃນການຄວບຄຸມ LED ໂດຍການກົດປຸ່ມ (Button-Controlled LED)**

---

### 12. Potentiometer (5KΩ)

**Potentiometer** ແມ່ນຕົວຕ້ານທານທີ່ປັບໄດ້ສາມຂາ, ໂດຍປົກກະຕິແລ້ວແມ່ນ 5kΩ. ມັນຖືກໃຊ້ເພື່ອຄວບຄຸມຄ່າຄວາມຕ້ານທານແບບປັບໄດ້ ຫຼື ເປັນຕົວແບ່ງໂວນທີ່ປັບໄດ້.

ການໝູນລູກບິດ, ຄວາມຕ້ານທານລະຫວ່າງປາຍກາງ (wiper) ແລະ ປາຍທັງສອງສົ້ນຈະປ່ຽນແປງ. ເມື່ອເຊື່ອມຕໍ່ກັບ 5V ແລະ GND, ປາຍກາງຈະສົ່ງອອກໂວນທີ່ແຕກຕ່າງກັນ (0V ຫາ 5V), ເຊິ່ງ Arduino ສາມາດອ່ານໄດ້ຜ່ານ Pin ອະນາລັອກ (Analog Pin).

**Pins:** VCC (ເຊື່ອມຕໍ່ກັບ 5V), GND (ເຊື່ອມຕໍ່ກັບ Ground), ແລະ **Output** (ເຊື່ອມຕໍ່ກັບ Analog Pin ຂອງ Arduino). ເຮັດໜ້າທີ່ເປັນຕົວຄວບຄຸມການປ້ອນຂໍ້ມູນແບບອະນາລັອກ (ປ່ຽນແປງຕໍ່ເນື່ອງ).

![example.jpg](./photo/Potentiometer%20(5KΩ).png)
![example.jpg](./photo/schemetic%20Potentiometer%20(5KΩ).png)**ໃຊ້ Potentiometer ເພື່ອຄວບຄຸມຄວາມໄວຂອງ Servo Motor**

---

### 13. Active Buzzer

**Active Buzzer** ແມ່ນລຳໂພງ piezoelectric ຂະໜາດນ້ອຍທີ່ມີວົງຈອນກຳເນີດສຽງ (oscillator) ໃນຕົວ.

ມັນຜະລິດສຽງ (tone) ທີ່ຄວາມຖີ່ຄົງທີ່ເມື່ອໄດ້ຮັບໂວນ DC ທີ່ຖືກຕ້ອງ (ເຊັ່ນ: 5V). ມັນງ່າຍຕໍ່ການໃຊ້ງານ, ເພາະມັນພຽງແຕ່ຕ້ອງການສັນຍານ HIGH/LOW ຈາກ Arduino ເພື່ອເປີດ/ປິດສຽງ.

**Pins:** VCC (+) ແລະ GND (-).  ບໍ່ສາມາດປັບຄວາມຖີ່ຂອງສຽງໄດ້, ພຽງແຕ່ສາມາດເປີດ ຫຼື ປິດໄດ້

![example.jpg](./photo/Active%20Buzzer.png)

**ໃຊ້ໃນການສ້າງສຽງເຕືອນ (Simple Alarm Sound)**

---

### 14. Passive Buzzer

**Passive Buzzer** ແມ່ນລຳໂພງ piezoelectric ຂະໜາດນ້ອຍທີ່ບໍ່ມີວົງຈອນກຳເນີດສຽງໃນຕົວ. ມັນຕ້ອງການສັນຍານຄື້ນສີ່ຫຼ່ຽມ (square wave) ຈາກພາຍນອກເພື່ອສ້າງສຽງ.

Arduino ຕ້ອງໃຊ້ຟັງຊັນ **`tone()`** ເພື່ອສົ່ງສັນຍານຄື້ນສີ່ຫຼ່ຽມທີ່ຄວາມຖີ່ທີ່ແຕກຕ່າງກັນໄປຫາ Passive Buzzer. ນີ້ອະນຸຍາດໃຫ້ມັນສາມາດຜະລິດສຽງ (tones) ທີ່ຫຼາກຫຼາຍ ແລະ ສາມາດຫຼິ້ນເພງໄດ້.

**Pins:** VCC (+) ແລະ GND (-).ຕ້ອງເຊື່ອມຕໍ່ກັບ Digital Pin ຂອງ Arduino. ຄວາມສາມາດໃນການປັບຄວາມຖີ່ຂອງສຽງແມ່ນຂໍ້ໄດ້ປຽບຫຼັກ.
![example.jpg](./photo/Passive%20Buzzer.png)

**ໃຊ້ໃນການຫຼິ້ນເພງງ່າຍໆ (Playing Simple Tunes/Music)**

---

### 15. 16x2 LCD display

**16x2 LCD Display** ແມ່ນຈໍສະແດງຜົນຂໍ້ຄວາມທີ່ສາມາດສະແດງຕົວອັກສອນໄດ້ 16 ຕົວອັກສອນໃນ 2 ແຖວ.

ໂດຍປົກກະຕິແລ້ວມັນຈະສື່ສານກັບ Arduino ໂດຍໃຊ້ໂໝດ 4-bit ຫຼື 8-bit. ມັນຕ້ອງມີການເຊື່ອມຕໍ່ສາຍໄຟຫຼາຍສາຍກັບ Arduino (ເຊັ່ນ: 6-12 ສາຍ) ແລະ ມັກຈະໃຊ້ Potentiometer ເພື່ອປັບຄວາມຄົມຊັດ.

**Pins:** VSS, VDD, VO (Contrast), RS, RW, E, D0-D7, LED+ (Backlight).ຕ້ອງການຫ້ອງສະໝຸດ **LiquidCrystal** ຂອງ Arduino ເພື່ອຄວບຄຸມ.
![example.jpg](./photo/16x2%20LCD%20display.png)
![example.jpg](./photo/schemetic%2016x2%20LCD%20display.png)**ໃຊ້ໃນການສະແດງຄ່າອຸນຫະພູມທີ່ອ່ານໄດ້ຈາກ LM35**

---
### 16. I2C Serial Adapter board module

**I2C Serial Adapter board module** ແມ່ນໂມດູນທີ່ຕິດຕັ້ງຢູ່ດ້ານຫຼັງຂອງ 16x2 LCD ເພື່ອແປງການສື່ສານແບບ Parallel ຂອງ LCD ໃຫ້ເປັນການສື່ສານແບບ I2C Serial.

ມັນໃຊ້ໂປຣໂຕຄໍ I2C, ເຊິ່ງຕ້ອງການພຽງແຕ່ **ສອງສາຍ** (SDA - Data ແລະ SCL - Clock) ບວກກັບ VCC ແລະ GND, ເພື່ອຄວບຄຸມ LCD. ນີ້ຊ່ວຍປະຢັດ Pin ດິຈິຕອລສ່ວນໃຫຍ່ຂອງ Arduino ໄວ້ສຳລັບການໃຊ້ງານອື່ນ.

**Pins:** VCC, GND, SDA (Analog Pin A4 ຂອງ Uno), SCL (Analog Pin A5 ຂອງ Uno). ຕ້ອງການຫ້ອງສະໝຸດ **LiquidCrystal_I2C** ເພື່ອຄວບຄຸມ. ມັນມັກຈະມີຕົວປັບຄວາມຄົມຊັດ (Potentiometer) ໃນຕົວ.

![example.jpg](./photo/I2C%20Serial%20Adapter%20board%20module.png)

![example.jpg](./photo/schemetic%20I2C%20Serial%20Adapter%20board%20module.png)**ໃຊ້ໃນການເຊື່ອມຕໍ່ LCD 16x2 ກັບ Arduino ໂດຍໃຊ້ພຽງ 4 ສາຍ**

---
### 17. 7-segment display (Common Cathode +)

**7-Segment Display** ແມ່ນຮູບແບບການສະແດງຜົນເອເລັກໂຕຣນິກທີ່ໃຊ້ LED ເຈັດອັນ (ເຊັ່ນ: ແຕ່ລະອັນເປັນ "segment") ເພື່ອສະແດງຕົວເລກ 0 ຫາ 9. ຊຸດປະກອບມີແບບ **Common Cathode**.

ໃນແບບ **Common Cathode**, ຂາ Cathode ທັງໝົດຂອງ LED ທັງເຈັດຖືກເຊື່ອມຕໍ່ເຂົ້າກັນກັບ Ground (GND) ຜ່ານ Resistor. ເພື່ອເຮັດໃຫ້ segment ໃດນຶ່ງສະຫວ່າງ, ທ່ານຕ້ອງສົ່ງສັນຍານ **HIGH (5V)** ໄປຫາ Pin Anode ຂອງ segment ນັ້ນ.

**Pins:** ປົກກະຕິແລ້ວແມ່ນ 10 Pins (8 segments + 2 Common). * **Etc...:** ຕ້ອງໃຊ້ Resistor (ເຊັ່ນ: 220Ω) ສຳລັບແຕ່ລະ segment

![example.jpg](./photo/7-segment%20display%20(Common%20Cathode%20+).png)
![example.jpg](./photo/schemetic%207-segment%20display%20(Common%20Cathode%20+).png)**ການສະແດງເຄື່ອງນັບແບບງ່າຍດາຍ (Simple Numeric Counter)**

---

### 18. 4-Digit 7-Segment Display

**4-Digit 7-Segment Display** ແມ່ນການລວມຂອງ 7-segment display ສີ່ອັນເຂົ້າກັນເພື່ອສະແດງຕົວເລກສີ່ຕົວ.

ມັນໃຊ້ເຕັກນິກທີ່ເອີ້ນວ່າ **Multiplexing** ເພື່ອຄວບຄຸມທັງສີ່ຕົວເລກ. ໂດຍການເປີດ/ປິດແຕ່ລະຕົວເລກຢ່າງວ່ອງໄວໃນລຳດັບ (ເຊັ່ນ: ຕົວເລກ 1 > ຕົວເລກ 2 > ຕົວເລກ 3 > ຕົວເລກ 4), ຕາຂອງມະນຸດຈະຮັບຮູ້ວ່າພວກມັນສະແດງຜົນພ້ອມກັນ.

**Pins:** ມີ 8 Segment Pins ແລະ 4 Digit Control Pins. * **Etc...:** ມັກຈະມາພ້ອມກັບ Chip Driver (ເຊັ່ນ: TM1637) ທີ່ເຮັດໃຫ້ການເຊື່ອມຕໍ່ງ່າຍຂຶ້ນ (ໃຊ້ພຽງ 2 ຫາ 3 ສາຍ)
![example.jpg](./photo/4-Digit%207-Segment%20Display.png)


![example.jpg](./photo/schemetic%204-Digit%207-Segment%20Display.png)**ການສ້າງໂມງດິຈິຕອລ (Digital Clock)**

---
### 19. 8x8 Dot Matrix display

**8x8 Dot Matrix Display** ແມ່ນຈໍສະແດງຜົນທີ່ປະກອບດ້ວຍໄຟ LED 64 ດອກ ທີ່ຈັດຢູ່ໃນຮູບແບບຕາຂ່າຍ 8 ແຖວ x 8 ຖັນ.

ມັນຍັງໃຊ້ເຕັກນິກ **Multiplexing** ເພື່ອຄວບຄຸມ LED 64 ດອກດ້ວຍຈໍານວນ Pin ທີ່ຈຳກັດ (ເຊັ່ນ: 16 Pin). ແຕ່ລະຈຸດ (Dot) ຖືກຄວບຄຸມໂດຍການສົ່ງສັນຍານໄປຫາແຖວ ແລະ ຖັນທີ່ກົງກັນ.

**Pins:** 8 Pins ສຳລັບແຖວ ແລະ 8 Pins ສຳລັບຖັນ. * **Etc...:** ມັກຈະຖືກໃຊ້ກັບ Chip Driver ເຊັ່ນ **MAX7219** (ເຊິ່ງຫຼຸດການເຊື່ອມຕໍ່ລົງເຫຼືອພຽງ 3 ສາຍ) ເພື່ອສະແດງຂໍ້ຄວາມ ແລະ ຮູບແບບ (patterns)

![example.jpg](./photo/8x8%20Dot%20Matrix%20display.png)

![example.jpg](./photo/schemetic%208x8%20Dot%20Matrix%20display.png)**ການສະແດງຂໍ້ຄວາມແບບເລື່ອນໄດ້ (Scrolling Text Marquee)**

---
### 20. Temperature and humidity sensor (DHT11)

**DHT11** ແມ່ນເຊັນເຊີທີ່ໃຊ້ສຳລັບວັດແທກ **ອຸນຫະພູມ (Temperature)** ແລະ **ຄວາມຊຸ່ມຊື່ນ (Humidity)** ຂອງອາກາດ.

ມັນໃຊ້ການສື່ສານແບບ serial ດິຈິຕອລສາຍດຽວ (one-wire digital serial) ເພື່ອສົ່ງຂໍ້ມູນໄປຫາ Arduino. ມັນວັດແທກຄວາມຊຸ່ມຊື່ນໂດຍໃຊ້ສ່ວນປະກອບທີ່ຮັບຮູ້ຄວາມຊຸ່ມຊື່ນ ແລະ ວັດແທກອຸນຫະພູມໂດຍໃຊ້ Thermistor.

**Pins:** VCC (+), GND (-), ແລະ Data Pin (ເຊື່ອມຕໍ່ກັບ Digital Pin ຂອງ Arduino).ຕ້ອງການຫ້ອງສະໝຸດ DHT ພິເສດເພື່ອອ່ານຂໍ້ມູນ ແລະ ໂວນການເຮັດວຽກແມ່ນ 3.3V ຫາ 5V

![example.jpg](./photo/Temperature%20and%20humidity%20sensor%20(DHT11).png)

![example.jpg](./photo/schemetic%20Temperature%20and%20humidity%20sensor%20(DHT11).png)**ໃຊ້ເພື່ອກວດເຊັກຄວາມສົມດູນຂອງອຸນຫະພູມ ແລະ ຄວາມຊຸ່ມ (Basic Weather Station)**

---

### 21. LM35 Temperature Sensor

**LM35** ແມ່ນເຊັນເຊີອຸນຫະພູມທີ່ສົ່ງອອກ **ສັນຍານໂວນອະນາລັອກ (Analog Voltage)** ທີ່ເປັນເສັ້ນຊື່ຕາມອຸນຫະພູມໃນອົງສາ Celsius.

ມັນຜະລິດໂວນສົ່ງອອກ $10mV$ ຕໍ່ $1^\circ C$129. ຕົວຢ່າງ: ຖ້າອຸນຫະພູມແມ່ນ $25^\circ C$, ໂວນສົ່ງອອກຈະແມ່ນ $250mV$ ($0.25V$). Arduino ອ່ານໂວນນີ້ຜ່ານ Pin ອະນາລັອກ ແລະ ປ່ຽນມັນເປັນອຸນຫະພູມທີ່ແທ້ຈິງໃນລະຫັດ130.

**Pins:** VCC (Power), GND (Ground), ແລະ Output (ເຊື່ອມຕໍ່ກັບ Analog Pin ຂອງ Arduino)133. ມີຄວາມຖືກຕ້ອງສູງ (Typical accuracy is $\pm 0.5^\circ C$ at $25^\circ C$)134.

![example.jpg](./photo/LM35%20Temperature%20Sensor.png)
**ໃຊ້ໃນການວັດແທກອຸນຫະພູມຫ້ອງ ແລະ ການສະແດງຜົນເທິງ Serial Monitor**

---

### 22. Tilt sensor (x2)

**Tilt Sensor** ແມ່ນສະວິດທີ່ໃຊ້ວັດຖຸໂລຫະທີ່ເຄື່ອນທີ່ໄດ້ (ເຊັ່ນ: ລູກປັດ) ຢູ່ພາຍໃນເພື່ອກວດພົບການປ່ຽນແປງຂອງມຸມ ຫຼື ຄວາມອຽງ.

ເມື່ອເຊັນເຊີຖືກອຽງໄປໃນມຸມທີ່ແນ່ນອນ, ວັດຖຸໂລຫະພາຍໃນຈະຕິດຕໍ່ກັບສອງຂົ້ວໄຟຟ້າ, ປິດວົງຈອນ. ມັນເຮັດໜ້າທີ່ຄືກັບສະວິດດິຈິຕອລ: ເປັນ **ON** ເມື່ອອຽງ ແລະ **OFF** ເມື່ອຢູ່ໃນສະຖານະອື່ນ.

**Pins:** VCC/Signal, GND. ມັນເປັນເຊັນເຊີການປ້ອນຂໍ້ມູນດິຈິຕອລທີ່ດີສຳລັບການກວດພົບການເຄື່ອນໄຫວແບບງ່າຍດາຍ.
![example.jpg](./photo/Tilt%20sensor%20(x2).png)


**ໃຊ້ໃນການເຮັດໃຫ້ LED ຕິດເມື່ອເຊັນເຊີຖືກອຽງ (Tilt-Activated Light)**

### 23. Photoresistor (LDRs x3)

**Photoresistor (Light Dependent Resistor - LDR)** ແມ່ນ Resistor ທີ່ຄ່າຄວາມຕ້ານທານປ່ຽນແປງໄປຕາມຄວາມເຂັ້ມຂອງແສງທີ່ຕົກໃສ່ມັນ.

**ຊື່ອຸປະກອນ:** Photoresistor (LDRs) **ຮູບພາບຕົວຈິງ:** (ໃສ່ຮູບພາບຈິງຂອງ LDR) **ແຜນວາດ Schematic:** (ໃສ່ສັນຍາລັກຂອງ LDR) * **Pins:** ສອງຂາທີ່ບໍ່ມີຂົ້ວໄຟຟ້າ. * **Etc...:** ຖືກໃຊ້ເພື່ອວັດແທກຄວາມສະຫວ່າງຂອງສະພາບແວດລ້ອມ

ເມື່ອແສງສະຫວ່າງເພີ່ມຂຶ້ນ, ຄວາມຕ້ານທານຂອງ LDR ຈະ **ຫຼຸດລົງ**. ໃນຄວາມມືດ, ຄວາມຕ້ານທານຈະ **ສູງສຸດ**. ມັນຖືກໃຊ້ໃນວົງຈອນ Voltage Divider ຮ່ວມກັບ Resistor ຄ່າຄົງທີ່ (ເຊັ່ນ: 10kΩ) ເພື່ອປ່ຽນຄວາມເຂັ້ມແສງໃຫ້ເປັນຄ່າໂວນອະນາລັອກທີ່ Arduino ສາມາດອ່ານໄດ້.

![example.jpg](./photo/Photoresistor%20(LDRs%20x3).png)

![example.jpg](./photo/schemetic%20Photoresistor%20(LDRs%20x3).png)**ໃຊ້ໃນການສ້າງລະບົບໄຟເປີດ/ປິດອັດຕະໂນມັດໃນເວລາກາງຄືນ (Automatic Night Light)**

### 24. PIR sensor

**PIR Sensor (Passive Infrared Sensor)** ແມ່ນເຊັນເຊີທີ່ໃຊ້ສຳລັບກວດພົບການເຄື່ອນໄຫວຂອງມະນຸດ ຫຼື ສັດໃຫຍ່ໂດຍການວັດແທກການປ່ຽນແປງຂອງລະດັບລັງສີອິນຟຣາເຣດທີ່ປ່ອຍອອກມາຈາກສິ່ງມີຊີວິດ.

ຖ້າວັດຖຸທີ່ອົບອຸ່ນ (ເຊັ່ນ: ມະນຸດ) ເຄື່ອນທີ່ຜ່ານພື້ນທີ່ການກວດພົບ, ມັນຈະເຮັດໃຫ້ເຊັນເຊີປ່ຽນສະຖານະ Output ຈາກ LOW ເປັນ **HIGH**. ມັນສົ່ງສັນຍານ Output ແບບດິຈິຕອລ (Motion Detected / No Motion).

**ຊື່ອຸປະກອນ:** PIR sensor **ຮູບພາບຕົວຈິງ:** (ໃສ່ຮູບພາບຈິງຂອງ PIR Module) **ແຜນວາດ Pinout (Diagram):** * **Pins:** VCC, GND, ແລະ Output (ເຊື່ອມຕໍ່ກັບ Digital Pin ຂອງ Arduino). * **Etc...:** ມັກຈະມີຕົວປັບສອງອັນເພື່ອຄວບຄຸມຄວາມໄວ ແລະ ຄວາມອ່ອນໄຫວຂອງການກວດພົບ.
![example.jpg](./photo/PIR%20sensor.png)
![example.jpg](./photo/schemetic%20PIR%20sensor.png)**ໃຊ້ໃນການສ້າງລະບົບເຕືອນການບຸກລຸກ (Intruder Alarm System)**

### 25. Ultrasonic module

**Ultrasonic Module (HC-SR04)** ແມ່ນເຊັນເຊີໄລຍະຫ່າງທີ່ໃຊ້ຄື້ນສຽງຄວາມຖີ່ສູງ (ultrasound) ເພື່ອວັດແທກໄລຍະຫ່າງເຖິງວັດຖຸ.

ມັນສົ່ງຄື້ນສຽງ ultrasonic ອອກໄປຈາກຕົວສົ່ງ (Transmitter) ແລະ ຮັບຄື້ນທີ່ສະທ້ອນກັບຄືນມາໂດຍຕົວຮັບ (Receiver). Arduino ຄິດໄລ່ໄລຍະຫ່າງໂດຍອີງໃສ່ເວລາທີ່ຄື້ນສຽງໃຊ້ໃນການເດີນທາງໄປ-ກັບ (Time of Flight).

**ຊື່ອຸປະກອນ:** Ultrasonic module **Pins:** VCC, GND, **Trig** (Trigger - ເລີ່ມຕົ້ນການສົ່ງຄື້ນສຽງ), ແລະ **Echo** (ຮັບຄື້ນສຽງກັບຄືນ).
![example.jpg](./photo/Ultrasonic%20module.png)
![example.jpg](./photo/schemetic%20Ultrasonic%20module.png)**ໃຊ້ໃນການສ້າງເຊັນເຊີຖອຍຫຼັງສຳລັບລົດຫຸ່ນຍົນ (Parking Sensor)**

### 26. Sound sensor

**Sound Sensor (Microphone Module)** ແມ່ນໂມດູນທີ່ໃຊ້ໄມໂຄຣໂຟນ (microphone) ເພື່ອກວດພົບຄວາມເຂັ້ມຂອງສຽງໃນສະພາບແວດລ້ອມ.

**Sound Sensor (Microphone Module)** ແມ່ນໂມດູນທີ່ໃຊ້ໄມໂຄຣໂຟນ (microphone) ເພື່ອກວດພົບຄວາມເຂັ້ມຂອງສຽງໃນສະພາບແວດລ້ອມ.

**Pins:** VCC, GND, DO (Digital Output), ແລະ AO (Analog Output). Output ອະນາລັອກຊ່ວຍໃຫ້ສາມາດວິເຄາະຮູບແບບສຽງທີ່ຊັບຊ້ອນກວ່າ.
![example.jpg](./photo/Sound%20sensor.png)
![example.jpg](./photo/schemetic%20Sound%20sensor.png)**ໃຊ້ໃນການສ້າງສະວິດທີ່ຄວບຄຸມດ້ວຍການຕົບມື (Clap-Activated Switch)**

### 27. Water sensor

**Water Sensor** ແມ່ນໂມດູນທີ່ໃຊ້ສຳລັບກວດພົບລະດັບ ຫຼື ການມີຢູ່ຂອງນ້ຳໂດຍອີງໃສ່ການນໍາໄຟຟ້າຂອງມັນ.

ມັນມີແຖບໂລຫະທີ່ຕິດກັນທີ່ໃຊ້ເປັນຕົວນໍາ. ເມື່ອນ້ຳສໍາຜັດກັບແຖບເຫຼົ່ານີ້, ມັນຈະເຮັດໃຫ້ເກີດການເຊື່ອມຕໍ່ທາງໄຟຟ້າລະຫວ່າງພວກມັນ. ມັນສົ່ງ Output ອະນາລັອກທີ່ປ່ຽນແປງຕາມປະລິມານຂອງແຖບທີ່ສໍາຜັດກັບນ້ຳ, ເຊິ່ງ Arduino ສາມາດອ່ານໄດ້
![example.jpg](./photo/Water%20sensor.png)

![example.jpg](./photo/schemetic%20Water%20sensor.png)**ໃຊ້ໃນການສ້າງລະບົບເຕືອນການຮົ່ວໄຫຼຂອງນ້ຳ (Water Leak Detection Alarm)**

### 28. Flame sensor

**Flame Sensor** ແມ່ນເຊັນເຊີທີ່ອອກແບບມາເພື່ອກວດພົບຄື້ນແສງອິນຟຣາເຣດ (IR) ທີ່ປ່ອຍອອກມາຈາກໄຟ.

ມັນໃຊ້ phototransistor ຫຼື photodiode ທີ່ລະອຽດອ່ອນຕໍ່ແສງ IR ທີ່ມີຄວາມຍາວຄື້ນ $760nm$ ຫາ $1100nm$185. ເມື່ອແປວໄຟຖືກກວດພົບ, ໂມດູນຈະສົ່ງ Output ດິຈິຕອລ LOW ຫຼື Output ອະນາລັອກທີ່ສະແດງຄວາມເຂັ້ມຂອງແປ

![example.jpg](./photo/Flame%20sensor.png)
![example.jpg](./photo/schemetic%20Flame%20sensor.png)
**Pins:** VCC, GND, DO (Digital Output), ແລະ AO (Analog Output).

**ໃຊ້ໃນການສ້າງຫຸ່ນຍົນກວດພົບໄຟ (Fire Detecting Robot)**

### 29. RFID module

**RFID Module (ເຊັ່ນ: RC522)** ແມ່ນອຸປະກອນທີ່ອະນຸຍາດໃຫ້ Arduino ສາມາດອ່ານ ແລະ ຂຽນຂໍ້ມູນໄປຫາ RFID Tags (ເຊັ່ນ: key fobs ຫຼື cards). RFID ຫຍໍ້ມາຈາກ **Radio-Frequency Identification**

ໂມດູນສ້າງສະໜາມແມ່ເຫຼັກໄຟຟ້າ. ເມື່ອ Tag ເຂົ້າສູ່ສະໜາມນີ້, Tag ຈະໄດ້ຮັບພະລັງງານ ແລະ ສົ່ງຂໍ້ມູນທີ່ເປັນເອກະລັກຂອງມັນກັບຄືນໄປຫາໂມດູນ. ໂມດູນສື່ສານກັບ Arduino ໂດຍໃຊ້ໂປຣໂຕຄໍ SPI.

**Pins:** VCC, GND, RST, MISO, MOSI, SCK, SDA (Pins ທີ່ໃຊ້ສຳລັບການສື່ສານ SPI). ໂປຣໂຕຄໍການສື່ສານຫຼັກແມ່ນ SPI. ຕ້ອງການຫ້ອງສະໝຸດ MFRC522 ເພື່ອຄວບຄຸມ.

![example.jpg](./photo/RFID%20module.png)
![example.jpg](./photo/schemetic%20RFID%20module.png)**ໃຊ້ໃນການສ້າງລະບົບລັອກປະຕູທີ່ຄວບຄຸມດ້ວຍ RFID (RFID Access Control)**

### 30. RFID tag

**RFID Tag** (ມັກຈະເປັນບັດ ຫຼື key fob) ແມ່ນອຸປະກອນເກັບຂໍ້ມູນຕົວຕັ້ງຕົວຕີ (Passive) ທີ່ບັນຈຸ chip ແລະ ເສົາອາກາດ (antenna).

ມັນບໍ່ມີແບັດເຕີຣີ. ມັນໄດ້ຮັບພະລັງງານຈາກສະໜາມແມ່ເຫຼັກໄຟຟ້າທີ່ປ່ອຍອອກມາໂດຍ RFID Module. ເມື່ອມີພະລັງງານ, ມັນສົ່ງຂໍ້ມູນທີ່ເປັນເອກະລັກຂອງມັນ (UID) ກັບຄືນໄປຫາໂມດູນເພື່ອການກວດສອບ.
![example.jpg](./photo/RFID%20tag.png)
**ໃຊ້ໃນການເປີດ/ປິດໄຟຕາມການກວດສອບບັດທີ່ຖືກຕ້ອງ (Key Card Authentication)**

### 31. Infrared receiver

**Infrared Receiver (IR Receiver)** ແມ່ນສ່ວນປະກອບທີ່ໃຊ້ສຳລັບຮັບຄື້ນແສງອິນຟຣາເຣດ (IR) ທີ່ຖືກເຂົ້າລະຫັດ (encoded) ຈາກຣີໂໝດຄວບຄຸມ (remote control).

ມັນມີ Photodiode ທີ່ຖືກປັບໃຫ້ກົງກັບຄວາມຖີ່ຂອງສັນຍານ IR ທີ່ມາຈາກຣີໂໝດ (ປົກກະຕິແລ້ວແມ່ນ $38kHz$)209. ມັນແປງສັນຍານ IR ທີ່ໄດ້ຮັບໃຫ້ເປັນສັນຍານດິຈິຕອລທີ່ Arduino ສາມາດຖອດລະຫັດໄດ້ເພື່ອລະບຸປຸ່ມໃດທີ່ຖືກກົດ210.

**Pins:** VCC, GND, ແລະ Output (ເຊື່ອມຕໍ່ກັບ Digital Pin ຂອງ Arduino). ຕ້ອງການຫ້ອງສະໝຸດ **IRremote** ເພື່ອຖອດລະຫັດສັນຍານທີ່ໄດ້ຮັບ.
![example.jpg](./photo/Infrared%20receiver.png)
![example.jpg](./photo/schemetic%20Infrared%20receiver.png)
**ການຄວບຄຸມອົງປະກອບໂດຍໃຊ້ຣີໂໝດ TV (Remote Control of LEDs/Motors)**

### 32. Infrared remote control

**Infrared Remote Control (IR Remote)** ແມ່ນເຄື່ອງສົ່ງສັນຍານມືຖືທີ່ໃຊ້ສຳລັບການຄວບຄຸມອຸປະກອນຕ່າງໆ (ເຊັ່ນ: Arduino) ຈາກໄລຍະໄກໂດຍການສົ່ງຄື້ນແສງອິນຟຣາເຣດທີ່ຖືກເຂົ້າລະຫັດ.

ເມື່ອປຸ່ມຖືກກົດ, ມັນຈະສົ່ງສັນຍານ IR ທີ່ເປັນເອກະລັກທີ່ປະກອບດ້ວຍ **Address Code** (ລະບຸອຸປະກອນ) ແລະ **Command Code** (ລະບຸປຸ່ມ). ໄຟ LED IR ຢູ່ປາຍສຸດຂອງຣີໂໝດປ່ອຍຄື້ນແສງນີ້ອອກມາ.
![example.jpg](./photo/Infrared%20remote%20control.png)
**ໃຊ້ໃນການຄວບຄຸມລະດັບສຽງຂອງ Passive Buzzer ຈາກໄລຍະໄກ**

### 33. Joystick module

**Joystick Module (ເຊັ່ນ: PS2 Joystick)** ແມ່ນອຸປະກອນປ້ອນຂໍ້ມູນທີ່ໃຊ້ອ່ານການເຄື່ອນໄຫວສອງແກນ (X ແລະ Y) ແລະ ສະຖານະປຸ່ມກົດ (Button State)

ມັນໃຊ້ **ສອງ Potentiometer** (ໜຶ່ງສຳລັບແກນ X ແລະ ອີກອັນສຳລັບແກນ Y) ເພື່ອປ່ຽນການເຄື່ອນໄຫວຂອງແກນໃຫ້ເປັນຄ່າໂວນອະນາລັອກ (0-5V). ມັນຍັງມີປຸ່ມກົດ (Switch) ຢູ່ໃນແກນຕັ້ງທີ່ສົ່ງ Output ດິຈິຕອລເມື່ອຖືກກົດລົງ.
![example.jpg](./photo/Joystick%20module.png)
![example.jpg](./photo/schemetic%20Joystick%20module.pngg)
**ໃຊ້ໃນການຄວບຄຸມທິດທາງຂອງ Servo Motor ສອງອັນ (Two-Axis Motor Control)**

### 34. 4x4 Matrix Keyboard Module

**4x4 Matrix Keyboard Module** ແມ່ນແປ້ນພິມຂະໜາດນ້ອຍທີ່ມີ 16 ປຸ່ມ (4 ແຖວ ແລະ 4 ຖັນ).

ມັນໃຊ້ເຕັກນິກ **Matrix Keypad Scanning** ເພື່ອຫຼຸດຈຳນວນ Pin ທີ່ຕ້ອງການ. ແທນທີ່ຈະໃຊ້ 16 Pin, ມັນໃຊ້ພຽງ 8 Pin (4 ສຳລັບແຖວ, 4 ສຳລັບຖັນ). Arduino ຈະສະແກນແຕ່ລະຖັນ, ແລະ ອ່ານແຖວໃດທີ່ມີການກົດປຸ່ມ.
![example.jpg](./photo/4x4%20Matrix%20Keyboard%20Module.png)
![example.jpg](./photo/schemetic%204x4%20Matrix%20Keyboard%20Module.png)
**ໃຊ້ໃນການສ້າງລະບົບປ້ອນລະຫັດລັບ (Keypad Combination Lock)**

### 35. Relay module

**Relay Module** ແມ່ນສະວິດຄວບຄຸມໄຟຟ້າທີ່ອະນຸຍາດໃຫ້ວົງຈອນໂວນຕ່ຳ (ເຊັ່ນ: 5V ຂອງ Arduino) ສາມາດຄວບຄຸມວົງຈອນໂວນສູງ (ເຊັ່ນ: 120V/240V AC).

ເມື່ອ Arduino ສົ່ງສັນຍານ HIGH ໄປຫາໂມດູນ, ມັນຈະເປີດ/ປິດວົງຈອນແມ່ເຫຼັກ (solenoid) ທີ່ເຮັດໃຫ້ສະວິດພາຍໃນປ່ຽນສະຖານະ: * **Normally Open (NO)** ຈະປິດ. * **Normally Closed (NC)** ຈະເປີດ.

**Control Pins:** VCC, GND, Input Signal (ເຊື່ອມຕໍ່ກັບ Digital Pin ຂອງ Arduino). * **Load Pins:** NO, NC, COM (Common).ໃຫ້ຄວາມປອດໄພທາງໄຟຟ້າ (Isolation) ລະຫວ່າງວົງຈອນຄວບຄຸມ (Arduino) ແລະ ໂວນສູງ.
![example.jpg](./photo/Relay%20module.png)
![example.jpg](./photo/schemetic%20Relay%20module.png)
**ໃຊ້ໃນການເປີດ/ປິດໂຄມໄຟທີ່ໃຊ້ໄຟບ້ານໂດຍໃຊ້ Arduino (AC Light Control)**

### 36. Servo motor

**Servo Motor** ແມ່ນມໍເຕີ DC ທີ່ອະນຸຍາດໃຫ້ມີການຄວບຄຸມມຸມທີ່ຊັດເຈນ (ປົກກະຕິແລ້ວແມ່ນ $0^\circ$ ຫາ $180^\circ$)

ມັນຖືກຄວບຄຸມໂດຍໃຊ້ສັນຍານ **PWM (Pulse Width Modulation)** ຈາກ Arduino. ຄວາມກວ້າງຂອງ Pulse ກໍານົດມຸມທີ່ Shaft ຂອງມໍເຕີຄວນໝູນໄປ. ມັນມີວົງຈອນ Feedback ເພື່ອຮັກສາມຸມທີ່ກໍານົດໄວ້.

**Wires:** Power (ແດງ), Ground (ສີນ້ຳຕານ/ດຳ), ແລະ Signal (ສີສົ້ມ/ເຫຼືອງ - ເຊື່ອມຕໍ່ກັບ PWM Pin ຂອງ Arduino). ຕ້ອງການຫ້ອງສະໝຸດ **Servo.h** ເພື່ອຄວບຄຸມ.
![example.jpg](./photo/Servo%20motor.png)
![example.jpg](./photo/schemetic%20Servo%20motor.png)
**ໃຊ້ໃນການເປີດ/ປິດປະຕູອັດຕະໂນມັດ (Automated Door Opener)**

### 37. Stepper motor

**Stepper Motor** ແມ່ນມໍເຕີ DC ທີ່ໝູນເປັນບາດກ້າວທີ່ຊັດເຈນ (Fixed Increments) ແທນທີ່ຈະໝູນຕໍ່ເນື່ອງ.

ມັນມີຫຼາຍ Coils (ເຊັ່ນ: 4 Coils). ໂດຍການສະໜອງພະລັງງານໃຫ້ກັບ Coils ເຫຼົ່ານີ້ຕາມລໍາດັບທີ່ຖືກຕ້ອງ, ມໍເຕີຈະໝູນໄປເທື່ອລະບາດກ້າວ. ມັນດີສຳລັບໂຄງການທີ່ຕ້ອງການຕໍາແໜ່ງທີ່ຊັດເຈນ (Precision Positioning).

**Wires:** ມີ 5 ຫາ 6 ສາຍ (ສຳລັບ Unipolar Stepper). ຕ້ອງການ Chip Driver ພິເສດ (ເຊັ່ນ: ULN2003 ຫຼື A4988) ເພື່ອຄວບຄຸມກະແສໄຟຟ້າທີ່ສູງທີ່ຈຳເປັນ.
![example.jpg](./photo/Stepper%20motorr.png)
![example.jpg](./photo/schemetic%20Stepper%20motor.png)
**ໃຊ້ໃນການຄວບຄຸມແຂນຫຸ່ນຍົນ ຫຼື ຫົວພິມ 3D (Precise Robotic Arm Movement)**

### 38. Stepper motor driver board

**Stepper Motor Driver Board (ເຊັ່ນ: ULN2003 Driver)** ແມ່ນແຜງວົງຈອນທີ່ຈຳເປັນສຳລັບການຄວບຄຸມ Stepper Motor.

ມັນເຮັດໜ້າທີ່ເປັນໂຕເຊື່ອມຕໍ່ລະຫວ່າງ Arduino (ສົ່ງສັນຍານໂວນຕ່ຳ) ແລະ Stepper Motor (ຕ້ອງການກະແສໄຟຟ້າສູງ). Chip Driver ຈະຂະຫຍາຍສັນຍານດິຈິຕອລຂອງ Arduino ໃຫ້ເປັນກະແສໄຟຟ້າທີ່ສູງຂຶ້ນເພື່ອສະຫຼັບ Coils ຂອງມໍເຕີຕາມລໍາດັບ.

**Input Pins:** IN1, IN2, IN3, IN4 (ເຊື່ອມຕໍ່ກັບ Digital Pins ຂອງ Arduino). * **Output Pins:** ປລັກສຽບສຳລັບ Stepper Motor, VCC, GND. ປົກປ້ອງ Pin ຂອງ Arduino ຈາກກະແສໄຟຟ້າທີ່ສູງທີ່ມໍເຕີຕ້ອງການ.

![example.jpg](./photo/Stepper%20motor%20driver%20board.png)
![example.jpg](./photo/schemetic%20Stepper%20motor%20driver%20board.png)
**ໃຊ້ໃນການໝູນ Stepper Motor ໄປທາງໜ້າ ແລະ ຫຼັງ (Forward and Reverse Stepping)**

### 39. Real-time Clock Module DS1302

**Real-Time Clock Module (RTC) DS1302** ແມ່ນໂມດູນທີ່ຕິດຕາມເວລາປັດຈຸບັນ (ປີ, ເດືອນ, ວັນທີ, ມື້, ຊົ່ວໂມງ, ນາທີ, ວິນາທີ) ຢ່າງຖືກຕ້ອງ, ໂດຍມີແບັດເຕີຣີສໍາຮອງເພື່ອຮັກສາເວລາແມ້ວ່າໄຟຈະດັບ.

ມັນສື່ສານກັບ Arduino ໂດຍໃຊ້ໂປຣໂຕຄໍ **3-Wire Serial Interface**. ໂມດູນມີ Crystal Oscillator ຂອງມັນເອງທີ່ເຮັດໃຫ້ມັນສາມາດນັບເວລາໄດ້ຢ່າງຊັດເຈນໂດຍບໍ່ຕ້ອງເພິ່ງພາໂມງຂອງ Arduino.

**Pins:** VCC, GND, CLK (Clock), DAT (Data), RST (Reset). ມັກຈະໃຊ້ແບັດເຕີຣີ CR2032 3V ເພື່ອສໍາຮອງຂໍ້ມູນເວລາ. ຖືກໃຊ້ໃນໂຄງການທີ່ຕ້ອງການເວລາທີ່ຖືກຕ້ອງ.
![example.jpg](./photo/Real-time%20Clock%20Module%20DS1302.png)
![example.jpg](./photo/schemetic%20Real-time%20Clock%20Module%20DS1302.png)
**ໃຊ້ໃນການສ້າງໂມງທີ່ມີການສະແດງວັນທີ (Displaying Date and Time on LCD)**

### 40. 74HC595 Chip

**74HC595 Chip** ແມ່ນ **Shift Register** ທີ່ໃຊ້ສຳລັບການຂະຫຍາຍ Output ຂອງ Arduino. ມັນສາມາດປ່ຽນສັນຍານ Serial (ຂໍ້ຄວາມຕໍ່ເນື່ອງ) ເປັນສັນຍານ Parallel (ຫຼາຍ Output ພ້ອມກັນ).

ມັນອະນຸຍາດໃຫ້ Arduino ຄວບຄຸມເຖິງ **8 Output** ໂດຍໃຊ້ພຽງແຕ່ **3 Pin** ດິຈິຕອລ. Arduino ສົ່ງຂໍ້ມູນ 8 bits ຢ່າງຕໍ່ເນື່ອງ (Serial) ໄປຫາ Chip, ແລະ Chip ຈະເກັບຂໍ້ມູນນີ້ໄວ້ ແລະ ປ່ອຍມັນອອກມາພ້ອມກັນ (Parallel).

**Pins:** VCC, GND, DS (Data Serial Input), SHCP (Shift Register Clock), STCP (Storage Register Clock), Q0-Q7 (Parallel Outputs). ໃຊ້ສຳລັບການຄວບຄຸມໄຟ LED ຫຼາຍອັນ ຫຼື 7-Segment Display ຫຼາຍອັນ ເພື່ອປະຢັດ Pin ຂອງ Arduino
![example.jpg](./photo/74HC595%20Chip.png)
![example.jpg](./photo/schemetic%2074HC595%20Chip.png)

**ໃຊ້ໃນການຄວບຄຸມໄຟ LED 8 ດອກໂດຍໃຊ້ພຽງ 3 Pin ຂອງ Arduino**