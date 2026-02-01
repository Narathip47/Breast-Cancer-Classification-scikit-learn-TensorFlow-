# Breast-Cancer-Classification-scikit-learn-TensorFlow-

  มะเร็งเต้านม (Breast Cancer) คือโรคมะเร็งที่เกิดจากการเจริญเติบโตผิดปกติของเซลล์บริเวณเต้านม

# เครื่องมือที่ใช้
- ทำ Neural Network แบบ Sequential Model จาก TensorFlow เพื่อทำ Binary Classification สำหรับการจำแนกมะเร็งเต้านม
- โดยใช้ Sequential Model 32 Node และ epochs 100 ครั้ง ในการ Binary Classification (มีเนื้อร้าย yes / ไม่มีเนื้อร้าย no)

# ผลการทดลอง
- โมเดลมีความแม่นยำ 85.3%
- ค่ากลางที่สุดของโมเดล(0.5)  คือ (17.66,14.45)  คือ radius ≈ 17.66  กับ texture ≈ 14.45  ถ้ามากกว่าค่านี้จะบอกว่าเป็นมะเร็งเนื้อร้าย
  
<img width="578" height="456" alt="image" src="https://github.com/user-attachments/assets/20af7756-b6c7-4192-b5be-6f461db8ac09" />
