<picture>
  <source media="(prefers-color-scheme: light)" srcset="./header-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./header-dark.svg">
  <img src="./header-dark.svg" width="100%" alt="header"/>
</picture>

<p align="center">
  <a href="https://sugumaran-portfolio.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-sugumaran--portfolio.vercel.app-4F7DFF?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>&nbsp;&nbsp;
  <a href="https://linkedin.com/in/sugumaran-nix">
    <img src="https://img.shields.io/badge/LinkedIn-sugumaran--nix-4F7DFF?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>&nbsp;&nbsp;
  <a href="mailto:sugumarankugan@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-sugumarankugan%40gmail.com-4F7DFF?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>&nbsp;&nbsp;
  <img src="https://komarev.com/ghpvc/?username=sugumaran-nix&style=for-the-badge&color=4F7DFF&label=VIEWS"/>
</p>

<br/>

MCA graduate (2026) from Anna University, Coimbatore. I build full-stack AI apps — from model to frontend.

---

### Projects

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#F4C542;margin-bottom:8px;">
        <h3>Fake Job Posting Detection using ML</h3>
      </div>
      <div style="font-size:14px;color:#B5B5B5;line-height:1.5;margin-bottom:10px;">Job seekers waste time applying to fraudulent listings. This classifier catches them first — benchmarked 4 ML models on 17,880 real-world postings, 87.57% Fraud F1-score on a heavily imbalanced dataset, SHAP-style explainability, runtime model switching. Sub-800ms end-to-end.</div>
      <div style="margin-bottom:10px;">
        <img src="https://img.shields.io/badge/-sugumaran--nix%2Ffake--job--posting--ml-%234F7DFF?style=flat-square&logo=github&logoColor=white"/>
      </div>
      <div>
        <img src="https://img.shields.io/badge/Python-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=python"/>
        <img src="https://img.shields.io/badge/Scikit--learn-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=scikitlearn"/>
        <img src="https://img.shields.io/badge/Flask-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=flask"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#1a1a1a;border:1px solid #4F7DFF;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img src="https://opengraph.githubassets.com/1/sugumaran-nix/fake-job-posting-ml" width="100%" style="border-radius:4px;box-shadow:0 0 0 1px rgba(79,125,255,0.4);display:block;filter:brightness(0.92) saturate(0.9);"/>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#F4C542;margin-bottom:8px;">
        <h3>AI Generated Content Detector</h3>
      </div>
      <div style="font-size:14px;color:#B5B5B5;line-height:1.5;margin-bottom:10px;">Statistical classifier that distinguishes human-written from AI-generated text using perplexity, burstiness, and sentence-level variance. Highlights exact spans flagged as machine-generated with per-sentence confidence scores. Served via FastAPI.</div>
      <div style="margin-bottom:10px;">
        <img src="https://img.shields.io/badge/-sugumaran--nix%2Fai--content--detector-%234F7DFF?style=flat-square&logo=github&logoColor=white"/>
      </div>
      <div>
        <img src="https://img.shields.io/badge/Python-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=python"/>
        <img src="https://img.shields.io/badge/FastAPI-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=fastapi"/>
        <img src="https://img.shields.io/badge/React-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=react"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#1a1a1a;border:1px solid #4F7DFF;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img src="https://opengraph.githubassets.com/1/sugumaran-nix/ai-content-detector" width="100%" style="border-radius:4px;box-shadow:0 0 0 1px rgba(79,125,255,0.4);display:block;filter:brightness(0.92) saturate(0.9);"/>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#F4C542;margin-bottom:8px;">
        <h3>Sketchline — Real-Time Collaborative Whiteboard</h3>
      </div>
      <div style="font-size:14px;color:#B5B5B5;line-height:1.5;margin-bottom:10px;">Collaborative tools break when multiple people draw at once. Sketchline handles it — FastAPI WebSocket backend manages room state, stroke history, and multi-client broadcast via a 7-message-type JSON protocol. Sub-100ms stroke sync, board-state replay on reconnect, live cursor presence at 20 fps. No drawing library.</div>
      <div style="margin-bottom:10px;">
        <img src="https://img.shields.io/badge/-sugumaran--nix%2FSketchline--whiteboard-%234F7DFF?style=flat-square&logo=github&logoColor=white"/>
      </div>
      <div>
        <img src="https://img.shields.io/badge/Next.js-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=nextdotjs"/>
        <img src="https://img.shields.io/badge/FastAPI-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=fastapi"/>
        <img src="https://img.shields.io/badge/WebSockets-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=socketdotio"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#1a1a1a;border:1px solid #4F7DFF;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img src="https://opengraph.githubassets.com/1/sugumaran-nix/Sketchline-whiteboard" width="100%" style="border-radius:4px;box-shadow:0 0 0 1px rgba(79,125,255,0.4);display:block;filter:brightness(0.92) saturate(0.9);"/>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#F4C542;margin-bottom:8px;">
        <h3>ProjectScope — Eisenhower Matrix Task Manager</h3>
      </div>
      <div style="font-size:14px;color:#B5B5B5;line-height:1.5;margin-bottom:10px;">Most task apps dump everything in one list. ProjectScope forces prioritisation — drag-and-drop quadrant layout built in React.js + TypeScript with dnd-kit, keyboard-accessible interactions, cross-tab localStorage sync.</div>
      <div style="margin-bottom:10px;">
        <img src="https://img.shields.io/badge/-sugumaran--nix%2FProjectScope-%234F7DFF?style=flat-square&logo=github&logoColor=white"/>
      </div>
      <div>
        <img src="https://img.shields.io/badge/React.js-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=react"/>
        <img src="https://img.shields.io/badge/TypeScript-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=typescript"/>
        <img src="https://img.shields.io/badge/Tailwind%20CSS-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=tailwindcss"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#1a1a1a;border:1px solid #4F7DFF;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img src="https://opengraph.githubassets.com/1/sugumaran-nix/ProjectScope" width="100%" style="border-radius:4px;box-shadow:0 0 0 1px rgba(79,125,255,0.4);display:block;filter:brightness(0.92) saturate(0.9);"/>
    </td>
  </tr>
