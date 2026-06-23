<a id="top"></a>

# Akaash Vincent

**AI × HR Technology · People Analytics · I-O Psychology**

[LinkedIn](https://www.linkedin.com/in/akaash-vincent-548013338/) · akaashvincent@gmail.com

I build AI tools for HR and people teams, grounded in industrial-organizational psychology. I'm an HR
technology intern at an employee-owned architecture firm, and starting a part-time M.A./M.S. in I-O
Psychology in 2027. Most of my professional work is private, so a few representative projects are below.

**Jump to** · [StudyTutor](#studytutor) · [Recruiting analysis](#recruiting) · [L&D Agent](#ld-agent) · [Design pipeline](#design) · [Research](#research) · [DJ Stage Show](#dj) · [Skills](#skills)

---

<a id="studytutor"></a>

## StudyTutor: adaptive study platform · [live demo](https://mystudytutor.vercel.app)

Students practice with tools that never adapt to what they keep getting wrong. StudyTutor grades each answer,
explains the reasoning, and spaces repetition toward the gaps. I built and shipped it across organic
chemistry, ESL, and college math placement.

- One user raised an organic-chemistry grade from a C- to a 94%.
- Others used it to prep for college ESL and math placement (294 LOEP, 267 ACCUPLACER).
- Live in production. The triptych and clip below are the real app, not mockups.

**Built with** React, Vite, JavaScript, Firebase, Vercel.

<p align="center">
  <img src="assets/st-triptych.png" width="840" alt="StudyTutor on mobile: the subject picker, an organic-chemistry practice question, and a graded answer with a worked explanation and XP">
</p>
<p align="center">
  <img src="assets/studytutor-practice.gif" width="280" alt="StudyTutor live: answering a question, instant grading, a worked explanation, and XP">
</p>

<p align="center"><em>The live app: pick a subject, answer, and get graded with a worked explanation and spaced review.</em></p>

<p align="center">
  <img src="assets/st-home.jpg" width="240" alt="StudyTutor home dashboard: a daily goal of 5 problems, day-streak and total-XP counters, and Quiz, Test, and Vocab practice modes">
  <img src="assets/st-course.jpg" width="240" alt="StudyTutor course map: all 7 chapters of organic chemistry live with 363 problems, each chapter showing mastery progress">
  <img src="assets/st-testmode.jpg" width="240" alt="StudyTutor Test Mode: a timed, blueprint-aligned exam across all 20 topics, self-graded after the timer, aligned to Klein 4e">
</p>

<p align="center"><em>More of the app — a goal-driven home, a 7-chapter course map (363 problems), and timed exam prep.</em></p>

<p align="right"><sub><a href="#top">↑ back to top</a></sub></p>

---

<a id="recruiting"></a>

## Recruiting funnel analysis

A 300-candidate recruiting funnel was leaking, and the bottleneck was not obvious. I analyzed it in Excel,
Tableau, and Python, then rebuilt the findings as the dashboard below.

- The structural bottleneck: 49% of screened candidates never reached an interview.
- LinkedIn and Indeed together drove 71% of hires.
- Time-to-hire ran 2.4 times longer in Engineering than in Sales.

**Built with** Excel, Tableau, Python. Dashboard rebuilt for presentation with representative figures.

<p align="center">
  <img src="assets/dash-tableau.png" width="880" alt="Tableau dashboard: a recruiting funnel with the 49% screen-to-interview bottleneck flagged in red, hires by source (LinkedIn and Indeed at 71% combined), and median time-to-hire by department showing the 2.4x spread">
</p>

<p align="center"><em>Built in Tableau: the funnel, source mix, and time-to-hire on one canvas. The red stage marks the screen-to-interview bottleneck.</em></p>

<p align="right"><sub><a href="#top">↑ back to top</a></sub></p>

---

<a id="ld-agent"></a>

## L&D Agent: AI onboarding for specialty hiring · concept demo

Specialty architecture firms often can't hire architects with direct experience in their niche — the talent
sits one specialty over, in adjacent work. Every adjacent hire then means a senior architect building a
training program from scratch, so the hire frequently doesn't happen. The L&D Agent reads a candidate's
background, maps it to the firm's competency framework, and generates a gap analysis and a phased,
mentor-reviewed onboarding plan — so the specialty gap becomes closeable without burning senior time.

- Maps a résumé to a 10-competency framework, scores hiring readiness, and separates critical gaps from
  transferable strengths.
- Generates a phased ramp plan with review gates, senior sign-offs, and an estimated time-to-billable.
- Role-aware: an HR/talent-acquisition lens and a design-leadership lens read the same candidate differently.
- Grounded Q&A: a knowledge base of practice knowledge rides in the prompt as a cached prefix, so answers
  reflect the firm's own way of working.

**Built with** Claude API, Python, Flask, prompt caching, HTML, CSS, JavaScript.

<p align="center">
  <img src="assets/ld-gap.jpg" width="860" alt="L&D Agent gap analysis: a candidate mapped to a 10-competency framework with a 58 of 100 hiring-readiness score, three critical gaps flagged, an estimated nine-week time-to-billable, and a proceed-with-conditions recommendation">
</p>
<p align="center">
  <img src="assets/ld-plan.jpg" width="860" alt="L&D Agent training plan: a phased week-by-week onboarding ramp with deliverables, step-by-step guidance for the new hire and mentor, and senior sign-off gates">
</p>

<p align="center"><em>A concept demo built for an employee-owned architecture firm; the firm and candidate are fictional. The agent maps a candidate to a competency framework, then generates a mentor-reviewed onboarding plan.</em></p>

<p align="center">
  <img src="assets/ld-intake.jpg" width="420" alt="L&D Agent intake screen: paste a candidate background or import a résumé and portfolio, choose a competency track, and the AI maps it to the firm's competency framework">
  <img src="assets/ld-ask.jpg" width="420" alt="L&D Agent Ask-HR workspace: a knowledge-grounded chat answering questions about firm standards and the training plan, every answer citing its source">
</p>

<p align="center"><em>The full pipeline — paste a background at intake, then a knowledge-grounded Ask-HR workspace where every answer cites its source.</em></p>

<p align="right"><sub><a href="#top">↑ back to top</a></sub></p>

---

<a id="design"></a>

## Design-studio: multi-agent UI pipeline · sample: an AI HR copilot

Taking a product idea to a working, on-brand interface usually means a designer, a developer, and several
rounds of review. I built a pipeline that turns a brief into a self-contained UI, with a concept gate up
front and a screenshot-armed critic before anything ships. Concept, build, and critique run as separate
agents.

The sample below is **Aria**, an Ask-HR copilot concept the pipeline produced. Every answer cites the policy
it came from and shows how confident it is.

- A design sample from the pipeline, not a shipped product.
- Built to show how I design AI-for-HR interfaces, my main focus.

**Built with** Claude Code, multi-agent orchestration, HTML, CSS, JavaScript.

<p align="center">
  <img src="assets/aria-convo.png" width="840" alt="Aria Ask-HR copilot: an answer about PTO carryover with a 94% confidence bar, three cited policy sources, and a sources-cited side panel">
</p>
<p align="center">
  <img src="assets/aria-empty.png" width="540" alt="Aria empty state: ask anything about pay, leave, or benefits, with suggested questions">
</p>

<p align="center"><em>Sample output. Aria answers HR questions and cites the policy behind each answer.</em></p>

<p align="right"><sub><a href="#top">↑ back to top</a></sub></p>

---

<a id="research"></a>

## Dyslexia in the workplace: I-O research

A 2×2 factorial study (n=200 employed adults) on reading accommodations. Found a significant
Dyslexia-by-Condition effect on reading speed (F(1,151)=13.32, p<.001) and a workplace-competence gap
(t(153)=2.22, p=.03). Presented at the Eastern Psychological Association 2026 conference.

**Tools** Qualtrics, Excel, factorial ANOVA.

<p align="center">
  <img src="assets/dyslexia-poster.png" width="800" alt="Conference poster, Dyslexia in the Workplace (Coscia, Baka, Vincent and Budnick): a 2x2 text-to-speech by dyslexia factorial study, presented at EPA 2026">
</p>
<p align="center"><em><a href="assets/dyslexia-poster.pdf">Full poster (PDF)</a> · Eastern Psychological Association, 2026</em></p>

<p align="right"><sub><a href="#top">↑ back to top</a></sub></p>

---

<a id="dj"></a>

## DJ Stage Show: real-time performance visualizer

A live visual console I run at my DJ sets. It reads the playing track and the audio signal and renders a
dual-deck performance view — now-playing and cued decks, moving waveforms, BPM and key, and crossfade
timing — reacting to the music in real time. One self-contained HTML file, no backend, run from the booth.

- Run live at 5 paid events — weddings, parties, corporate — for crowds of 70 to 150, with repeat bookings.
- Reacts to the live audio signal (Web Audio API) and the currently-playing track from the Spotify API.
- Decks, platters, and album art render to canvas; the whole thing is a single file off a laptop.

**Built with** JavaScript, Web Audio API, Canvas, Spotify API.

<p align="center">
  <img src="assets/dj-console.jpg" width="840" alt="DJ Stage Show performance console: a now-playing deck and a cued deck with album art and spinning platters, live waveforms, BPM and musical key per deck, an 808 mix section with EQ, a crossfade control, and a track list">
</p>
<p align="center">
  <img src="assets/dj-console.gif" width="300" alt="The now-playing deck animating live: album art, a spinning record platter, a moving neon waveform, and a ticking elapsed time">
</p>

<p align="center"><em>The live console during a set — decks, moving waveforms, and crossfade timing, reacting to the track in real time.</em></p>

<p align="right"><sub><a href="#top">↑ back to top</a></sub></p>

---

<a id="skills"></a>

<details>
<summary><b>Skills &amp; tools</b> — AI application development · full-stack prototyping · people analytics · HR systems</summary>

<br>

AI application development (Claude API, Codex, structured outputs, prompt caching), full-stack prototyping
(Python, Flask, React), people analytics (Excel, Tableau, SQL, Qualtrics), and HR systems (Oracle Fusion
Cloud HCM, SAP SuccessFactors, Workday, Greenhouse, SharePoint, Copilot).

</details>

---

Some professional work, including AI HR tools built during my internship, is confidential. Happy to walk
through it on request.

<p align="right"><sub><a href="#top">↑ back to top</a></sub></p>
