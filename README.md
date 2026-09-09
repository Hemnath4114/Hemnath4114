<div align="center">

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:050505,50:0A0F14,100:111827&text=HEMNATH%20M&fontColor=FFFFFF&fontSize=52&fontAlignY=40&desc=AI%20ENGINEERING%20%2F%2F%20VOICE%20%2F%2F%20LLM%20SYSTEMS&descAlignY=62&descSize=16&animation=fadeIn"/>

<br/>

### `01 // IDENTITY`

```text
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║   H E M N A T H   M                                                   ║
║                                                                      ║
║   AI ENGINEER                                                        ║
║   REAL-TIME SYSTEMS                                                  ║
║   VOICE + LLM INFRASTRUCTURE                                        ║
║                                                                      ║
║   building machines that listen → reason → act → speak              ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2800&pause=900&color=00E5FF&center=true&vCenter=true&width=850&lines=Engineering+real-time+AI+systems.;Designing+voice+agents+that+feel+instant.;LLMs+%2B+streaming+%2B+tools+%2B+speech.;Obsessed+with+latency%2C+architecture%2C+and+systems.;Turning+complex+pipelines+into+simple+experiences."/>

<br/>

<a href="https://github.com/Hemnath4114">
<img src="https://img.shields.io/badge/GITHUB-050505?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/hemnath-marimuthu-in/">
<img src="https://img.shields.io/badge/LINKEDIN-050505?style=for-the-badge&logo=linkedin&logoColor=00E5FF"/>
</a>
<a href="mailto:hemnath041104@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-050505?style=for-the-badge&logo=gmail&logoColor=EA4335"/>
</a>

<br/><br/>

</div>

---

<div align="center">

# `SYSTEM // ONLINE`

```text
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│  DOMAIN        AI ENGINEERING                                      │
│  CORE          VOICE AI + LLM SYSTEMS                              │
│  FOCUS         REAL-TIME / STREAMING / ORCHESTRATION               │
│  PRIORITY      LATENCY                                             │
│  STATUS        BUILDING                                            │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

</div>

---

# `02 // WHO AM I`

I'm **Hemnath M**.

I started from full-stack engineering.

Then I became more interested in something deeper:

> **What actually happens between a human saying something and an intelligent machine responding?**

That question pulled me into **AI engineering**.

Now I work around systems involving:

`Speech → Language → Reasoning → Tools → State → Streaming → Speech`

My interest is not just in using an AI model.

It is in engineering the **system around the model**.

---

# `03 // CORE DOMAIN`

<div align="center">

|       `01`      |     `02`     |      `03`      |       `04`       |
| :-------------: | :----------: | :------------: | :--------------: |
|        🧠       |      🎙️     |        ⚡       |        🏗️       |
| **LLM SYSTEMS** | **VOICE AI** |   **LATENCY**  | **ARCHITECTURE** |
|  orchestration  |   ASR / TTS  | critical paths |   async systems  |
|   tool calling  |      VAD     |   TTFT / TTFA  |     streaming    |
|     context     |  turn-taking |    queueing    |       state      |
|      memory     |   barge-in   |   parallelism  |    reliability   |

</div>

---

# `04 // THE SYSTEMS I BUILD`

```text
                         HUMAN
                           │
                           ▼
                  ┌─────────────────┐
                  │   AUDIO INPUT   │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │   VAD / ASR     │
                  │ perception layer│
                  └────────┬────────┘
                           │
                           ▼
              ┌───────────────────────────┐
              │     ORCHESTRATION CORE   │
              │                           │
              │  state • routing • policy │
              └─────────────┬─────────────┘
                            │
                 ┌──────────┼───────────┐
                 │          │           │
                 ▼          ▼           ▼
             ┌───────┐  ┌───────┐  ┌────────┐
             │  LLM  │  │ TOOLS │  │ MEMORY │
             └───┬───┘  └───┬───┘  └───┬────┘
                 │          │           │
                 └──────────┼───────────┘
                            ▼
                  ┌─────────────────┐
                  │ STREAMING OUTPUT│
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │      TTS        │
                  │ audio generation│
                  └────────┬────────┘
                           │
                           ▼
                         HUMAN
```

