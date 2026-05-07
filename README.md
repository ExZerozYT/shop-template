# ร้านพร้อมขาย

เทมเพลตเว็บหน้าร้านออนไลน์สำหรับแม่ค้า ใช้งานได้กับ GitHub Pages แบบ static ไม่ต้องมี backend

## ไฟล์สำคัญ

- `index.html` หน้าโปรโมต/หน้าแนะนำตัวอย่างบริการ
- `styles.css` สไตล์ของหน้า `index.html`
- `store-template.html` ตัวอย่างหน้าร้านพร้อมแคตตาล็อกสินค้า
- `store-template.css` สไตล์ของหน้า `store-template.html`

## วิธีแก้ลิงก์ LINE

ค้นหา `https://line.me/ti/p/~exzerozyt` แล้วเปลี่ยน `exzerozyt` เป็น LINE ID ของร้าน

ตัวอย่าง:

```html
<a href="https://line.me/ti/p/~LINE_ID" target="_blank" rel="noreferrer">ทัก LINE</a>
```

## วิธีเปิดบน GitHub Pages

1. สร้าง repository ใหม่ใน GitHub
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้เข้า repository
3. ไปที่ `Settings` > `Pages`
4. เลือก `Deploy from a branch`
5. เลือก branch `main` และ folder `/root`
6. กด `Save`

หลังจากนั้น GitHub จะให้ลิงก์เว็บประมาณนี้:

```text
https://username.github.io/repository-name/
```
