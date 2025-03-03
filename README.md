<div id="header" align="center">
  <h1>🔥 เทคนิคการเขียน Prompt (Techniques)</h1>
</div>
<div id="badges" align="center">
  <a href="https://www.facebook.com/KongRuksiamTutorial" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/>
  </a>
  <a href="https://www.youtube.com/@KongRuksiamOfficial" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/>
  </a>
    <a href="https://www.udemy.com/user/kong-ruksiam/" target="_blank">
    <img src="https://img.shields.io/badge/Udemy-A435F0?style=for-the-badge&logo=Udemy&logoColor=white"/>
  </a>
  <a href="https://www.youtube.com/@KongRuksiamOfficial/store" target="_blank">
    <img src="https://img.shields.io/badge/Shopee-EE4D2D?style=for-the-badge&logo=Shopee&logoColor=white"/>
  </a>
  <a href="https://medium.com/@kongruksiam" target="_blank">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/>
  </a>
  <a href="https://codepen.io/kongruksiamstudio" target="_blank">
    <img src="https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white"/>
  </a>
  <a href="https://www.tiktok.com/@kongruksiamstudio" target="_blank">
    <img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white"/>
  </a>
  <br>
  <img src="https://komarev.com/ghpvc/?username=kongruksiamza&style=flat-square&color=blue" alt="kongruksiamza"/>
</div>

