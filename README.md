<p align="center">
  <img src="assets/banner.svg" alt="Joshua Hayes: software engineer at Markel, building sensors and software against campus hunger" width="100%">
</p>

<p align="center">
  <a href="https://littlerampantries.com/"><img src="https://img.shields.io/badge/Little%20Ram%20Pantries-live-ffd166?style=for-the-badge&labelColor=0b1020" alt="Little Ram Pantries, live"></a>
  <a href="https://www.linkedin.com/in/joshua-hayes-vcu/"><img src="https://img.shields.io/badge/LinkedIn-connect-7cc4ff?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b1020" alt="LinkedIn"></a>
</p>

### Hi, I'm Joshua 👋

I'm a software engineer at **Markel** by day. The rest of the time I build things that leave the screen: sensors on food pantry doors, a newspaper that prints itself onto a Kindle every morning, a monitor that tells my Arch box what is wrong with it before I find out the hard way.

I like software that has a physical consequence, runs on hardware I can hold, and still works when the network does not.

<p align="center"><img src="assets/divider.svg" alt="" width="100%"></p>

## 🔭 What I'm building

<table>
<tr>
<td width="50%" valign="top">

### 🥫 Little Ram Pantries

Free food pantries across VCU's campuses, each with a door sensor and a camera, so a student can check what is on the shelf before making the walk.

I lead the engineering: the public site (map, a page per pantry, works offline), the admin tools for restocking and outages, the device fleet, and the AWS accounts underneath.

`TypeScript` `Go` `AWS IoT Greengrass` `CloudFront`

**[littlerampantries.com →](https://littlerampantries.com/)**

</td>
<td width="50%" valign="top">

### 📰 [MNN: Muse News Network](https://github.com/JoshuaHayesWasHere/MNN)

A daily newspaper written by your AI agent and delivered to your e-reader. Each morning the Kindle wakes to a front page, and the full edition is already waiting in KOReader.

The agent is the newsroom and a Raspberry Pi is the press.

`Python` `AI agents` `Docker` `KOReader` `e-ink`

**[JoshuaHayesWasHere/MNN →](https://github.com/JoshuaHayesWasHere/MNN)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🩺 Archaholics Anonymous

`aa check`: a read-only health monitor for Arch Linux. It probes the system, ranks what it finds by severity, and hands you the exact command to fix each problem. It never changes anything itself.

`Python` `uv` `systemd` `pacman`

</td>
<td width="50%" valign="top">

### 🐉 Hydra

An orchestrator for coding agents, arranged as a tree: each orchestrator has a home of its own and hands work down to the ones beneath it. It runs on local workers first, with a second execution plane to follow.

`Python` `uv` `JSON Schema`

![status](https://img.shields.io/badge/status-first%20slice%20in%20progress-ffd166?style=flat-square&labelColor=0b1020)

</td>
</tr>
</table>

> ### 🖥️ My setup: [dotfiles](https://github.com/JoshuaHayesWasHere/dotfiles)
>
> Everything on the machine the projects above get built on: Arch and Hyprland, a zsh setup split so coding agents get a fast, plain shell while I keep the fancy one, kitty, tmux, Neovim, and my full Claude Code configuration.
>
> `Arch Linux` `Hyprland` `zsh` `tmux` `Neovim` `Claude Code`

<p align="center"><img src="assets/divider.svg" alt="" width="100%"></p>

## 🐍 A year of commits, eaten

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JoshuaHayesWasHere/JoshuaHayesWasHere/output/snake-dark.svg">
    <img src="https://raw.githubusercontent.com/JoshuaHayesWasHere/JoshuaHayesWasHere/output/snake.svg" alt="A snake eating its way across my GitHub contribution graph" width="100%">
  </picture>
</p>

## 🧰 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,python,ts,js,cs,dotnet,svelte&theme=dark" alt="Go, Python, TypeScript, JavaScript, C#, .NET, Svelte">
  <br>
  <img src="https://skillicons.dev/icons?i=aws,dynamodb,terraform,docker,githubactions,raspberrypi,arch,bash&theme=dark" alt="AWS, DynamoDB, Terraform, Docker, GitHub Actions, Raspberry Pi, Arch Linux, Bash">
</p>

## 🧭 How I work

- **Ship the whole thing.** Frontend, API, infrastructure, the device on the wall, and the release notes.
- **Read-only first.** Tools should explain and recommend before they are ever allowed to change state.
- **Local by default.** One command brings up the full stack with no cloud account.
- **Agents are teammates.** Most of my recent work is built alongside coding agents, with pipelines that check their output before it lands.

<p align="center"><img src="assets/divider.svg" alt="" width="100%"></p>

<p align="center">
  <sub>Want to talk pantries, Kindles, or Arch? <a href="https://www.linkedin.com/in/joshua-hayes-vcu/">Find me on LinkedIn.</a></sub>
</p>
