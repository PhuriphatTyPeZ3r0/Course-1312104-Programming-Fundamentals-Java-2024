# 1312104 Programming Fundamentals (การโปรแกรมเบื้องต้น - Java)

<div align="center">

[![Institution: PIM](https://img.shields.io/badge/Institution-PIM-003366?style=for-the-badge&logo=google-classroom&logoColor=white)](https://www.pim.ac.th/)
[![Program: CAI](https://img.shields.io/badge/Program-CAI-blue?style=for-the-badge)](https://www.pim.ac.th/)
[![Academic Year](https://img.shields.io/badge/Academic%20Year-1%2F2024-orange?style=for-the-badge)](https://github.com/PhuriphatTyPeZ3r0)
[![Grade: A](https://img.shields.io/badge/Grade-A%20(4.00)-success?style=for-the-badge)](https://github.com/PhuriphatTyPeZ3r0)
[![Language: Java](https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Obsidian Compatible](https://img.shields.io/badge/Obsidian-Vault%20Ready-7C3AED?style=for-the-badge&logo=obsidian&logoColor=white)](https://obsidian.md/)

**คลังแบบฝึกหัด โค้ดแล็บ และสื่อการเรียนรู้รายวิชาการโปรแกรมเบื้องต้น (Java)**  
*สาขาวิชาวิศวกรรมคอมพิวเตอร์และปัญญาประดิษฐ์ (CAI) — สถาบันการจัดการปัญญาภิวัฒน์ (PIM)*

</div>

---

## 📌 สารบัญ (Table of Contents)
- [📖 1. ข้อมูลรายวิชาเบื้องต้น (Course Information)](#-1-ข้อมูลรายวิชาเบื้องต้น-course-information)
- [📂 2. โครงสร้าง Repository (Standard Course Layout)](#-2-โครงสร้าง-repository-standard-course-layout)
- [📚 3. เนื้อหาและการบรรยาย (Lectures & Slides)](#-3-เนื้อหาและการบรรยาย-lectures--slides)
- [💻 4. แบบฝึกหัดและการทดลองภาคปฏิบัติ (Labs & Assignments)](#-4-แบบฝึกหัดและการทดลองภาคปฏิบัติ-labs--assignments)
- [🏆 5. โครงงานประจำรายวิชา (Course Projects)](#-5-โครงงานประจำรายวิชา-course-projects)
- [📝 6. สรุปทบทวนและเตรียมสอบ (Exams Review)](#-6-สรุปทบทวนและเตรียมสอบ-exams-review)
- [⚖️ 7. จริยธรรมทางวิชาการ (Academic Integrity Notice)](#-7-จริยธรรมทางวิชาการ-academic-integrity-notice)
- [👨‍💻 8. ผู้จัดทำ (Author)](#-8-ผู้จัดทำ-author)

---

## 📖 1. ข้อมูลรายวิชาเบื้องต้น (Course Information)

- **รหัสวิชา:** `1312104`
- **ชื่อวิชาภาษาอังกฤษ:** Programming Fundamentals (Java)
- **ชื่อวิชาภาษาไทย:** การโปรแกรมเบื้องต้น
- **ภาษาโปรแกรมที่ใช้:** Java (OpenJDK 17+)
- **หน่วยกิต:** 3 หน่วยกิต (3-0-6)
- **ภาคการศึกษา / ปีการศึกษา:** ภาคเรียนที่ 1 / ปีการศึกษา 2567 (1/2024)
- **ผลการเรียนที่ได้รับ (Grade):** **A (4.00)**
- **อาจารย์ผู้สอน (Instructor):** ดร. ชนะกาญจน์ กิ่งแก้ว (Dr. Chanakarn Kingkaew)

---

## 📂 2. โครงสร้าง Repository (Standard Course Layout)

```text
Course-1312104-Programming-Fundamentals-Java-2024/
├── 00_Templates/               # Template โน้ตและคู่มือ format (Markdown/Obsidian)
├── 01_Lectures/                # เอกสารและตำราประกอบการสอน
│   ├── 01_Docs/               # เอกสารประกอบการสอน (Syllabus, Handouts)
│   └── 02_Teaching_Slides/    # สไลด์ประกอบการสอนประจำสัปดาห์
├── 02_Labs_Assignments/       # ใบงาน แบบฝึกหัด และโค้ดแล็บประจำบทเรียน
│   ├── 01-Introduction/
│   ├── 02-Data Types and Operators/
│   ├── 03-Relational & Logical Operators/
│   ├── 04-Conditional Statement/
│   ├── 05-Loop/
│   ├── 06-Arrays and Multidimensional Arrays/
│   └── 07-GUI/
├── 03_Projects/                # โครงงานและมินิโปรเจกต์ประจำวิชา
│   └── README.md
├── 04_Exams_Review/            # แนวข้อสอบ สรุปทบทวนก่อนสอบกลางภาคและปลายภาค
└── README.md                   # เอกสารแนะนำและสารบัญหลัก
```

> **หมายเหตุ:** โครงสร้างนี้รองรับการเปิดอ่านบน GitHub และเปิดเป็น **Obsidian Vault** โดยสมบูรณ์

---

## 📚 3. เนื้อหาและการบรรยาย (Lectures & Slides)

| หมวดเนื้อหา | หัวข้อการบรรยาย (Lecture Topics) | รายละเอียดเนื้อหา | สไลด์ / เอกสาร |
| :---: | :--- | :--- | :---: |
| **Java Syntax** | **Introduction to Java & Compilation** | โครงสร้างโปรแกรม Java, JVM/JRE/JDK, Class & Main Method, Compilation & Execution | [เอกสาร](01_Lectures/01_Docs/) |
| **Data & Operators** | **Variables, Primitive Types & Expressions** | Data Types, Type Casting, Arithmetic & Assignment Operators | [เอกสาร](01_Lectures/01_Docs/) |
| **Logic & Control** | **Conditional Execution & Flow Control** | Boolean Logic, If-Else, Nested If, Switch-Case Pattern Matching | [เอกสาร](01_Lectures/01_Docs/) |
| **Repetition** | **Loops & Iterative Algorithms** | While, Do-While, For loops, Break/Continue, Nested Iterations | [เอกสาร](01_Lectures/01_Docs/) |
| **Data Structures** | **Single & Multidimensional Arrays** | Array Declaration, Memory Allocation, Matrix Operations | [เอกสาร](01_Lectures/01_Docs/) |
| **GUI & Events** | **Desktop Graphical User Interface** | Java Swing, JFrame, JButton, Event Listeners, Action Handling | [เอกสาร](01_Lectures/01_Docs/) |

---

## 💻 4. แบบฝึกหัดและการทดลองภาคปฏิบัติ (Labs & Assignments)

| ลำดับแล็บ | หัวข้อแบบฝึกหัด (Lab Topic) | คำอธิบายและโจทย์ปฏิบัติการ | โฟลเดอร์ซอร์สโค้ด |
| :---: | :--- | :--- | :---: |
| **Lab 01** | **Introduction to Java** | โครงสร้างไวยากรณ์พื้นฐาน, Class, Method `main`, และการแสดงผล Standard I/O | [เปิดโค้ด](02_Labs_Assignments/01-Introduction/) |
| **Lab 02** | **Data Types & Operators** | ชนิดข้อมูลพื้นฐาน (Primitive Types), ตัวดำเนินการทางคณิตศาสตร์, Type Casting | [เปิดโค้ด](02_Labs_Assignments/02-Data%20Types%20and%20Operators/) |
| **Lab 03** | **Relational & Logical Operators** | ตัวดำเนินการเปรียบเทียบและการรวมเงื่อนไขตรรกศาสตร์ (`==`, `!=`, `&&`, `\|\|`) | [เปิดโค้ด](02_Labs_Assignments/03-Relational%20&%20Logical%20Operators/) |
| **Lab 04** | **Conditional Statements** | การควบคุมทิศทางการทำงานด้วย `if`, `if-else`, `else if`, และ `switch-case` | [เปิดโค้ด](02_Labs_Assignments/04-Conditional%20Statement/) |
| **Lab 05** | **Loop Constructs** | โครงสร้างการทำงานซ้ำ: `for loop`, `while loop`, `do-while loop` และ Nested Loops | [เปิดโค้ด](02_Labs_Assignments/05-Loop/) |
| **Lab 06** | **Arrays & Multidimensional Arrays** | อาร์เรย์ 1 มิติและ 2 มิติ, การจัดสรรหน่วยความจำ, การค้นหาและวนลูปประมวลผล | [เปิดโค้ด](02_Labs_Assignments/06-Arrays%20and%20Multidimensional%20Arrays/) |
| **Lab 07** | **Graphical User Interface (GUI)** | การพัฒนา UI บนเดสก์ท็อปด้วย Java Swing / AWT, Event Handling เบื้องต้น | [เปิดโค้ด](02_Labs_Assignments/07-GUI/) |

---

## 🏆 5. โครงงานประจำรายวิชา (Course Projects)

> โครงงานและโปรแกรมประยุกต์เชิงวัตถุที่พัฒนาขึ้นในรายวิชา (เก็บอยู่ในโฟลเดอร์ `03_Projects/`)

### ☕ Desktop Application & Interactive Console Program
- **บทบาทและหน้าที่:** โปรแกรมประยุกต์สำหรับแก้โจทย์ปัญหาเชิงตรรกะและประมวลผลข้อมูล พัฒนาด้วยภาษา Java พร้อมหน้าต่างกราฟิก Swing
- **เทคโนโลยี:** `Java SE (OpenJDK 17), Java Swing, Java AWT, NetBeans / VS Code`
- **ซอร์สโค้ด:** [โฟลเดอร์โครงงาน](03_Projects/)

---

## 📝 6. สรุปทบทวนและเตรียมสอบ (Exams Review)

- [x] **สรุปทบทวนการสอบกลางภาค (Midterm Review):** [บันทึกสรุปไวยากรณ์และ Control Flow](04_Exams_Review/)
- [x] **สรุปทบทวนการสอบปลายภาค (Final Review):** [บันทึกสรุป Arrays, Methods และ GUI Swing](04_Exams_Review/)

---

## ⚖️ 7. จริยธรรมทางวิชาการ (Academic Integrity Notice)

> [!NOTE]  
> คลังนี้จัดทำขึ้นเพื่อเป็น **บันทึกการเรียนรู้ส่วนบุคคล (Personal Learning Archive)** และนำเสนอพัฒนาการทางวิชาการ (Academic Portfolio) เท่านั้น  
> ไม่อนุญาตให้นำโค้ดหรือการบ้านไปคัดลอก (Plagiarism) เพื่อส่งงานในรายวิชาโดยไม่ได้รับอนุญาตตามระเบียบของสถาบันฯ

---

## 👨‍💻 8. ผู้จัดทำ (Author)

**Phuriphat Hemakul (PhuriphatTyPeZ3r0)**
- 🎓 นักศึกษา สาขาวิศวกรรมคอมพิวเตอร์และปัญญาประดิษฐ์ (CAI)
- 🏛️ สถาบันการจัดการปัญญาภิวัฒน์ (PIM)
- 🐙 GitHub: [@PhuriphatTyPeZ3r0](https://github.com/PhuriphatTyPeZ3r0)
- 🌐 Portfolio: [resume-phuriphat-hemakul.vercel.app](https://resume-phuriphat-hemakul.vercel.app)
