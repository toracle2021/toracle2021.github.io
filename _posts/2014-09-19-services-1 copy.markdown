---
layout: default
category: Services
title: Keynote<br>
description: |
---
![](../img/alastair-donaldson.jpg)

[Prof. Alastair Donaldson](https://www.imperial.ac.uk/people/alastair.donaldson), Imperial College London, UK

August 24, 10:10 - 11:10 EEST (UTC +3) 

**Title:** Oracles, Test Case Reduction and Undefined Behaviour in Randomized Testing

**Abstract:** Randomized testing is a cheap and effective technique for finding bugs in or increasing test coverage of software systems. It involves running a system under test (SUT) on an endless stream of inputs that are either randomly generated from scratch, or randomly mutated based on existing inputs. For randomized testing to be useful, a test oracle must be available: an oracle is essential for finding bugs, and new tests that improve coverage serve little purpose if we cannot determine whether they pass or fail. Randomized testing also requires a means for shrinking generated test cases to a size that makes them actionable: a test case that exposes a bug must be small enough to facilitate debugging, while a test case that achieves new coverage must be simple enough that it can be added to a regression test suite. I will first give an overview of arguably the most successful application of randomized testing: fuzzing for security-critical vulnerabilities in C++ programs. This is a sweet spot because the bugs detected are critical, the rules of the programming language provide a general-purpose oracle, and test case reduction is relatively straightforward. I will then explain why the oracle and test case reduction problems are much harder when using randomized testing to find functional errors, and why undefined behaviour exacerbates both problems. Finally, I will give examples from my recent work (with collaborators) of how metamorphic testing can be used to circumvent the oracle problem, provide easy test case reduction, and facilitate finding bugs and generating high coverage test suites, in the domains of compilers and software libraries.

**Bio:** Alastair Donaldson is a Professor in the Department of Computing at Imperial College London and a Visiting Researcher at Google. At Imperial he leads the Multicore Programming Group, investigating novel techniques and tool support for programming, testing and reasoning about highly parallel systems. He was Founder and Director of GraphicsFuzz Ltd., a start-up company specialising in metamorphic testing of graphics drivers, which was acquired by Google in 2018. He was the recipient of the 2017 BCS Roger Needham Award and has published 90+ articles on programming languages, formal verification, software testing and parallel programming.  Alastair was previously a Visiting Researcher at Microsoft Research Redmond, an EPSRC Postdoctoral Research Fellow at the University of Oxford and a Research Engineer at Codeplay Software Ltd.  He holds a PhD from the University of Glasgow, and is a Fellow of the British Computer Society.
  
