# Real Analysis

In this book, the order of description is chosen for the ease of theoretical understanding, and is not the same as that of real analysis procedure. To make that diffence clearer, we give here a brief description of the latter, as well as to declare the current coverage [^1] of `Molass Library` there.

Analysis of SEC-SAXS experiment data involves several steps. To list a simplest course for discussion here:

1. Circular Average
2. Background Subtraction
3. `Trimming`
4. `Baseline Correcction`
5. `Low Rank Factorization`
6. `Rg Estimation - Guinier Plot` {cite:p}`Guinier_1939`
7. `Shape Inspection - Kratky Plot` {cite:p}`Kratky_1963`
8. Electron Density Estimation

among which `Molass Library` currently supports only steps 3-7. For the first two steps, `SAngler` {cite:p}`Shimizu:2016` can be used, while `DENSS` {cite:p}`Grant:2018` is available for the last. For all those steps, there already exist alternative software tools with various coverage. The most comprehensive and popular tool is `ATSAS` {cite:p}`Manalastas-Cantos:ge5081`, which is proprietary (closed-source) and consists of a standard SAXS suite of command line interface programs for each responsible step, coupled with GUI programs for them. Other tools include `BioXTAS RAW` {cite:p}`Hopkins:jl5075`, which is an open-source GUI application for running such executable modular programs, some of which are open-source and others of which include the ATSAS suite. In such a semi-closed state of tools for SEC-SAXS experiments, `Molass Library` is expected to help researchers better understand, improve, and utilize their tools by making larger part of the tools more open and flexible together with the Python ecosystem.

[^1]: As stated in the text, the coverage is shown as `colored steps 3-7`.