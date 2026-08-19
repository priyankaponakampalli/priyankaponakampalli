<!-- Replace YOUR_USERNAME and YOUR_LINKEDIN -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=220&section=header&text=Sai%20Priyanka%20Ponakampalli&fontSize=42&fontColor=ffffff&animation=fadeIn&desc=Software%20Engineer%20%7C%20Mobile%20App%20Developer%20%7C%20AI%20Enthusiast&descAlignY=68"/>
</p>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=22&duration=3000&pause=1000&center=true&vCenter=true&width=900&lines=Software+Engineer+%7C+AI+Enthusiast;Government+Projects+%7C+Startup+Experience;Java+Developer+%7C+Frappe+Learner;Where+technical+skills+meet+leadership+and+public+speaking" />
</p>

<p align="center">
<a href="https://github.com/priyankaponakampalli"><img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Profile%20Views&color=2563eb&style=for-the-badge"/></a>
<a href="https://www.linkedin.com/in/sai-priyanka-ponakampalli-861216323/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin"/></a>
<a href="mailto:saipriyankaponakampalli@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail"/></a>
</p>

# About Me

I'm **Sai Priyanka Ponakampalli**, a Computer Science undergraduate at **VIT-AP University** passionate about building software that solves meaningful real-world problems.

I've worked with a **Government of Andhra Pradesh initiative** and multiple startups, contributing to products in agriculture and home services. I enjoy taking ideas from concept to deployment while continuously learning backend development, enterprise software, and AI.

Beyond coding, I'm an active **public speaker** who has participated in **debates, youth parliaments, technical talks, NGO initiatives, hackathons, and student leadership programs**, helping me become a confident communicator and collaborative team player.

---

# Recruiter Snapshot

| Quick Facts | |
|---|---|
| 🎓 Education | B.Tech CSE, VIT-AP University |
| 📊 CGPA | 8.61 / 10 |
| 💻 Interested In | Software Engineering • Backend • Full Stack |
| 🌱 Currently Learning | Frappe Framework, ERPNext, System Design |
| 📍 Open To | Internships & Full-Time Opportunities |

---

# Featured Experience

## 🌱 Rythu Sadhikara Samstha (PavithraMithra) — Government of Andhra Pradesh

A cross-platform application connecting **farmers, buyers, sellers, and aggregators** in the natural farming ecosystem.

### My Contributions
- Developing production-ready mobile features
- Integrated backend APIs
- Improved application performance
- Enhanced user experience

### Impact
Every farmer receives a **unique QR code** that opens their digital profile containing:
- Ratings & Reviews
- Farm Details
- Product Information
- Credibility & Trust
- Contact Information

This helps buyers confidently purchase from verified farmers while promoting transparency.

---

## 🏠 OnlyClick — Marketing, Startup

OnlyClick connects customers with trusted home-service professionals (electricians, plumbers, painters, cleaners, appliance technicians, etc.).

### My Contributions
- 📣 Led **outreach and promotion** to build early awareness among target customers
- 🤝 Onboarded **service professionals** onto the platform
- 📈 Contributed to **growth strategy** for acquiring customers and providers in the early stage
- 🧩 Worked directly with the founding team on real-time market feedback and iteration
- 🗣️ Used pitching and communication skills to convert outreach into sign-ups

### What I Gained
- Hands-on **startup marketing & growth** experience
- Understanding of acquisition, onboarding, and customer-first product thinking

---

# Projects

## 💎 Gemstone Classification using Deep Learning

A deep learning-based image classification system built to accurately identify **87 different gemstone categories** from images — a fine-grained classification problem where visually similar stones can be easy to confuse.

Rather than settling on a single model, I treated this as a comparative study: training and evaluating multiple deep learning architectures on the same dataset to understand *why* certain models generalize better than others on fine-grained visual tasks.

### Key Features
- 🔍 Classifies gemstones into **87 distinct categories**
- 🧠 Implemented and compared multiple deep learning models
- 📈 Evaluated model performance using accuracy, precision, recall, and F1-score
- ⚙️ Applied Transfer Learning and Fine-Tuning to boost prediction performance
- 📊 Analysed the strengths and limitations of each architecture
- 📝 Findings are being written up as a research paper

### Models Explored
- CNN (baseline)
- Xception
- ResNet50V2

### What I Learned
This project took me through the full deep learning workflow — image preprocessing and dataset preparation, building and training CNNs from scratch, applying transfer learning and fine-tuning pre-trained models, hyperparameter tuning, and interpreting training/validation curves to iteratively improve results. Most importantly, it taught me how to reason about *which* architecture suits a problem, not just how to train one.

