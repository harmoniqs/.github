<div align="center">

<img src="./harmoniqs-title.svg" alt="Harmoniqs" />


**Next-generation quantum optimal control — built on ideas from robotics trajectory optimization.**

![Actively Maintained](https://img.shields.io/badge/status-actively_maintained-brightgreen?style=flat-square)
![Julia](https://img.shields.io/badge/language-Julia-9558B2?style=flat-square&logo=julia)
![MIT License](https://img.shields.io/badge/license-MIT-yellow?style=flat-square)
[![Docs](https://img.shields.io/badge/docs-docs.harmoniqs.co-blue?style=flat-square)](https://docs.harmoniqs.co)

</div>

---

<table>
<tr>
<td width="50%">

### 🤖 → ⚛️ &nbsp;Why robotics?

Robotics and quantum gates both share a deep structure. They both require steering a dynamical system along an optimal path. We port industry-tested trajectory optimization methods from robotics into quantum control.

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

### [`Stretto.jl`](https://github.com/harmoniqs/Stretto.jl) &nbsp;`compiler`

Circuit-to-pulse compilation layer built on Piccolo. Treats a gate-level circuit as a single unitary and synthesizes one optimized control pulse for the whole block — skipping gate decomposition and gate-boundary error accumulation.

> **→ Use this** to compile circuits (e.g. QEC syndrome blocks) directly to hardware pulses.

![Stars](https://img.shields.io/github/stars/harmoniqs/Stretto.jl?style=flat-square) ![Forks](https://img.shields.io/github/forks/harmoniqs/Stretto.jl?style=flat-square)

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

**💬 Slack**<br>
Join our [Slack community](https://join.slack.com/share/enQtMTA2MTQyOTEzNjg3ODYtODliMjllOGY4YjI3NzgwN2UyZTFlYjY3OTI0YWY3Nzc5OTJlY2MxY2NiZTk4YzNhYjc5ZWIyNzAyMzgxODdkYg) to chat with the team

</td>
<td align="center" width="33%">

**📖 Docs & Examples**<br>
Full tutorials and API reference at [docs.harmoniqs.co](https://docs.harmoniqs.co)

</td>
<td align="center" width="33%">

**👋 Work With Us**<br>
Interested in collaborating? [Reach out to us](https://www.harmoniqs.ai/company#careers)

</td>
</tr>
</table>


---

<div align="center">

Built with ❤️ by the Harmoniqs team &nbsp;·&nbsp; [harmoniqs.co](https://harmoniqs.ai) &nbsp;·&nbsp; MIT License

</div>
