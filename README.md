<div align="center">

<a href="https://github.com/ApoorvMathur28">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Digital+Design+%26+Verification+Engineer;RTL+%E2%86%92+GDSII+%7C+UVM+%7C+Constrained-Random+Verification;Occasionally+I+build+full-stack+IoT+things+for+fun" alt="Typing SVG" />
</a>

</div>

<br>

I design digital hardware, then prove it's actually correct — self-checking UVM testbenches, constrained-random stimulus, and functional coverage closure, not just eyeballing waveforms. Recent work spans CubeSat power electronics, AXI-based SoC peripherals, and a from-scratch ASIC design flow.

<br>

## 🔬 Featured work

<table>
<tr>
<td width="50%" valign="top">

### [AXI4-Lite Slave — UVM Verification](https://github.com/ApoorvMathur28/AXI4-Lite-Slave-UVM-Functional-Verification)
A self-checking UVM environment for a 4-register AXI4-Lite slave, built from scratch — driver, monitor, scoreboard, agent, env.

- ✅ **0 errors** across a 34-transaction directed + constrained-random regression
- ✅ **100% functional coverage** (address × R/W × response-type cross coverage)
- ✅ Perl regression triage that independently re-counts errors rather than trusting the simulator's own summary

`SystemVerilog` `UVM` `Perl`

</td>
<td width="50%" valign="top">

### [SSPC Load Shaper](https://github.com/ApoorvMathur28/SSPC-Load-Shaper)
RTL + verification for a CubeSat EPS sink-side power controller that soft-starts a payload so its inrush current doesn't brown out the shared DC bus.

- ⚡ **~40% reduction** in bus voltage sag under worst-case inrush (3.05V → 3.48V)
- ✅ **91.7% functional coverage** across 20 constrained-random scenarios
- 🔍 Located the exact **~2.5A inrush limit** the shaper can no longer hold

`Verilog` `SystemVerilog` `Perl`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Modular ALU — RTL to GDSII](https://github.com/ApoorvMathur28/Modular-ALU)
4-bit ALU (8 arithmetic/logic ops via a 3-bit opcode), taken all the way from RTL through to GDSII for IIIT-Dharwad's **YUKTI chip design competition**.

`Verilog`

</td>
<td width="50%" valign="top">

### [Massive MIMO: ZF vs RZF](https://github.com/ApoorvMathur28/Massive-MIMO-Scaling-Problem-)
MATLAB simulation comparing Zero-Forcing and Regularized ZF precoding in a 64×48 massive MIMO system — BER vs SNR across a 0–40dB sweep.

`MATLAB`

</td>
</tr>
</table>

Also building **PixelLink** — a full-stack IoT project of my own: a Flask dashboard driving a physical ESP32-S3 LED matrix panel, with a from-scratch Three.js 3D live preview modeling every individual LED, and Spotify-reactive visualizers.

<br>

## 🛠️ Tools I actually reach for

<p>
<img src="https://img.shields.io/badge/SystemVerilog-1E90FF?style=for-the-badge&logo=verilog&logoColor=white" />
<img src="https://img.shields.io/badge/Verilog-8A2BE2?style=for-the-badge&logo=verilog&logoColor=white" />
<img src="https://img.shields.io/badge/UVM-006400?style=for-the-badge" />
<img src="https://img.shields.io/badge/MATLAB-orange?style=for-the-badge&logo=mathworks&logoColor=white" />
<img src="https://img.shields.io/badge/Perl-39457E?style=for-the-badge&logo=perl&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
</p>

<br>

## 📊 GitHub stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=ApoorvMathur28&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ApoorvMathur28&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ApoorvMathur28&theme=tokyo-night&hide_border=true&area=true" width="100%" />
</p>

<br>

<p align="center">
<img src="https://raw.githubusercontent.com/ApoorvMathur28/ApoorvMathur28/output/github-contribution-grid-snake-dark.svg" width="100%" />
</p>

</div>
