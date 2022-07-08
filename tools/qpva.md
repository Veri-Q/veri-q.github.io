---
title: Quantum Programs Verification and Analysis
layout: page
show_sidebar: false
menubar: menu_tools
toc: true
hero_height: 400px
---
In the *Quantum Programs Verification and Analysis* project in *VeriQ*, we develop new theories and tools to verify the correctness and analyze the effectiveness of quantum programs. With the help of our original theoretical framework, high-level and large-scale quantum programs can be effectively verified and analyzed on both paper and classical computers.
## QHLProver
We formalize quantum Hoare logic in Isabelle/HOL. In particular, we specify the syntax and denotational semantics of a simple model of quantum programs. Then, we write down the rules of quantum Hoare logic for partial correctness, and show the soundness and completeness of the resulting proof system. As an application, we verify the correctness of Grover's algorithm.

See [{% include tag.html tag="Isabelle AFP" %}](https://www.isa-afp.org/entries/QHLProver.html)
