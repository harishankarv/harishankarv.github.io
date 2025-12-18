---
layout: homepage
---

## About Me

I'm interested in building systems that are secure, verifiable, and efficient. My research interests are broadly in Operating Systems, Programming Languages and Formal Methods. I'm privileged to work under the guidance of [Prof. Srinivas Narayana](https://people.cs.rutgers.edu/~sn624/) and [Prof. Santosh Nagarakatte](https://people.cs.rutgers.edu/~santosh.nagarakatte/). Currently, I work closely with the [eBPF](https://lwn.net/Articles/740157/) run-time in the Linux kernel; specifically I am looking at the static program analysis taking place in the eBPF in-kernel verifier.  

I previously completed a Masters from the [University at Buffalo](https://www.buffalo.edu/). I worked with [Prof. Steven Ko](https://steveyko.github.io/), [Prof. Karthik Dantu](https://cse.buffalo.edu/faculty/kdantu/), and [Prof. Lukasz Ziarek](https://cse.buffalo.edu/~lziarek/) on developing richer runtimes for trusted applications written for the [ARM TrustZone](https://developer.arm.com/ip-products/security-ip/trustzone) trusted execution enviroment. I have also worked with [Prof. Anton Burtsev](https://www.ics.uci.edu/~aburtsev/) on designing fast hash tables that utilize the high bandwidth provided by modern memory (DRAM) subsystems. 

<!-- ## Research Interests

- **Program Verification:** image recognition, image generation, video captioning
- **Operating Systems:** meta-learning, incremental learning, transfer learning -->

## News

<ul>
  <li>
    <strong>July 2025: </strong><a href="assets/files/agni_sas25.pdf">Paper</a> on comparing the precision of abstract operators in the eBPF verifier through differential synthesis using <a href="https://github.com/bpfverif/agni">Agni</a> is accepted to <a href="https://2025.splashcon.org/home/sas-2025">SAS '25</a>.
  </li>
  <li>
    <strong>June 2025: </strong> <a href="https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/commit/?id=7a998a731627">Patch</a> improving the precision of the abstract operators for addition and subtraction in the eBPF verifier, discovered by our automated synthesis tool <a href="https://github.com/bpfverif/vayu">Vayu</a>, is upstreamed.
  </li>
  <li>
    <strong>June 2025: </strong><a href="assets/files/vayu_ebpf25.pdf">Paper</a> on automatically synthesizing abstract operators for the eBPF verifier is accepted to SIGCOMM eBPF Workshop (<a href="https://conferences.sigcomm.org/sigcomm/2025/workshop/ebpf/">eBPF'25</a>). Try out our tool <a href="https://github.com/bpfverif/vayu">Vayu</a>, which automatically synthesizes abstract operators. 
  </li>
  <li>
    <strong>Dec 2024: </strong> <a href="https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/commit/?id=9aa0ebde0014">Patch</a> improving the precision of the abstract operator for multiplication in the eBPF verifier is upstreamed.
  </li>
  <li>
    <strong>Jul 2024: </strong><a href="assets/files/agni_sas24.pdf">Paper</a> on scaling the verification of abstract operators in the Linux eBPF verifier using our tool <a href="https://github.com/bpfverif/agni">Agni</a> and fixing latent unsound abstract operators is accepted to <a href="https://2024.splashcon.org/home/sas-2024">SAS '24</a>.
  </li>
  <li>
    <strong>Apr 2024: </strong><a href="https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/commit/?id=1f586614f3ffa80fdf2116b2a1bebcdb5969cef8">Patch</a> to the Linux kernel fixing a latent unsoundness in the eBPF verifier is upstreamed.
  </li>
  <li>
    <strong>Nov 2023: </strong>Presented a talk and demoed our tool <a href="https://github.com/bpfverif/agni">Agni</a> at the Linux Plumbers Conference (<a href="https://lpc.events/event/17/">LPC '23</a>). See the slides <a href="assets/files/lpc23_talk.pdf">here</a>.
  </li>
  <li>
    <strong>Oct 2023: </strong> Presented my Ph.D. qualifying talk entitled: <em>Developing Verified Static Analyzers for Kernel Extensions</em>. See the <a href="assets/files/qe_report.pdf">report</a> on work related to my research. <em>Officially a Ph.D. candidate!</em>
  </li>
  <li>
    <strong>May 2023: </strong>Presented a talk on verifying the range analysis in the eBPF verifier of the Linux Kernel at <a href="http://www.njpls.org/">NJPLS '23</a>.
  </li>
  <li>
    <strong>Apr 2023: </strong><a href="assets/files/agni_cav23.pdf">Paper</a> on the verifying the range analysis in the eBPF verifier of the Linux kernel is accepted to <a href="http://www.i-cav.org/2023/">CAV '23</a>. Our tool <a href="https://github.com/bpfverif/agni">Agni</a>, is publicly available on github. Artifact for CAV '23 submission is available at <a href="https://zenodo.org/record/7931901">zenodo</a>.
  </li>
  <li>
    <strong>Apr 2022: </strong><a href="https://zenodo.org/record/5703630">Artifact</a> for CGO '22 submission on tristate numbers receives <em>Artifact Reusable</em> and <em>Results Reproduced</em> badges.
  </li>
  <li>
    <strong>Dec 2021: </strong>Paper on the abstract domain of tristate numbers (used in the Linux kernel's eBPF verifier) is accepted to <a href="https://conf.researchr.org/home/cgo-2022">CGO '22</a>. See the paper <a href="https://arxiv.org/abs/2105.05398">here</a>.
  </li>
  <li>
    <strong>May 2021: </strong>Linux kernel <a href="https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/commit/?id=05924717ac70">patch</a> introducing a new algorithm for multiplication of tristate numbers is upstreamed.
  </li>
  <li>
    <strong>Apr 2019: </strong><a href="https://dl.acm.org/doi/abs/10.1145/3307334.3328650">Poster</a> about garbage-collected runtimes for Trusted Applications written for ARM TrustZone is accepted to <a href="https://www.sigmobile.org/mobisys/2019/">MobiSys '19</a>.
  </li>
</ul>

{% include_relative _includes/publications.md %}

<!-- {% include_relative _includes/services.md %} -->

## Teaching

<ul>
  <li>
    TA, <a href="https://people.cs.rutgers.edu/~sn624/416-F23/">CS 416/518</a>, Operating Systems, with <a href="https://people.cs.rutgers.edu/~sn624/">Srinivas Narayana</a> at <a href="https://rutgers.edu/">Rutgers University</a>, Fall 2023.
  </li>
  <li>
    TA, <a href="https://www.ics.uci.edu/~aburtsev/143A/2020fall/index.html">CS 143A</a>, Operating Systems, with <a href="https://users.cs.utah.edu/~aburtsev//">Anton Burtsev</a> at <a href="https://uci.edu/">University of California, Irvine</a>, Fall 2020.
  </li>
  <li>
    TA, <a href="https://www.ics.uci.edu/~aburtsev/238P/2020spring/index.html">CS 238P</a>, Operating Systems, with <a href="https://users.cs.utah.edu/~aburtsev//">Anton Burtsev</a> at <a href="https://uci.edu/">University of California, Irvine</a>, Spring 2020.
  </li>
<li>
    TA, <a href="https://cse.buffalo.edu/~stevko/courses/cse486/spring19/"> CSE 486/586</a>, Distributed Systems, with <a href="https://steveyko.github.io/">Steven Y. Ko</a> at <a href="https://www.buffalo.edu/">University at Buffalo</a>, Spring 2019.
  </li>
</ul>
