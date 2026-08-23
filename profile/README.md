<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/delentia-labs/.github/main/profile/assets/delentia-banner-dark.svg">
  <img src="https://raw.githubusercontent.com/delentia-labs/.github/main/profile/assets/delentia-banner-light.svg"
    alt="Delentia Labs — Intent-Centric Local AI Operating System" width="100%" />
</picture>

<br/>

# Δ Delentia Labs

### *An Experimental Causal-Constraint AI Operating System SDK*
### *ระบบปฏิบัติการ AI ขนาดเล็กแบบ Local-First เพื่อการทดลองความปลอดภัย*

<br/>

> 💬 **RFC-001 is Live!** We just crossed **5,195 monthly downloads** on Hugging Face. Join our architecture review and help us audit weight-level security constraints in our [GitHub Discussions #58](https://github.com/delentia-labs/Delentia-OS/discussions/58).

<br/>

[![Website](https://img.shields.io/badge/delentia.com-Visit%20Now-0066FF?style=for-the-badge&logo=vercel&logoColor=white)](https://delentia.com)
&nbsp;
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Delentia-yellow?style=for-the-badge)](https://huggingface.co/Delentia)
&nbsp;
[![GitHub Sponsors](https://img.shields.io/github/sponsors/delentia-labs?label=Sponsor%20Us%20%E2%9D%A4%EF%B8%8F&logo=github-sponsors&style=for-the-badge&color=EA4AAA)](https://github.com/sponsors/delentia-labs)

<br/>

[![SDK Version](https://img.shields.io/badge/SDK-v2.2.6-blue)](https://github.com/delentia-labs/Delentia-OS)
[![License](https://img.shields.io/badge/license-Apache%202.0-green)](https://github.com/delentia-labs/Delentia-OS/blob/main/LICENSE)
[![PyPI Downloads](https://img.shields.io/badge/HuggingFace-5.1K_Downloads/mo-yellow)](https://huggingface.co/Delentia/delentia-slm-jitna-v0.4)
[![Python](https://img.shields.io/badge/python-3.10+-3776AB?logo=python)](https://pypi.org/project/delentia-os/)

<p align="center">
  <a href="#-english">🇺🇸 English Profile</a> •
  <a href="#-ภาษาไทย">🇹🇭 ข้อมูลภาษาไทย</a>
</p>

</div>

---

## 🇺🇸 English

### Welcome to Delentia Labs
We are the research and engineering playground behind **Delentia OS** — an experimental, local-first AI Operating System SDK focusing on structural weight-level governance and edge VRAM optimization. 

This is not a commercial enterprise or a venture-backed startup. It is an open-source hobby experiment designed to solve local agent safety at the infrastructural level, rather than relying on brittle prompt rules.

> **"A hobby experiment in resource constraints: trying to make small local AI models behave safely using mathematical gates instead of prompts."**

---

### 📝 A Sincere Note from the Solo Creator

I have no formal background in Computer Science, and a year ago, I didn't know how to write code. I graduated with a degree in Architecture, majoring in Facilities Management. I am not an AI researcher or a Silicon Valley founder. I am just a solo developer coding from a small desk in an 8-story flat in Bangkok, Thailand.

I wanted to see if I could combine my background in building resource allocation with AI to manage hardware constraints. With a hard limit of 4.9 GB VRAM (coding on a gaming handheld), I built Delentia's **1+N Adapter Swapping** stack. 

The base model card crossed **5,195 downloads last month** on Hugging Face. I honestly do not know if these downloads are bots or real developers, and the system is not yet fully stable in my eyes. I have reached the absolute boundary of what I can figure out alone. I opened this profile and our RFC discussions because I need your advice and engineering criticism to help me learn and make it work.

---

### 🏛️ The FDIA Safety Equation
The core safety system is governed by a multiplicative gate:

$$F = D^I \times A$$

*   **F (Future)**: The authorized strength of the output.
*   **D (Data)**: Context quality score (0.0 - 1.0).
*   **I (Intent)**: Intent precision (user alignment exponent).
*   **A (Architect)**: Human veto gate (A = 0 or 1). **When A = 0, the next-token probability distribution is mathematically suppressed to absolute zero.**

---

### 📦 Ecosystem Repositories

| Repo | Description | Status |
|------|-------------|--------|
| **[Delentia-OS](https://github.com/delentia-labs/Delentia-OS)** | Core Python SDK (Apache 2.0) — JITNA v3, FDIA, HexaCore | ![CI](https://github.com/delentia-labs/Delentia-OS/actions/workflows/ci.yml/badge.svg?branch=main) |
| **[Delentia-OS-Gui](https://github.com/delentia-labs/Delentia-OS-Gui)** | Desktop app — Tauri v2 + Next.js 15 (Delentia Desk) | ![CI](https://github.com/delentia-labs/Delentia-OS-Gui/actions/workflows/ci.yml/badge.svg) |
| **[Delentia-AI-SLM](https://github.com/delentia-labs/Delentia-AI-SLM)** | SLM QLoRA fine-tuning factory & Colab notebook | ![License](https://img.shields.io/badge/License-Apache%202.0-green) |
| **[Delentia-Ecosystem](https://github.com/delentia-labs/Delentia-Ecosystem)** | Plugin & skill manifest registry (LINE, Slack, etc.) | ![Manifest CI](https://img.shields.io/github/actions/workflow/status/delentia-labs/Delentia-Ecosystem/validate-adapter.yml?branch=main&label=Manifest+CI) |
| **[Delentia-Website](https://github.com/delentia-labs/Delentia-Website)** | Next.js 16 App Router marketing & documentation website | ![Deployed](https://img.shields.io/badge/deployed-delentia.com-brightgreen?logo=vercel) |
| **[Delentia-Infra-Public](https://github.com/delentia-labs/Delentia-Infra-Public)** | Public Docker Compose & Helm Chart configurations | ![Docker](https://img.shields.io/badge/Docker-%3E%3D24-blue) |

---

## 🇹🇭 ภาษาไทย

### ยินดีต้อนรับสู่ Delentia Labs
พวกเราคือค่ายวิจัยและพัฒนาเบื้องหลัง **Delentia OS** — โครงการทดลองสร้างระบบปฏิบัติการ AI ขนาดเล็กแบบ Local-First เพื่อทดลองการควบคุมความปลอดภัยผ่านกติกาคณิตศาสตร์ระดับน้ำหนักโมเดล (Weight-level) และการบริหาร VRAM บนอุปกรณ์พกพา

นี่ไม่ใช่โครงการเพื่อการค้าหรือสตาร์ทอัพที่ได้ทุนสนับสนุนก้อนโต แต่คือโปรเจกต์งานอดิเรกโอเพนซอร์สเพื่อแก้ไขความเสี่ยงในระดับ **โครงสร้างพื้นฐาน (Infrastructural Level)** ไม่ใช่ระดับชั้นแอปพลิเคชัน

> **"การทดลองส่วนตัวในข้อจำกัดฮาร์ดแวร์: พยายามทำให้โมเดลภาษาขนาดเล็กแบบโลคอลทำงานได้อย่างปลอดภัยด้วยเงื่อนไขทางคณิตศาสตร์แทนการใช้คำสั่ง Prompt"**

---

### 🇹🇭 คำสารภาพอันซื่อตรงจากผู้สร้าง

ผมไม่มีวุฒิวิทยาการคอมพิวเตอร์ และเมื่อ 12 เดือนก่อนผมเขียนโค้ดไม่เป็นเลย ผมเป็นเพียงผู้ที่เรียนจบด้านสถาปัตยกรรมศาสตร์ สาขาการจัดการทรัพยากรอาคาร (Facilities Management) ไม่ใช่นักวิจัย AI หรือผู้ก่อตั้งบริษัทในซิลิคอนวัลเลย์ ผมคือคนธรรมดาคนหนึ่งที่นั่งเขียนโค้ดอยู่บนโต๊ะตัวเล็กๆ ในแฟลต 8 ชั้นแถบคลองเตย กรุงเทพมหานคร

ผมอยากลองนำความรู้เรื่องการจัดสรรทรัพยากรและพื้นที่ (Resource Allocation) มาประยุกต์ร่วมกับ AI เพื่อควบคุมข้อจำกัดฮาร์ดแวร์ ภายใต้ VRAM ceiling 4.9 GB (พัฒนาและทดสอบบนเครื่องเกมพกพา ROG Ally X) ผมสร้างสถาปัตยกรรม **1+N Adapter Swapping** สลับโมเดลหน้ากากเฉพาะทางในหน่วยความจำเครื่อง

โมเดลหลักในโครงการนี้มียอดดาวน์โหลดบน Hugging Face กว่า **5,195 ครั้งในเดือนที่ผ่านมา** ซึ่งผมเองก็ไม่ทราบแน่ชัดว่าเป็นบอทหรือนักพัฒนาที่นำไปทดสอบ และระบบในมุมมองของผมยังหยาบและไม่เสถียรเลย ผมมาถึงทางตันที่คนคนเดียวจะเรียนรู้และคิดออกแล้ว ผมจึงเปิดกระทู้เสนอแนวคิดวิจัย (RFC-001) ขึ้นมาเพื่อขอรับฟังคำชี้แนะ คำวิจารณ์ และคำแนะนำเชิงวิศวกรรมจากพี่ๆ และเพื่อนๆ ในวงการทุกท่านเพื่อนำไปพัฒนาต่อครับ

---

### 🏛️ สมการควบคุมความปลอดภัย FDIA
การประมวลผลถูกกำกับดูแลด้วยคณิตศาสตร์ผ่าน **สมการ FDIA**:

$$F = D^I \times A$$

*   **F (Future)**: ผลลัพธ์คำสั่งการทำงานที่ต้องการของเอเจนต์
*   **D (Data)**: ค่าระดับคะแนนคุณภาพข้อมูลนำเข้า (0.0 - 1.0)
*   **I (Intent)**: ความแม่นยำของเจตนา (ตัวยกกำลังขยายสัญญาณข้อมูล)
*   **A (Architect)**: มนุษย์ควบคุมผ่านเกณฑ์สิทธิ์ **เมื่อ A = 0 สิทธิการประมวลผล Token ถัดไปจะถูกกดน้ำหนักคณิตศาสตร์ให้กลายเป็นศูนย์ทันที**

---

## 👥 Team & Creator / ทีมผู้พัฒนา

| Role / บทบาท | GitHub / รายละเอียด |
|------|--------|
| 🏛️ **Founder & Developer** | [@ittirit-delentia](https://github.com/ittirit-delentia) — อิทธิฤทธิ์ แซ่โง้ว (เรียนรู้และทดลองระบบปฏิบัติการ AI ทั้งหมดจากย่านคลองเตย กรุงเทพมหานคร 🇹🇭) |

---

<div align="center">

**Δ Delentia Labs — Constitutional AI for the Intelligence Age**

*Building secure, human-governed AI infrastructure from Bangkok, Thailand 🇹🇭*

[![delentia.com](https://img.shields.io/badge/delentia.com-Visit%20Now-0066FF?style=for-the-badge)](https://delentia.com)
&nbsp;
[![🤗 HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20Delentia-yellow?style=for-the-badge)](https://huggingface.co/Delentia)

</div>
