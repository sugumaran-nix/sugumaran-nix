<picture>
  <source media="(prefers-color-scheme: light)" srcset="./header-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./header-dark.svg">
  <img src="./header-dark.svg" width="100%" alt="header"/>
</picture>

<p align="center">
  <a href="https://sugumaran-portfolio.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-sugumaran--portfolio.vercel.app-4CAF50?style=for-the-badge&logo=vercel&logoColor=F8F4E3&labelColor=1F2937"/>
  </a>&nbsp;&nbsp;
  <a href="https://linkedin.com/in/sugumaran-nix">
    <img src="https://img.shields.io/badge/LinkedIn-sugumaran--nix-4CAF50?style=for-the-badge&logo=linkedin&logoColor=F8F4E3&labelColor=1F2937"/>
  </a>&nbsp;&nbsp;
  <a href="mailto:sugumarankugan@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-sugumarankugan%40gmail.com-F59E0B?style=for-the-badge&logo=gmail&logoColor=F8F4E3&labelColor=1F2937"/>
  </a>&nbsp;&nbsp;
  <img src="https://komarev.com/ghpvc/?username=sugumaran-nix&style=for-the-badge&color=4CAF50&label=VIEWS&abbreviated=true"/>
</p>

<br/>

MCA graduate (2026) from Anna University, Coimbatore. I build full-stack AI apps — from model to frontend.

---

