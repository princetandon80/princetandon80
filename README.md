# Hi there 👋

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Astronaut.png" alt="Astronaut" width="25" height="25" />
 👋, I'm Prince Tandon

🎓 BCA Student | 💻 Developer | 🚀 Learning by Building

I'm a BCA student who enjoys coding, building projects, and learning new technologies.

### 👨‍💻 About Me

- 🎓 BCA Student
- 💻 Learning **Web Development & Software Development**
- 🐍 Python | C | JavaScript | SQL
- 🌐 HTML | CSS | React | FastAPI
- 🧠 Practicing **DSA**
- 🤖 Exploring **Machine Learning**
- 🚀 Building projects and improving my skills

### 🔗 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Prince%20Tandon-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/prince-tandon-193ba437b)

[![GitHub](https://img.shields.io/badge/GitHub-My%20GitHub-black?style=for-the-badge&logo=github)](https://github.com/YOUR_USERNAME)

---


## 🐍 My Contributions
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10

    permissions:
      contents: write

    steps:
      - name: Generate contribution snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: princetandon80
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

      - name: Publish snake
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          build_dir: dist
          target_branch: output
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

⭐ Learning • Building • Improving

## 👋 Hey!

![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Aspiring+Full+Stack+Developer;Machine+Learning+Enthusiast;JavaScript+Developer;Building+Projects+and+Learning)
