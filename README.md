<div align="center">

```
 ██████╗ ██████╗ ██╗██████╗ ███████╗██████╗ ██╗  ██╗████████╗███████╗ ██████╗██╗  ██╗
██╔════╝ ██╔══██╗██║██╔══██╗██╔════╝██╔══██╗╚██╗██╔╝╚══██╔══╝██╔════╝██╔════╝██║  ██║
╚█████╗  ██████╔╝██║██║  ██║█████╗  ██████╔╝ ╚███╔╝    ██║   █████╗  ██║     ███████║
 ╚═══██╗ ██╔═══╝ ██║██║  ██║██╔══╝  ██╔══██╗ ██╔██╗    ██║   ██╔══╝  ██║     ██╔══██║
██████╔╝ ██║     ██║██████╔╝███████╗██║  ██║██╔╝ ██╗   ██║   ███████╗╚██████╗██║  ██║
╚═════╝  ╚═╝     ╚═╝╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝   ╚══════╝ ╚═════╝╚═╝  ╚═╝
```

<a href="https://github.com/Spider4Tech">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=1200&color=8B5CF6&center=true&vCenter=true&width=720&height=40&lines=Systems+Engineer+%E2%80%A2+Applied+Cryptography;Distributed+Computing+%E2%80%A2+Security;Memory+Safety+%E2%80%A2+Zero-Compromise+Correctness" alt="Roles" />
</a>

<br/>

<a href="https://github.com/Spider4Tech"><img src="https://komarev.com/ghpvc/?username=Spider4Tech&style=for-the-badge&color=8B5CF6&label=PROFILE+VIEWS" alt="Profile Views" /></a>
&nbsp;
<img src="https://img.shields.io/github/followers/Spider4Tech?style=for-the-badge&color=8B5CF6&labelColor=1a1b27&label=FOLLOWERS" alt="Followers" />
&nbsp;
<img src="https://img.shields.io/badge/OPEN%20TO-COLLABORATION-8B5CF6?style=for-the-badge&labelColor=1a1b27" alt="Open to collaboration" />

</div>

---

## `~/ whoami`

```rust
struct Spider4Tech {
    focus:     &'static [&'static str],
    languages: &'static [&'static str],
    interests: &'static [&'static str],
    motto:     &'static str,
}

const ME: Spider4Tech = Spider4Tech {
    focus:     &["Systems Programming", "Applied Cryptography", "Distributed Computing", "Web Engineering"],
    languages: &["Rust", "Go", "C", "C++", "COBOL", "Svelte", "TypeScript", "Python"],
    interests: &["Memory Safety", "Secure Vaults", "HPC / MPI", "Cryptanalysis", "Low-level Internals"],
    motto:     "A little spider building serious tech — with precision and curiosity.",
};
```

I design software at the intersection of **performance**, **security**, and **correctness** — from bare-metal memory management to distributed cluster orchestration. My work emphasises **minimal attack surface**, **formal reasoning about system state**, and **zero compromise** on safety invariants.

---

## `~/ featured-projects`

<table>
<tr>
<td width="50%" valign="top">

### 🕸 [HyperCompute](https://github.com/Spider4Tech/Hypercompute)

**Distributed compute cluster · Rust**

A production-grade task scheduler and execution fabric for MPI workloads across heterogeneous node clusters. Real-time scoring algorithm, WebSocket worker protocol, fault tolerance, and a full REST API.

<sub>
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/WebSocket-4353FF?style=flat-square&logo=socketdotio&logoColor=white" />
<img src="https://img.shields.io/badge/MPI-0F62FE?style=flat-square" />
</sub>

`distributed` · `HPC` · `scheduler` · `fault-tolerance`

</td>
<td width="50%" valign="top">

### 🔐 [Hecate](https://github.com/Spider4Tech/Hecate)

**Cryptographic memory vault · Rust**

An in-memory secret vault using AEAD encryption, Argon2 key derivation, memory fragmentation, decoy data, and zeroize-backed structures — engineered to minimise memory-forensics exposure for long-lived secrets in RAM.

