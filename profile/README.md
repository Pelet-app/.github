# PELET (Pencari Lowongan Efektif & Tepat)
### AI Semantic Matching Berbasis SKKNI

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)

Selamat datang di repositori resmi **PELET**, proyek *Capstone* **Coding Camp 2026 powered by DBS Foundation** oleh tim **CC26-PSU060**. Kami berfokus pada tema *Future-Ready Work & Economy* untuk mengatasi tantangan *skill mismatch* ketenagakerjaan di Indonesia.

---

## Ringkasan Eksekutif

Indonesia menghadapi tantangan besar berupa ketidakcocokan keterampilan (*skill mismatch*) yang berdampak pada tingginya angka pengangguran lulusan SMK dan Pendidikan Tinggi (mencapai 8,62% per Februari 2024, BPS). Sistem rekrutmen saat ini masih mengandalkan pencocokan kata kunci (*keyword matching*) yang kaku, serta belum terintegrasi secara optimal dengan Standar Kompetensi Kerja Nasional Indonesia (SKKNI).

**PELET** hadir sebagai solusi cerdas yang mengintegrasikan *Semantic Matching Engine* berbasis AI dengan database SKKNI untuk memetakan *resume* pelamar kerja secara akurat ke unit-unit kompetensi resmi, menganalisis *skill gap*, serta menyediakan panduan persiapan wawancara secara transparan.

---

## Anggota Tim (CC26-PSU060)

| ID Anggota | Nama | Peran | Status |
| :--- | :--- | :--- | :--- |
| **CFCC938D6Y0854** | Muhammad Firdaus | Full-Stack Web Developer | Aktif |
| **CFCC490D6Y1911** | Bintang Akbar Putra Ansori | Full-Stack Web Developer | Aktif |
| **CDCC237D6X1337** | Sukma Novianti Tulak | Data Scientist | Aktif |
| **CDCC237D6X1441** | Ai Irma Anjelina | Data Scientist | Aktif |
| **CACC222D6Y2568** | Muhamad Yazid Zinky Arisona | AI Engineer | Aktif |
| **CACC965D6Y2630** | Gihan Dimas Ardiyan | AI Engineer | Aktif |

**Advisor Capstone:**
* Marya Batubara
* Pandu Pratama Kusnandi

---

## Fitur Utama & Solusi Teknologi

1. **Semantic Matching Engine (Sentence-BERT)**
   Menggunakan model `paraphrase-multilingual-MiniLM-L12-v2` untuk membandingkan kesamaan makna antara CV dan lowongan secara kontekstual (bukan sekadar kata kunci kaku).
   * *Performa:* Test Accuracy: **99,06%**, F1-Score: **0,99**, MAE: **0,0173**.
2. **Analisis Gap Kompetensi Berbasis SKKNI**
   Menganalisis kekurangan kompetensi pelamar langsung mengacu pada kode unit resmi SKKNI menggunakan prinsip *Competency-Based Learning (CBL)*.
3. **AI Interview Question Generator (Qwen Model)**
   Membuat 1 pertanyaan teknis utama dan 2 pertanyaan *follow-up* adaptif yang diikat pada unit SKKNI untuk sarana simulasi dan persiapan mandiri pelamar.
4. **Explainable AI (XAI)**
   Menghadirkan transparansi penuh dengan menjelaskan alasan di balik rekomendasi pelatihan dan keterkaitan pertanyaan wawancara dengan standar SKKNI.
5. **PII Redaction (Keamanan Data)**
   Fungsi `redact_pii()` bawaan secara otomatis menyensor informasi pribadi sensitif sebelum data berinteraksi dengan API eksternal.

---

## Tech Stack & Penyelesaian Proyek

Proyek ini telah selesai **100%** sesuai rencana dengan cakupan (MVP) pada 5 bidang digital & finansial terpopuler (*Programmer, UI/UX Designer, Data Analyst, Cyber Security, dan Keuangan*).

### Main & Side Quests Checklist
- [x] **Front-End:** Web responsive, bundler Vite, integrasi API, bebas Web Generator.
- [x] **Back-End:** RESTful API Express.js dengan arsitektur rapi (routes, controllers, services, repositories) dan local storage UX.
- [x] **Artificial Intelligence:** Deep Learning TensorFlow, FastAPI untuk model serving, integrasi API Qwen via OpenRouter.
- [x] **Data Science:** End-to-end Data Wrangling, EDA mendalam, ab tetsing, dan Interactive Dashboard menggunakan Streamlit.

---

## Tautan Penting & Sumber Daya

Silakan akses komponen proyek kami melalui tautan di bawah ini:

* **[Deploy Aplikasi Web Frontend](https://pelet-app.vercel.app/)**
* **[Deploy Server Backend API](http://backendcapstone-production-6ba8.up.railway.app)**
* **[Deploy API Service AI/ML](https://egoekosetio-ai-capstone.hf.space)** 
* **[Dashboard Data Science (Streamlit)](https://data-science-jtqg8peajwjqqksibr9pji.streamlit.app/)** 
* **[Dataset PELET](https://github.com/SkillBridge-AI-Semantic-Skill-Matching/Data-Science/tree/main/dataset)** 
* **[Slide Presentasi Proyek](https://canva.link/ygdedjt2vezfsut)** 

---

## Antarmuka Aplikasi (Product Screenshots)

### Tampilan Pencari Kerja (Job Seeker)
![Job Seeker View](https://via.placeholder.com/800x450.png?text=Tampilan+Job+Seeker+Halaman+Utama) 
*Analisis CV, Score Kecocokan Semantik, dan Rekomendasi Pelatihan Mandiri.*

### Tampilan Perekrut (HRD / Recruiter)
![HR View](https://via.placeholder.com/800x450.png?text=Tampilan+HRD+Applicant+Ranking)
*Dashboard Pelamar, Fitur Applicant Ranking otomatis, dan Penyaringan CV objektif.*

---

## Analisis Singkat SWOT

* **Strengths:** Akurasi pencocokan tinggi (99.06%), terintegrasi SKKNI, transparan (XAI), aman (PII Redaction).
* **Weaknesses:** Ketergantungan terhadap API eksternal (OpenRouter), kebutuhan biaya server GPU untuk inferensi nyata.
* **Opportunities:** Menjawab potensi Bonus Demografi 2030 di Indonesia, tingginya adopsi pencarian kerja digital (>72% pemuda usia 18-35 tahun).
* **Threats:** Kompetisi ketat dari platform global yang sudah mapan (*LinkedIn, Glints*).

---
<p align="center">
  <b>PELET © 2026 - Future-Ready Work & Economy Capstone Project</b><br>
  Powered by DBS Foundation & Dicoding Indonesia
</p>
