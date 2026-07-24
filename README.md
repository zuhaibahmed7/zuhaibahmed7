<!-- ⚠️ REPLACE "zuhaibahmed7" BELOW WITH YOUR ACTUAL GITHUB USERNAME EVERYWHERE ⚠️ -->

<h1 align="center">Hi 👋, I'm Zuhaib Ahmed</h1>
<h3 align="center">A passionate AI Engineer</h3>

- 🔭 **I'm currently working on:** AI
- 🌱 **I'm currently learning:** AI
- ⚡ **Fun fact:** I Love Tech and Tech Loves Me

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zuhaibahmed7/zuhaibahmed7/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/zuhaibahmed7/zuhaibahmed7/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/zuhaibahmed7/zuhaibahmed7/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

> **Note:** The snake animation only appears after the workflow below runs at least once on your repo.

<details>
<summary>⚙️ Snake animation setup (click to expand)</summary>

1. In your `zuhaibahmed7/zuhaibahmed7` profile repo, create the file `.github/workflows/snake.yml` with the following content:

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"   # runs every 12 hours
  push:
    branches:
      - main
  workflow_dispatch: {}       # lets you trigger it manually from the Actions tab

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake animation SVG
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push snake output to the "output" branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

2. Commit it, then go to the **Actions** tab of your repo and manually run "Generate Snake Animation" once (or wait for the next scheduled run / push to `main`).
3. This creates an `output` branch containing the generated SVGs, which the snake image above already points to.

</details>

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-trophies.vercel.app/?username=zuhaibahmed7&theme=radical&no-frame=false&no-bg=true&margin-w=4" />
</p>

---

## 📊 GitHub Profile Summary

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=zuhaibahmed7&theme=dark&hide_border=false&include_all_commits=true&count_private=false" alt="zuhaibahmed7's GitHub stats" />
</p>

<p align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=zuhaibahmed7&theme=dark&hide_border=false" alt="zuhaibahmed7's streak stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zuhaibahmed7&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact" alt="Top languages by repo" />
</p>

---

## 🌐 Socials

<p align="left">
<a href="https://facebook.com/zuhaibahmed347" target="_blank"><img src="https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white" /></a>
<a href="https://instagram.com/yaa.itszuhaibahmed" target="_blank"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/zuhaib-ahmed-69951a39a/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" /></a>
<a href="https://reddit.com/user/zuhaibahmed7" target="_blank"><img src="https://img.shields.io/badge/Reddit-%23FF4500.svg?logo=Reddit&logoColor=white" /></a>
<a href="https://x.com/ZohaibAhmedMah2" target="_blank"><img src="https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white" /></a>
<a href="mailto:zuhaibahmedlodromahar@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" /></a>
</p>

---

## 💻 Tech Stack

<p align="left">
<img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
<img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
<img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white" />
<img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
<img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" />
<img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" />
</p>

---

### ✍️ Random Dev Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" />
</p>

---

<p align="center">
  <a href="https://visitcount.itsvg.in"><img src="https://visitcount.itsvg.in/api?id=zuhaibahmed7&icon=0&color=0" /></a>
</p>

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
