<p align="center">
  <a href="https://portfolio.davishiggins.com"><img src="assets/hero.svg" width="100%" alt="DH Portfolio: a portfolio you can ask questions. Animated cover with the DH mark beside the Davis Intelligence chat window, where a question types in and an answer streams back." /></a>
</p>

<h1 align="center">DH Portfolio</h1>

<p align="center"><strong>A conversational portfolio: ask Davis Intelligence about my experience, projects, and skills, or browse the full portfolio by section.</strong></p>

<p align="center">
  <a href="https://portfolio.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="Ask a question" /></a>&nbsp;
  <a href="https://www.higginsd.com/work/dh-portfolio"><img src="assets/btn-case.svg" height="44" alt="Case study" /></a>&nbsp;
  <a href="https://davishiggins.com"><img src="assets/btn-dh.svg" height="44" alt="davishiggins.com" /></a>
</p>

<p align="center"><sub>Live · Designed and built by Davis Higgins</sub></p>

---

## See it in motion

<p align="center">
  <img src="assets/demo.gif" width="720" alt="Screen recording of portfolio.davishiggins.com: opening Ask Davis AI, typing 'What did Davis build for Flowcast?', and reading the answer." />
</p>

<p align="center"><sub>Real capture of the live assistant answering one question. <a href="assets/demo.png">Static frame</a></sub></p>

## What it does

- **Ask instead of scroll.** Davis Intelligence answers questions about my experience, projects, skills, education, and goals in plain language, with suggested questions to get started.
- **Answers that stay on topic.** The assistant speaks to my real work and points visitors to the live projects behind it.
- **Browsing is always there.** Home, Experience, Projects, Education, Skills, Impact, Résumé, and Contact stay one click away, and each project has a full write-up with an on-page index.

## Why I built it

A portfolio answers the questions its author anticipated, and no others. A recruiter wants to know about one technology; a prospective client wants to know whether I've done similar work. Making both of them hunt through pages written for a general audience is the wrong interface.

So the portfolio answers directly, and the conventional pages stay for anyone who would rather read.

## What I built

- The single-page portfolio: section navigation, project write-ups with an on-page index, experience timeline, skills, impact, and résumé
- Davis Intelligence: the chat experience, suggested questions, typing state, and conversation memory
- The knowledge the assistant draws on, kept in step with my projects
- The secure service layer that powers the assistant

<details>
<summary><strong>How it's put together</strong></summary>

<br />

```mermaid
flowchart TB
    Q[Visitor asks a question] --> P[Chat panel keeps<br/>the conversation]
    P --> S[Secure assistant service]
    S --> A[Answer about my work<br/>with links to live projects]
    A --> P
```

| Decision | Why |
|---|---|
| **Secrets never reach the browser** | The assistant runs behind a server-side service, so nothing sensitive ships in the page. |
| **Grounded in my real work** | Answers come from knowledge I write and maintain, not open-ended guessing. |
| **Conversation-aware** | Follow-up questions keep their context, and replies are formatted to read cleanly as chat. |

</details>

## Screens

<table>
  <tr>
    <td width="62%"><img src="assets/screenshot-home.png" alt="DH Portfolio home: 'Hi, I'm Davis Higgins' with focus tags and a headshot card." /></td>
    <td rowspan="2" width="38%" align="center"><img src="assets/screenshot-mobile.png" width="300" alt="Davis Intelligence open on a phone with suggested questions." /></td>
  </tr>
  <tr>
    <td><img src="assets/screenshot-projects.png" alt="Projects section with the Cade write-up and an 'On this page' index of projects." /></td>
  </tr>
</table>

<sub>Home · Projects with on-page index · Davis Intelligence on mobile</sub>

## Technology

| Layer | Technology |
|---|---|
| App | React, Vite, Tailwind CSS |
| Motion | Framer Motion |
| Hosting | Vercel |

---

<p align="center">
  <a href="https://portfolio.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="Ask a question" /></a>&nbsp;
  <a href="https://github.com/DavisHiggins"><img src="assets/btn-more.svg" height="44" alt="More of my work" /></a>
</p>

<p align="center"><sub>© 2026 Davis Higgins. All rights reserved.</sub></p>
