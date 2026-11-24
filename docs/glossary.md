# ศัพท์ EN-TH สำหรับซ้อมพรีเซนต์

| ศัพท์ | ความหมาย | จำง่าย ๆ |
|---|---|---|
| ADC (Analog-to-Digital Converter) | ตัวแปลงสัญญาณอนาล็อกเป็นดิจิทัล | ADC = A→D |
| DAC (Digital-to-Analog Converter) | ตัวแปลงสัญญาณดิจิทัลเป็นอนาล็อก | DAC = D→A ตรงข้าม ADC |
| Sampling | การสุ่มค่าสัญญาณเป็นช่วง ๆ | |
| Sampling rate | ความถี่ในการสุ่ม | ยิ่งสูงยิ่งละเอียด |
| Quantization | การปัดค่าให้เป็นระดับจำกัด | เหมือนปัดเกรด |
| Resolution | จำนวนบิตของ ADC | 10-bit = 1,024 ระดับ |
| Nyquist | ต้องสุ่มอย่างน้อย **2 เท่า** ของความถี่สูงสุด | fs ≥ 2·f_max |
| Aliasing | สัญญาณเพี้ยนเพราะสุ่มถี่ไม่พอ | ต่ำกว่า Nyquist = เพี้ยน |

## ประโยคที่ใช้ได้ตอนพรีเซนต์
- "Analog signal is continuous." — สัญญาณอนาล็อกต่อเนื่อง
- "Sampling rate must be at least twice the highest frequency." — ต้องสุ่มอย่างน้อยสองเท่าของความถี่สูงสุด
- "Thank you for listening." — ขอบคุณที่รับฟัง
