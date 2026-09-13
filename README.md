 <div align="center">

# Spider4Tech

### Building software. Exploring systems. Understanding security.

*Developer · Systems · Cybersecurity · Cryptography · Distributed Computing*

<a href="https://github.com/Spider4Tech">
  <img src="https://img.shields.io/badge/GitHub-Spider4Tech-181717?style=for-the-badge&logo=github" alt="GitHub"/>
</a>
<a href="https://altrion-systems.fr/">
  <img src="https://img.shields.io/badge/Altrion_Systems-Website-2563EB?style=for-the-badge" alt="Altrion Systems"/>
</a>

</div>

---

## Who I am

I'm a developer who enjoys going beyond the surface of software.

I like understanding how systems work, where they fail, and how they can be made more reliable, secure, or efficient.

My projects cover a fairly wide range: distributed computing, cryptography, cybersecurity, Linux tooling, web applications, and experimental software.

Some are designed as practical tools. Others are explorations of an idea. What connects them is the desire to build, test, and learn by doing.

> I don't just want to use technology. I want to understand it, build it, and see what it can become.

---

## Areas of interest

<table>
<tr>
<td width="50%" valign="top">

### Systems & Performance

* Rust and low-level programming
* Concurrency and memory management
* Distributed computing
* Linux and infrastructure
* Performance-oriented software

</td>
<td width="50%" valign="top">

### Security & Cryptography

* Defensive security tooling
* File analysis and malware detection
* Secure storage and secret handling
* Cryptographic implementations
* Post-quantum cryptography

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Applications & Web

* Rust, Python, TypeScript
* Svelte and web applications
* Desktop tools
* APIs and backend services
* Automation and utilities

</td>
<td width="50%" valign="top">

### Research & Experimentation

* Simulations
* Algorithmic experiments
* New architectures
* Prototypes
* Exploring unconventional approaches

</td>
</tr>
</table>

---

# Featured projects

These are some of the projects that best represent the kind of software I enjoy building.

## SODIUM

### File Security Scanner

**Go · ClamAV · YARA · Wazuh · Podman**

A multi-engine file analysis service designed to integrate with Wazuh and analyze files originating from both Windows and Linux systems.

SODIUM combines several independent detection and analysis layers:

* ClamAV and YARA for threat detection.
* Linux Malware Detect and LOKI for complementary detection and IOC analysis.
* CAPA and Detect It Easy for program capability and binary identification.
* Static analysis of PE, ELF, scripts, documents, and archives.
* A local reputation database based on file hashes.
* A configurable Risk Engine producing a score, verdict, confidence, and explanation.

The project is designed around an important security principle: **the scanner itself never executes the analyzed file.**

Dynamic analysis is treated as a separate, explicitly triggered operation using an isolated CAPE environment.

The architecture also separates the scanner from the Wazuh manager, avoiding direct access to the manager's filesystem.

[Explore SODIUM →](https://github.com/Spider4Tech/SODIUM)

---

## HyperCompute

### Distributed Computing

**Rust · REST · WebSockets · Scheduling**

An exploration of distributed computing and workload orchestration.

HyperCompute focuses on coordinating workers, dispatching jobs, handling node capabilities, and distributing workloads across a computing environment.

The project explores the practical challenges behind distributed execution: scheduling, communication, reliability, and the coordination of multiple machines.

[Explore HyperCompute →](https://github.com/Spider4Tech/Hypercompute)

---

## Hecate

### Secure Memory Vault

**Rust · Argon2 · Encryption · Zeroization**

A security-oriented project exploring the protection of sensitive information in application memory.

Hecate focuses on encrypted storage, password-based key derivation, and memory handling for secrets.

The goal is to understand the practical challenges involved in protecting sensitive data throughout its lifecycle.

[Explore Hecate →](https://github.com/Spider4Tech/Hecate)

---

## Horizon

### Cryptography & Secure Software

**Rust · Symmetric Cryptography · BLAKE3 · Argon2id**

A cryptographic software project exploring encryption, key derivation, parallel processing, and secure handling of sensitive data.

Horizon is part of my broader interest in understanding cryptographic systems beyond simply calling a library function.

[Explore Horizon →](https://github.com/Spider4Tech/gh)

---

## kyberlib

### Post-Quantum Cryptography

**Rust · ML-KEM / Kyber · no_std**

An implementation-oriented project exploring post-quantum cryptography and key encapsulation mechanisms.

The project investigates how cryptographic primitives can be implemented in Rust with attention to portability, allocation constraints, and secure key exchange.

[Explore kyberlib →](https://github.com/Spider4Tech/kyberlib_SODIUM)

---

## IronPass

### Password Manager Concept

**Rust · Web · Argon2id · Encrypted Storage**

A security-oriented password manager project exploring encrypted client-side data, password-derived keys, and the design of a system where sensitive information remains protected.

The project brings together several of my interests: application development, cryptography, and security architecture.

[Explore IronPass →](https://github.com/Spider4Tech/IronPass)

---

## NukeIt

### Secure File Deletion

**Cross-platform · File Systems · Security**

A project exploring secure file deletion and the practical limitations of erasing data from modern storage devices.

It is an example of the kind of utility I enjoy building: focused on a specific problem, but requiring an understanding of what happens beneath the interface.

[Explore NukeIt →](https://github.com/Spider4Tech/NukeIt)

---

## Other projects

My repositories also include web applications, desktop tools, automation, and experimental projects.

Some are smaller utilities. Others are early-stage ideas that I use to explore a technology or a different approach to solving a problem.

A few examples:

* **Social-Sync** — Application development and social-platform integration.
* **Starduste Video** — Web application project.
* **2050** — Experimental simulation project.
* **Rcontrol** — Tooling and experimentation.
* **AutoBump** — Automation.
* **Planalife** — Experimental software.
* **SendIT** — Utility project.

[Browse all repositories →](https://github.com/Spider4Tech?tab=repositories)

---

# Technologies

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=rust,python,typescript,go,c,cpp" alt="Rust, Python, TypeScript, Go, C and C++"/>

### Web & Applications

<img src="https://skillicons.dev/icons?i=svelte,html,css" alt="Svelte, HTML and CSS"/>

### Infrastructure & Security

<img src="https://skillicons.dev/icons?i=linux,docker,git" alt="Linux, Docker and Git"/>

</div>

---

# How I approach projects

I enjoy projects that require more than simply connecting a few libraries together.

Whether it's a distributed scheduler, a file security scanner, a cryptographic implementation, or a small utility, I like understanding the underlying mechanisms and thinking about what happens when things go wrong.

That means paying attention to:

* Security boundaries and failure modes.
* Resource usage and performance.
* Clear separation of responsibilities.
* Practical testing and validation.
* The difference between a promising prototype and a reliable tool.

Not every repository is a finished product. Some are experiments, and that's part of the point.

---

<div align="center">

## Thanks for visiting.

If you find something interesting, feel free to explore the repositories.

<a href="https://github.com/Spider4Tech?tab=repositories">View my repositories →</a>

</div>
