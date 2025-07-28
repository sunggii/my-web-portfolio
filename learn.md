# What I learn new thing
## note
* ตัวแปรสี
```css
/* Color Variables */
:root {
    --primary-black: #000000;
    --primary-white: #ffffff;
    --primary-blue: #3573b7;
    --black-blue-gradient: linear-gradient(135deg, #000000 0%, #3573b7 100%);
    --blue-pink-gradient: linear-gradient(135deg, #3573b7, #fecfef);
    --LINE: #06c755; /*สีของ LINE*/
}
```
* อะไรที่ซ้ำๆ เอามาทำเป็น class
* ```min-height: 100vh;``` ใส่ min จะได้ไม่ล้น

## ไอเดียการทำ responsive
```@media screen and (max-width: 768px)``` ให้คิดว่าถ้าหน้าจอเหลือแค่นี้จะจัดหน้ายังไง
1. ลดขนาด font img
2. ```flex-direction: column;``` เพื่อให้เนื้อหาลงมาต่อข้างล่างได้
3. เปลี่ยนการจัดเรียงของ