</table>

---

### Tech Stack

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#F4C542;margin-bottom:10px;">Languages</div>
      <div>
        <img src="https://img.shields.io/badge/-Python-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=python"/>
        <img src="https://img.shields.io/badge/-JavaScript-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=javascript"/>
        <img src="https://img.shields.io/badge/-TypeScript-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=typescript"/>
        <img src="https://img.shields.io/badge/-SQL-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=mysql"/>
        <img src="https://img.shields.io/badge/-C-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=c"/>
        <img src="https://img.shields.io/badge/-C++-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=cplusplus"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#F4C542;margin-bottom:10px;">Frontend</div>
      <div>
        <img src="https://img.shields.io/badge/-React-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=react"/>
        <img src="https://img.shields.io/badge/-Next.js-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=nextdotjs"/>
        <img src="https://img.shields.io/badge/-Tailwind%20CSS-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=tailwindcss"/>
        <img src="https://img.shields.io/badge/-HTML5-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=html5"/>
        <img src="https://img.shields.io/badge/-CSS3-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=css3"/>
        <img src="https://img.shields.io/badge/-Bootstrap-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=bootstrap"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#F4C542;margin-bottom:10px;">Backend & APIs</div>
      <div>
        <img src="https://img.shields.io/badge/-FastAPI-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=fastapi"/>
        <img src="https://img.shields.io/badge/-Flask-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=flask"/>
        <img src="https://img.shields.io/badge/-Node.js-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=nodedotjs"/>
        <img src="https://img.shields.io/badge/-WebSockets-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=socketdotio"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#F4C542;margin-bottom:10px;">AI · ML · NLP</div>
      <div>
        <img src="https://img.shields.io/badge/-Scikit--learn-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=scikitlearn"/>
        <img src="https://img.shields.io/badge/-Hugging%20Face-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=huggingface"/>
        <img src="https://img.shields.io/badge/-NLTK-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=python"/>
        <img src="https://img.shields.io/badge/-TF--IDF-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=python"/>
        <img src="https://img.shields.io/badge/-BERT-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=huggingface"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#F4C542;margin-bottom:10px;">Databases</div>
      <div>
        <img src="https://img.shields.io/badge/-MySQL-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=mysql"/>
        <img src="https://img.shields.io/badge/-MongoDB-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=mongodb"/>
        <img src="https://img.shields.io/badge/-SQLite-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=sqlite"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#121212;border:1px solid #4F7DFF;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#F4C542;margin-bottom:10px;">Tools & DevOps</div>
      <div>
        <img src="https://img.shields.io/badge/-Git-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=git"/>
        <img src="https://img.shields.io/badge/-GitHub%20Actions-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=githubactions"/>
        <img src="https://img.shields.io/badge/-Docker-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=docker"/>
        <img src="https://img.shields.io/badge/-Linux-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=linux"/>
        <img src="https://img.shields.io/badge/-Vercel-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=vercel"/>
        <img src="https://img.shields.io/badge/-Railway-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=railway"/>
        <img src="https://img.shields.io/badge/-VS%20Code-%23ffffff?style=flat-square&labelColor=1a1a1a&color=1a1a1a&logoColor=ffffff&logo=visualstudiocode"/>
      </div>
    </td>
  </tr>
</table>

---

### Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=sugumaran-nix&hide_border=true&background=FFFDF7&ring=3B6EF5&fire=F29E38&currStreakLabel=3B6EF5&sideLabels=6b6b6b&dates=8a8a8a&currStreakNum=3B6EF5&sideNums=2a2a2a&stroke=FFFDF7">
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=sugumaran-nix&hide_border=true&background=121212&ring=F4C542&fire=E88C3A&currStreakLabel=F4C542&sideLabels=4F7DFF&dates=6b7280&currStreakNum=F4C542&sideNums=ffffff&stroke=121212">
  <img src="https://streak-stats.demolab.com?user=sugumaran-nix&hide_border=true&background=121212&ring=F4C542&fire=E88C3A&currStreakLabel=F4C542&sideLabels=4F7DFF&dates=6b7280&currStreakNum=F4C542&sideNums=ffffff&stroke=121212" alt="Streak">
</picture>

</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=sugumaran-nix&bg_color=FFFDF7&color=3B6EF5&line=F29E38&point=3B6EF5&area=true&area_color=dbe6ff&hide_border=true&radius=6">
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=sugumaran-nix&bg_color=121212&color=F4C542&line=4F7DFF&point=F4C542&area=true&area_color=16213d&hide_border=true&radius=6">
    <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=sugumaran-nix&bg_color=121212&color=F4C542&line=4F7DFF&point=F4C542&area=true&area_color=16213d&hide_border=true&radius=6" alt="activity graph"/>
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
