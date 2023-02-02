# Symbolic Execution - All In One

## Table of Contents
* [Papers](https://github.com/XD3an/symbolic-execution-all-in-one#Papers)
* [Videos](https://github.com/XD3an/symbolic-execution-all-in-one#Videos)
* [Tools](https://github.com/XD3an/symbolic-execution-all-in-one#Tools)

## Papers
* [Symbolic execution and program testing](https://dl.acm.org/doi/10.1145/360248.360252), Communications of the ACM, James C. King
* [Symbolic execution for software testing: three decades later](https://dl.acm.org/doi/10.1145/2408776.2408795), Communications of the ACM, Cristian Cadar, Koushik Sen
* [A Survey of Symbolic Execution Techniques](https://dl.acm.org/doi/10.1145/3182657), ACM Computing Surveys, Roberto Baldoni, Emilio Coppa, Daniele Cono D’elia, Camil Demetrescu, Irene Finocchi
* [SOK: (State of) The Art of War: Offensive Techniques in Binary Analysis](https://ieeexplore.ieee.org/document/7546500), 2019 International Conference on Communications, Signal Processing and Networks (ICCSPN)
    * angr

## Videos
* [Symbolic execution Lecture (6.858 Fall 2014 Lecture 10: Symbolic execution)](https://www.youtube.com/watch?v=mffhPgsl8Ws&ab_channel=NickolaiZeldovich)

## [Tools](https://github.com/ksluckow/awesome-symbolic-execution#tools)

### Java

* [Symbolic PathFinder (SPF)](https://babelfish.arc.nasa.gov/trac/jpf/wiki/projects/jpf-symbc): Symbolic execution tool built on [Java PathFinder](https://babelfish.arc.nasa.gov/trac/jpf/). Supports multiple constraint solvers, lazy initialization, etc.
* [JDart](https://github.com/psycopaths/jdart): Dynamic symbolic execution tool built on [Java PathFinder](https://babelfish.arc.nasa.gov/trac/jpf/). Supports multiple constraint solvers using [JConstraints](https://github.com/psycopaths/jconstraints).
* [CATG](https://github.com/ksen007/janala2): Concolic execution tool that uses [ASM](http://asm.ow2.org/) for instrumentation. Uses CVC4.
* [LimeTB](http://www.tcs.hut.fi/Software/lime/): Concolic execution tool that uses [Soot](https://sable.github.io/soot/) for instrumentation. Supports [Yices](http://yices.csl.sri.com/) and [Boolector](http://fmv.jku.at/boolector/). Concolic execution can be distributed.
* [Acteve](https://code.google.com/archive/p/acteve/): Concolic execution tool that uses [Soot](https://sable.github.io/soot/) for instrumentation. Originally for Android analysis. Supports [Z3](https://github.com/Z3Prover/z3).
* [jCUTE](http://osl.cs.illinois.edu/software/jcute/): Concolic execution tool that uses [Soot](https://sable.github.io/soot/) for instrumentation. Supports [lp_solve](http://lpsolve.sourceforge.net/).
* [JFuzz](http://people.csail.mit.edu/akiezun/jfuzz/): Concolic execution tool built on [Java PathFinder](https://babelfish.arc.nasa.gov/trac/jpf/).
* [JBSE](http://pietrobraione.github.io/jbse/): Symbolic execution tool that uses a custom JVM. Supports CVC3, CVC4, Sicstus, and Z3.
* [Key](https://www.key-project.org/): Theorem Prover that uses specifications written in Java Modeling Language (JML).


### LLVM

* [KLEE](http://klee.github.io/): Symbolic execution engine built on LLVM.
* [Cloud9](http://cloud9.epfl.ch/): Parallel symbolic execution engine built on KLEE.
* [Kite](http://www.cs.ubc.ca/labs/isd/Projects/Kite/): Based on KLEE and LLVM.
* [SymCC](https://github.com/eurecom-s3/symcc): A compiler wrapper which embeds symbolic execution into the program during compilation, and an associated run-time support library.

### .NET

* [PEX](http://pex4fun.com/About.aspx): Dynamic symbolic execution tool for .NET.


### C

* [CREST](https://github.com/jburnim/crest): is an open-source tool for concolic testing of C programs.
* [Otter](https://bitbucket.org/khooyp/otter/): is a pure, source-level symbolic executor for C that can be used to test programs.
* [CIVL](http://vsl.cis.udel.edu/civl/): A framework that includes the CIVL-C programming language, a model checker and a symbolic execution tool.


### JavaScript

* [Jalangi2](https://github.com/Samsung/jalangi2): Dynamic analysis framework for JavaScript.
* [SymJS](https://doi.org/10.1145/2635868.2635913): Automatic symbolic testing of JavaScript web applications.


### Python

* [CrossHair](https://github.com/pschanely/CrossHair): Symbolic execution tool for verifying properties of Python functions.
* [PyExZ3](https://github.com/thomasjball/PyExZ3): Symbolic execution of Python functions. A rewrite of the [NICE](https://code.google.com/archive/p/nice-of) project's symbolic execution tool.


### Ruby

* [Rubyx](https://www.cs.umd.edu/~avik/papers/ssarorwa.pdf): Symbolic execution tool for Ruby on Rails web apps.


### Android

* [SymDroid](https://www.cs.umd.edu/sites/default/files/scholarly_papers/QianwenLi_1.pdf): A Symbolic Executor to Identify Activity Permission in Android Application.


### Binaries

* [Mayhem](https://users.ece.cmu.edu/~aavgerin/papers/mayhem-oakland-12.pdf).
* [SAGE](https://patricegodefroid.github.io/public_psfiles/ndss2008.pdf): Whitebox file fuzzing tool for X86 Windows applications.
* [DART](https://dl.acm.org/doi/10.1145/1064978.1065036):is the first concolic testing tool that combines dynamic test generation.  
* [BitBlaze](http://bitblaze.cs.berkeley.edu/): Binary Analysis for Computer Security.
* [PathGrind](https://github.com/codelion/pathgrind): Path-based dynamic analysis for 32-bit programs.
* [FuzzBALL](http://bitblaze.cs.berkeley.edu/fuzzball.html): Symbolic execution tool built on the BitBlaze Vine component.
* [S2E](http://s2e.systems/): Symbolic execution platform supporting x86, x86-64, or ARM software stacks.
* [miasm](https://github.com/cea-sec/miasm): Reverse engineering framework. Includes symbolic execution.
* [pysymemu](https://github.com/feliam/pysymemu/): Supports x86/x64 binaries.
* [BAP](https://github.com/BinaryAnalysisPlatform/bap): Binary Analysis Platform provides a framework for writing program analysis tools.
* [angr](http://angr.io/): Python framework for analyzing binaries. Includes a symbolic execution tool.
* [Triton](https://triton.quarkslab.com/): Dynamic binary analysis platform that includes a dynamic symbolic execution tool.
* [manticore](https://github.com/trailofbits/manticore): Symbolic execution tool for binaries (x86, x86_64 and ARMV7) and Ethereum smart contract bytecode.
* [MAAT](https://github.com/trailofbits/maat): Low-level symbolic execution tool, uses Ghidra's p-code.  
* [BinCAT](https://github.com/airbus-seclab/bincat): Binary code static analyser, with IDA integration. Performs value and taint analysis, type reconstruction, use-after-free and double-free detection.


### Misc

* [Symbooglix](https://github.com/symbooglix/symbooglix): Symbolic execution tool for Boogie programs.

## Further reading

* [awesome-symbolic-execution](https://github.com/ksluckow/awesome-symbolic-execution)
#
