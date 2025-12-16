<h2>
Hi 👋, I'm Monalisa Panda
<img src="https://media.giphy.com/media/12oufCB0MyZ1Go/giphy.gif" width="45">
</h2>

<img align="right" src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif" width="230"/>

<p>
2nd Year B.Tech CSE (AI & ML) student  
Focused on DSA, Java, C++, and Machine Learning
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/monalisa-panda-76405831a)
[![GitHub Followers](https://img.shields.io/github/followers/monalisa0105?style=social)](https://github.com/monalisa0105)
![Profile Views](https://komarev.com/ghpvc/?username=monalisa0105&color=blue)
![Waka Readme](https://github.com/monalisa0105/monalisa0105/workflows/Waka%20Readme/badge.svg)

---

### 👩‍💻 About Me

```java
class Monalisa {
    String education = "B.Tech CSE (AI & ML)";
    String year = "2nd Year";
    String[] languages = {"Java", "C++", "Python", "JavaScript"};
    String focus = "DSA + Machine Learning";
    String funFact = "Late-night coding works best 🌙";
}

<img src="https://raw.githubusercontent.com/monalisa0105/monalisa0105/output/github-contribution-grid-snake-dark.svg"/>

```yml
name: Waka Readme

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - uses: athul/waka-readme@v0.3.1
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          TIME_RANGE: last_7_days
          SHOW_TIME: true
          SHOW_TOTAL: true
          LANG_COUNT: 6
          BLOCKS: ░▒▓█
