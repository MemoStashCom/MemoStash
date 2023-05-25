<p align="center">
   <a href="https://discord.gg/f5ymEKBxRG"><img src="https://img.shields.io/badge/Discord-memostash.com-informational?logo=discord&style=for-the-badge" alt="Join The MemoStash Discord Community"></a> 
   <a href="https://github.com/MemoStashCom/MemoStash/stargazers"><img src="https://img.shields.io/github/stars/memostashcom/memostash?logo=github&style=for-the-badge&color=yellow" alt="Github Stars"></a>
</p>
<p align="center">
   <a href="https://github.com/MemoStashCom/MemoStash/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPLv3-yellow?style=for-the-badge" alt="License"></a>
   <a href="https://github.com/MemoStashCom/MemoStash/pulse"><img src="https://img.shields.io/github/commit-activity/m/memostashcom/memostash?style=for-the-badge&color=green" alt="Commits-per-month"></a>
</p>
<p align="center" style="margin-top: 12px">
  <a href="https://MemoStash.com">
   <img width="250px" src="https://avatars.githubusercontent.com/u/89918857?s=400&u=fed83c21df964361ab135ac1a56198e46c897a07&v=4" alt="MemoStash Logo">
  </a>

  <h1 align="center"><tt>MemoStash</tt></h1>
  <h2 align="center">The simple Voice Memo App for thinkers and do-ers!</h2>

<p align="center">
From <b>Ideas</b> 💡 to <b>Journals</b> 📔 - <b>Personal Logs</b> 📈 to <b>Notes</b> 📝 - <b>ToDos</b> ✅ to <b>ToDonts</b> ⛔️
<br />
<br />
By Keyboard ⌨️, Voice 🎤 or telepathically 🧠 (Maybe one day)!
<br />
<br />
Alone 👀, with friends 🫂 or with the world 🌍!
</p>
<p align="center">
    <a href="https://memostash.com"><strong>To our Website & App »</strong></a>
    <br />
    <br />
    <a href="https://twitter.com/memostash">Twitter</a>
    ·
    <a href="https://discord.gg/f5ymEKBxRG">Community Discord</a>
    ·
    <a href="https://github.com/memostashcom/memostash/issues">Issues</a>
    ·
    <a href="https://github.com/memostashcom/memostash/milestones">Roadmap</a>
  </p>
</p>

----------
## :construction: Current Status

`MemoStash` is currently in Public Alpha/Beta. The Cloud/Managed version is available at [https://`MemoStash`.com](https://memostash.com).

We're under active development with no plans to stop any time soon. An update video is posted regularly to our [Youtube Channel](https://www.youtube.com/@memostash)

Self-hosting is currently not advised, see below!

----------

## 🧱 `MemoStash` framework

***`Memo`*** is your individual thought. *`Memos`* can be text, voice or voice transcribed to text - and can include auto summaries. They live in:

***`Stash`*** is a collection of *`Memos`*. A *`Memo`* can live in multiple *`Stashes`*. Each *`Stash`* can be shared with other users, or made public.

More great features are planned for the future including *`Blocks`*, *`Reminder`*, *`Recaps`*, *`Auto-Export`* & more!


## 🤔 Why

There are a lot of "notes", "todo" or "personal tracking" tools, each niching down to a specific user type or industry. It's all too complicated and you need 10 different apps to record or save all your different thoughts.

`MemoStash` is a simple tool that focuses on a single point of capture for a wide variety of thoughts. Giving you a framwork to capture, review and act on your thoughts.

We're not targeting a specific user group *(Is this one of the 7 deadly startup sins?)*, instead we're targeting a user action.

**A tool for people who think and do.**

----

>*Could you imaging if Archimedes lived today?*

>*"Finally, I solved it! **Eur-** Wait, let me record this. Which app was it, this one? No, that's for meta- philosophical stuff!.. This one, ah it has 500-character limit and no support for Greek!... let's try here, hmm which project do I want this to go under? Is it scientific discovery or mathematical equations, why do I need to add a tag!... too complicated I'll try this, is this a task or a document... ok this has to be the app, WHY DO I HAVE TO UPGRADE!!!!... Fine, I'll just run to the king and tell him... what was it again? Oh, yes - **eka! EUREKA!***


## ⚙️ Tech Stack
`MemoStash` is built with the following epic technologies & tools:

- [Nuxt JS (VueJS)](https://nuxt.com) FrontEnd & Backend + modules
- [Nitro](https://nitro.unjs.io/) Public API
- [unoCSS](https://unocss.dev/) CSS Engine (tailwind compatiable)
- [tRPC](https://trpc.io/) Typesafe APIs
- [EdgeDB](https://edgedb.com/) Database & ORM
- [Minio](https://min.io/) File Storage

For a full list of all technologies, packages and libraries used, please check within each app/package directory.

## 💾 Self Hosting

The official Self-Host version will be made available as a docker-compose file once the main app is stable enough and has upgrade utilities in place.

You can currently Self-host by building and deploying yourself, but it's completely unsupported for now. There will be breaking changes and very possible dead-ends for upgrades.

*We will cosntantly upgrade the Could version located at [https://`MemoStash`.com](https://memostash.com) and later provide a migration path from **Cloud > Self-Hosted > Cloud***
