<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,100:00C9FF&height=220&section=header&text=DMONINK&fontSize=72&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20Dev%20%7C%20Discord%20Bots%20%7C%20AI-Powered%20Tools&descAlignY=55&descSize=18" width="100%"/>

<a href="https://github.com/DMONINK">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=C792EA&center=true&vCenter=true&width=650&lines=Hey%2C+Micky+here+%F0%9F%91%8B;Full-Stack+%2B+Discord+Bot+Developer;Building+AI-Powered+Tools+%E2%9A%99%EF%B8%8F;Node.js+%E2%80%A2+Python+%E2%80%A2+Flask+%E2%80%A2+Android" alt="Typing SVG" />
</a>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=DMONINK&color=8a2be2&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/DMONINK?label=FOLLOWERS&style=for-the-badge&color=00c9ff&logo=github)
![Location](https://img.shields.io/badge/📍-Delhi%2C%20India-7F00FF?style=for-the-badge)

</div>

---

### 🚀 About Me

- 🛠️ I build **full-stack web apps**, **Discord bots**, and **AI-powered tools** end-to-end — frontend to deployment.
- 🏰 Currently deep in a large-scale **automated civilization simulation** — six fantasy clans, procedural map generation, and a live Flask/Socket.IO dashboard.
- 🤖 Designer of **Spark**, a Discord bot for social matchmaking, and **cocdot**, a command-driven Discord bot.
- 📦 Building **AutoDrop AI**, an Android dropshipping app for the Indian e-commerce market powered by Gemini AI flows.
- 🎮 Outside of code: anime/manga, Valorant lore, cyberpunk-anime music production, and speculative worldbuilding.
- ⚡ Fun fact: I'd rather simulate a civilization than balance my own spreadsheet — which is exactly why I built an expense tracker instead.

---

### 🛠️ Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=js,nodejs,python,flask,discordjs,react,html,css,kotlin,android,androidstudio,git,github,replit,heroku,vscode&theme=dark" />
</div>

---

### 🎯 What I'm Building

<table width="100%">
<tr>
<td width="50%" valign="top">

**🏰 Civilization Simulation Engine**
Multi-thousand-line text-based sim — 6 fantasy clans, procedural maps, live Flask + Socket.IO dashboard, Discord webhook events.
`Python` `Flask` `Socket.IO` `Discord API`

</td>
<td width="50%" valign="top">

**🤖 Spark**
Discord bot for social matchmaking — pairs members up based on shared interests.
`Node.js` `Discord.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**💰 Personal Expense Tracker**
Full-stack web app for logging income/expenses and visualizing spending trends.
`JavaScript` `Node.js` `Full-Stack`

</td>
<td width="50%" valign="top">

**📦 AutoDrop AI**
Android dropshipping app concept for the Indian market, built around Gemini AI flows.
`Android` `Kotlin` `Gemini AI`

</td>
</tr>
</table>

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=DMONINK&repo=Live-Simulation&theme=tokyonight&hide_border=true&cache_seconds=21600" />
</div>

---

### 📊 GitHub Stats

<table width="100%">
<tr>
<td width="50%"><img src="https://github-readme-stats.vercel.app/api?username=DMONINK&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" /></td>
<td width="50%"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DMONINK&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" /></td>
</tr>
</table>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=DMONINK&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
<img src="https://github-trophies.vercel.app/?username=DMONINK&theme=tokyonight&no-frame=true&row=1&column=6&margin-w=10" />
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=DMONINK&theme=tokyo-night&hide_border=true" width="100%"/>
</div>

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/wakatime?username=DMONINK&theme=tokyonight&hide_border=true&layout=compact" />
</div>

> ⚙️ **WakaTime card needs setup:** the `username` here must be your **WakaTime** username, not GitHub. Create a free account at [wakatime.com](https://wakatime.com), install the plugin for your editor (VS Code, Android Studio, etc.), and turn on both **"Display code time publicly"** and **"Display languages, editors, os, categories publicly"** in your WakaTime profile settings. Data can take up to 24h to appear after signup. Swap `DMONINK` in the URL above for your real WakaTime username once set up.

---

### 🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/DMONINK/DMONINK/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

<details>
<summary>⚙️ Setup instructions (one-time, ~2 min)</summary>

<br/>

The snake above won't render until you add this GitHub Action to **this repo** (the special `DMONINK/DMONINK` repo). Create `.github/workflows/snake.yml`:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches: [ main ]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake SVGs
        uses: Platane/snk@v3
        with:
          github_user_name: DMONINK
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Push it, run the workflow once manually (Actions tab → Generate Snake → Run workflow), and the snake will animate your contribution graph going forward.

> If you already tried the older version of this workflow, delete the `output` branch first (Branches page → trash icon next to `output`) so the next run starts clean, then re-run.

</details>

---

### 🌌 3D Contribution Calendar

<div align="center">
<img src="https://raw.githubusercontent.com/DMONINK/DMONINK/main/profile-3d-contrib/profile-night-rainbow.svg" width="100%"/>
</div>

<details>
<summary>⚙️ Setup instructions (one-time, ~2 min)</summary>

<br/>

Create `.github/workflows/profile-3d.yml` in **this repo**:

```yaml
name: GitHub-Profile-3D-Contrib
on:
  schedule:
    - cron: "0 18 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-3d-contrib
    steps:
      - uses: actions/checkout@v5
      - uses: yoshi389111/github-profile-3d-contrib@latest
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ${{ github.repository_owner }}
      - name: Commit & Push
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -A .
          if git commit -m "generated"; then git push; fi
```

Commit it, then run it once manually (Actions tab → GitHub-Profile-3D-Contrib → Run workflow). It writes several SVG themes into a `profile-3d-contrib/` folder on `main` — the one embedded above is `profile-night-rainbow.svg`; other variants (`profile-south.svg`, `profile-north.svg`, etc.) appear there too if you want to swap the look.

> Want private contributions included too? Go to your GitHub profile → Settings → Public profile → Contributions & Activity → check "Include private contributions on my profile."

</details>

---

### 🎧 Now Playing

<div align="center">
<img src="https://spotify-github-profile.kittinanx.com/api/view?uid=31mybvdvoctptlky35rkgkphj63i&cover_image=true&theme=spotify-embed&show_offline=false&background_color=121212&interchange=false&profanity=false&hide_remaster=false&mode=dark&bar_color=53b14f&bar_color_cover=false" />
</div>

<details>
<summary>⚙️ Setup instructions (one-time, ~1 min — no Vercel deploy needed)</summary>

<br/>

1. Click this to connect your Spotify account: [Connect with Spotify](https://spotify-github-profile.kittinanx.com/api/login)
2. After authorizing, you'll be given a `uid` — copy it
3. Replace `YOUR_SPOTIFY_UID` in the image URL above with that value

Themes available: `default`, `compact`, `natemoo-re`, `novatorem` (used above), `karaoke`, `spotify-embed`. Card auto-updates to show your currently playing track, or your last played if you're offline (add `&show_offline=true` to keep showing last track instead of going blank).

</details>

---

### 💬 Random Quote & Dev Joke

<div align="center">
<a href='https://github.com/DMONINK'>
<!--START_SECTION:quote-->
<!--END_SECTION:quote-->
</a>
</div>

<div align="center">
<img src="https://readme-jokes.vercel.app/api?theme=tokyonight&hideBorder" alt="Jokes Card" />
</div>

<details>
<summary>⚙️ Setup instructions for the quote (one-time, ~2 min) — the jokes card above needs no setup</summary>

<br/>

The jokes card is a live hosted image, already working as-is. The quote section needs one small GitHub Action since it writes text directly into this README. Create `.github/workflows/quote.yml` in **this repo**:

```yaml
name: Update Quote Readme
on:
  workflow_dispatch:
  schedule:
    - cron: "0 2 * * *"

jobs:
  update-readme:
    name: Update Quote README
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: siddharth2016/quote-readme@main
        with:
          OPTION: "both"
```

Commit it, then run it once manually (Actions tab → Update Quote Readme → Run workflow). It'll replace the text between the `<!--START_SECTION:quote-->` and `<!--END_SECTION:quote-->` comments above with a random quote or dev fun-fact, refreshing daily.

</details>

---

### 🌐 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-DMONINK-181717?style=for-the-badge&logo=github)](https://github.com/DMONINK)
[![Discord](https://img.shields.io/badge/Discord-Add%20Tag-5865F2?style=for-the-badge&logo=discord&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-Add%20Address-D14836?style=for-the-badge&logo=gmail&logoColor=white)](#)

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,100:7F00FF&height=120&section=footer" width="100%"/>
</div>
