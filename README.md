<picture>
  <source media="(prefers-color-scheme: light)" srcset="./header-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./header-dark.svg">
  <img src="./header-dark.svg" width="100%" alt="header"/>
</picture>
<br/>

<p align="center">
  <a href="https://sugumaran-portfolio.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-sugumaran--portfolio.vercel.app-5C6BC0?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>&nbsp;&nbsp;
  <a href="https://linkedin.com/in/sugumaran-nix">
    <img src="https://img.shields.io/badge/LinkedIn-sugumaran--nix-5C6BC0?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>&nbsp;&nbsp;
  <a href="mailto:sugumarankugan@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-sugumarankugan%40gmail.com-5C6BC0?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>&nbsp;&nbsp;
  <img src="https://komarev.com/ghpvc/?username=sugumaran-nix&style=for-the-badge&color=5C6BC0&label=VIEWS"/>
</p>

<br/>

MCA graduate (2026) from Anna University, Coimbatore. I build full-stack AI apps — from model to frontend.

---

### Projects

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#141414;border:1px solid #5C6BC0;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#E8B84B;margin-bottom:8px;">
        <h3>Fake Job Posting Detection using ML</h3>
      </div>
      <div style="font-size:14px;color:#C9C2B4;line-height:1.5;margin-bottom:10px;">Job seekers waste time applying to fraudulent listings. This classifier catches them first — benchmarked 4 ML models on 17,880 real-world postings, 87.57% Fraud F1-score on a heavily imbalanced dataset, SHAP-style explainability, runtime model switching. Sub-800ms end-to-end.</div>
      <div style="margin-bottom:10px;">
        <img src="https://img.shields.io/badge/-sugumaran--nix%2Ffake--job--posting--ml-%235C6BC0?style=flat-square&logo=github&logoColor=white"/>
      </div>
      <div>
        <img src="https://img.shields.io/badge/Python-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=python"/>
        <img src="https://img.shields.io/badge/Scikit--learn-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=scikitlearn"/>
        <img src="https://img.shields.io/badge/Flask-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=flask"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#191919;border:1px solid #5C6BC0;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img style="border-radius:4px;box-shadow:0 0 0 1px rgba(92,107,192,0.4);display:block;filter:brightness(0.92) saturate(0.9);" src="https://opengraph.githubassets.com/1/sugumaran-nix/fake-job-posting-ml" width="100%"/>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#141414;border:1px solid #5C6BC0;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#E8B84B;margin-bottom:8px;">
        <h3>AI Generated Content Detector</h3>
      </div>
      <div style="font-size:14px;color:#C9C2B4;line-height:1.5;margin-bottom:10px;">Statistical classifier that distinguishes human-written from AI-generated text using perplexity, burstiness, and sentence-level variance. Highlights exact spans flagged as machine-generated with per-sentence confidence scores. Served via FastAPI.</div>
      <div style="margin-bottom:10px;">
        <img src="https://img.shields.io/badge/-sugumaran--nix%2Fai--content--detector-%235C6BC0?style=flat-square&logo=github&logoColor=white"/>
      </div>
      <div>
        <img src="https://img.shields.io/badge/Python-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=python"/>
        <img src="https://img.shields.io/badge/FastAPI-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=fastapi"/>
        <img src="https://img.shields.io/badge/React-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=react"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#191919;border:1px solid #5C6BC0;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img style="border-radius:4px;box-shadow:0 0 0 1px rgba(92,107,192,0.4);display:block;filter:brightness(0.92) saturate(0.9);" src="https://opengraph.githubassets.com/1/sugumaran-nix/ai-content-detector" width="100%"/>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#141414;border:1px solid #5C6BC0;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#E8B84B;margin-bottom:8px;">
        <h3>Sketchline — Real-Time Collaborative Whiteboard</h3>
      </div>
      <div style="font-size:14px;color:#C9C2B4;line-height:1.5;margin-bottom:10px;">Collaborative tools break when multiple people draw at once. Sketchline handles it — FastAPI WebSocket backend manages room state, stroke history, and multi-client broadcast via a 7-message-type JSON protocol. Sub-100ms stroke sync, board-state replay on reconnect, live cursor presence at 20 fps. No drawing library.</div>
      <div style="margin-bottom:10px;">
        <img src="https://img.shields.io/badge/-sugumaran--nix%2FSketchline--whiteboard-%235C6BC0?style=flat-square&logo=github&logoColor=white"/>
      </div>
      <div>
        <img src="https://img.shields.io/badge/Next.js-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=nextdotjs"/>
        <img src="https://img.shields.io/badge/FastAPI-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=fastapi"/>
        <img src="https://img.shields.io/badge/WebSockets-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=socketdotio"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#191919;border:1px solid #5C6BC0;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img style="border-radius:4px;box-shadow:0 0 0 1px rgba(92,107,192,0.4);display:block;filter:brightness(0.92) saturate(0.9);" src="https://opengraph.githubassets.com/1/sugumaran-nix/Sketchline-whiteboard" width="100%"/>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#141414;border:1px solid #5C6BC0;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#E8B84B;margin-bottom:8px;">
        <h3>ProjectScope — Eisenhower Matrix Task Manager</h3>
      </div>
      <div style="font-size:14px;color:#C9C2B4;line-height:1.5;margin-bottom:10px;">Most task apps dump everything in one list. ProjectScope forces prioritisation — drag-and-drop quadrant layout built in React.js + TypeScript with dnd-kit, keyboard-accessible interactions, cross-tab localStorage sync.</div>
      <div style="margin-bottom:10px;">
        <img src="https://img.shields.io/badge/-sugumaran--nix%2FProjectScope-%235C6BC0?style=flat-square&logo=github&logoColor=white"/>
      </div>
      <div>
        <img src="https://img.shields.io/badge/React.js-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=react"/>
        <img src="https://img.shields.io/badge/TypeScript-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=typescript"/>
        <img src="https://img.shields.io/badge/Tailwind%20CSS-%23ffffff?style=flat-square&labelColor=191919&color=191919&logoColor=ffffff&logo=tailwindcss"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#191919;border:1px solid #5C6BC0;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img style="border-radius:4px;box-shadow:0 0 0 1px rgba(92,107,192,0.4);display:block;filter:brightness(0.92) saturate(0.9);" src="https://opengraph.githubassets.com/1/sugumaran-nix/ProjectScope" width="100%"/>
    </td>
  </tr>
