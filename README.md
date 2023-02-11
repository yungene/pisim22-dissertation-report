### pisim22-dissertation-report
This repository contains my MCS dissertation report. There is a separate repository with the source code of the tool produces as a part of my dissertation work -- [pisim22](https://github.com/yungene/pisim22).

### Details
<b>Title</b>: An Algorithm and Implementation of Equivalence Checking in Pi-Calculus through Fresh-Register Automata

<b>Author</b>: Jevgenijus Čistiakovas

<b>Supervisor</b>:  Dr. Vasileios Koutavas

<b>Venue</b>:  University of Dublin, Trinity College

<b>Date</b>: April 2022

<b>Abstract</b>: 

Mobile concurrent systems permeate the world. Their often great importance means that errors in their designs can carry significant consequences. For guaranteeing correctness, formal verification methods are used. One particular approach is equivalence checking, where a design or implementation is checked against a specification.

The π-calculus is a language for describing mobile concurrent systems. The semantics of a π-calculus model is given by a labelled transition system (LTS) that describes how the model can transition states when interacting with the environment. Usually, such LTSs are infinite. However, the formalism of fresh-register automata (FRAs) can be used to represent many infinite-state models finitely. 

This dissertation presents a solution to the problem of equivalence checking in π-calculus. It tackles the issue through an intermediate representation using the formalism of FRAs. The solution builds on prior work in generating LTSs of π-calculus models through the use of FRAs. To allow for equivalence checking in π-calculus an algorithm for n-bisimulation checking in the intermediate representation is proposed. The overall result corresponds to early bisimulation in π-calculus.

Furthermore, a command-line tool is created for practical equivalence checking of π-calculus models. The tool combines a modified version of the existing π-calculus-to-FRA translator with the implementation of the proposed algorithm. The tool supports both weak and strong early bisimulation checking. The tool is evaluated on the well-known examples from the literature and test cases from other similar tools. The results show that the approach is viable but is likely not practical for verifying large models

<b> Other copies </b> https://www.scss.tcd.ie/publications/theses/diss/2022/TCD-SCSS-DISSERTATION-2022-006.pdf
