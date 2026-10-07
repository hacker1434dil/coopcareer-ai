# CoopCareer AI: Empowering Skills, Enabling Careers

> **Smart India Hackathon 2026** | Team **Tech Mavericks** | Aditya University

CoopCareer AI is an AI-powered platform that connects **learning, skills, verified credentials and employment** in one ecosystem, built to bridge the talent gap for rural and cooperative-sector learners.

**Demo video:** [ADD YOUR LINK HERE]
**Live demo:** [ADD YOUR DEPLOYED LINK HERE]
**Presentation:** [`docs/SIH2026_COOPCAREER_AI.pdf`](docs/SIH2026_COOPCAREER_AI.pdf)

---

## Problem Statement

| | |
|---|---|
| **Problem Statement ID** | SIH26087 |
| **Title** | AI & LMS-Enabled Cooperative Capacity Building, ERP & Employment Ecosystem |
| **Theme** | Smart Education |
| **Category** | Software |
| **Organization** | Ministry of Cooperation, Government of India |
| **Department** | National Council for Cooperative Training (NCCT) |
| **Team ID** | AUS_SIH26_274 |

## The Problem

A certificate shows that someone completed a course. It does not always show their real skills, strengths or job readiness. Skilled learners, especially in rural areas, stay invisible to employers because there is no trusted proof of what they can do.

## Our Solution

One platform that takes a learner from first lesson to first job:

**Learn → Attend → Assess → Build Skills → Certify → Career → Job → Recruit**

### Key Features

- **Digital Learning:** structured courses and modules with progress and attendance tracking
- **Skill Assessment:** knowledge tests, assignments and practical evaluations
- **AI Skill Profile:** a verified skill profile built from learning performance and assessments
- **Skill-Gap Intelligence:** compares a learner's skills against a target job role and shows what to learn next
- **AI Career Guidance:** recommends suitable career paths
- **Verified Credentials:** certificates that can be authenticated instantly; invalid IDs are rejected
- **Explainable AI Job Matching:** employers see *why* a candidate matches, not just a score
- **Four connected portals:** Student, Trainer, Employer and Admin dashboards

## Screenshots

| Landing page hero section | Enterprise platform architecture |
|---|---|
| ![CoopCareer AI landing page hero section](assets/landing.png) | ![CoopCareer AI enterprise platform architecture cards](assets/platform-architecture.png) |

| About platform audience cards | Student dashboard |
|---|---|
| ![Rural skill and employment divide and audience cards](assets/about-platform.png) | ![Rahul Deshmukh student dashboard](assets/student-dashboard.png) |

## Tech Stack

> Update this section so it matches exactly what you built.

| Layer | Technology |
|---|---|
| Frontend | React.js, Tailwind CSS, Chart.js |
| Backend | Python (FastAPI) / Node.js (Express) |
| AI & NLP | spaCy, Transformers (sentence embeddings for matching) |
| Database | PostgreSQL, MongoDB |
| Auth & Security | JWT authentication, role-based access |
| Deployment | Vercel (frontend), Render (backend), Docker |

## How It Works

1. **Data Collection:** learners, courses, assessments, skills and job postings
2. **Data Processing:** cleaning, validating and structuring the data
3. **Skill Extraction:** AI extracts and maps skills from learner activity
4. **Matching Engine:** matches learners with careers and jobs
5. **Recommendation:** suggests courses and skills to improve readiness
6. **Visualization & Insights:** dashboards for learners, trainers, employers and admins

## Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/coopcareer-ai.git
cd coopcareer-ai

# 2. Backend
cd backend
pip install -r requirements.txt
cp .env.example .env        # add your own values
uvicorn main:app --reload

# 3. Frontend (in a new terminal)
cd frontend
npm install
npm run dev
```

> Replace these commands with the exact steps for your project.

## Demo Accounts

> Add demo-only logins here if you want judges or visitors to try each role.
> Never publish real passwords or personal data.

| Role | Email | Password |
|---|---|---|
| Student | | |
| Trainer | | |
| Employer | | |
| Admin | | |

## Team Tech Mavericks

- Dilip Chigirivalasa
- M. Yeswanth Reddy
- P. Pavan
- Shaik Mohammad Nusrath
- Shaik Mohammad Ajmal
- Atrija Devanjana

Built during the Internal Hackathon for SIH 2026 at **Aditya University**, with support from the Entrepreneurship Development Cell (EDC) and the Institution's Innovation Council (IIC).

## References

- [National Education Policy 2020](https://www.education.gov.in/sites/upload_files/mhrd/files/NEP_Final_English_0.pdf)
- [National Skill Development Corporation (NSDC)](https://www.nsdcindia.org/resources/annual-report)
- [Ministry of Cooperation](https://www.cooperation.gov.in/)
- [National Career Service Portal](https://www.ncs.gov.in/)
- [SWAYAM](https://swayam.gov.in/) | [NPTEL](https://nptel.ac.in/)

## License

[MIT](LICENSE) (or choose the license your team prefers)