</table>

---

### Tech Stack

**Languages**

![Python](https://img.shields.io/badge/-Python-%235C6BC0?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-%235C6BC0?style=flat&logo=javascript&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-%235C6BC0?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-%235C6BC0?style=flat&logo=mysql&logoColor=white)
![C](https://img.shields.io/badge/-C-%235C6BC0?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-C++-%235C6BC0?style=flat&logo=cplusplus&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/-React-%234FA89C?style=flat&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-%234FA89C?style=flat&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-%234FA89C?style=flat&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-%234FA89C?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-%234FA89C?style=flat&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-%234FA89C?style=flat&logo=bootstrap&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/-FastAPI-%23E08A5B?style=flat&logo=fastapi&logoColor=black)
![Flask](https://img.shields.io/badge/-Flask-%23E08A5B?style=flat&logo=flask&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-%23E08A5B?style=flat&logo=nodedotjs&logoColor=black)
![WebSockets](https://img.shields.io/badge/-WebSockets-%23E08A5B?style=flat&logo=socketdotio&logoColor=black)

**AI · ML · NLP**

![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-%23D98BA0?style=flat&logo=scikitlearn&logoColor=black)
![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-%23D98BA0?style=flat&logo=huggingface&logoColor=black)
![NLTK](https://img.shields.io/badge/-NLTK-%23D98BA0?style=flat&logo=python&logoColor=black)
![TF-IDF](https://img.shields.io/badge/-TF--IDF-%23D98BA0?style=flat&logo=python&logoColor=black)
![BERT](https://img.shields.io/badge/-BERT-%23D98BA0?style=flat&logo=huggingface&logoColor=black)

**Databases**

![MySQL](https://img.shields.io/badge/-MySQL-%23C9695C?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-%23C9695C?style=flat&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-%23C9695C?style=flat&logo=sqlite&logoColor=white)

**Tools & DevOps**

![Git](https://img.shields.io/badge/-Git-%23E8B84B?style=flat&logo=git&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-%23E8B84B?style=flat&logo=githubactions&logoColor=black)
![Docker](https://img.shields.io/badge/-Docker-%23E8B84B?style=flat&logo=docker&logoColor=black)
![Linux](https://img.shields.io/badge/-Linux-%23E8B84B?style=flat&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/-Vercel-%23E8B84B?style=flat&logo=vercel&logoColor=black)
![Railway](https://img.shields.io/badge/-Railway-%23E8B84B?style=flat&logo=railway&logoColor=black)
![VS Code](https://img.shields.io/badge/-VS%20Code-%23E8B84B?style=flat&logo=visualstudiocode&logoColor=black)

---

### Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=sugumaran-nix&hide_border=true&background=F7F2E7&ring=8A6A1D&fire=A85A2E&currStreakLabel=8A6A1D&sideLabels=3E4A96&dates=6b6b6b&currStreakNum=8A6A1D&sideNums=333333&stroke=F7F2E7">
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=sugumaran-nix&hide_border=true&background=000000&ring=E8B84B&fire=C9695C&currStreakLabel=E8B84B&sideLabels=8a9bc9&dates=6b7280&currStreakNum=E8B84B&sideNums=C9C2B4&stroke=000000">
  <img src="https://streak-stats.demolab.com?user=sugumaran-nix&hide_border=true&background=000000&ring=E8B84B&fire=C9695C&currStreakLabel=E8B84B&sideLabels=8a9bc9&dates=6b7280&currStreakNum=E8B84B&sideNums=C9C2B4&stroke=000000" alt="Streak">
</picture>

</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=sugumaran-nix&bg_color=F7F2E7&color=8A6A1D&line=2F6F66&point=8A6A1D&area=true&area_color=cbd5f0&hide_border=true&radius=6">
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=sugumaran-nix&bg_color=000000&color=E8B84B&line=4FA89C&point=E8B84B&area=true&area_color=1c2438&hide_border=true&radius=6">
    <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=sugumaran-nix&bg_color=000000&color=E8B84B&line=4FA89C&point=E8B84B&area=true&area_color=1c2438&hide_border=true&radius=6" alt="activity graph"/>
  </picture>
</div>

<br/>

### Contribution Graph

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sugumaran-nix/sugumaran-nix/output/pacman-contribution-graph-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sugumaran-nix/sugumaran-nix/output/pacman-contribution-graph.svg">
    <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/sugumaran-nix/sugumaran-nix/output/pacman-contribution-graph.svg">
  </picture>
</div>

<br/>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="./footer-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./footer-dark.svg">
  <img src="./footer-dark.svg" width="100%" alt="footer"/>
</picture>
