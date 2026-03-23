<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&section=header&text=Roshan%20Sah&fontSize=40&fontColor=ffffff" />
</p>
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: RoshanSah123
          outputs: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

# Hi, I'm Roshan Sah 👋

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Aspiring+Developer;Python+%7C+JavaScript+%7C+Web+Dev;Cybersecurity+Enthusiast;Always+Learning+New+Things&center=true&width=500&height=45">
</p>

---

## 🚀 About Me

* 🌱 Learning: Python, JavaScript, HTML, Git & GitHub
* 🔐 Interested in Cybersecurity
* 🎮 Exploring Game Development
* 🌐 Focused on Web Development

---

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>

---

## 🚀 Projects

### 📄 Resume Portfolio Website

* Personal portfolio to showcase my skills
* Built using HTML, CSS, JavaScript

---

## 🌐 Connect with Me

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram\&logoColor=white)](https://instagram.com/roshan.sah3514)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail\&logoColor=white)](mailto:roshansah624@gmail.com)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=RoshanSah123&show_icons=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=RoshanSah123&theme=tokyonight" />
</p>

---

## 📈 Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=RoshanSah123&theme=tokyo-night" />
</p>

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=RoshanSah123&theme=radical&margin-w=10" />
</p>

---

## 🎯 Goals

* Become a skilled developer
* Build real-world projects
* Learn cybersecurity fundamentals

---

⭐️ Thanks for visiting my profile!

## 🐍 Contribution Snake
<p align="center">
  <img src="https://raw.githubusercontent.com/RoshanSah123/RoshanSah123/output/github-contribution-grid-snake.svg" />
</p>
