# Topics

Where each topic lives. Owned by `/organize`; `/integrate` appends to it.
What earns a chapter, a section and a subsection: `.claude/ORGANIZATION.md`.

<!-- INFERENCE, not a plan, and written after the fact. 21-603 ran in Fall 2025 and
     these notes were taken before this file existed, so the outline below is read
     off the sources rather than accumulated lecture by lecture, and the usual
     per-line lecture dates are not recoverable. Treat the structure as observed,
     not as endorsed: nobody has yet run /organize over it.

     The shape reads as: first-order model theory built up from scratch in chapter 1,
     with submodels as the load-bearing idea, then abstract elementary classes in
     chapter 2 as the generalization the course was heading for all along, arriving at
     Erdos-Rado. That is a coherent arc and mostly matches the corpus. The next run
     should feel free to disagree. -->

## 1. An Introduction to Model Theory  ->  `Chapters/1_Intro/`

```
1.1 A Crash Course on First-Order Logic                      [date not recorded]
    The vocabulary everything else is stated in.             1_1_FOL.tex, 313 lines
    1.1.1 Languages and Structures
    1.1.2 Syntax: Terms, Formulae, Sentences and Theories
    1.1.3 Semantics: Satisfaction
    1.1.4 Elementary Equivalence
    1.1.5 Deduction and Proof
1.2 Cardinality and Categoricity                             [date not recorded]
    What counting models buys you.                           1_2_Card_Cat.tex, 105 lines
    1.2.1 The Spectrum Problem
    1.2.2 Cardinal Arithmetic
1.3 A Word on Submodels                                      [date not recorded]
    The chapter's centre of gravity: when one structure      1_3_Submodels.tex, 344 lines
    sits inside another and what survives the inclusion.
    1.3.1 Submodel Existence
    1.3.2 Elementary Submodels
    1.3.3 The Tarski-Vaught Test
    1.3.4 Chains of Substructures
    1.3.5 Restrictions and Expansions        <- carries an author TODO; see below
    1.3.6 The Löwenheim-Skolem Theorems
    1.3.7 Complete and Elementary Diagrams
1.4 Models of Peano Arithmetic                               [date not recorded]
    The worked example the general theory was for.           1_4_Peano.tex, 161 lines
    1.4.1 The Language and Theory of Peano Arithmetic
    1.4.2 Existence of Non-Standard Models of Peano Arithmetic
    1.4.3 Famous Results on Peano Arithmetic
    1.4.4 True Arithmetic and the Twin Prime Conjecture
```

`Chapters/1_Intro/` is the author's directory name for chapter 1 across three of the
four sibling repositories, whatever that chapter is titled. It is a convention, not
template residue. Leave it.

## 2. Abstract Elementary Classes  ->  `Chapters/2_AEC/`

```
2.1 A Word on Infinitary Logic                               [date not recorded]
    The language chapter 1's tools stop covering.            2_1_Infinitary_Logic.tex, 48 lines
    2.1.1 The Syntax and Semantics of $L_{\omega_1, \omega}$
    2.1.2 New Languages using Infinite Cardinals
2.2 The Basics of Abstract Elementary Classes                [date not recorded]
    The axiomatization itself.                               2_2_AECs.tex, 167 lines
    2.2.1 The Intuition of Abstract Elementary Classes
    2.2.2 Decomposing Uncountable Models into Countable Elementary Submodels
2.3 The Erdős-Rado Theorem                                   [date not recorded]
    The combinatorial engine, reached via types.             2_3_Galois.tex, 335 lines
    2.3.1 Une Perspective Galoisienne
    2.3.2 Pigeons and Holes - A Study in Regularity
    2.3.3 Ramsey and Sierpiński Join the Fray
    2.3.4 The Main Result
```

The file is `2_3_Galois.tex` while the section is titled *The Erdős-Rado Theorem*.
That is not a stale name: the section reaches Erdős-Rado through types, by an approach
the opening subsection calls *Une Perspective Galoisienne*. Both names describe it.

## Appendices  ->  `Chapters/Appendices/`

```
A A List of Interesting Quotes by Rami Grossberg             [date not recorded]
    A.1 Mathematical Insights                                A_First_Appendix.tex, 21 lines
    A.2 Beyond the Mathematical
```

**Written but not rendered.** `\input{Chapters/Appendices/Appendices.tex}` is
commented out in `main.tex`, which is the template's default, so this content does not
appear in the published PDF. It is real content rather than scaffolding, so the
comment-out is more likely to have gone unrevisited than to be deliberate — but that
is the author's call, not a skill's.

## Deliberate deviations

Nothing recorded. Nothing here has been through `/organize`, so an apparent deviation
is at present more likely to be an unreviewed accident than a tolerated one.

Worth noting for whoever runs it first: 1.3 carries seven subsections in 344 lines,
which is at the top of the corpus range for a section but not outside it —
LieAlgebrasNotes' *Important Definitions and First Examples* carries ten. Size is not
the test. The question is whether submodel existence, elementary submodels, the
Tarski-Vaught test, chains, restrictions, Löwenheim-Skolem and diagrams are one line
of enquiry or two, and that is answered by reading them, not by counting them.

## Signposted

Topics a lecture pointed at without reaching. Nothing recorded — the lecture notes
this would have been built from were taken before this file existed.

## Unplaced

Nothing.

## Structural pressure

What `/integrate` noticed but is not allowed to fix. Each entry is a standing
recommendation to run `/organize`.

```
1_3_Submodels.tex:227 carries an author TODO, inline:

    \subsection{Restrictions and Expansions} % Move to section on submodels!!!!

  The subsection is already inside "A Word on Submodels", so either the move was
  made and the comment outlived it, or it was written when the material sat
  elsewhere. Resolve it by reading the subsection rather than by deleting the
  comment: if it belongs where it is, the comment goes; if it was meant for a
  finer-grained destination, that is a real /organize finding.

39 \sorry markers, unevenly spread -- 11 in 1_3_Submodels.tex, 8 in 2_3_Galois.tex.
  Not structural pressure as such, but it is where the notes are least finished, and
  /fill-sorries is the skill for it.
```

## Template scaffolding

None left under `Chapters/`. Both chapters and the appendix carry real content.
