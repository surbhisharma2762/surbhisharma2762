<h1 align="center">Hi 👋, I'm Surbhi Sharma</h1>
<h3 align="center">🚀 Passionate Full Stack Developer</h3>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&duration=3000&color=36BCF7&center=true&vCenter=true&width=600&lines=Full+Stack+Developer;Next.js+%7C+Node.js+%7C+TypeScript;Building+Scalable+Web+Applications;Always+Learning+New+Things" />
</p>

---

# 👨‍💻 About Me

- 💻 Full Stack Developer  
- 🌱 Currently learning **Backend, Microservices & Cloud**  
- ⚡ Love building **clean APIs & smooth UI**  
- 💬 Ask me about **React, Next.js, Node.js, TypeScript**  
- 📫 Reach me at **your@email.com**  
- 🧠 Fun fact: *Every bug is a hidden feature 🐛*

---

# 🛠️ Tech Stack

### 🚀 Languages & Frameworks

<p>
<img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,nodejs,tailwind" />
</p>

### 🗄️ Backend & Database

<p>
<img src="https://skillicons.dev/icons?i=express,mongodb,postgres,mysql,redis" />
</p>

### ⚙️ Tools & DevOps

<p>
<img src="https://skillicons.dev/icons?i=git,github,vscode,aws,docker" />
</p>

---

# 🔥 GitHub Stats

<p align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=surbhisharma2762&show_icons=true&theme=tokyonight"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=surbhisharma2762&layout=compact&theme=tokyonight"/>

</p>

---

# 🔥 GitHub Streak

<p align="center">
<img src="https://streak-stats.demolab.com?user=surbhisharma2762&theme=tokyonight"/>
</p>

---

# 📊 Contribution Graph

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=surbhisharma2762&theme=tokyo-night"/>
</p>

---

# 🐍 Contribution Snake

Add this animation:
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"

  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v2

      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_USERNAME
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v2
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
