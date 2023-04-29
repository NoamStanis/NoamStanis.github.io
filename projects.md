---
layout: inner
title: Projects
permalink: /projects/
---

Projects
----------

**Performance Modeling for Large-Scale Linear Applications**

Sandia
 
 &nbsp; 
 &nbsp;
 
**HPC Optimization Using Hyper-Threading**

My NSF REU project at [South Dakota State](https://www.sdstate.edu/mechanical-engineering/research-experience-undergraduates) from summer 2021. Read the abstract and poster below:


Poster:
![](img/projects/REU_POSTER.jpg)

Abstract: Intel’s Hyper-Threading Technology is an implementation of simultaneous multi-threading upon Intel proprietary CPU architecture. This technology allows for a single CPU core to handle two distinct processes concurrently, with the end-user and operating system recognizing the single core as two “logical processors.” Under certain conditions, this technology can improve processing speed by thirty percent. The goal of this research is to determine the potential performance boosts or degradations exist when utilizing Hyper-Threading in a high performance computing cluster environment. Hyper-Threading technology introduces a multitude of additional possible bottlenecks and runtime slow downs via the added logical cores, and isolating these issues when possible to improve performance can be crucial in large scale applications. The central hypothesis of this work is that heavily parallelized or multi-threaded applications will see increased performance from Hyper-Threading, while processes that must be run in serial will experience little to no computational benefit. The project strategy is to re-examine
and retest the earlier findings of T. Leng et al. conducted at Dell in 2002 using our small-scale development high performance computing cluster. Our data collection relies on two types of software: cluster computing benchmarks and a performance analysis tool evaluating said benchmarks performance. In this case, we have used four benchmarking programs: High Performance Linpack and the EP (Embarrassingly Parallel), IS (Integer Sort), and FT (Fourier Transform) benchmarks from the NAS Parallel Benchmark suite.
All of these applications are monitored by Intel’’s VTune Profiler for performance analysis, which determines statistics such as multi level cache misses, cycle per instruction retired, and total number of floating-point instructions. By utilizing these software and our cluster architecture it is determined that Hyper-Threading is a worthwhile technology for cluster computing if optimized parallel programs are being run.

