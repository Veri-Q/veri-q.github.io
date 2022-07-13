---
title: QDA
subtitle: Design Automation for Quantum Computing
layout: page
show_sidebar: false
menubar: menu_tools
toc: true
hero_height: 400px
---

In *QDA (Design Automation for Quantum Computing)* project in *VeriQ*, a series of QDA tools are developed, including a fault simulator based on tensor network and BDD, an ATPG (Automatic Test Pattern Generation) algorithm for testing quantum circuits, and a tensor network based decision diagram for representation of quantum circuits. These tools have a wide range of applications such as simulation, verification, synthesis, circuit testing and equivalence checking.

## VeriQBench
VeriQBench is a benchmark for general tasks in Quantum Computing. It includes the most commonly used types of quantum circuits --- combinational quantum circuits, dynamic quantum circuits, sequential quantum circuits, and variational quantum circuits. For most of the quantum circuits, our benchmark includes three scales: small scale (<20 qubits), medium scale (20-50 qubits), and large scale (>50 qubits). We also provide a series of scrips for users to generate quantum circuits of arbitrary number of qubits.

See [{% include tag.html tag="Github Repo" %}](https://github.com/Veri-Q/Benchmark)

<td align="right" class="bibtexnumber">
[<a name="chen2022veriqbench">1</a>]
</td>
<td class="bibtexitem">
Kean Chen, Wang Fang, Ji&nbsp;Guan, Xin Hong, Mingyu Huang, Junyi Liu, Qisheng Wang,
  and Mingsheng Ying.
 Veriqbench: A benchmark for multiple types of quantum circuits.
 <em>arXiv preprint arXiv:2206.10880</em>, 2022.

</td>


## Fault Simulator
A fault simulation tool for noisy quantum circuits based on tensor network and BDD(binary decision diagram) method.

See [{% include tag.html tag="Github Repo" %}](https://github.com/hmy98213/Fault-Simulation)

## ATPG (Automatic Test Pattern Generation)
An automatic test pattern generation (ATPG) algorithm for robust quantum circuit testing based on stabilizer projector decomposition.

See [{% include tag.html tag="Github Repo" %}](https://github.com/cccorn/Q-ATPG)

<td align="right" class="bibtexnumber">
[<a name="chen2022automatic">2</a>]
</td>
<td class="bibtexitem">
Kean Chen and Mingsheng Ying.
 Automatic test pattern generation for robust quantum circuit testing.
 <em>arXiv preprint arXiv:2202.10697</em>, 2022.

</td>

## TDD (Tensor Decision Diagram)
A tensor network based decision diagram for representation and operation of tensor networks and quantum circuits.

See [{% include tag.html tag="Github Repo" %}](https://github.com/Veriqc/TDD)

<td align="right" class="bibtexnumber">
[<a name="10.1145/3514355">3</a>]
</td>
<td class="bibtexitem">
Xin Hong, Xiangzhen Zhou, Sanjiang Li, Yuan Feng, and Mingsheng Ying.
 A tensor network based decision diagram for representation of quantum
  circuits.
 <em>ACM Trans. Des. Autom. Electron. Syst.</em>, 27(6), jun 2022.
[&nbsp;<a href="http://dx.doi.org/10.1145/3514355">DOI</a>&nbsp;| 
<a href="https://doi.org/10.1145/3514355">http</a>&nbsp;]

</td>
