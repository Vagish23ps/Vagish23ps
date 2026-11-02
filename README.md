<!-- Animated profile header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:050816,45:073B5C,100:00A6C7&height=165&section=header&text=VAGISH%20SHANBHAG&fontSize=43&fontColor=FFFFFF&fontAlignY=42&animation=twinkling" width="100%" alt="Animated greeting banner"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=2500&pause=850&color=22D3EE&center=true&vCenter=true&width=680&height=55&lines=Hi%2C+I%27m+Vagish+%F0%9F%91%8B;IoT+%26+Cybersecurity+Engineering+Student;Exploring+Vulnerability+Assessment+%26+Network+Security;Building+Local-First+Applications;Experimenting+with+AI+%26+Information+Verification;Learning+by+Building+and+Testing" alt="Animated areas of interest"/>
</p>

<p align="center">
  <a href="https://github.com/Vagish23ps"><img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/vagish-shanbhag-a39752341/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/Vagishps_23/"><img src="https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
</p>

---

## About Me

I'm an engineering student focused on **IoT and Cybersecurity**. I spend most of my time learning how software, networks, and connected devices work, then applying that knowledge through projects and lab experiments. My current focus is cybersecurity, networking, Linux, Python, and problem-solving.

---

## Technical Interests

| Area | What I work on and explore |
|---|---|
| **Cybersecurity & VAPT** | Reconnaissance, vulnerability assessment, web security testing, and tools such as Metasploit, Nikto, and OpenVAS in authorised labs. |
| **Network Security** | TCP/IP, routing, packet analysis, network services, traffic inspection, and common network weaknesses. |
| **IoT & Embedded Systems** | ESP32, sensors, Bluetooth/BLE, device communication, and securing connected devices. |
| **Linux & System Security** | Kali Linux, Ubuntu, shell commands, permissions, processes, services, and system configuration. |
| **AI & Information Analysis** | Semantic similarity, evidence retrieval, AI-generated text detection, and multi-signal credibility analysis. |
| **Web & API Security** | HTTP, APIs, authentication, input handling, common web vulnerabilities, and secure development practices. |

---

## Technologies & Tools

**Programming languages**

<p>
  <img src="https://skillicons.dev/icons?i=python,c,cpp,java,js,ts&theme=dark" alt="Programming languages"/>
</p>

**IoT & hardware**

`ESP32` · `Sensors` · `Bluetooth / BLE` · `Embedded Systems` · `Firebase`

**Cybersecurity & networking**

<p><img src="https://skillicons.dev/icons?i=linux,bash&theme=dark" alt="Linux and Bash"/></p>

`Kali Linux` · `Metasploit` · `Nikto` · `OpenVAS` · `Nmap` · `Wireshark` · `TCP/IP` · `VAPT`

**Development**

<p><img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,fastapi,flutter,html,css&theme=dark" alt="Development technologies"/></p>

**Databases & tools**

<p><img src="https://skillicons.dev/icons?i=mysql,mongodb,firebase,git,github,vscode&theme=dark" alt="Databases and tools"/></p>

---

## Featured Projects

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:073B5C,100:00A6C7&height=58&section=header&text=01%20%7C%20SATYA%20%E2%80%94%20Misinformation%20Detection&fontSize=21&fontColor=FFFFFF&animation=fadeIn" width="100%" alt="SATYA project banner"/>
</p>

