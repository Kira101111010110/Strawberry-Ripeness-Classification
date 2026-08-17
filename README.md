# 🍓 Strawberry Ripeness Classification
> ระบบจำแนกความสุกของสตรอว์เบอร์รีเพื่อช่วยคัดแยกผลที่พร้อมเก็บเกี่ยว ด้วยการประมวลผลภาพและ Machine Learning ใน Python

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer-Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

---

## 📌 Project Overview

โปรเจกต์นี้พัฒนาระบบสำหรับจำแนกสตรอว์เบอร์รีออกเป็น 2 กลุ่ม ได้แก่

- 🍓 **Pickable** — ผลที่พร้อมเก็บเกี่ยว
- 🌱 **UnPickable** — ผลที่ยังไม่พร้อมเก็บเกี่ยว

โดยใช้ชุดข้อมูลภาพสตรอว์เบอร์รีสำหรับฝึกและทดสอบโมเดลภายใน Jupyter Notebook พร้อมเตรียมข้อมูลให้สามารถนำไปต่อยอดกับงานด้าน Computer Vision และเกษตรอัจฉริยะ (Smart Agriculture)

---

## ✨ Features

- **Binary Classification** สำหรับจำแนกผลสตรอว์เบอร์รีเป็น Pickable และ UnPickable
- **Image Dataset Organization** จัดโครงสร้างชุดข้อมูลสำหรับงาน Machine Learning
- **Jupyter Notebook Workflow** รวมขั้นตอนการเตรียมข้อมูล การฝึกโมเดล และการทดสอบไว้ใน Notebook เดียว
- **Dataset for Training & Testing** รองรับการทดลองและพัฒนาระบบจำแนกภาพ

---

## 📊 Dataset

ชุดข้อมูลประกอบด้วยภาพสตรอว์เบอร์รีทั้งหมดประมาณ **625 ภาพ** แบ่งเป็นสองคลาสหลัก

| Class | Description |
|-------|-------------|
| Pickable | สตรอว์เบอร์รีที่พร้อมเก็บเกี่ยว |
| UnPickable | สตรอว์เบอร์รีที่ยังไม่พร้อมเก็บเกี่ยว |

ตัวอย่างโครงสร้างข้อมูลถูกจัดเก็บไว้ในโฟลเดอร์สำหรับการฝึกและทดสอบโมเดล

---

## 🛠️ Project Structure

```text
├── Pickable/              # ภาพสตรอว์เบอร์รีที่พร้อมเก็บ
├── UnPickable/            # ภาพสตรอว์เบอร์รีที่ยังไม่พร้อมเก็บ
├── p1/                    # ชุดภาพเพิ่มเติมสำหรับคลาส Pickable
├── u1/                    # ชุดภาพเพิ่มเติมสำหรับคลาส UnPickable
├── ทำนายสตอไทย.ipynb      # Notebook สำหรับฝึกและทดสอบโมเดล
└── README.md              # Project Documentation
```

---

## ⚙️ Workflow

1. เตรียมชุดข้อมูลและจัดแบ่งตามคลาส
2. โหลดข้อมูลเข้าสู่ Jupyter Notebook
3. ฝึกโมเดลจำแนกภาพ
4. ทดสอบผลลัพธ์และประเมินการจำแนก
5. นำโมเดลไปต่อยอดสำหรับระบบคัดแยกผลผลิต

---

## 🚀 How to Run

1. Clone โปรเจกต์

```bash
git clone https://github.com/your-username/strawberry-ripeness-classification.git
```

2. เปิด Jupyter Notebook

```bash
jupyter notebook
```

3. เปิดไฟล์

```text
ทำนายสตอไทย.ipynb
```

4. รันทุกเซลล์เพื่อฝึกและทดสอบโมเดล

---

## 🌾 Applications

- Smart Agriculture
- Automated Fruit Sorting
- Harvest Readiness Detection
- Computer Vision for Farming

---

## 👨‍💻 Author

**Kittiphop Inthisan**

Computer Engineering Student • AI & Computer Vision Projects
