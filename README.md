# Study Coven 🎓✨

An interactive web platform where high school and university students study together, stay focused, and build strong academic habits — in a safe, supportive, and gamified online environment.

---

## 📌 Overview

Study Coven is an HCI (Human-Computer Interaction) project focused on designing and prototyping a collaborative study platform. The project combats common student challenges such as procrastination, lack of focus, and ineffective study habits by combining AI-powered group matching, distraction monitoring, gamification, and creative collaboration spaces into one seamless experience.

This repository contains the project documentation, research artifacts, and design files. The high-fidelity prototype is hosted on Figma (links below).

---

## 🎯 Project Objectives

- **AI-Powered Group Matching** — Group students into video study calls based on subject, grade level, gender, and personal interests.
- **Focus Monitoring** — Use AI to monitor group sessions, reduce distractions, and gently encourage on-task behavior.
- **Personalized AI Study Assistant** — Allow students to upload study materials and auto-generate personalized study plans with milestones.
- **Study Method Optimization** — Teach evidence-based techniques like Pomodoro, mind mapping, and spaced repetition, plus access to AI-powered study tools.
- **Healthy Study Habits** — Promote effective, balanced, and diligent study routines over cramming.
- **Gamification & Leaderboard** — Boost engagement with a points system for completing tasks, attending sessions, and helping peers, plus customizable avatars.
- **Peer Mentorship Program** — Encourage older students to volunteer as mentors and earn badges or recognized volunteer hours (e.g., Fazaa program certification).
- **Creative Collaboration Spaces** — Digital art rooms, writing rooms, and debate/discussion rooms for non-academic collaboration.
- **Shared Music Experience** — Collaborative playlists with real-time voting, skipping, and track suggestions.

---

## 🎨 Figma High-Fidelity Prototype

- 🔗 **Version 1 (Initial Prototype)** —
-   https://www.figma.com/proto/1dTkDSDc0jkuN0KWyY4uFO/Give-up--me-?node-id=653-17646&t=sNeOPSI49WfnQkoT-1&scaling=min-zoom&content-scaling=fixed&page-id=645%3A7592&starting-point-node-id=653%3A19022
- 🔗 **Version 2 (Iterated Prototype — Recommended)** —
- https://www.figma.com/proto/1dTkDSDc0jkuN0KWyY4uFO/Study-Coven?node-id=653-24878&t=H5Dydy7jMPA8LUPI-1&scaling=min-zoom&content-scaling=fixed&page-id=653%3A24597&starting-point-node-id=653%3A26254
### Prototype Contents

- Onboarding & user profile setup (grade, subjects, interests, gender)
- AI-matched study room lobby
- Live group video study session UI (with focus indicators)
- Personalized AI study assistant & study plan generator
- Smart calendar with milestones & deadline tracking
- Gamified dashboard (points, streaks, leaderboard, avatar customization)
- Creative collaboration rooms (art, writing, debate)
- Shared music experience
- Peer mentorship hub
- Settings, privacy, and safety controls

---

## 🧠 HCI Design Process

| Phase | Description |
|---|---|
| 1. Empathize | User interviews & two surveys (requirement gathering + feature validation) |
| 2. Define | Problem statements, user personas, pain points, and goals |
| 3. Ideate | Brainstorming, affinity diagrams, low-fi sketches |
| 4. Prototype | Wireframes → mid-fi → high-fidelity Figma prototype |
| 5. Test | Two rounds of usability testing + heuristic evaluation |
| 6. Iterate | Design refinements based on user feedback (Version 1 → Version 2) |

---

## 👥 Target Users

- **Primary:** High school students (grades 8–12)
- **Secondary:** University undergraduates
- **Tertiary:** Older students volunteering as peer mentors

### User Needs

- A safe and secure platform
- Gender-based group separation
- Supportive, judgement-free academic environment
- A distraction-free study experience
- Smart group matching by grade level, subject, and gender

### Pain Points