### Projects

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#F5F5F5;margin-bottom:8px;">
        <h3>Fake Job Posting Detection using ML</h3>
      </div>
      <div style="font-size:14px;color:#7D8590;line-height:1.5;margin-bottom:12px;">Job seekers waste time applying to fraudulent listings. This classifier catches them first — benchmarked 4 ML models on 17,880 real-world postings, 87.57% Fraud F1-score on a heavily imbalanced dataset, SHAP-style explainability, runtime model switching. Sub-800ms end-to-end.</div>
      <div style="margin-bottom:12px;">
        <a href="#">
          <img src="https://img.shields.io/badge/%E2%97%8F%20live-view%20project-B22222?style=for-the-badge&logoColor=F5F5F5&labelColor=B22222&color=0D1117"/>
        </a>
      </div>
      <div>
        <img src="https://img.shields.io/badge/Python-F5F5F5?style=flat-square&logo=python&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Scikit--learn-F5F5F5?style=flat-square&logo=scikitlearn&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Flask-F5F5F5?style=flat-square&logo=flask&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#0D1117;border:1px solid #B22222;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img src="https://opengraph.githubassets.com/1/sugumaran-nix/fake-job-posting-ml" width="100%" style="border-radius:4px;display:block;filter:brightness(0.92) saturate(0.9);"/>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#F5F5F5;margin-bottom:8px;">
        <h3>AI Generated Content Detector</h3>
      </div>
      <div style="font-size:14px;color:#7D8590;line-height:1.5;margin-bottom:12px;">Statistical classifier that distinguishes human-written from AI-generated text using perplexity, burstiness, and sentence-level variance. Highlights exact spans flagged as machine-generated with per-sentence confidence scores. Served via FastAPI.</div>
      <div style="margin-bottom:12px;">
        <a href="#">
          <img src="https://img.shields.io/badge/%E2%97%8F%20live-view%20project-B22222?style=for-the-badge&logoColor=F5F5F5&labelColor=B22222&color=0D1117"/>
        </a>
      </div>
      <div>
        <img src="https://img.shields.io/badge/Python-F5F5F5?style=flat-square&logo=python&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/FastAPI-F5F5F5?style=flat-square&logo=fastapi&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/React-F5F5F5?style=flat-square&logo=react&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#0D1117;border:1px solid #B22222;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img src="https://opengraph.githubassets.com/1/sugumaran-nix/ai-content-detector" width="100%" style="border-radius:4px;display:block;filter:brightness(0.92) saturate(0.9);"/>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#F5F5F5;margin-bottom:8px;">
        <h3>Sketchline — Real-Time Collaborative Whiteboard</h3>
      </div>
      <div style="font-size:14px;color:#7D8590;line-height:1.5;margin-bottom:12px;">Collaborative tools break when multiple people draw at once. Sketchline handles it — FastAPI WebSocket backend manages room state, stroke history, and multi-client broadcast via a 7-message-type JSON protocol. Sub-100ms stroke sync, board-state replay on reconnect, live cursor presence at 20 fps. No drawing library.</div>
      <div style="margin-bottom:12px;">
        <a href="#">
          <img src="https://img.shields.io/badge/%E2%97%8F%20live-view%20project-B22222?style=for-the-badge&logoColor=F5F5F5&labelColor=B22222&color=0D1117"/>
        </a>
      </div>
      <div>
        <img src="https://img.shields.io/badge/Next.js-F5F5F5?style=flat-square&logo=nextdotjs&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/FastAPI-F5F5F5?style=flat-square&logo=fastapi&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/WebSockets-F5F5F5?style=flat-square&logo=socketdotio&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#0D1117;border:1px solid #B22222;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img src="https://opengraph.githubassets.com/1/sugumaran-nix/Sketchline-whiteboard" width="100%" style="border-radius:4px;display:block;filter:brightness(0.92) saturate(0.9);"/>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td width="65%" valign="top" style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-right:none;border-radius:6px 0 0 6px;">
      <div style="font-size:16px;font-weight:700;color:#F5F5F5;margin-bottom:8px;">
        <h3>ProjectScope — Eisenhower Matrix Task Manager</h3>
      </div>
      <div style="font-size:14px;color:#7D8590;line-height:1.5;margin-bottom:12px;">Most task apps dump everything in one list. ProjectScope forces prioritisation — drag-and-drop quadrant layout built in React.js + TypeScript with dnd-kit, keyboard-accessible interactions, cross-tab localStorage sync.</div>
      <div style="margin-bottom:12px;">
        <a href="#">
          <img src="https://img.shields.io/badge/%E2%97%8F%20live-view%20project-B22222?style=for-the-badge&logoColor=F5F5F5&labelColor=B22222&color=0D1117"/>
        </a>
      </div>
      <div>
        <img src="https://img.shields.io/badge/React.js-F5F5F5?style=flat-square&logo=react&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/TypeScript-F5F5F5?style=flat-square&logo=typescript&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Tailwind%20CSS-F5F5F5?style=flat-square&logo=tailwindcss&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
    <td width="35%" valign="middle" style="background:#0D1117;border:1px solid #B22222;border-left:none;border-radius:0 6px 6px 0;overflow:hidden;padding:6px;">
      <img src="https://opengraph.githubassets.com/1/sugumaran-nix/ProjectScope" width="100%" style="border-radius:4px;display:block;filter:brightness(0.92) saturate(0.9);"/>
    </td>
  </tr>
</table>

---

