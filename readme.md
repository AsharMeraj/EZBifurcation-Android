# EZBifurcation 📱

> An Android app for managing patient registrations, vitals, and doctor consultations — built for clinics that need things done on the go.

![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android)
![Kotlin](https://img.shields.io/badge/Kotlin-Language-7F52FF?style=flat-square&logo=kotlin)
![XML](https://img.shields.io/badge/UI-XML%20Layouts-orange?style=flat-square)
![Retrofit](https://img.shields.io/badge/Networking-Retrofit-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Patient Registration](#patient-registration)
- [Vitals](#vitals)
- [Doctors Portal](#doctors-portal)
- [Doctors Prescription](#doctors-prescription)
- [Tech Stack](#tech-stack)
- [License](#license)

---

## Overview

I built EZBifurcation to bring clinic management onto Android — no desktop required. The app covers the full patient workflow, from first-time registration all the way through to a doctor's final prescription, with separate flows for staff and physicians. Everything talks to a backend API so data stays in sync across the clinic. The goal was to keep it practical and fast to use, even for staff who aren't particularly tech-savvy.

---

## 👤 Patient Registration

This is the starting point for any new patient walk-in. Staff can fill in all the key demographic details — name, age, contact info, and other identifiers — and get the patient into the system within a minute. Returning patients can be looked up and updated just as quickly. I kept the form layout clean so there's no guesswork involved.

- Register new patients or update existing records directly from the app
- Patient data is saved to the backend and immediately available across all other sections

<img src="/public/assets/PatientRegistration.png" width="500"/>

---

## 📊 Vitals

After registration, the next step is getting a patient's vitals on record. This screen lets staff log readings like blood pressure, heart rate, temperature, and oxygen levels, all linked to the patient's profile. Each vital shows up in its own card so it's quick to scan. Doctors can reference this history when they're ready to consult.

- Log and store patient vitals with each entry tied to the correct patient profile
- Historical vital data is displayed in a card-based layout for easy review before consultations

<img src="/public/assets/Vitals.png" width="500"/>

---

## 🩺 Doctor's Portal

The Doctor's Portal is the physician's side of the app. Doctors have their own sign-in flow and land in a dedicated space where they can view patient demographics, check recorded vitals, and kick off a consultation. The portal also handles doctor registration and profile management, so adding a new doctor to the system takes no time. I made sure the navigation here is tight — switching between patient info and consultation tools is straightforward.

- Separate doctor authentication with profile management built into the portal
- Full access to patient demographics and vitals before starting any consultation

<img src="/public/assets/DoctorPortal.png" width="500"/>

---

## 📝 Doctor's Prescription

This is where the consultation wraps up. After reviewing a patient's details, the doctor can record a diagnosis, write out prescriptions, and add any notes — all from one screen. I used structured selection components to make picking diagnoses and medications faster and less error-prone. The completed prescription gets saved against the patient's record so it's always there to reference later.

- Write structured prescriptions with diagnosis and medication selection built right in
- Consultation records and notes are saved per patient for future reference

<img src="/public/assets/DoctorPrescription.png" width="500"/>

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| Kotlin | Primary development language |
| Android SDK | Core app framework |
| XML Layouts | UI design and screen structure |
| Retrofit | API communication and networking |
| ViewModel / LiveData | State management across screens |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">Built to make clinic workflows a little less painful 💙</p>