- Struggle to find good study partners
- Difficulty avoiding distractions while studying
- Hesitation to ask for help due to shame or fear of judgment
- Feeling unsafe or uncomfortable with strangers online
- Struggle to stay motivated alone

### Goals

- Connect with other students
- Study more effectively
- Access tutoring in a supportive environment
- Study with peers in their own age and gender group safely
- Reduce exam stress

---

## 🧪 Usability Testing

### Round 1
Minor bugs identified and patched before proceeding to Round 2.

### Round 2 (Face-to-face with university & high school students)
- ~90% of users could use the app independently without assistance.
- Users found the design easy to learn and navigate.
- Users enjoyed the interactivity and expressed interest in testing a fully developed version.

### Design Complaints → Improvements

| Complaint | Fix |
|---|---|
| Plain white background on sign-up/sign-in | Adjusted colours to be more engaging and readable |
| Homepage appeared too empty | Added extra descriptions about app features |
| Some text hard to read due to colour choices | Improved colour contrast |
| Calendar page size issues | Adjusted calendar page sizes |
| AI app in meeting was hard to find (white) | Changed AI app colour to stand out |
| Messages button hard to use/find | Added messages button to the meeting bottom bar |

**Iteration Result:** Version 2 was tested again to confirm all issues were resolved.

---

## 🔒 Safety & Moderation Protocols

- **Participant Reporting & Moderation** — Vote-to-remove disruptive users, automated logging, false-report detection, and manual moderator review.
- **Verified Account Access** — Sign-up/login via verified institutional credentials only; no anonymous accounts.
- **Privacy Assurance** — Cameras disabled by default, screen sharing requires permission, no unauthorized recording.

---

## 📁 Repository Structure

```
StudyCoven/
├── README.md
├── docs/
│   ├── research/            # Surveys & requirement gathering
│   ├── personas/            # User personas
│   └── usability-testing/   # Round 1 & Round 2 results
├── design/
│   ├── wireframes/
│   ├── mid-fi/
│   └── hi-fi/               # Figma exports
└── prototype/
    └── figma-links.md       # Direct links to prototypes
```

---

## 🔗 Quick Links

- [Figma Prototype v1](#)
- [Figma Prototype v2](#)
- [Figma Project File](#)

---

## 🛠️ Tech & Tools

**Design:** Figma (high-fidelity prototype)

**Research:** User interviews, surveys, usability testing, heuristic evaluation

**Proposed Development Stack:**
- **Frontend:** React / Next.js
- **Backend:** Node.js + Express
- **AI:** OpenAI API / custom ML models for matching & focus detection
- **Video:** WebRTC / Daily.co / Agora
- **Database:** PostgreSQL / Firebase

---

## ✅ Status

- [x] Problem definition & user research (2 surveys)
- [x] Personas & user journey maps
- [x] Low-fidelity wireframes
- [x] High-fidelity Figma prototype (v1)
- [x] Usability testing Round 1
- [x] Usability testing Round 2
- [x] Iteration & redesign (v2)
- [x] Final prototype validation
- [ ] Fully developed web application (future work)

---

## 🤝 Contributors

| Name | Role |
|---|---|
| Your Name | UX Research / UI Design / Prototyping |
| Teammate | HCI Evaluation |
| Teammate | Interaction Design |

---

## 📜 Conclusion

No project is ever perfect, but given the timeframe and the team's initial lack of Figma experience, Study Coven successfully achieved almost all of its goals. We applied HCI principles across all phases — from requirements gathering to sketching and finally building an accessible, user-friendly design. We relied on recognition over recall through consistent symbols, offered adjustable text sizes and voice functionality in the AI assistant for accessibility, and prioritized the Usability Design Principles — validated by users navigating the prototype without assistance.

> ⚠️ **Note on Figma:** We encountered persistent, unpredictable bugs where elements would randomly appear, disappear, or change size. If issues arise, refreshing the Figma page resolves them.

---

## 📬 Contact

For questions or feedback, please open an issue or reach out via email: saraalmessabie@gmail.com

---

⭐ If you find this project interesting, give it a star!
