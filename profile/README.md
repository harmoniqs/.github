<div align="center">

<svg width="800" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
  <rect width="800" height="120" fill="#0d1117" rx="8"/>

  <text
    x="400" y="58"
    font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif"
    font-size="48"
    font-weight="700"
    fill="#f0f6fc"
    text-anchor="middle"
    opacity="0"
  >
    Harmoniqs
    <animate attributeName="opacity" from="0" to="1" dur="1.4s" begin="0.2s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.4 0 0.2 1"/>
  </text>

  <text
    x="400" y="88"
    font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif"
    font-size="15"
    fill="#8b949e"
    text-anchor="middle"
    opacity="0"
    letter-spacing="1"
  >
    robotics inspired quantum control
    <animate attributeName="opacity" from="0" to="1" dur="1.4s" begin="0.7s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.4 0 0.2 1"/>
  </text>
</svg>

**Next-generation quantum optimal control — built on ideas from robotics trajectory optimization.**

![Actively Maintained](https://img.shields.io/badge/status-actively_maintained-brightgreen?style=flat-square)
![Julia](https://img.shields.io/badge/language-Julia-9558B2?style=flat-square&logo=julia)
![MIT License](https://img.shields.io/badge/license-MIT-yellow?style=flat-square)
[![Docs](https://img.shields.io/badge/docs-docs.harmoniqs.co-blue?style=flat-square)](https://docs.harmoniqs.co)
[![Discord](https://img.shields.io/badge/chat-Unitary_Discord-5865F2?style=flat-square&logo=discord)](https://discord.unitary.foundation)

</div>

---

<table>
<tr>
<td width="50%">

### 🤖 → ⚛️ &nbsp;Why robotics?

Robotic arms and quantum gates share a deep structure: both require steering a dynamical system along an optimal path. We port battle-tested trajectory optimization methods from robotics into quantum control.

</td>
<td width="50%">

### 🎯 &nbsp;What we solve

High-fidelity gate synthesis, pulse optimization, and open-loop control for quantum hardware — with fine-grained control over constraints, costs, and solver backends.

</td>
</tr>
</table>

---

## 📦 Packages

<table>
<tr>
<td width="50%">

### [`Piccolo.jl`](https://github.com/harmoniqs/Piccolo.jl) &nbsp;`flagship`

Solve quantum optimal control problems using direct trajectory optimization. Define your system, constraints, and objectives — Piccolo handles the rest.

> **→ Use this first.** High-level interface for gate synthesis & pulse optimization.

![Stars](https://img.shields.io/github/stars/harmoniqs/Piccolo.jl?style=flat-square) ![Forks](https://img.shields.io/github/forks/harmoniqs/Piccolo.jl?style=flat-square)

</td>
<td width="50%">

### [`DirectTrajOpt.jl`](https://github.com/harmoniqs/DirectTrajOpt.jl) &nbsp;`core`

Low-level abstractions for direct collocation and shooting methods. Build custom trajectory optimization pipelines with full control over discretization and solver setup.

> **→ Use this** when you need to go beyond Piccolo's defaults.

![Stars](https://img.shields.io/github/stars/harmoniqs/DirectTrajOpt.jl?style=flat-square) ![Forks](https://img.shields.io/github/forks/harmoniqs/DirectTrajOpt.jl?style=flat-square)

</td>
</tr>
<tr>
<td width="50%">

### [`NamedTrajectories.jl`](https://github.com/harmoniqs/NamedTrajectories.jl) &nbsp;`utility`

A lightweight data structure for working with trajectories keyed by user-defined component names. Makes trajectory data ergonomic to inspect, slice, and pass between solvers.

> **→ Use this** for trajectory post-processing or standalone trajectory handling.

![Stars](https://img.shields.io/github/stars/harmoniqs/NamedTrajectories.jl?style=flat-square) ![Forks](https://img.shields.io/github/forks/harmoniqs/NamedTrajectories.jl?style=flat-square)

</td>
<td width="50%">

### [`PiccoloMultidocs.jl`](https://github.com/harmoniqs/PiccoloMultidocs.jl) &nbsp;`docs`

Unified documentation tooling across the Piccolo ecosystem. Keeps cross-package docs consistent and co-located.

> **→ For contributors** working across multiple Harmoniqs packages.

![Stars](https://img.shields.io/github/stars/harmoniqs/PiccoloMultidocs.jl?style=flat-square) ![Forks](https://img.shields.io/github/forks/harmoniqs/PiccoloMultidocs.jl?style=flat-square)

</td>
</tr>
</table>

---

## 🤝 Collaborations

*Enabling quantum technology for researchers and institutions worldwide.*

<table>
<tr>
<td width="33%">

**🎓 Harvard University**

Systematically benchmarking the expressivity of neutral atom arrays by engineering effective quantum interactions under various control regimes.

</td>
<td width="33%">

**🎓 Stanford University**

Designing and testing new hardware by developing novel integrated controls for complex quantum systems.

</td>
<td width="33%">

**⚡ Infleqtion**

Applying novel quantum optimal control approaches to design integrated solutions for quantum sensing applications.

</td>
</tr>
<tr>
<td width="33%">

**💻 QCK**

Maximizing classical-quantum hardware integration to make the most of classical resources in quantum computing architectures.

</td>
<td width="33%">

**🎓 NYU**

Driving innovation in bosonic encodings for quantum error correction, navigating large state spaces with fine-tuned control.

</td>
<td width="33%">
</td>
</tr>
</table>

---

## 🤝 Get Involved

<table>
<tr>
<td align="center" width="33%">

**💬 Discord**<br>
Chat with us on the [Unitary Foundation Discord](https://discord.unitary.foundation) in the #piccolo channel

</td>
<td align="center" width="33%">

**🐛 Contribute**<br>
Open issues, submit PRs, or pick up a good first issue in any repo

</td>
<td align="center" width="33%">

**📖 Docs & Examples**<br>
Full tutorials and API reference at [docs.harmoniqs.co](https://docs.harmoniqs.co)

</td>
</tr>
</table>

---

<div align="center">

Built with ❤️ by the Harmoniqs team &nbsp;·&nbsp; [harmoniqs.co](https://harmoniqs.co) &nbsp;·&nbsp; MIT License

</div>