The architecture is the product.

The model is one component inside it.

---

# `05 // LOLA`

<div align="center">

## `LOLA // REAL-TIME CONVERSATIONAL AI`

</div>

One of the areas I'm most interested in is **real-time voice interaction**.

A voice agent is not:

```text
audio → LLM → audio
```

A serious implementation is closer to:

```text
 ┌───────────┐
 │   USER    │
 └─────┬─────┘
       │
       ▼
 ┌──────────────┐
 │ VAD / AUDIO  │
 └──────┬───────┘
        │
        ▼
 ┌──────────────┐
 │     ASR      │
 └──────┬───────┘
        │
        ▼
 ┌──────────────────────────┐
 │   CONVERSATION ENGINE    │
 │                          │
 │ state / context / policy │
 └───────┬─────────┬────────┘
         │         │
         │         └─────────────┐
         ▼                       ▼
      ┌───────┐              ┌────────┐
      │  LLM  │◄────────────►│  TOOL  │
      └───┬───┘              └────────┘
          │
          ▼
 ┌────────────────┐
 │ STREAMING TEXT │
 └───────┬────────┘
         │
         ▼
 ┌────────────────┐
 │ STREAMING TTS  │
 └───────┬────────┘
         │
         ▼
    🔊 USER AUDIO
```

### The interesting part?

**The milliseconds between those boxes.**

---

# `06 // LATENCY IS A FEATURE`

```text
USER
 │
 │  speech
 ▼
┌────────────┐
│ endpointing│
└─────┬──────┘
      │
      ▼
┌────────────┐
│    ASR     │
└─────┬──────┘
      │
      ▼
┌────────────┐
│    LLM     │───────┐
└─────┬──────┘       │
      │              │
      │         ┌────▼────┐
      │         │  TOOL   │
      │         └────┬────┘
      │              │
      └──────────────┘
             │
             ▼
       ┌────────────┐
       │    TTS     │
       └─────┬──────┘
             │
             ▼
           AUDIO
```

My favorite engineering question:

```text
"What can happen BEFORE the thing finishes?"
```

That leads to:

`streaming`

`parallel execution`

`early tool execution`

`queue optimization`

`state reuse`

`connection reuse`

`cancellation`

`critical-path reduction`

---

# `07 // ENGINEERING DNA`

<div align="center">

```text
                 ┌──────────────────┐
                 │     OBSERVE      │
                 └────────┬─────────┘
                          ↓
                 ┌──────────────────┐
                 │     MEASURE      │
                 └────────┬─────────┘
                          ↓
                 ┌──────────────────┐
                 │    IDENTIFY      │
                 │    BOTTLENECK    │
                 └────────┬─────────┘
                          ↓
                 ┌──────────────────┐
                 │    OPTIMIZE      │
                 └────────┬─────────┘
                          ↓
                 ┌──────────────────┐
                 │     RE-MEASURE   │
                 └──────────────────┘
```

</div>

I don't consider:

```text
"it feels faster"
```

to be a performance measurement.

I care about:

`TTFT` · `TTFA` · `E2E latency` · `queue delay` · `tool latency` · `token throughput` · `audio startup`

---

# `08 // STACK`

### `AI / ML`

<p align="center">
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow&theme=dark"/>
</p>

<div align="center">

`LLMs` · `Speech Models` · `ASR` · `TTS` · `Embeddings` · `Inference` · `Evaluation`

</div>

---

### `BACKEND / SYSTEMS`

<p align="center">
<img src="https://skillicons.dev/icons?i=python,fastapi,nodejs,express,docker,linux&theme=dark"/>
</p>

<div align="center">

`AsyncIO` · `WebSockets` · `REST` · `Streaming` · `Queues` · `Concurrency`

</div>

---

### `DATA / INFRA`

<p align="center">
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,docker,git,github&theme=dark"/>
</p>

<div align="center">

`State` · `Caching` · `Persistence` · `Containers` · `Observability`

</div>

---

### `FRONTEND`

<p align="center">
<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,html,css,tailwind&theme=dark"/>
</p>

<div align="center">

