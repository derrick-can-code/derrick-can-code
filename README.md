# I am Derrick Mensah
Full-stack engineer in progress — learning to build things that matter, one commit at a time.

---

### About

Software engineering student passionate about building across the full stack — from pixel-perfect interfaces to robust server-side logic. Currently deep in the **Full Stack Open** curriculum and growing fast. I'm a polyglot by nature: I pick up whatever language the problem demands. Particularly excited about how AI can be leveraged to solve real-world problems.

---

### Tech stack

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML%20%26%20CSS-E34F26?style=flat&logo=html5&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

### Currently focused on

- 📖 Full Stack Open — React, Node.js, REST APIs, testing
- 🤖 Exploring AI integrations and building tools with LLMs
- 🔧 Strengthening my backend fundamentals (databases, auth, deployment)

---

### Snake game

> Because every great developer needs a README game.

<!-- Snake game powered by GitHub Actions — add the workflow below to animate it -->

![snake gif](https://github.com/derrick-can-code/derrick-can-code/blob/output/github-contribution-grid-snake.gif)

<details>
<summary>How to enable the snake animation</summary>

1. Create `.github/workflows/snake.yml` in your profile repo with this content:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: derrick-can-code
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

2. Push and run the workflow once manually from the Actions tab.
3. The snake gif will appear on your README automatically.

</details>

---

### GitHub stats

![derrick-can-code's GitHub stats](https://github-readme-stats.vercel.app/api?username=derrick-can-code&show_icons=true&theme=default&hide_border=true&count_private=true)

---

<p align="center">still building · still learning · always shipping</p>
