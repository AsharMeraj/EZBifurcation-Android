# Digital Clinic Desktop 🏥

> A desktop app for managing patients, vitals, and doctor consultations — built with Next.js and Electron.

![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript)
![Electron](https://img.shields.io/badge/Electron-Desktop-47848F?style=flat-square&logo=electron)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=flat-square&logo=tailwind-css)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Patient Registration](#patient-registration)
- [Vitals](#vitals)
- [Doctor's Portal](#doctors-portal)
- [Doctor's Prescription](#doctors-prescription)
- [Tech Stack](#tech-stack)
- [License](#license)

---

## Overview

I built Digital Clinic Desktop to give clinics a single, organized place to handle everything — from patient intake to doctor consultations. It runs as a native desktop app and covers the full workflow a clinic goes through during a typical patient visit. The app has separate flows for front-desk staff and doctors, so everyone only sees what they need. All data moves through a central API layer, keeping things consistent across the board.

---

## 👤 Patient Registration

This is where every patient journey starts. Staff can register new patients or pull up existing ones and make updates on the spot. The form captures all the key demographic details — name, age, contact info, and more — in a clean, simple layout that doesn't get in the way. I made sure the fields are straightforward so even non-technical staff can get through registration quickly.

- Register new patients or update existing patient records with ease
- Demographic data is validated and stored through the backend API for reliable retrieval across sessions

<img src="/public/assets/PatientRegistration.png" width="800"/>

---

## 📊 Vitals

Once a patient is registered, the next step is recording their vitals. This section lets staff log readings like blood pressure, heart rate, temperature, and more, all tied to the specific patient. Each reading is displayed in its own card so it's easy to scan at a glance. Historical vitals can also be reviewed here, giving doctors useful context before a consultation.

- Log and track key patient vitals in a structured, card-based layout
- Vital history is persisted per patient, making it available during consultations

<img src="/public/assets/Vitals.png" width="800"/>

---

## 🩺 Doctor's Portal

The Doctor's Portal is where physicians take over. Doctors sign in separately from front-desk staff and get access to patient information, their recorded vitals, and the tools they need to carry out a consultation. The portal also handles doctor registration and profile management, so onboarding a new doctor to the system is straightforward. I kept the navigation tight here — doctors can move between patient data and consultation tools without losing their place.

- Separate doctor sign-in and profile management built right into the portal
- Doctors get a focused view of patient demographics and vitals before starting a consultation

<img src="/public/assets/DoctorPortal.png" width="800"/>

---

## 📝 Doctor's Prescription

This is the core of the consultation flow. After reviewing a patient's data, the doctor can record their diagnosis, write out prescriptions, and add any notes — all from one screen. I used multi-select and single-select components here to make picking diagnoses and medications faster and less error-prone. Once the consultation is complete, the prescription is saved and can be referenced later.

- Write and save prescriptions with structured diagnosis and medication selection
- Consultation notes and records are tied to the patient for future reference

<img src="/public/assets/DoctorPrescription.png" width="800"/>

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 15 | Frontend framework (React-based) |
| Electron | Desktop app packaging |
| TypeScript | Type-safe development |
| Tailwind CSS | Styling and UI design system |
| PostCSS | CSS processing |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">Built with care for clinics that deserve better tools 💙</p>