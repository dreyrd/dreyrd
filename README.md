<p align="center">
  <a href="https://github.com/dreyrd">
    <img src="./crash.gif" height="250" width="250" alt="Unform" />
  </a>
</p>

<div align="center">
  <img height="180px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dreyrd&layout=compact">
  <img height="180px" src="https://github-readme-stats.vercel.app/api?username=dreyrd&show_icons=true&theme=transparent">
</div>

![snake animation](https://github.com/<dreyrd>/<dreyrd>/blob/output/github-contribution-grid-snake2.svg)

uses: Platane/snk@v3
  with:
    github_user_name: ${{ github.dreyrd }}
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
