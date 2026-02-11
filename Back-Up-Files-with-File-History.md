# การสำรองข้อมูล (Backup)
## 9.5.6 Back up Files with File History

![Lab](9.png)

### คำอธิบาย
ใน Windows 10 มีฟีเจอร์ File History  
ใช้สำหรับสำรองข้อมูลไฟล์แบบอัตโนมัติ โดยสามารถเลือกไดรฟ์ปลายทาง และตั้งค่าระยะเวลาการสำรองข้อมูลได้

---

## Required Actions (สิ่งที่ต้องทำ)

- ตั้งค่าไดรฟ์ backup (Backup E:)
- ตั้งค่า backup แบบรายวัน (Daily)
- เก็บไฟล์ backup เป็นเวลา 6 เดือน
- ทำการ backup โฟลเดอร์ Data (D:)
- สั่ง Make a backup now

---

## ขั้นตอนการทำงาน

![Lab](21.png)

1. คลิกปุ่ม **Start** แล้วเลือก **Settings**  
   ![Lab](3.png)

2. เลือกเมนู **Update & Security**  
   ![Lab](4.png)

3. เลือกเมนู **Backup**  
   ![Lab](5.png)

4. คลิก **Add a drive**  
   ![Lab](6.png)

5. เลือกไดรฟ์ **Backup (E:)**  
   ![Lab](7.png)  
   ![Lab](9.png)

6. เปิดสวิตช์ **Automatically back up my files** เป็น **On**  
   ![Lab](8.png)

7. คลิก **More options**  
   ![Lab](10.png)

8. ตั้งค่า **Back up my files** จาก drop-down menu เป็น **Daily**  
   ![Lab](11.png)

9. ตั้งค่า **Keep my backups** จาก drop-down menu เป็น **6 months**  
   ![Lab](12.png)

10. ตั้งค่า **Back up these folders** แล้วคลิก **Add a folder**  
    ![Lab](14.png)  
    ![Lab](15.png)

11. เลือกโฟลเดอร์ **Data (D:)** แล้วคลิก **Choose this folder**  
    ![Lab](16.png)

12. คลิก **Back up now**  
    ![Lab](17.png)

13. ตรวจสอบความสมบูรณ์ของการ backup เมื่อเสร็จสิ้น

---

## ผลลัพธ์ LAB

![Lab](18.png)

---

## คำศัพท์ที่เกี่ยวข้อง

**File History**  
: ฟีเจอร์ใน Windows สำหรับสำรองข้อมูลไฟล์อัตโนมัติ และสามารถกู้คืนไฟล์ได้

**Backup**  
: การสำรองข้อมูล เพื่อป้องกันข้อมูลสูญหาย

**Update & Security**  
: เมนูสำหรับตั้งค่าการอัปเดต และความปลอดภัยของระบบ

**Automatically back up my files**  
: ตัวเลือกสำหรับเปิดการสำรองข้อมูลอัตโนมัติ

**Daily**  
: การตั้งค่าให้สำรองข้อมูลทุกวัน

**Data (D:)**  
: ไดรฟ์ข้อมูลที่เลือกทำการสำรอง

**Volume**  
: พื้นที่จัดเก็บข้อมูลในไดรฟ์