Full-stack foundations remain part of the stack.

</div>

---

# `09 // WHAT I ACTUALLY THINK ABOUT`

```text
┌────────────────────────────────────────────────────────────────────┐
│                                                                    │
│  Why is the agent waiting?                                        │
│                                                                    │
│  Can two operations happen simultaneously?                        │
│                                                                    │
│  Can the model start producing before the full answer exists?     │
│                                                                    │
│  Can the tool execute earlier?                                    │
│                                                                    │
│  Can the user interrupt safely?                                   │
│                                                                    │
│  What happens when the network disappears?                        │
│                                                                    │
│  Where does state actually live?                                  │
│                                                                    │
│  Which operation is truly on the critical path?                   │
│                                                                    │
└────────────────────────────────────────────────────────────────────┘
```

---

# `10 // CURRENT EXPLORATION`

```yaml
FOCUS:
  ├── Voice AI
  ├── Conversational Agents
  ├── LLM Orchestration
  ├── Streaming Architectures
  ├── Tool Calling
  ├── Async Systems
  ├── Latency Engineering
  └── AI Infrastructure

DEEPER:
  ├── VAD
  ├── ASR
  ├── TTS
  ├── Context Management
  ├── Memory
  ├── DAG Execution
  ├── Observability
  └── Failure Handling

MENTAL_MODEL:
  build → measure → profile → optimize → repeat
```

---

# `11 // PROJECT SIGNAL`

<div align="center">

### `THINKNOTES`

Collaborative full-stack application.

`MERN` · `real-time collaboration` · `UI/UX`

---

### `MOODTUNES`

Mood-driven music experience.

`JavaScript` · `interaction design` · `frontend`

---

### `LOLA`

Real-time conversational AI engineering.

`Voice` · `LLM` · `Tool Calling` · `Streaming` · `Latency`

</div>

---

# `12 // GITHUB TELEMETRY`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Hemnath4114&show_icons=true&theme=tokyonight&hide_border=true&border_radius=16&include_all_commits=true&count_private=true"/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=Hemnath4114&theme=tokyonight&hide_border=true&border_radius=16"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hemnath4114&layout=compact&theme=tokyonight&hide_border=true&border_radius=16&langs_count=8"/>

</div>

---

# `13 // CONTRIBUTION MATRIX`

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Hemnath4114&theme=tokyo-night&hide_border=true&area=true&radius=16"/>

</div>

---

# `14 // TROPHIES`

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Hemnath4114&theme=algolia&no-frame=true&no-bg=true&margin-w=8&column=7"/>

</div>

---

# `15 // THE PRINCIPLES`

```text
01  Measure before optimizing.

02  Optimize the critical path.

03  Stream whenever possible.

04  Minimize unnecessary work.

05  Design for interruption.

06  Assume dependencies will fail.

07  Keep architecture understandable.

08  Let complexity live inside the system,
    not inside the user experience.
```

---

# `16 // THE NEXT BUILD`

<div align="center">

```text
                    ┌───────────────┐
                    │   HUMAN       │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │   INTENT      │
                    └───────┬───────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   INTELLIGENCE      │
                 │                     │
                 │ reason / remember   │
                 │ plan / execute      │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │     REAL-TIME       │
                 │       ACTION        │
                 └──────────┬──────────┘
                            │
                            ▼
                       EXPERIENCE
```

</div>

I'm interested in the point where **AI stops feeling like a software feature and starts feeling like an interface.**

---

# `17 // OFF THE STACK`

`football` · `cricket` · `music` · `design` · `late-night debugging`

Still obsessed with clean interfaces.

Just increasingly interested in the systems underneath them.

---

<div align="center">

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=4000&pause=1200&color=8B949E&center=true&vCenter=true&width=700&lines=The+goal+isn't+to+make+AI+look+intelligent.;The+goal+is+to+make+intelligence+feel+natural."/>

<br/><br/>

```text
────────────────────────────────────────────────────────

                HEMNATH M // AI ENGINEER

         build systems • measure everything
              make intelligence feel simple

────────────────────────────────────────────────────────
```

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:111827,50:0A0F14,100:050505"/>

</div>