[**Repository: satya-ai-misinformation-detector**](https://github.com/Vagish23ps/satya-ai-misinformation-detector)

SATYA analyses submitted text, news headlines, and forwarded messages to estimate the credibility of a claim. It gathers fact-check results and external evidence, compares the evidence semantically, and combines several signals into a report with a credibility score and risk category.

**Numbers and implementation**

- **40+ RSS news feeds** are listed in the project for Indian national, Karnataka regional, international, government, fact-checking, science, and technology coverage.
- **6 scoring signals** contribute to the credibility estimate:
  1. AI-generated-text probability.
  2. Existing fact-check verdicts.
  3. Semantic evidence stance (supporting, contradicting, or uncertain).
  4. Quantity of collected evidence.
  5. Suspicious or danger-keyword patterns.
  6. Implausible-claim pattern checks.
- **0–100 credibility score**, mapped to LOW RISK (90–100), MEDIUM RISK (70–89), and HIGH RISK (0–69).
- **AI detection:** Hugging Face RoBERTa model.
- **Fact-check lookup:** Google Fact Check Tools API.
- **Evidence collection:** RSS feeds, DuckDuckGo search, and Wikipedia.
- **Semantic analysis:** Sentence Transformers with `all-MiniLM-L6-v2`.
- **Backend:** Python, FastAPI, and Uvicorn.
- **Main endpoint:** `POST /api/text/analyze`; health and API documentation endpoints are also provided.
- **Report output:** credibility score, risk level, verdict, and evidence; the result can be copied or exported as PDF.

**Request flow**

`Text input → AI detection → Fact-check lookup + evidence collection → Semantic analysis → Scoring engine → Truth report`

**Current limitations:** The score is an estimate based on available signals, not proof that a claim is true or false. Fact-check coverage depends on claims already reviewed by fact-checking sources. The repository documents that image, video, and audio analysis are not included in the current version.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:073B5C,100:00A6C7&height=58&section=header&text=02%20%7C%20Lectra%20%E2%80%94%20Local-First%20Productivity%20App&fontSize=20&fontColor=FFFFFF&animation=fadeIn" width="100%" alt="Lectra project banner"/>
</p>

[**Repository: Lectra**](https://github.com/Vagish23ps/Lectra)

Lectra is a local-first productivity app for capturing notes, organising tasks, tracking deadlines, and managing reminders. It works as a web app and as an Android app packaged with Capacitor. Its data is stored on the device, allowing the core app to work offline without a mandatory account or external application server.

**Implemented features and numbers**

- **12 built-in tags**, with support for creating, renaming, and deleting custom tags.
- **20 MB maximum file size** for each photo or PDF attachment.
- **5 task urgency groups:** Overdue, Due Today, Tomorrow, Upcoming, and Other.
- **Entry-linked tasks** with optional deadlines and importance flags.
- **IndexedDB attachment storage** using binary Blobs, separate from lightweight text data.
- **Search** across entry titles, categories, notes, tags, and task descriptions.
- **Calendar month and day views** with indicators for completed, pending, and important items.
- **2 backup formats:** JSON export and full ZIP archive including binary attachments; both have restore support.
- **Recurring reminders:** daily, weekly, monthly, or selected days.
- **Notification history** with unread tracking and recorded actions.
- **Android notification actions** for completing tasks, snoozing reminders, and stopping reminders.

**Technology and architecture**

- Next.js **16.3.7**, React **19.2.4**, and TypeScript.
- Capacitor **8** for Android packaging and native plugin integration.
- Zustand **5** for application state and persistence.
- IndexedDB for attachment Blobs and localStorage for lightweight local data.
- `@capacitor/local-notifications` for native Android notifications.
- PDF.js for in-app PDF previews and JSZip for complete backup archives.

**Validation recorded in the repository**

| Check | Result recorded in project README |
|---|---|
| TypeScript | `npx tsc --noEmit` — 0 errors |
| ESLint | `npm run lint` — 0 errors |
| Production build | 16/16 static routes prerendered |
| Capacitor sync | 4 native plugins synchronised |
| Android notifications | Tested on physical Android hardware |

**Platform note:** Android battery-management settings can affect scheduled background notifications. The repository specifically notes that manufacturer-specific battery policies may throttle alarms unless the app is exempted from battery optimisation.

---

## GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Vagish23ps&show_icons=true&include_all_commits=true&hide_border=true&theme=transparent&rank_icon=github" height="170" alt="GitHub account statistics"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vagish23ps&layout=compact&hide_border=true&theme=transparent" height="170" alt="Most used repository languages"/>
</p>

<p align="center"><sub>These cards are generated by an external service and may be temporarily unavailable or rate-limited. Language percentages describe code in repositories, not overall engineering ability.</sub></p>

---

## LeetCode

I practise Data Structures and Algorithms to improve problem-solving and understand time and space complexity.

<p align="center">
  <a href="https://leetcode.com/u/Vagishps_23/">
    <img src="https://leetcard.jacoblin.cool/Vagishps_23?theme=dark&font=Fira+Code&ext=heatmap" alt="LeetCode statistics and activity heatmap"/>
  </a>
</p>

---

## Currently Learning

- Cybersecurity, VAPT, and web application security.
- Network protocols, packet analysis, and Linux system security.
- IoT security and connected-device communication.
- DSA and problem-solving through LeetCode.
- AI-based evidence retrieval and information verification.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00A6C7,55:073B5C,100:050816&height=115&section=footer&text=Thanks%20for%20visiting%20%E2%80%94%20Keep%20building%20and%20learning&fontSize=17&fontColor=FFFFFF&fontAlignY=65&animation=fadeIn" width="100%" alt="Animated footer with closing message"/>
</p>
