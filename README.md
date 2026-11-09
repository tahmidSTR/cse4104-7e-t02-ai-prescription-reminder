# AI-Powered Prescription Recognition and Intelligent Medication Reminder System

> Photograph a handwritten prescription, confirm what the AI read, and get a reliable medication reminder schedule.

## Team Information

| Field | Details |
|---|---|
| **Team Name** | CSE4104-7E-T02 |
| **Section** | 7E |
| **Repository** | https://github.com/tahmidSTR/cse4104-7e-t02-ai-prescription-reminder |

| Role | Name | Student ID |
|---|---|---|
| Team Leader | Syed Tahmid Reza | 11230321330 |
| Member | Ashikur Rahman Sobuj | 11230321319 |
| Member | Md Siam | 11230321333 |

## Project Description

In Bangladesh, most prescriptions are handwritten and use shorthand dose patterns such as "1+0+1" (morning, noon, night). Many patients, especially elderly people, find them hard to read and follow, which leads to missed doses, medicines taken at the wrong time, and a poor understanding of the treatment.

Existing tools each solve only part of the problem. Global reminder apps require manual entry of every medicine, local apps cannot read a paper prescription, medicine index apps have no reminders, and research prototypes stop at text extraction. There is no accessible tool that turns a photo of a handwritten Bangladeshi prescription directly into a confirmed reminder schedule.

This project fills that gap. A user photographs a prescription, a multimodal AI model extracts the medicine names, doses, durations and timing patterns, and the user reviews and confirms the result before anything is saved. The system then creates reminders, tracks whether each dose was taken or missed, and provides plain-language medicine information.

The system supports, and does not replace, the advice of a doctor or pharmacist. Low-confidence readings are highlighted so that nothing unverified is trusted automatically.

**Target users:** Everyone from elderly individuals and their caregivers to busy professionals managing their health without full-time support.

### Objectives

- Extract medicine names, doses, durations and timing patterns from a photo of a handwritten prescription.
- Let users review, correct and confirm the extracted schedule before it is saved.
- Send timely medicine reminders and track taken and missed doses.
- Provide plain-language medicine information, including generic names and general price data.
- Gently flag a medicine that does not seem to match the stated condition and advise consulting a doctor or pharmacist.
- Provide a simple, responsive interface suitable for elderly users and caregivers.

## Proposed Features

- User registration and login with secure authentication
- Prescription photo upload and image storage
- AI-based extraction of medicine name, dose, duration and timing from the photo
- Confirm-and-edit screen for the extracted schedule, with low-confidence readings highlighted
- Automatic reminder schedule creation from the confirmed prescription
- Scheduled reminders for each dose
- Dose tracking (taken, missed, skipped) with history
- Medicine information page with a plain-language explanation, generic name and general price data
- Condition-based caution note advising the user to consult a doctor or pharmacist
- Dashboard showing today's doses, adherence summary and active prescriptions
- Caregiver view so a family member can monitor adherence *(if time permits)*
- Responsive design that works on mobile

## Technology Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React (Vite), Tailwind CSS, Capacitor shell |
| **Native Plugins** | `@capacitor/local-notifications`, `@capacitor/camera`, `@capacitor/filesystem`, `@capacitor/push-notifications` |
| **Backend** | Node.js, Express, JSON Web Token (JWT) authentication, bcrypt, node-cron |
| **Database** | PostgreSQL (Supabase free plan), Supabase Storage for prescription images |
| **AI** | Google Gemini API (multimodal) |
| **Deployment** | Render, Vercel / Netlify, Supabase, GitHub Releases / Firebase App Distribution |
| **Tools** | GitHub, Postman, Figma, Android Studio, Vitest / Jest |

## Installation Instructions

*Coming soon.*

## Deployment Link

*Coming soon.*

## Screenshots

*Coming soon.*

## Disclaimer

This application is an academic project. It is a reminder and information aid and does not provide medical advice. Always follow your doctor's or pharmacist's instructions.
