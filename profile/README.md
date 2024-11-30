<div align="center">
<img src="unum-poster.png"/>
</div>

<h3 align="center">
Cloud Infrastructure Designed to Scale
</h3>

<div align="center">

<p align="center">
<a href="https://discord.gg/4mxGrenbNt"><img height="25" src="https://github.com/unum-cloud/.github/raw/main/assets/discord.svg" alt="Discord"></a>
&nbsp;&nbsp;&nbsp;
<a href="https://www.linkedin.com/company/unum-cloud/"><img height="25" src="https://github.com/unum-cloud/.github/raw/main/assets/linkedin.svg" alt="LinkedIn"></a>
&nbsp;&nbsp;&nbsp;
<a href="https://twitter.com/unum_cloud"><img height="25" src="https://github.com/unum-cloud/.github/raw/main/assets/twitter.svg" alt="Twitter"></a>
&nbsp;&nbsp;&nbsp;
<a href="https://unum.cloud/blog"><img height="25" src="https://github.com/unum-cloud/.github/raw/main/assets/blog.svg" alt="Blog"></a>
&nbsp;&nbsp;&nbsp;
<a href="https://www.youtube.com/watch?v=ybWeUf_hC7o"><img height="25" src="https://github.com/unum-cloud/.github/raw/main/assets/youtube.svg" alt="Youtube"></a>
&nbsp;&nbsp;&nbsp;
<a href="https://github.com/unum-cloud/"><img height="25" src="https://github.com/unum-cloud/.github/raw/main/assets/github.svg" alt="GitHub"></a>
</p>
</div>

<hr>

What if we could redesign the cloud from the ground up?

1.	We would realize that the foundation of the modern cloud stack is small and can be maintained by a tiny team.
2.	Despite being fast, networking isn't free. The concept of "disaggregated storage and compute" is great for convenience but not for software efficiency.
3.	Even the best compilers struggle to vectorize high-level code, resulting in approximately 10× lower hardware utilization for computational workloads.
4.	Most operating systems have custom mechanisms to accelerate I/O that are unused by 99% of modern software, leading to about 10× higher latency for networking and storage.
5.	Data-center servers often feature purpose-built accelerators, meaning a single simple build toolchain is unlikely to handle bleeding-edge heterogeneous software.
6.	Reimplementing solutions in every language isn't feasible. An abundant language with a well-defined committee and strong industry support, like C99 and C++17, should be used.
7.	Consolidating all cloud technology into a mono-repo increases component interdependencies, hindering the adoption of individual parts. A modular design with clear isolation is preferable.

Since 2015, Unum has been striving to meet all these conditions.
We have developed a unified framework consisting of concise, low-level implementations for storage, computing, and AI modeling systems, all designed with efficiency in mind.
This endeavor compelled us to build our own liquid-cooled clusters for R&D, collaborate closely with multiple cloud providers, and implement assembly-level optimizations often unique in the software industry.

Today, some of our projects run on hundreds of millions of devices, trusted by unicorns, decacorns, trillion-dollar tech companies, governments, and even intelligence agencies.
Our primary goal is to power the next generation of computing, focusing on applications in AI and computational science.
Since 2022, we've been increasingly open-sourcing our work and look forward to sharing much more soon!

<hr/>

> <sup>1</sup>
> Most database management systems are built on top of just a few key-value stores, like RocksDB.
> Proximity graphs and algorithms like HNSW can replace most indexing data structures.
> Most networking is built on top of TCP/IP and relies on just a few algorithms.
> Similar statements hold true for numeric libraries, machine learning frameworks, and even the models built on top of them.
> <sup>2</sup>
> InfiniBand is now powering the majority of Top-500 supercomputers, and Remote Direct Memory Access systems provide convenient abstractions for users, but their latency is still orders of magnitude higher than accessing local memory.
> <sup>3</sup>
> Our optimizations encompass SIMD instructions across AVX2, AVX-512 generations, NEON, SVE, SVE2, Intel and Apple AMX variants, SME, WMMA, and other NVIDIA extensions.
> <sup>4</sup>
> We utilize SPDK, DPDK, and io_uring for Linux kernel bypass.
> <sup>5</sup>
> The last 10 years of attempts to build heterogeneous compilers, like SyCL, have failed, so multiple tools have to be used in conjunction.
> <sup>6</sup>
> Many mechanisms exist for implementing language bindings.
> Unum generally focuses on Python, Rust, and JavaScript as the primary languages in machine learning and the web.

<!--
<div align="center">

<a href="https://github.com/unum-cloud/usearch"> <img src="https://img.shields.io/github/stars/unum-cloud/usearch?style=social&label=USearch"/> </a>
<a href="https://github.com/unum-cloud/ucall"> <img src="https://img.shields.io/github/stars/unum-cloud/ucall?style=social&label=UCall"/> </a>
<a href="https://github.com/unum-cloud/uform"> <img src="https://img.shields.io/github/stars/unum-cloud/uform?style=social&label=UForm"/> </a>
<a href="https://github.com/unum-cloud/ustore"> <img src="https://img.shields.io/github/stars/unum-cloud/ustore?style=social&label=UStore"/> </a>

<a href="https://www.youtube.com/watch?v=UMrhB3icP9w&list=PL2kcrNAeGTFzZbccNB3P_xruYPskMmwRT&index=4&t=65s"> <img alt="" src="https://img.shields.io/youtube/views/UMrhB3icP9w?label=USearch"> </a>
<a href="https://www.youtube.com/watch?v=ybWeUf_hC7o&list=PL2kcrNAeGTFzZbccNB3P_xruYPskMmwRT&index=2"> <img alt="" src="https://img.shields.io/youtube/views/ybWeUf_hC7o?label=UStore"> </a>
  
<a href="https://github.com/unum-cloud/examples">Examples</a>
•
<a href="https://github.com/unum-cloud/awesome/blob/main/Workflow.md">Contributing</a>
•
<a href="https://github.com/unum-cloud/ucsb">UCSB</a> Storage Benchmarks
•
<a href="https://github.com/unum-cloud/udsb">UDSB</a> Analytics Benchmarks
</div>
-->