## สารบัญเนื้อหา
- [Zero-Shot Prompting](#zero-shot-prompting)
- [One-Shot Prompting](#one-shot-prompting)
- [Few-Shot Prompting](#few-shot-prompting)
- [Chain-of-Thought (CoT) Prompting](#chain-of-thought-cot-prompting) 
- *Role-Play Prompting
- *Counterfactual Prompting
- *Self-Consistency
- *Tree of Thoughts (ToT) Prompting
- *Generated Knowledge Prompting
- *Prompt Chaining
- *Meta Prompting
- *Constitutional AI Prompting

---

## Zero-Shot Prompting

```
แนะนำเมนูอาหารไทยที่เผ็ดน้อยและเหมาะกับเด็กเล็ก
```
```
ช่วยแปลประโยคนี้จากภาษาไทยเป็นภาษาอังกฤษ : ฉันอยากไปเที่ยวญี่ปุ่น
```
```
แนะนำสูตรอาหารง่าย ๆ ที่สามารถทำได้ในเวลาไม่เกิน 30 นาที
```
```
ช่วยตั้งชื่อช่อง YouTube สำหรับคนที่ทำคอนเทนต์เกี่ยวกับไลฟ์สไตล์
```
```
ช่วยคิดคำคมเกี่ยวกับการใช้ชีวิตที่สร้างแรงบันดาลใจ
```
```
แนะนำวิธีถ่ายภาพให้ดูสวยและมืออาชีพมากขึ้น
```

## One-Shot Prompting

```
ช่วยแนะนำจังหวัดที่น่าท่องเที่ยวในประเทศไทย โดยอธิบายเหตุผลสั้นๆที่ฉันควรจะไป ตามตัวอย่างนี้: 
จังหวัด : เชียงใหม่
เหตุผล : เมืองที่มีวัฒนธรรมล้านนา อากาศเย็นสบาย อาหารอร่อย 
```
```
เขียนคำอวยพรวันเกิดที่อบอุ่นและจริงใจ ตามตัวอย่างนี้:
🎉 สุขสันต์วันเกิดนะครับ! ขอให้ปีนี้เป็นปีที่เต็มไปด้วยความสุข ความสำเร็จ และสุขภาพแข็งแรง 🎂✨
ช่วยเขียนคำอวยพรวันเกิดให้เพื่อนร่วมงาน
```

```
ช่วยสร้างแผนการตลาดสำหรับร้านขายเสื้อผ้าออนไลน์
โดยใช้งบประมาณ 10,000 บาท/เดือน โดยใช้ตัวอย่างนี้ : 

สัปดาห์ที่ 1: 
- โฆษณา Facebook (3,000 บาท) 
* กลุ่มเป้าหมาย: ผู้หญิง 25-35 ปี 
* พื้นที่: กรุงเทพฯ และปริมณฑล 
- สร้างคอนเทนต์ TikTok (2 โพสต์/วัน)
```
## Few-Shot Prompting

```
ช่วยเขียนรีวิวร้านอาหารจากข้อความต่อไปนี้ โดยใช้รูปแบบตามตัวอย่าง :

ตัวอย่างที่ 1 
ข้อความ: "ร้านก๋วยเตี๋ยวน้ำซุปอร่อยมาก"
รีวิว: "ร้านก๋วยเตี๋ยวสูตรเด็ด น้ำซุปหอมรสชาติกลมกล่อม เส้นเหนียวนุ่มละมุนลิ้น 4.9/5 ⭐" 

ตัวอย่างที่ 2 
ข้อความ: "ข้าวผัดรสชาติดี บรรยากาศร้านน่านั่ง" 
รีวิว: "ข้าวผัดรสจัดจ้าน บรรยากาศร้านอบอุ่น ราคาเป็นกันเอง 4.5/5 ⭐"

ช่วยเขียนรีวิวจากข้อความนี้: "ร้านกาแฟบรรยากาศดี กาแฟรสชาติกลมกล่อม"
```
```
ช่วยเขียนแคปชั่น Instagram โดยมีองค์ประกอบดังนี้
- ข้อความสั้นๆ อธิบายความรู้สึก/บรรยากาศ ในสถานที่ต่างๆ
- อิโมจิที่เกี่ยวข้อง
- แฮชแท็กที่เหมาะสม 1-2 แฮชแท็ก

ตัวอย่างที่ 1
สถานที่/เหตุการณ์: พระอาทิตย์ตกที่หาดป่าตอง #phuket
แคปชั่น: ความงามของธรรมชาติที่ไม่มีวันเบื่อ 🌅 #phuket #sunset

ตัวอย่างที่ 2
สถานที่/เหตุการณ์: คาเฟ่กลางป่า เชียงใหม่
แคปชั่น: หลบความวุ่นวายมาจิบกาแฟท่ามกลางธรรมชาติ 🌲☕️ #chiangmai #cafehoping

ช่วยเขียนแคปชั่นสำหรับ: น้ำตกเอราวัณ
```
```
ช่วยเขียนประกาศขายของมือสอง โดยมีองค์ประกอบดังนี้ 
- ชื่อสินค้าและรายละเอียดพื้นฐาน 
- สภาพสินค้า/อายุการใช้งาน 
- ราคา 
- อุปกรณ์ที่จะได้รับ 
- วิธีการจัดส่ง/การชำระเงิน 
- ช่องทางติดต่อ

ตัวอย่างที่ 1 
ประกาศ :  ขาย iPhone 12 64GB สีดำ 
- สภาพ 90% มีรอยนิดหน่อยตามการใช้งาน 
- อุปกรณ์: กล่อง, สายชาร์จ, หัวชาร์จของแท้ 
- ราคา 15,000 บาท (ต่อรองได้) 
- ส่ง Kerry เก็บปลายทาง/โอนก่อนส่ง 
- นัดรับได้ที่ BTS อโศก 📞 Line: kongza007

ตัวอย่างที่ 2 
ประกาศ: ขายโน๊ตบุ๊ค Dell สภาพสวย 95% 
- ใช้งานเพียง 6 เดือน รับประกันศูนย์เหลือ 2.5 ปี  
- ราคา 18,500 บาท (จากราคาเต็ม 27,900 บาท) 
- อุปกรณ์ : สายชาร์จพร้อมกระเป๋าสะพาย 
- ส่ง EMS ฟรี / นัดรับเซ็นทรัลเวิลด์📱 โทร 08x-xxx-xxxx

ช่วยเขียนประกาศขาย : "ขายลำโพง Marshall ใช้งาน 1 ปี"
```
## Chain-of-Thought (CoT) Prompting 

```
ฉันต้องการวางแผนมื้อกลางวันสำหรับ 7 วัน โดยคำนึงถึงงบประมาณจำกัด (ประมาณ 1,000 บาทต่อสัปดาห์) 
และต้องการเมนูที่หลากหลายทั้งผักผลไม้และเนื้อสัตว์
ช่วยแสดงขั้นตอนการคิดเพื่อเลือกเมนูที่เหมาะสมและสรุปเมนูในแต่ละวัน
```
```
ฉันมีรายได้ 30,000 บาท/เดือนและมีค่าใช้จ่ายจำเป็น 
20,000 บาท/เดือน ต้องการซื้อรถราคา 600,000 บาทภายใน 2 ปี ช่วยอธิบายขั้นตอนการวางแผนว่าฉันควรวางแผนการออมเงินอย่างไร 
โดยคำนึงถึงรายรับ-รายจ่ายเป้าหมายการออมและระยะเวลา
```
```
ฉันมีงานที่ต้องทำ 4 อย่าง คือ 
ทำรายงานส่งพรุ่งนี้ , ประชุมทีมเวลา 14:00 น. 
ตอบอีเมลลูกค้า 5 ฉบับ , เตรียมพรีเซนต์สัปดาห์หน้า 
ช่วยแสดงขั้นตอนการคิดว่าควรจัดลำดับความสำคัญอย่างไร 
โดยพิจารณาจากกำหนดส่งความเร่งด่วนและเวลาที่ต้องใช้
```

```
ฉันอยากดูซีรีส์ใหม่ที่มีจำนวน 16 ตอน ตอนละ 1 ชั่วโมง 
มีเวลาว่าง 2 ชั่วโมงต่อวัน และต้องการดูให้จบภายใน 2 สัปดาห์ 
ช่วยอธิบายขั้นตอนการวางแผนว่าควรวางแผนดูอย่างไรให้เหมาะสม
```
