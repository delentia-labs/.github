<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/delentia-labs/.github/main/profile/assets/delentia-banner-dark.svg">
  <img src="https://raw.githubusercontent.com/delentia-labs/.github/main/profile/assets/delentia-banner-light.svg"
    alt="Delentia Labs: an experimental, self-hosted, intent-centric AI agent runtime" width="100%" />
</picture>

<br/>

# Δ Delentia Labs

### *An experimental, self-hosted, intent-centric AI agent runtime*
### *รันไทม์ AI agent เชิงทดลองแบบ self-hosted ที่ยึดเจตนาของผู้ใช้เป็นศูนย์กลาง*

<br/>

[![Website](https://img.shields.io/badge/delentia.com-Visit-0066FF?style=for-the-badge&logo=vercel&logoColor=white)](https://delentia.com)
&nbsp;
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Delentia-yellow?style=for-the-badge)](https://huggingface.co/Delentia)

<br/>

[![PyPI](https://img.shields.io/pypi/v/delentia-os?label=delentia-os)](https://pypi.org/project/delentia-os/)
[![License](https://img.shields.io/badge/license-Apache%202.0-green)](https://github.com/delentia-labs/Delentia-OS/blob/main/LICENSE)
[![Status](https://img.shields.io/badge/status-experimental-orange)](https://github.com/delentia-labs/Delentia-OS/blob/main/docs/release/RELEASE_LEVELS.md)
[![Python](https://img.shields.io/badge/python-3.10+-3776AB?logo=python)](https://pypi.org/project/delentia-os/)

<p align="center">
  <a href="#-english">🇺🇸 English</a> •
  <a href="#-ภาษาไทย">🇹🇭 ภาษาไทย</a>
</p>

</div>

---

## 🇺🇸 English

### What Delentia is

Delentia develops an experimental, open-source, self-hosted AI agent runtime centred on the user's intent. Its design draws on **FDIA** and **RCT-7** to structure work, govern actions through implemented policies and signed approvals, and preserve evidence for review. The runtime contains its own agent loop, tools, memory, skills, scheduling and subagents. You choose the model and you run the installation.

**Current scope:** public code and scripted mechanism demos, with supervised use on the creator's machine. Evaluation with capable models, comparative ablations and outside reproduction are still ahead. A scripted demo replaces the language model with a fixed program; it shows a mechanism, not a model's ability. Nothing here is a running public service.

### Start here

- Runtime and source: **[Delentia-OS](https://github.com/delentia-labs/Delentia-OS)**
- The definition in one page, and what is still to be tested: [Current public information](https://github.com/delentia-labs/Delentia-OS/blob/main/docs/public/CURRENT_PUBLIC_INFORMATION_EN.md)
- Status and release scope: [RELEASE_LEVELS](https://github.com/delentia-labs/Delentia-OS/blob/main/docs/release/RELEASE_LEVELS.md)
- Try the scripted demo (no model, no API key): [Quick start](https://github.com/delentia-labs/Delentia-OS/blob/main/docs/demo/QUICKSTART_EN.md)
- Questions and reproduction reports: [Discussions](https://github.com/delentia-labs/Delentia-OS/discussions) · [Issues](https://github.com/delentia-labs/Delentia-OS/issues)
- Security reports: [SECURITY.md](https://github.com/delentia-labs/Delentia-OS/blob/main/SECURITY.md)

### The two ideas behind it

**FDIA Equation, `F = (D^I) × A`.** The creator's framework: **F**uture (the outcome that actually happens), **D**ata (reality and experience), **I**ntent (the exponent that gives the data direction) and **A**rchitect (the human who designs, decides and answers for the outcome). It has no official expanded name. In the runtime it is read as a score for whether an action is admissible, used together with the owner's policy and signed human approvals. The score alone does not stop an action, and it does not change a model's output.

**RCT-7, Reverse Component Thinking.** A way of working in seven steps: observe, analyze, deconstruct, reason backward from the wanted result, identify the core intent, reconstruct (show the plan before building) and compare the result with the intent (stop and ask when it does not match). This is the design; the runtime implements parts of it, and the [step-by-step status](https://github.com/delentia-labs/Delentia-OS/blob/main/docs/public/RCT7_IMPLEMENTATION_STATUS.md) says which.

### Repositories

| Repo | What it is |
|------|------------|
| **[Delentia-OS](https://github.com/delentia-labs/Delentia-OS)** | The agent runtime (Apache 2.0). Also holds the Desk GUI (`apps/gui`), the adapter registry (`plugins/adapters`) and the public deployment files (`deploy/`) |
| **[delentia-mcp](https://github.com/delentia-labs/delentia-mcp)** | Delentia Guard (a policy filter in front of an MCP server) and six advisory MCP tools on Cloudflare Workers. These serve agents people already use; the Python runtime has its own agent loop. Treat their status separately |
| **[Delentia-Website](https://github.com/delentia-labs/Delentia-Website)** | The website, delentia.com |
| Delentia-OS-Gui, Delentia-Ecosystem, Delentia-Infra-Public | Archived. Their content moved into Delentia-OS (`apps/gui`, `plugins/adapters`, `deploy`) |
| Delentia-AI-SLM, Delentia-Answer-Engine-Test | Archived historical experiments, not maintained as the current runtime |

Earlier repositories, whitepapers and posts record the project's development history; their descriptions may differ from the current implementation. Where they do, the pages linked above are the current reference.

---

## 🇹🇭 ภาษาไทย

### Delentia คืออะไร

Delentia พัฒนา AI agent runtime แบบโอเพนซอร์สและ self-hosted ในเชิงทดลอง โดยยึดเจตนาของผู้ใช้เป็นศูนย์กลาง การออกแบบอาศัย **FDIA** และ **RCT-7** เพื่อจัดโครงงาน กำกับการกระทำด้วยนโยบายและลายเซ็นอนุมัติที่ใช้งานจริง และเก็บหลักฐานไว้ตรวจย้อนหลัง ภายใน runtime มีวงจร agent เครื่องมือ ความจำ ทักษะ การจัดตารางงาน และเอเจนต์ย่อยของตัวเอง ผู้ใช้เลือกโมเดลและดูแลการติดตั้งเอง

**ขอบเขตปัจจุบัน:** มีโค้ดสาธารณะและเดโมกลไกแบบสคริปต์ กับการใช้งานภายใต้การดูแลบนเครื่องของผู้สร้าง การประเมินกับโมเดลที่เก่ง การเปรียบเทียบเชิงทดลอง และการทำซ้ำโดยคนนอก ยังเป็นงานถัดไป เดโมแบบสคริปต์ใช้โปรแกรมกำหนดพฤติกรรมแทนโมเดลภาษา จึงแสดงกลไก ไม่ได้แสดงความสามารถของโมเดล และตอนนี้ยังไม่มีบริการสาธารณะที่เปิดให้ใช้

### เริ่มที่นี่

- Runtime และซอร์สโค้ด: **[Delentia-OS](https://github.com/delentia-labs/Delentia-OS)**
- นิยามหนึ่งหน้า และสิ่งที่ยังต้องทดสอบ: [ข้อมูลปัจจุบัน](https://github.com/delentia-labs/Delentia-OS/blob/main/docs/public/CURRENT_PUBLIC_INFORMATION_TH.md)
- สถานะและขอบเขตของแต่ละระดับ: [RELEASE_LEVELS](https://github.com/delentia-labs/Delentia-OS/blob/main/docs/release/RELEASE_LEVELS.md)
- ลองเดโมแบบสคริปต์ (ไม่ต้องมีโมเดลหรือ API key): [คู่มือเดโมภาษาไทย](https://github.com/delentia-labs/Delentia-OS/blob/main/docs/demo/QUICKSTART_TH.md)
- คำถามและรายงานการทำซ้ำ: [Discussions](https://github.com/delentia-labs/Delentia-OS/discussions) · [Issues](https://github.com/delentia-labs/Delentia-OS/issues)
- รายงานช่องโหว่: [SECURITY.md](https://github.com/delentia-labs/Delentia-OS/blob/main/SECURITY.md)

### สองแนวคิดเบื้องหลัง

**FDIA Equation, `F = (D^I) × A`** เป็นกรอบคิดของผู้สร้าง: **F**uture (ผลที่เกิดขึ้นจริง) **D**ata (ความเป็นจริงและประสบการณ์) **I**ntent (ตัวยกกำลังที่ให้ทิศทางแก่ข้อมูล) และ **A**rchitect (มนุษย์ผู้ออกแบบ ตัดสินใจ และรับผิดชอบผล) ยังไม่มีชื่อเต็มทางการ ใน runtime ถูกตีความเป็นคะแนนว่าการกระทำหนึ่งควรได้รับอนุญาตหรือไม่ ใช้ร่วมกับนโยบายของเจ้าของและลายเซ็นอนุมัติของมนุษย์ คะแนนอย่างเดียวไม่ได้หยุดการกระทำ และไม่ได้เปลี่ยนผลลัพธ์ของโมเดล

**RCT-7, Reverse Component Thinking** คือวิธีทำงานเจ็ดขั้น: สังเกต วิเคราะห์ แยกองค์ประกอบ คิดย้อนจากผลที่ต้องการ ระบุเจตนาหลัก ประกอบใหม่ (แสดงแผนก่อนสร้าง) และเทียบผลกับเจตนา (หยุดถามเมื่อไม่ตรง) นี่คือการออกแบบ runtime ทำได้บางส่วน ดู[สถานะรายขั้น](https://github.com/delentia-labs/Delentia-OS/blob/main/docs/public/RCT7_IMPLEMENTATION_STATUS.md)

### Repositories

| Repo | คืออะไร |
|------|---------|
| **[Delentia-OS](https://github.com/delentia-labs/Delentia-OS)** | agent runtime (Apache 2.0) รวม Desk GUI (`apps/gui`) ทะเบียน adapter (`plugins/adapters`) และไฟล์ deploy สาธารณะ (`deploy/`) |
| **[delentia-mcp](https://github.com/delentia-labs/delentia-mcp)** | Delentia Guard (ตัวกรองนโยบายหน้า MCP server) และเครื่องมือ MCP เชิงแนะนำ 6 ตัวบน Cloudflare Workers สำหรับ agent ที่คนใช้อยู่แล้ว runtime ภาษา Python มีวงจร agent ของตัวเอง ให้แยกสถานะกัน |
| **[Delentia-Website](https://github.com/delentia-labs/Delentia-Website)** | เว็บไซต์ delentia.com |
| Delentia-OS-Gui, Delentia-Ecosystem, Delentia-Infra-Public | เก็บถาวรแล้ว เนื้อหาย้ายเข้า Delentia-OS (`apps/gui`, `plugins/adapters`, `deploy`) |
| Delentia-AI-SLM, Delentia-Answer-Engine-Test | การทดลองในอดีตที่เก็บถาวร ไม่ได้ดูแลในฐานะ runtime ปัจจุบัน |

repo เก่า เอกสารขาว และโพสต์ในอดีตบันทึกประวัติการพัฒนา คำอธิบายในนั้นอาจต่างจากการใช้งานปัจจุบัน หากต่างกัน ให้ถือหน้าที่ลิงก์ไว้ข้างบนเป็นข้อมูลปัจจุบัน

---

## 👤 Creator / ผู้สร้าง

**Ittirit Saengow (อิทธิฤทธิ์ แซ่โง้ว)**: thinker and creator of Delentia · [@ittirit-delentia](https://github.com/ittirit-delentia)

---

<div align="center">

**Δ Delentia Labs: an experimental, self-hosted AI agent runtime, built in the open from Bangkok, Thailand 🇹🇭**

[![delentia.com](https://img.shields.io/badge/delentia.com-Visit-0066FF?style=for-the-badge)](https://delentia.com)
&nbsp;
[![🤗 HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20Delentia-yellow?style=for-the-badge)](https://huggingface.co/Delentia)

</div>
