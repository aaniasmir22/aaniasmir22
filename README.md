<div align="center">

<img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/banner.svg" width="100%" alt="Aania Sayida Mir // Cyber Angel"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=00E5FF&center=true&vCenter=true&width=760&lines=Greetings.+Allow+me+to+introduce+myself.;I+am+Jarvis.+(Aania+built+me.);rule+30+%7C+photoacoustics+%7C+cultural+archives;serve+%2F+protect+%2F+silent+%E2%9C%A6;tech+for+good.+ethics+first.+always." alt="typing"/>

![visitors](https://komarev.com/ghpvc/?username=aaniasmir22&color=ff2bd6&style=for-the-badge&label=VISITORS)
![stars](https://img.shields.io/github/stars/aaniasmir22?style=for-the-badge&color=00e5ff&labelColor=05030f)

<img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/divider.svg" width="100%"/>

<img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/dossier.svg" width="92%" alt="subject file"/>

<img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/divider.svg" width="100%"/>

<img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/overview.svg" width="92%" alt="system overview"/>

</div>

<br/>

<div align="center">

### ✦ OPEN A WINDOW ✦

<a href="#-rule-137 and 193"><img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/win-research.svg" width="32%"/></a>
<a href="https://safardarwatan.omeka.net/"><img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/win-heritage.svg" width="32%"/></a>
<a href="#-jarvis-display--voice-controlled-cyberdeck"><img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/win-jarvis.svg" width="32%"/></a>

</div>

<img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/divider.svg" width="100%"/>

## 🧬 Rule 137 and 193 
I researched **periodicity in the vertical centre columns of cellular automata** in the **Wolfram High School Summer Research Program**. This is Rule 30 growing from one cell:

```text
····················█····················
···················███···················
··················██··█··················
·················██·████·················
················██··█···█················
···············██·████·███···············
··············██··█····█··█··············
·············██·████··██████·············
············██··█···███·····█············
···········██·████·██··█···███···········
··········██··█····█·████·██··█··········
·········██·████··██·█····█·████·········
········██··█···███··██··██·█···█········
·······██·████·██··███·███··██·███·······
······██··█····█·███···█··███··█··█······
·····██·████··██·█··█·█████··███████·····
```

<details>
<summary><b>▸ decrypt: what I actually found interesting</b></summary>
<br/>

- Rule 30's centre column passes randomness tests, yet comes from a **one-line deterministic rule**.
- My project asked whether hidden periodic structure shows up in the centre columns across rules.
- This project led to my selection in the **Wolfram Emerging Leaders Program**. Currently working on a computational essay on the **physics and modelling of photoacoustic imaging**, in Wolfram Language.

```wolfram
ArrayPlot[CellularAutomaton[30, {{1}, 0}, 100]]
```

</details>

<img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/divider.svg" width="100%"/>

## 🤖 Jarvis Display : voice-controlled cyberdeck

<details>
<summary><b>▸ boot jarvis.exe</b></summary>
<br/>

```mermaid
flowchart LR
    A[🎙️ Voice] --> B[🐍 Python<br/>SpeechRecognition]
    B --> C[🔌 Serial / USB]
    C --> D[⚡ Arduino Uno]
    D -->|pulls pad to GND| E[🔘 Display pad]
    E --> F[🖥️ Video plays]
    B --> G[🗣️ pyttsx3 reply]
```

- Reverse-engineered a video-brochure PCB (board `V607D-V01`) and mapped its button pads
- Arduino fakes presses with the open-drain trick (`INPUT` ↔ `OUTPUT LOW`), so a 5V board never harms a 3.3V one
- Stack: Arduino C++ · Python · pyserial · SpeechRecognition · pyttsx3

</details>

## 🏔️ Safar Dar Watan, Datascope & more

<details>
<summary><b>▸ open heritage.exe : Safar Dar Watan</b></summary>
<br/>

- Founded a **multimedia digital archive** (Omeka.net) and a **podcast** of Kashmiri voices
- Reached 50K+ people across 10+ countries

[🌐 Archive](https://safardarwatan.omeka.net/) · [🎙️ Podcast](https://open.spotify.com/show/7mAIw2bOGrkhVEfROZoXq4) · [▶️ YouTube](https://youtube.com/@safardarwatan22)

</details>

<details>
<summary><b>▸ open datascope.exe : privacy for under-18s</b></summary>
<br/>

- Founded an initiative on how websites collect and use data, with a focus on young users
- Surveyed **118 people** on privacy awareness and tracking concerns

</details>

<details>
<summary><b>▸ open games.exe : simulations & arcade</b></summary>
<br/>

- 👾 **Space Invader**: arcade game with levels and a high score
- 🧫 **Conway's Game of Life**: zero-player simulation
- 🐚 **Fibonacci Visualiser**: turtle-graphics spirals
- 🌿 **Green Wings**: eco-business concept (1st place, Business Battlefield)

</details>

<img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/divider.svg" width="100%"/>

## 💾 Top 8 (yes, like Spacehey)

| 1 | 2 | 3 | 4 |
|:-:|:-:|:-:|:-:|
| 🐍 **Python** | ⚡ **Arduino** | 🔶 **Wolfram Language** | 🌐 **HTML/CSS** |
| 🐳 **Docker** | 🌿 **Git** | 📊 **C++** | 🗃️ **Omeka** |

<div align="center">

### 📊 SYSTEM STATS

<img height="180" src="https://github-readme-stats.vercel.app/api?username=aaniasmir22&show_icons=true&hide_border=true&bg_color=05030f&title_color=ff2bd6&icon_color=00e5ff&text_color=e8f6ff&ring_color=7a3cff&rank_icon=github"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aaniasmir22&layout=compact&hide_border=true&bg_color=05030f&title_color=ff2bd6&text_color=e8f6ff"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=aaniasmir22&background=05030F&ring=FF2BD6&fire=00E5FF&currStreakLabel=FF2BD6&sideLabels=00E5FF&currStreakNum=E8F6FF&sideNums=E8F6FF&dates=C9A0FF&stroke=7A3CFF&hide_border=true"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=aaniasmir22&bg_color=05030f&color=00e5ff&line=ff2bd6&point=ffffff&area=true&area_color=7a3cff&hide_border=true" width="95%"/>



<img src="https://raw.githubusercontent.com/aaniasmir22/aaniasmir22/main/assets/divider.svg" width="100%"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-ff2bd6?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aania-sayidamir-50460134a)
[![Podcast](https://img.shields.io/badge/PODCAST-7a3cff?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/show/7mAIw2bOGrkhVEfROZoXq4)
[![YouTube](https://img.shields.io/badge/YOUTUBE-00e5ff?style=for-the-badge&logo=youtube&logoColor=black)](https://youtube.com/@safardarwatan22)
[![Guestbook](https://img.shields.io/badge/SIGN_MY_GUESTBOOK-b6ff5c?style=for-the-badge&logoColor=black)](https://github.com/aaniasmir22/aaniasmir22/issues/new?title=%E2%9C%A6%20Guestbook%20signature&body=name%3A%20%0Aleft%20from%3A%20%0Amessage%3A%20)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff2bd6,50:7a3cff,100:00e5ff&height=110&section=footer" width="100%"/>

*✦ SYSTEM ANGEL // ONLINE ✦*

</div>
