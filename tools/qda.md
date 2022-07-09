---
title: QDA
subtitle: Design Automation for Quantum Computing
layout: page
show_sidebar: false
menubar: menu_tools
toc: true
hero_height: 400px
---

In *QDA (Design Automation for Quantum Computing)* project in *VeriQ*, a series of QDA tools are developed, including a fault simulator based on tensor network and BDD, an ATPG (Automatic Test Pattern Generation) algorithm based on stabilizer projector decomposition, and a tensor network based decision diagram for representation of tensor networks and quantum circuits. These tools have a wide range of applications such as simulation, verification, synthesis, circuit testing and equivalence checking.

## VeriQBench
VeriQBench is a benchmark for general tasks in Quantum Computing. It includes the most commonly used types of quantum circuits including combinational quantum circuits, dynamic quantum circuits, sequential quantum circuits, and variational quantum circuits. For most of the quantum circuits, our benchmark includes three scales: small scale (<20 qubits), medium scale (20-50 qubits), and large scale (>50 qubits). We also provide a series of scrips for users to generate quantum circuits of arbitrary number of qubits.

See [{% include tag.html tag="Github Repo" %}](https://github.com/Veri-Q/Benchmark)


## Fault Simulator
A fault simulation tool for noisy quantum circuits based on tensor network and BDD(binary decision diagram) method.

See [{% include tag.html tag="Github Repo" %}](https://github.com/hmy98213/Fault-Simulation)

## ATPG (Automatic Test Pattern Generation)
An automatic test pattern generation (ATPG) algorithm for robust quantum circuit testing based on stabilizer projector decomposition.

See [{% include tag.html tag="Github Repo" %}](https://github.com/cccorn/Q-ATPG)

## TDD (Tensor Decision Diagram)
A tensor network based decision diagram for representation and operation of tensor networks and quantum circuits.

See [{% include tag.html tag="Github Repo" %}](https://github.com/Veriqc/TDD)
