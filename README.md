# ⚡ Quant Dev Roadmap
> Based on **Coding Jesus** (getcracked.io) · Engineering-only path · No finance math required
 
**[→ View Full Roadmap](https://lilsax.github.io/quant)**
 
---
 
## 🗺️ The Path
 
```
QUANT DEV / HFT ENGINEER
│
├── C++          ← your main grind (3–5 months)
├── OS           ← layer in mid-way through C++
├── Comp Arch    ← start here (2 weeks)
├── Networking   ← save for last
├── Sys Design   ← matching engine, order books
└── Python       ← secondary, still tested
```
 
---
 
## 📚 Books
 
| # | Book | Author | Topic | Priority |
|---|------|--------|-------|----------|
| 1 | C++ Concurrency in Action | Anthony Williams | C++ | 🔴 Must-read |
| 2 | Beautiful C++ | J. Guy Davidson | C++ | 🔴 Must-read |
| 3 | C++ Software Design | Klaus Iglberger | C++ | 🔴 Must-read |
| 4 | The Art of Writing Efficient Programs | Fedor G. Pikus | C++ / Perf | 🔴 Must-read |
| 5 | Operating Systems: Three Easy Pieces | Arpaci-Dusseau | OS | 🟡 Important |
| 6 | Inside the Machine | Jon Stokes | Comp Arch | 🟡 Important |
| 7 | TCP/IP Illustrated Vol. 1 | W. Richard Stevens | Networking | 🟡 Important |
 
---
 
## 🗓️ Study Order
 
### 1. Computer Architecture · `1–2 weeks`
Read *Inside the Machine* first. Short book. Gives you the mental model — cache, pipeline, branch prediction — before you write a single line of C++.
 
### 2. C++ Core → Concurrency · `3–5 months`
Your main grind. Start with modern C++ fundamentals (RAII, smart pointers, move semantics), then go deep on concurrency with *C++ Concurrency in Action*. Layer in *Beautiful C++* and *C++ Software Design* as you go.
 
### 3. OS Internals · `6–8 weeks`
Start *OS: Three Easy Pieces* mid-way through C++ concurrency. Threads and mutexes will make kernel-level concepts click immediately. Focus on the concurrency and virtualization sections.
 
### 4. Networking · `4–6 weeks`
*TCP/IP Illustrated* is the most self-contained — save it for last. Understand the full stack: latency sources, UDP, multicast, exchange protocols (FIX, ITCH).
 
---
 
## 🎯 What Firms Actually Test
 
| Topic | Frequency |
|-------|-----------|
| C++ deep dives | 🔴 High |
| Concurrency / threading | 🔴 High |
| OS internals | 🔴 High |
| Memory model | 🔴 High |
| Computer architecture | 🟡 Medium |
| Networking fundamentals | 🟡 Medium |
| System design | 🟡 Medium |
| Python gotchas | 🟡 Medium |
| Basic probability | ⚪ Occasional |
| Logic puzzles | ⚪ Occasional |
 
---
 
## 🏗️ Portfolio Project
 
Build a **Matching Engine in C++** and put it on GitHub.
 
```
Order book (bid/ask)  ·  Price-time priority  ·  Limit + market orders
Lock-free queue  ·  Nanosecond timing  ·  Unit tested
```
 
> The single best portfolio project for HFT roles per Coding Jesus.
 
---
 
## 🏢 Target Firms
 
`Jane Street` · `Citadel Securities` · `Optiver` · `Jump Trading` · `Virtu` · `SIG` · `Hudson River Trading` · `IMC Trading` · `Tower Research`
 
---
 
*Sourced from [Coding Jesus](https://www.youtube.com/@CodingJesus) · [getcracked.io](https://getcracked.io)*
