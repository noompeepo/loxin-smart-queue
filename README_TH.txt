====================================================================
LOXIN SMART QUEUE SYSTEM v24 FULL PACKAGE (ฉบับตรวจสอบสมบูรณ์ 100%)
====================================================================

[สำคัญ] วิธีเปิดใช้งานที่ถูกต้อง:
  1. แตกไฟล์ ZIP (Extract All) ออกมาเป็นโฟลเดอร์ก่อนเปิดใช้งานทุกครั้ง
     (หากดับเบิลคลิกเปิดไฟล์ index.html จากข้างในไฟล์ ZIP โดยตรงโดยไม่แตกไฟล์
      เบราว์เซอร์จะบล็อกการโหลดสคริปต์และไม่สามารถบันทึกข้อมูลได้)
  2. ดับเบิลคลิกที่ไฟล์ index.html (เปิดได้ทันทีบน Chrome / Edge / Safari / มือถือ)
     หรือใช้ไฟล์ในโฟลเดอร์ windows_desktop_app/Launch_Windows_Queue_App.bat

[รหัสผ่านเข้าสู่ระบบเครื่องออกคิวเริ่มต้น (Staff Login)]:
  - ผู้ดูแลระบบ (Admin):  Username = admin   | Password = 1234
  - ช่องบริการ 1 (Staff):  Username = staff1  | Password = 1111
  - ช่องบริการ 2 (Staff):  Username = staff2  | Password = 2222
  * หรือกดปุ่มลัด "เข้าสู่ระบบด่วน (Admin / ช่องบริการ 1 / ช่องบริการ 2)" บนหน้า Login ได้ทันที

[รายการไฟล์ทั้งหมดในชุด FULL PACKAGE]:
  1. โฟลเดอร์หลัก (Root):
     - index.html        (ไฟล์โปรแกรมหลักฉบับสมบูรณ์)
     - manifest.json     (ตั้งค่าแอป PWA)
     - sw.js             (ระบบแคชทำงานออฟไลน์)
     - icon-192.png      (ไอคอนแอป 192x192)
     - icon-512.png      (ไอคอนแอป 512x512)
     - README_TH.txt     (คู่มือการใช้งาน)
  2. windows_desktop_app/ (สำหรับติดตั้งบน Windows PC / เครื่อง POS):
     - index.html
     - Launch_Windows_Queue_App.bat
     - Launch_Kiosk_Silent_Print_58mm.bat
     - Launch_External_TV_Display.bat
     - Open_Smart_Queue_Windows.vbs
  3. android_pwa_project/ (สำหรับติดตั้งบนแท็บเล็ต / มือถือ Android):
     - index.html, manifest.json, sw.js, icon-192.png, icon-512.png
  4. web_hosting_render_github/ (สำหรับอัปโหลดขึ้น GitHub / Render Static Site):
     - index.html, manifest.json, sw.js, icon-192.png, icon-512.png, render.yaml
====================================================================
