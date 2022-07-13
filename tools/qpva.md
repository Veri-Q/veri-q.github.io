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

<td align="right" class="bibtexnumber">
[<a name="DBLP:conf/cav/LiuZWYLLYZ19">1</a>]
</td>
<td class="bibtexitem">
Junyi Liu, Bohua Zhan, Shuling Wang, Shenggang Ying, Tao Liu, Yangjia Li,
  Mingsheng Ying, and Naijun Zhan.
 Formal verification of quantum algorithms using quantum hoare logic.
 In <em>Computer Aided Verification - 31st International Conference,
  CAV 2019</em>, volume 11562 of <em>Lecture Notes in Computer Science</em>, pages
  187&ndash;207. Springer, 2019.
[&nbsp;<a href="http://dx.doi.org/10.1007/978-3-030-25543-5\_12">DOI</a>&nbsp;| 
<a href="https://doi.org/10.1007/978-3-030-25543-5\_12">http</a>&nbsp;]

</td>