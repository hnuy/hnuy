# สวัสดี ผม Prakrit Yoophoon 👋

🇬🇧 [English](README.md) · 📄 [Resume (ไทย)](https://hnuy.github.io/th.html)

**วิศวกร Full-Stack & DevSecOps** ประสบการณ์ 6 ปีขึ้นไป สร้างระบบระดับองค์กร ทั้ง ERP, WMS, ระบบ HR และเว็บแอปแบบ real-time

---

## เกี่ยวกับผม

- ปัจจุบันทำงานที่ **Bitsoft** ตำแหน่ง Full-Stack Developer
- ส่งมอบงาน **ครบวงจร** ตั้งแต่ออกแบบฐานข้อมูลจนถึง deploy บน cloud
- ให้ความสำคัญกับ **clean architecture**, **test-driven development** และระบบที่ขยายตัวได้
- ใช้ **AI integration** จริง (Claude Code, Claude API, OpenAI) และ deploy แบบ cloud-native บน AWS
- ทำ **ISO/IEC 27001:2022**: สร้าง ISMS portal ของบริษัท, เพิ่มความปลอดภัยให้ AWS production และทำ change บน production ตามกระบวนการ change management อย่างเป็นทางการ

---

## Tech Stack

**Frontend**
![React](https://img.shields.io/badge/React-18/19-61DAFB?logo=react&logoColor=white&style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white&style=flat-square)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white&style=flat-square)
![Material UI](https://img.shields.io/badge/Material--UI-007FFF?logo=mui&logoColor=white&style=flat-square)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=flat-square)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white&style=flat-square)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white&style=flat-square)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white&style=flat-square)

**Database & Cloud**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=flat-square)
![AWS](https://img.shields.io/badge/AWS_Lambda-FF9900?logo=amazonaws&logoColor=white&style=flat-square)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?logo=amazons3&logoColor=white&style=flat-square)

**Testing & DevOps**
![Jest](https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white&style=flat-square)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white&style=flat-square)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white&style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat-square)

**Security & AI**
![ISO 27001](https://img.shields.io/badge/ISO%2FIEC_27001:2022-0A66C2?style=flat-square)
![AWS IAM](https://img.shields.io/badge/AWS_IAM_%26_VPC-FF9900?logo=amazonaws&logoColor=white&style=flat-square)
![Falco](https://img.shields.io/badge/Falco-00AEC7?logo=falco&logoColor=white&style=flat-square)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?logo=anthropic&logoColor=white&style=flat-square)

---

## โปรเจกต์เด่น

### ISMS Portal ตาม ISO 27001
> ระบบภายในที่บริษัทใช้บริหาร ISMS ตาม ISO/IEC 27001:2022

- **Tech:** React 19, NestJS, TypeScript, MySQL, AWS S3, Docker
- **ฟีเจอร์:** risk register พร้อม residual risk, SoA (93 control ใน Annex A), ทะเบียนสินทรัพย์, change management พร้อมประวัติการอนุมัติ, ผู้ส่งมอบ, BCP, การทบทวนสิทธิ์
- **งานที่เกี่ยวข้อง:** release gate ใน Jenkins ที่ผูกกับ change hold, เพิ่มความปลอดภัย AWS VPC/IAM, backup แบบแก้ไขไม่ได้บน S3 Object Lock พร้อมทดสอบ restore

---

### ระบบ ERP (Enterprise Resource Planning)
> แพลตฟอร์ม ERP แบบ full-stack สำหรับงานธุรกิจองค์กร

- **Tech:** React, TypeScript, GraphQL, Apollo, NestJS, MySQL, AWS Lambda
- **ฟีเจอร์:** อัปเดต real-time (WebSocket), สแกน QR/Barcode, OCR (Tesseract.js), ฟีเจอร์ AI (Google Generative AI), รายงานขั้นสูง (ApexCharts, Highcharts)
- **สถาปัตยกรรม:** backend แบบ serverless บน AWS Lambda, GraphQL API พร้อม code generation

---

### ระบบบริหารงานบุคคล (HR)
> ระบบ HR หลายแพลตฟอร์ม (เว็บ + มือถือ)

- **Tech:** NestJS, React 19, Flutter, MySQL, AWS SAM, JWT
- **ฟีเจอร์:** จัดการพนักงาน, วันลา, เงินเดือน, ประเมินผลงาน, เชื่อม Google Sheets, บังคับอัปเดตแอปมือถือ
- **สถาปัตยกรรม:** backend NestJS แบบ modular พร้อมเอกสาร Swagger, แอป Flutter, แดชบอร์ดเว็บ React

---

### ระบบบริหารคลังสินค้า (WMS)
> WMS สำหรับสารเคมีและสินค้าอันตราย ตามข้อกำหนดของไทย

- **Tech:** React 19, Express, TypeScript, Zustand, Zod, TailwindCSS, Radix UI
- **ฟีเจอร์:** จำแนกสินค้าอันตราย, รายงานตามข้อกำหนดกรมโรงงานอุตสาหกรรม (DIW), สิทธิ์ตามบทบาท (Admin/Manager/Operator), งานรับเข้า/จ่ายออก
- **สถาปัตยกรรม:** แยกชั้น service/repository ชัดเจน, REST API

---

### ระบบจัดการแข่งขันหมากรุก BBB Chess
> แพลตฟอร์มแข่งขันหมากรุกแบบ real-time จับคู่แบบ Swiss

- **Tech:** React, TypeScript, GraphQL, Apollo Server, MySQL (Monorepo)
- **ฟีเจอร์:** อัลกอริทึมจับคู่ Swiss (แบบ FIDE), คะแนน Buchholz, อัปเดต real-time, จัดการ bye, จัดการทัวร์นาเมนต์
- **สถาปัตยกรรม:** GraphQL subscription, AWS Lambda, OpenTelemetry distributed tracing

---

### เอกสาร Workshop TDD
> หลักสูตร Test-Driven Development ในยุค AI

- ออกแบบและจัด workshop TDD ให้ทีมพัฒนา
- เอกสารสองภาษา (ไทย/อังกฤษ)
- แบบฝึก kata: String Calculator, Expense Analyzer
- ครอบคลุมหลัก TDD ในบริบทการพัฒนาที่มี AI ช่วย

---

## GitHub Stats

![Prakrit's GitHub stats](https://github-readme-stats.vercel.app/api?username=hnuy&show_icons=true&theme=default&hide_border=true)

---

## ติดต่อ

| | |
|---|---|
| อีเมล | prakrit.software@gmail.com |
| GitHub | [github.com/hnuy](https://github.com/hnuy) |
| Line | hnuyza20075 |
| โทร | 099-909-5881 |

---

> *"โค้ดที่ดีไม่ใช่แค่โค้ดที่ทำงานได้ แต่เป็นโค้ดที่คนอื่นอ่านเข้าใจ ทดสอบได้ และต่อยอดได้"*