<sub>
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Argon2-721412?style=flat-square" />
<img src="https://img.shields.io/badge/AES--GCM-4B0082?style=flat-square" />
<img src="https://img.shields.io/badge/SHA3-8B5CF6?style=flat-square" />
</sub>

`cryptography` · `memory-safety` · `AEAD` · `vault`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌅 [Horizon](https://github.com/Hestia-Tech/gh)

**High-performance symmetric cipher · Rust**

A parallelised cipher built on custom key-dependent S-boxes (GF(256) + BLAKE3), Argon2id key derivation, HMAC-SHA256 integrity, and constant-time operations throughout — hardened against timing, cache, and linear cryptanalysis.

<sub>
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/BLAKE3-2A2A72?style=flat-square" />
<img src="https://img.shields.io/badge/HMAC--SHA256-8B5CF6?style=flat-square" />
<img src="https://img.shields.io/badge/Rayon-DEA584?style=flat-square&logoColor=black" />
</sub>

`cipher` · `side-channel-resistant` · `parallel` · `GF256`

</td>
<td width="50%" valign="top">

### ☀️ [2050](https://github.com/Spider4Tech/2050)

**Dyson Sphere panel manager · Rust**

A solar-panel management system for a Dyson Sphere — an exploratory systems project in Rust with a Makefile-driven build, pushing large-scale resource orchestration as a design exercise.

<sub>
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Makefile-427819?style=flat-square&logo=gnu&logoColor=white" />
</sub>

`systems` · `simulation` · `resource-management`

</td>
</tr>
</table>

---

## `~/ open-source-contributions`

> Selected upstream work on production cryptography.

**[`sebastienrousseau/kyberlib`](https://github.com/sebastienrousseau/kyberlib)** &nbsp;·&nbsp; ![Stars](https://img.shields.io/github/stars/sebastienrousseau/kyberlib?style=flat-square&color=8B5CF6&labelColor=1a1b27)

FIPS 203 **ML-KEM (CRYSTALS-Kyber)** for Rust — pure-Rust, `no_std`, ACVP 180/180, KyberSlash-clean, with SLSA L3 + cosign-signed releases. Published on crates.io as `kyberlib` and `kyberlib-wasm`. A reference-grade **post-quantum** key-encapsulation crate.

---

## `~/ tech-stack`

**Systems & Low-level**
&nbsp;
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![COBOL](https://img.shields.io/badge/COBOL-005C84?style=flat-square&logoColor=white)

**Backend & Services**
&nbsp;
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Web & Frontend**
&nbsp;
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Security & Cryptography**
&nbsp;
![OpenSSL](https://img.shields.io/badge/OpenSSL-721412?style=flat-square&logo=openssl&logoColor=white)
![Argon2](https://img.shields.io/badge/Argon2-4B0082?style=flat-square)
![AES-GCM](https://img.shields.io/badge/AES--GCM-4B0082?style=flat-square)
![SHA-3](https://img.shields.io/badge/SHA--3-8B5CF6?style=flat-square)
![BLAKE3](https://img.shields.io/badge/BLAKE3-2A2A72?style=flat-square)
![ML-KEM](https://img.shields.io/badge/ML--KEM-8B5CF6?style=flat-square)

**Tooling**
&nbsp;
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## `~/ github-stats`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Spider4Tech&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=8B5CF6&icon_color=8B5CF6" height="165" alt="GitHub Stats" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Spider4Tech&layout=compact&langs_count=8&card_width=340&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=8B5CF6" height="165" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Spider4Tech&theme=tokyonight&hide_border=true&background=1a1b27&ring=8B5CF6&fire=8B5CF6&currStreakLabel=8B5CF6" height="165" alt="Streak Stats" />
</div>
---

## `~/ philosophy`

> *"Security is not a feature. It's a constraint the entire system must satisfy — from the allocator to the API boundary."*

I build things that work correctly under adversarial conditions. I care about **memory hygiene**, **cryptographic correctness**, and systems that **degrade gracefully** under failure.

---

<div align="center">

### Let's build something secure.

<a href="https://github.com/Spider4Tech"><img src="https://img.shields.io/badge/GitHub-Spider4Tech-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

<sub>Open to collaboration</sub>

</div>