### Impact
Demonstrates how deep learning can automate gemstone identification, cutting down manual effort while improving classification accuracy, and provides a practical framework for choosing the right architecture on fine-grained image classification tasks.

---

## 🏨 Hostel Complaint Management System

A web-based system built on the **Frappe Framework** that turns hostel complaint handling — usually scattered across texts and word-of-mouth — into a centralized, trackable workflow for both students and administrators.

### Why Frappe
I chose Frappe because it comes with the essentials of a real-world application out of the box — database management, authentication, user roles and permissions, forms, APIs, and an admin interface — so I could focus on designing the actual complaint workflow rather than rebuilding infrastructure from scratch. It also gave me hands-on experience with a framework purpose-built for ERP and business applications.

### How It Works
```
Student submits complaint → Pending → Assigned to Admin → In Progress → Resolved
```
Students submit complaints with details like name, registration number, room number, category, and description. Administrators can then view, assign, and update the status of each complaint through to resolution.

### Key Features
- Web form for submitting hostel complaints
- Structured, categorized complaint storage in the database
- Status tracking (Pending → In Progress → Resolved)
- Complaint assignment to administrators
- Role-based access and authentication
- Admin management via Frappe Desk

### Tech Stack
`Frappe Framework` `Python` `JavaScript` `MariaDB` `Redis` `HTML/CSS` `Frappe Bench` `Git/GitHub`

### What I Learned
Building this end-to-end taught me how to create DocTypes, design web forms, manage users and permissions, and run and deploy an app with Frappe Bench — and, more broadly, how to turn a everyday real-world problem into a structured software workflow instead of a basic CRUD exercise.

### Future Improvements
Student-specific complaint visibility, email/status notifications, an admin dashboard with complaint statistics, image attachments, a more mobile-friendly interface, and analytics/reports.

---

## 🌿 Telangana Mandi Price Finder

**🔗 Live app:** [mandi-price-finder.streamlit.app](https://mandi-price-finder.streamlit.app)

A Streamlit app that pulls **real, official mandi (market) prices** from across Telangana, so you know the fair price of a vegetable or fruit before you go shopping — instead of trusting whatever the vendor quotes.

### Why I Built It
Prices swing depending on the day, season, and market, and there's no easy baseline — especially if you're new to an area. This app fixes that: pick a commodity and a mandi, and see the actual minimum, maximum, and modal price reported that day, sourced directly from government data.

### What It Does
- Pulls **live** data from the Government of India's Open Data API on every search — no cached snapshots
- Populates the market dropdown from real, current mandi names in the dataset
- Shows the full min / modal / max price range, not just a single number
- Falls back gracefully to the nearest available market record when exact data isn't available, and flags that it did so
- Covers fruits, vegetables, pulses, and spices, with district, variety, grade, and reporting date

### Tech Stack
`Streamlit` `Python` `Requests` — powered by the **Agmarknet dataset** (Ministry of Agriculture & Farmers Welfare) via [data.gov.in](https://www.data.gov.in)'s Open Government Data API.

### The Harder Parts (a.k.a. real debugging)
- Requests were silently hanging — traced it to the API stalling on Python's default `requests` User-Agent, fixed with a browser-like header
- The dataset's API resource ID had quietly changed after a data.gov.in migration — had to dig through their live catalog for the current endpoint
- Actual API field names (`Market`, `Min_Price`, `Modal_Price`) didn't match the documented casing, so records were silently empty until diagnosed
- Added retries and fast-failing timeouts so the app degrades gracefully instead of hanging when the government API is slow

### Impact
Makes local market prices transparent and accessible, especially useful for anyone new to a city who has no baseline for what's a fair price.

---

# Tech Stack

**Languages**

`Java` `Python` `C` `C++` `SQL` `R`

**Frameworks**

`Frappe` `ERPNext` `React` `HTML` `CSS`

**Databases**

`MariaDB` `MySQL` `MongoDB`

**Tools**

`Git` `GitHub` `VS Code` `IntelliJ IDEA`

---

# Leadership & Activities

- CSI VTalks Lead
- Electoral Society Co-Lead
- Public Speaker
- Debate Participant
- Youth Parliament Participant
- NGO Volunteer
- Technical Event Host & Anchor
- Smart India Hackathon Participant

---

# GitHub Stats

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=github_dark&hide_border=true"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=github_dark&hide_border=true"/>
</p>

<p align="center">
<img src="https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=github-dark&hide_border=true"/>
</p>

---

# Connect

- LinkedIn: Sai Priyanka Ponakampalli
- Email: saipriyankaponakampalli@gmail.com
- Phone: +917569274762

---

> **"Where technical skills meet leadership and public speaking."**
