<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24c6dc&height=230&section=header&text=Dan%20Garden&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Software%20Engineer%20%C2%B7%20Rust%20%C2%B7%20TypeScript%20%C2%B7%20Applied%20AI&descSize=20&descAlignY=60&animation=fadeIn" width="100%" alt="Dan Garden: Full-Stack Software Engineer" />

<a href="https://github.com/FusionVault">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=24C6DC&center=true&vCenter=true&width=720&lines=10%2B+years+shipping+products+from+idea+to+production;Rust+engines+%C2%B7+React+frontends+%C2%B7+AI+pipelines;Turning+messy+data+into+live+maps+and+answers;Building+FusionVault%2C+an+open-source+data+platform;Self-taught+and+endlessly+curious" alt="Typing intro" />
</a>

<br />

<img src="https://img.shields.io/badge/Gold%20Coast-Australia-0ea5e9?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Gold Coast, Australia" />
<img src="https://img.shields.io/badge/Open%20to-opportunities-22c55e?style=for-the-badge" alt="Open to opportunities" />
<a href="https://fusionvault.net"><img src="https://img.shields.io/badge/fusionvault.net-visit-7c3aed?style=for-the-badge&logo=rust&logoColor=white" alt="fusionvault.net" /></a>
<a href="mailto:dangarden@gmail.com"><img src="https://img.shields.io/badge/Email-dangarden%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email me" /></a>

</div>

## 👋 About me

I'm a **self-taught full-stack software engineer** with **10+ years** of turning ideas into products people
actually use: pixel-perfect websites, SaaS platforms, cloud pipelines that chew through hundreds of
gigabytes of documents, and Rust engines that stream live data onto a 3D globe.

In plain English: **I take messy, real-world data and turn it into fast, secure, good-looking software.**

