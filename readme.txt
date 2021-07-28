โปรเจคนี้เป็นการวิเคราะห์ข้อมูลความเสี่ยงของการปล่อยเงินกู้ โดยข้อมูลมี attributes ดังนี้
Gender : Male/Female
Income : Applicant income (10000 - 500000)
Education : Applicant Education Level (Bachelor, Master, Doctorate, Others)
Dependent : Number of dependents
Marital Status : Single, Married, Divorced, Widowed, Separated
Employment Status: Employed, Employed Part-time, Self-employed, Unemployed, Retired, Others
Mortgage : Yes/No
Resident : Urban/Semi-urban/Rural
Credit : Credit history meets guidelines (Yes/No)
Risk Status: 1/2/3/4/5 (1 = lowest risk, 5 = highest risk)

1. ให้ใช้ข้อมูลดังกล่าวในการ Classify ว่าลูกค้าแต่ละคนมีความเสี่ยงต่อการกู้เงินในระดับใด (1-5)

2. มีไฟล์ข้อมูล 2 ไฟล์ได้แแก่
- train.csv เป็นข้อมูลสำหรับ Train model
- test.csv เป็นข้อมูลสำหรับทดสอบ จะไม่มีข้อมูลในคอลัมน์ risk status

3. ส่งคำตอบโดยพิมพ์คำตอบลงใน Column Risk Status ในไฟล์ test.csv แล้ว submit มาเฉพาะไฟล์ test.csv เท่านั้น

4. การวัดผล คือทีมที่ได้ค่า Accuracy สูงที่สุด

Note: ไฟล์ Solution คือผลเฉลยของ test.csv
