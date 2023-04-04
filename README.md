วิธีการติดตั้งและใช้งาน
    
     ---** การติดตั้ง **---
     1. เข้าไปที่ลิงก์ https://github.com/tars-23/FuturePlanner
     2. Download JAR และ src ใส่ไว้ในโฟลเดอร์โปรเจกต์
     3. ในไฟล์ JAR เป็น Library ที่ต้องนำไปใส่ใน Project constructor 
     File -> Project Structure -> Modules -> Dependencies -> add “+” , -> JARs or Directories , 
     Copy Path จาก JarFile ใน Folderโปรเจคที่ได้แตกไฟล์ไว้แล้วกด CTRL ค้างไว้แล้วกดที่ไฟล์ทั้งหมดจากนั้นแล้วกด OK
     และทำการเลือกไฟล์ที่เราได้นำเข้ามาแล้วกด Apply
     
     
     
     ---** การใช้งาน **---
     Page.1
        ให้เลือกการคำนวณต้องการที่ต้องการ
        
     Deposit Page จะโผล่ขึ้นมาหลังจากกดปุ่ม Deposit
        ใส่ข้อมูลให้ครบแล้วกด Calculate *** หมายเหตุ หากไม่ต้องการทราบมูลค่าในอนาคตให้ใส่ 0 ลงไปในช่อง Enter annual contribute
     
     Tax page จะโผล่ขึ้นมาหลังจากกดปุ่ม Tax
        ใส่ข้อมูลให้ครบแล้วกด Calculate
        
      
     Saving page จะโผล่ขึ้นมาหลังจากกดปุ่ม Saving
        ใส่วันที่และจำนวนเงินที่เก็บได้
        1. คำนวณเงินรวมกด SUM
        2. บันทึกค่าลงตารางกด SAVE
        3. บันทึกออกเป็นไฟล์ text กด EXPORT TO TEXT จากนั้นเลือกว่าจะเก็บไว้ที่ไหนและตั้งชื่อไฟล์กดกัน save