- 🦀 Building **[FusionVault](https://github.com/FusionVault)**, an open-source data platform in Rust and TypeScript
- 🤖 Studying a **Diploma of Artificial Intelligence**, and shipping AI features (RAG, OCR, local LLMs) for real
- 🧱 Off the keyboard: Lego builder, traveller, gardener and forever-learner
- 💬 Ask me about stream processing, geospatial maths, or why your RAG might not need a vector database

## 🏆 Highlights

- 📦 Built a serverless cloud pipeline that processes **200 GB+ document datasets** to find leaked personal data after breaches
- 🚢 Designed **zero-downtime CI/CD** from scratch for a high-traffic, highly regulated national platform
- ⚡ Created monorepos and local testing tools that **sped up delivery for whole teams**
- 🧠 Shipped an **AI document platform** (OCR + RAG + entity extraction) and a **QR-code ordering SaaS** for restaurants
- 🏅 Led a move to modern headless web architecture, with the work **recognised at an industry conference**
- 🦀 Published **8 open-source Rust crates** and made **1,800+ commits** to FusionVault in 2026

## 🚀 FusionVault

> **The short version:** pull data from many systems (aircraft, sensors, documents, spreadsheets) into one
> live, searchable *digital twin* of the world, explore it on maps and a 3D globe, and make sure every
> person sees only what they're allowed to see.

Under the hood it's Rust on Apache DataFusion, Kafka, Iceberg and OpenSearch, fine-grained access
control with OpenFGA, machine-learning enrichment, and a React console with MapLibre, deck.gl and Cesium.
These pieces are open source:

| | Project | What it does |
|:-:|---|---|
| 🌊 | **[Streams](https://github.com/FusionVault/streams)** <br /> [![crates.io](https://img.shields.io/crates/v/fv-streams?style=flat-square&color=orange&label=crates.io)](https://crates.io/crates/fv-streams) | A stream-processing engine. Describe a pipeline in one TOML or SQL file and it handles windows, joins, checkpoints and exactly-once output. Runs the full Nexmark benchmark suite. |
| 🌍 | **[geo3d](https://github.com/FusionVault/geo3d)** <br /> [![crates.io](https://img.shields.io/crates/v/geo3d?style=flat-square&color=orange&label=crates.io)](https://crates.io/crates/geo3d) | 3D geodesy with zero dependencies: Earth-centred frames, look angles, line of sight, closest approach. |
| ⏱️ | **[geo4d](https://github.com/FusionVault/geo4d)** <br /> [![crates.io](https://img.shields.io/crates/v/geo4d?style=flat-square&color=orange&label=crates.io)](https://crates.io/crates/geo4d) | Adds time: nanosecond atomic clocks, trajectories, *"will these two aircraft get too close in the next 10 minutes?"*, even tectonic-plate drift. |
| 🌌 | **[geo5d](https://github.com/FusionVault/geo5d)** <br /> [![crates.io](https://img.shields.io/crates/v/geo5d?style=flat-square&color=orange&label=crates.io)](https://crates.io/crates/geo5d) | Adds gravity and relativity. Tested against the Tokyo Skytree optical-clock experiment, because clocks really do tick faster upstairs. |
| 🔎 | **[datafusion-opensearch](https://github.com/FusionVault/datafusion-opensearch)** <br /> [![crates.io](https://img.shields.io/crates/v/datafusion-opensearch?style=flat-square&color=orange&label=crates.io)](https://crates.io/crates/datafusion-opensearch) | Query OpenSearch or Elasticsearch with plain SQL, pushing filters and limits down to the cluster. |
| 📉 | **[downsampling](https://crates.io/crates/downsampling)** <br /> [![crates.io](https://img.shields.io/crates/v/downsampling?style=flat-square&color=orange&label=crates.io)](https://crates.io/crates/downsampling) | Shrinks millions of points into a chart line or map track that still looks right. |

## 🧪 Side quests

- 📚 **[pageindex](https://github.com/dan-garden/rust-pageindex)**: RAG without a vector database. An AI agent reads a document's table of contents the way a person would, then cites the pages. Indexes a 758-page textbook in about 1 second, 16× faster than the original.
- 🛰️ **Satellite radar tomography** *(coming soon)*: rebuilding a published radar-imaging method from scratch in Rust, every equation pinned by tests, to independently check it against open satellite data.
- 🍽️ **DineQuick**: QR-code ordering and menu management for restaurants and franchises.
- 🎮 Just for fun: a **[fish tank game](https://dan-garden.github.io/tank-of-fish/)**, **[Tetris](https://dan-garden.github.io/tetris/)** on the raw Canvas API, and **[2dcraft](https://github.com/dan-garden/2dcraft)**, a 2D take on Minecraft.
- 🏠 Home-lab tinkerer: my NAS runs my own APIs and webhooks, and my house speakers announce alerts.

## 🧰 Tech I reach for

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,ts,py,js,react,nextjs,vite,tailwind,threejs&theme=dark" alt="Languages and frontend" /><br />
  <img src="https://skillicons.dev/icons?i=nodejs,bun,graphql,postgres,redis,kafka,elasticsearch,wasm&theme=dark" alt="Backend and data" /><br />
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,gcp,aws,cloudflare,linux,githubactions,figma&theme=dark" alt="Cloud and DevOps" />
</p>

<p align="center">
  <b>Also:</b> Apache DataFusion · OpenFGA · RAG · OCR · NER · ONNX · vector search · Ollama · MapLibre · deck.gl · Cesium
</p>

## 📈 Activity

<div align="center">

<img src="https://streak-stats.demolab.com/?user=dan-garden&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dan-garden/dan-garden/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dan-garden/dan-garden/output/github-snake.svg" />
  <img alt="A snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/dan-garden/dan-garden/output/github-snake.svg" />
</picture>

</div>

<div align="center">

### 🤝 Let's build something great

Hiring, collaborating, or just curious about FusionVault? **[Drop me a line](mailto:dangarden@gmail.com)**.

<img src="https://komarev.com/ghpvc/?username=dan-garden&style=flat-square&color=24c6dc&label=profile+views" alt="Profile views" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24c6dc,50:302b63,100:0f0c29&height=120&section=footer" width="100%" alt="" />

</div>
