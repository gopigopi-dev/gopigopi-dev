<div align="center">

<img src="./assets/banner.svg" alt="Gopzz - Aspiring Developer, Android and Web, AI Enthusiast" width="100%">

<br>

**Android apps in Kotlin &nbsp;·&nbsp; Web tools in HTML, CSS and JavaScript &nbsp;·&nbsp; Exploring AI agents**

<a href="https://github.com/gopigopi-dev?tab=repositories">Repositories</a> &nbsp;·&nbsp;
<a href="#featured-projects">Projects</a> &nbsp;·&nbsp;
<a href="#technologies-and-tools">Technologies</a> &nbsp;·&nbsp;
<a href="#connect-with-me">Connect</a>

</div>

<img src="./assets/divider.svg" alt="" width="100%">

## About Me

I'm **Gopzz**, a BCA student and aspiring developer. I build small, practical tools: a voice-first billing app for a mechanical workshop, an Android app that enforces daily limits on distracting apps, and web tools for college use.

I learn by building. My GitHub history moves from web fundamentals (HTML, CSS, JavaScript) into native Android with Kotlin and Jetpack Compose, and I'm interested in AI agents. Tamil and English both matter in my work, and the billing app understands both.

## My Development Journey

Based on the activity visible on my repositories.

| When | Focus | What I built |
| :-- | :-- | :-- |
| Oct 2026 | Web fundamentals | [College Transport Portal](https://github.com/gopigopi-dev/College-transport-portal-) in HTML, CSS and JavaScript, deployed on GitHub Pages |
| Oct 2026 | JavaScript and browser storage | [Student Attendance Tracker](https://github.com/gopigopi-dev/Student-attendance-tracker-) with Local Storage |
| Nov 2026 | Native Android | [Calculators](https://github.com/gopigopi-dev/Calculators-Mechanical-Workshop-Billing-Application-) and [Force Stop](https://github.com/gopigopi-dev/Force-stop-digital-wellbeing) in Kotlin, Jetpack Compose and Room |
| Ongoing | AI agents | Designing the AGENTIC-AI Desktop assistant (concept stage) |

<img src="./assets/divider.svg" alt="" width="100%">

## Featured Projects

| Project | Type | Main stack | Status |
| :-- | :-- | :-- | :-- |
| [Calculators](#calculators--mechanical-workshop-billing) | Android app | Kotlin, Jetpack Compose, Room | In Progress |
| [Force Stop](#force-stop--digital-wellbeing) | Android app | Kotlin, Jetpack Compose, Room | In Progress |
| [Student Attendance Tracker](#student-attendance-tracker) | Web app | HTML, CSS, JavaScript | Completed |
| [College Transport Portal](#college-transport-portal) | Web app | HTML, CSS, JavaScript | Completed |
| [AGENTIC-AI Desktop](#agentic-ai-desktop) | Desktop AI assistant | Not decided | Planned / Concept |

## Project Details and Real-World Problems

### Calculators — Mechanical Workshop Billing

<table width="100%">
<tr><td>

A native Android billing app for **mechanical workshops**. Speak or type a machine part, quantity and amount in Tamil, English or mixed speech, and the app builds the bill.

**Problem it addresses:** workshop billing for spare parts is slow when every item is typed by hand. This app lets the user say the item instead.

**Main features (from the project README)**
- Voice entry in Tamil, English and mixed speech using Android's speech recognizer
- Parsing of product name, quantity and amount from free-form text
- Mechanical parts dictionary with image matching and manual correction
- Line totals and grand total with `BigDecimal`, shown in ₹
- Draft and finalized bills saved locally, with bill history
- PDF receipt preview, print and share



![Status](https://img.shields.io/badge/Status-In%20Progress-A78BFA?style=flat-square&labelColor=0D0B18)




![Kotlin](https://img.shields.io/badge/Kotlin-8B5CF6?style=flat-square)




![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-8B5CF6?style=flat-square)




![Room](https://img.shields.io/badge/Room-8B5CF6?style=flat-square)



[Repository](https://github.com/gopigopi-dev/Calculators-Mechanical-Workshop-Billing-Application-) &nbsp;·&nbsp; No demo or release yet

</td></tr>
</table>

### Force Stop — Digital Wellbeing

<table width="100%">
<tr><td>

An offline-first Android app that enforces **strict daily usage limits** on distracting and entertainment apps.

**Problem it addresses:** it is easy to lose hours to video and social apps. Force Stop blocks an app once its daily allowance runs out.

**Main features (from the project README)**
- Dashboard with a screen-time gauge and a YouTube usage card
- Foreground service with 80% and 100% limit notifications
- Full-screen blocker when a limit is reached, with an optional PIN
- 7-day usage history stored locally in Room



![Status](https://img.shields.io/badge/Status-In%20Progress-A78BFA?style=flat-square&labelColor=0D0B18)




![Kotlin](https://img.shields.io/badge/Kotlin-8B5CF6?style=flat-square)




![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-8B5CF6?style=flat-square)




![Room](https://img.shields.io/badge/Room-8B5CF6?style=flat-square)



[Repository](https://github.com/gopigopi-dev/Force-stop-digital-wellbeing) &nbsp;·&nbsp; [Preview screens](https://github.com/gopigopi-dev/Force-stop-digital-wellbeing/tree/main/docs/screenshots) &nbsp;·&nbsp; No release yet

</td></tr>
</table>

### Student Attendance Tracker

<table width="100%">
<tr><td>

A faculty-oriented web app for keeping student records and daily attendance.

**Problem it addresses:** paper registers make it hard to see attendance percentages and spot students falling behind.

**Main features (checked against the source)**
- Add, edit and delete students
- Date-wise attendance: Present, Absent, Late and On Duty
- Automatic attendance percentage, with a low-attendance warning (default 75%, adjustable)
- Search and filter by name, ID, department or status
- Per-student attendance history and summary cards
- Duplicate attendance for the same student and date is prevented
- Data saved in browser Local Storage



![Status](https://img.shields.io/badge/Status-Completed-8B5CF6?style=flat-square&labelColor=0D0B18)




![HTML5](https://img.shields.io/badge/HTML5-8B5CF6?style=flat-square)




![CSS3](https://img.shields.io/badge/CSS3-8B5CF6?style=flat-square)




![JavaScript](https://img.shields.io/badge/JavaScript-8B5CF6?style=flat-square)



[Repository](https://github.com/gopigopi-dev/Student-attendance-tracker-) &nbsp;·&nbsp; No live demo yet

</td></tr>
</table>

### College Transport Portal

<table width="100%">
<tr><td>

A single-page portal where students can look up **bus routes, pickup points and timings** (branded CampusRide).

**Problem it addresses:** students need one place to find which bus serves their stop and when it arrives.

**Main features (checked against the source)**
- Six bus routes with a stop-by-stop timeline
- Pickup points table with a bus filter, sorted by time
- Live search across buses and pickup points
- "Find My Bus" picker with a countdown to the next pickup
- Route data is stored in the script, so it is sample data until replaced with real college data



![Status](https://img.shields.io/badge/Status-Completed-8B5CF6?style=flat-square&labelColor=0D0B18)




![HTML5](https://img.shields.io/badge/HTML5-8B5CF6?style=flat-square)




![CSS3](https://img.shields.io/badge/CSS3-8B5CF6?style=flat-square)




![JavaScript](https://img.shields.io/badge/JavaScript-8B5CF6?style=flat-square)




![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-8B5CF6?style=flat-square)



[Repository](https://github.com/gopigopi-dev/College-transport-portal-) &nbsp;·&nbsp; [Live demo](https://gopigopi-dev.github.io/College-transport-portal-/)

</td></tr>
</table>

### AGENTIC-AI Desktop

<table width="100%">
<tr><td>

A **concept** for a desktop "Dev Agent" workspace that extends an on-device mobile agent into a multi-agent assistant for software development.

**Problem it addresses:** a privacy-minded assistant that can help with development work while keeping the user in control of what it may do.

**Current state:** I have written a design specification and am working through which parts are technically realistic. There is **no public implementation yet**, so nothing here is claimed as built.



![Status](https://img.shields.io/badge/Status-Planned%20%2F%20Concept-4C1D95?style=flat-square&labelColor=0D0B18)



No repository yet

</td></tr>
</table>

<img src="./assets/divider.svg" alt="" width="100%">

## Technologies and Tools

Only technologies that appear in my repositories.

| Area | Used in my projects |
| :-- | :-- |
| Android | 

![Kotlin](https://img.shields.io/badge/Kotlin-8B5CF6?style=flat-square)

 

![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-8B5CF6?style=flat-square)

 

![Material 3](https://img.shields.io/badge/Material%203-8B5CF6?style=flat-square)

 

![Room](https://img.shields.io/badge/Room-8B5CF6?style=flat-square)

 

![Coroutines](https://img.shields.io/badge/Coroutines-8B5CF6?style=flat-square)

 |
| Web | 

![HTML5](https://img.shields.io/badge/HTML5-8B5CF6?style=flat-square)

 

![CSS3](https://img.shields.io/badge/CSS3-8B5CF6?style=flat-square)

 

![JavaScript](https://img.shields.io/badge/JavaScript-8B5CF6?style=flat-square)

 

![Local Storage](https://img.shields.io/badge/Local%20Storage-8B5CF6?style=flat-square)

 |
| Tools | 

![Git](https://img.shields.io/badge/Git-8B5CF6?style=flat-square)

 

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-8B5CF6?style=flat-square)

 

![Android Studio](https://img.shields.io/badge/Android%20Studio-8B5CF6?style=flat-square)

 |

## Currently Learning

- Kotlin and Jetpack Compose, through the two Android apps above
- AI and ML, including Gemini in Android Studio
- How AI agents are structured: memory, tools, orchestration and permissions

## Work in Progress

| Project | Latest activity |
| :-- | :-- |
| [Force Stop](https://github.com/gopigopi-dev/Force-stop-digital-wellbeing) | Nov 2026 |
| [Calculators](https://github.com/gopigopi-dev/Calculators-Mechanical-Workshop-Billing-Application-) | Nov 2026 |
| AGENTIC-AI Desktop | Design stage, no repository |

<img src="./assets/divider.svg" alt="" width="100%">

## GitHub Statistics

<div align="center">

<img width="48%" alt="GitHub stats for gopigopi-dev" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=gopigopi-dev&theme=dracula">
<img width="48%" alt="Top languages by repository for gopigopi-dev" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=gopigopi-dev&theme=dracula">

</div>

## Contribution Streak

<div align="center">

<img alt="GitHub contribution streak for gopigopi-dev" src="https://streak-stats.demolab.com/?user=gopigopi-dev&hide_border=true&background=0D0B18&ring=8B5CF6&fire=A78BFA&currStreakNum=E9D5FF&sideNums=E9D5FF&currStreakLabel=A78BFA&sideLabels=A78BFA&dates=A78BFA">

</div>

## GitHub Activity Graph

<div align="center">

<img alt="GitHub contribution activity heatmap for gopigopi-dev" width="100%" src="https://ghchart.rshah.org/8B5CF6/gopigopi-dev">

</div>

<sub>These cards are generated live by third-party services. If one does not load, see the [contribution graph on my profile](https://github.com/gopigopi-dev) or my [repositories](https://github.com/gopigopi-dev?tab=repositories).</sub>

## Milestones

Only things I can point to.

- Four projects published on GitHub, spanning web and native Android
- College Transport Portal deployed publicly on GitHub Pages: [live demo](https://gopigopi-dev.github.io/College-transport-portal-/)
- Student Attendance Tracker built for a college web development hackathon, as stated in its README. No result or award is claimed.
- Moved from web-only projects to Kotlin and Jetpack Compose apps

No releases, certifications or awards to list yet.

## Future Goals

- Work through which parts of the AGENTIC-AI Desktop design are technically realistic
- Explore AI and ML development, including Gemini in Android Studio
- Keep building practical apps and learning new technologies

<img src="./assets/divider.svg" alt="" width="100%">

## Connect With Me

<a href="https://github.com/gopigopi-dev"><img alt="GitHub: gopigopi-dev" src="https://img.shields.io/badge/GitHub-gopigopi--dev-8B5CF6?style=for-the-badge&labelColor=0D0B18"></a>
<a href="https://www.linkedin.com/in/gopi-l-346669417"><img alt="LinkedIn: Gopi L" src="https://img.shields.io/badge/LinkedIn-Gopi%20L-8B5CF6?style=for-the-badge&labelColor=0D0B18"></a>

<br>

<img src="./assets/footer.svg" alt="Building projects. Learning new technologies." width="100%">