### Tech Stack

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#B22222;margin-bottom:10px;">Languages</div>
      <div>
        <img src="https://img.shields.io/badge/Python-F5F5F5?style=flat-square&logo=python&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/JavaScript-F5F5F5?style=flat-square&logo=javascript&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/TypeScript-F5F5F5?style=flat-square&logo=typescript&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/SQL-F5F5F5?style=flat-square&logo=mysql&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/C-F5F5F5?style=flat-square&logo=c&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/C++-F5F5F5?style=flat-square&logo=cplusplus&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#B22222;margin-bottom:10px;">Frontend</div>
      <div>
        <img src="https://img.shields.io/badge/React-F5F5F5?style=flat-square&logo=react&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Next.js-F5F5F5?style=flat-square&logo=nextdotjs&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Tailwind%20CSS-F5F5F5?style=flat-square&logo=tailwindcss&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/HTML5-F5F5F5?style=flat-square&logo=html5&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/CSS3-F5F5F5?style=flat-square&logo=css3&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Bootstrap-F5F5F5?style=flat-square&logo=bootstrap&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#B22222;margin-bottom:10px;">Backend &amp; APIs</div>
      <div>
        <img src="https://img.shields.io/badge/FastAPI-F5F5F5?style=flat-square&logo=fastapi&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Flask-F5F5F5?style=flat-square&logo=flask&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Node.js-F5F5F5?style=flat-square&logo=nodedotjs&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/WebSockets-F5F5F5?style=flat-square&logo=socketdotio&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#B22222;margin-bottom:10px;">AI · ML · NLP</div>
      <div>
        <img src="https://img.shields.io/badge/Scikit--learn-F5F5F5?style=flat-square&logo=scikitlearn&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Hugging%20Face-F5F5F5?style=flat-square&logo=huggingface&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/NLTK-F5F5F5?style=flat-square&logo=python&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/TF--IDF-F5F5F5?style=flat-square&logo=python&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/BERT-F5F5F5?style=flat-square&logo=huggingface&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#B22222;margin-bottom:10px;">Databases</div>
      <div>
        <img src="https://img.shields.io/badge/MySQL-F5F5F5?style=flat-square&logo=mysql&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/MongoDB-F5F5F5?style=flat-square&logo=mongodb&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/SQLite-F5F5F5?style=flat-square&logo=sqlite&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
  </tr>
</table>

<br/>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="padding:16px 20px;background:#0D1117;border:1px solid #B22222;border-radius:6px;">
      <div style="font-size:15px;font-weight:700;color:#B22222;margin-bottom:10px;">Tools &amp; DevOps</div>
      <div>
        <img src="https://img.shields.io/badge/Git-F5F5F5?style=flat-square&logo=git&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/GitHub%20Actions-F5F5F5?style=flat-square&logo=githubactions&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Docker-F5F5F5?style=flat-square&logo=docker&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Linux-F5F5F5?style=flat-square&logo=linux&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Vercel-F5F5F5?style=flat-square&logo=vercel&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/Railway-F5F5F5?style=flat-square&logo=railway&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
        <img src="https://img.shields.io/badge/VS%20Code-F5F5F5?style=flat-square&logo=visualstudiocode&logoColor=0D1117&labelColor=7D8590&color=7D8590"/>
      </div>
    </td>
  </tr>
</table>

---

### By the Numbers

<div align="center">

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=sugumaran-nix&hide_border=true&background=00000000&ring=4CAF50&fire=F59E0B&currStreakLabel=4CAF50&sideLabels=1F2937&dates=1F2937&currStreakNum=4CAF50&sideNums=1F2937&stroke=00000000">
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=sugumaran-nix&hide_border=true&background=00000000&ring=B22222&fire=F5F5F5&currStreakLabel=B22222&sideLabels=7D8590&dates=7D8590&currStreakNum=B22222&sideNums=F5F5F5&stroke=00000000">
  <img src="https://streak-stats.demolab.com?user=sugumaran-nix&hide_border=true&background=00000000&ring=B22222&fire=F5F5F5&currStreakLabel=B22222&sideLabels=7D8590&dates=7D8590&currStreakNum=B22222&sideNums=F5F5F5&stroke=00000000" alt="Streak"/>
</picture>

</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=sugumaran-nix&bg_color=00000000&color=1F2937&line=4CAF50&point=F59E0B&area=true&area_color=4CAF5033&hide_border=true&radius=6">
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=sugumaran-nix&bg_color=00000000&color=7D8590&line=B22222&point=F5F5F5&area=true&area_color=B2222233&hide_border=true&radius=6">
    <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=sugumaran-nix&bg_color=00000000&color=7D8590&line=B22222&point=F5F5F5&area=true&area_color=B2222233&hide_border=true&radius=6" alt="activity graph"/>
  </picture>
</div>

---

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
