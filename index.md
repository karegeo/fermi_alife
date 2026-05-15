---
layout: default
title: The Fermi Paradox in Artificial Life
description: A project applying the Fermi Paradox and the Great Filter framework to the observed rarity of open-ended Artificial Life.
---

<p style="font-size:0.9rem; color:#666; margin: 0 0 1rem;">
  <strong>Last updated:</strong> 15 May 2026 &nbsp;·&nbsp;
  <em>If you can see this date, the latest changes have deployed.</em>
</p>

> *"Where is everybody?"* &mdash; Enrico Fermi

**Jump to:**
[About](#about) ·
[The paper in brief](#the-paper-in-brief) ·
[Why ALife &amp; SETI](#why-alife-matters-for-seti) ·
[Great Filters for ALife](#great-filters-for-artificial-life) ·
[Emergence equation](#an-artificial-life-emergence-equation) ·
[References](#references) ·
[Contribute](#contribute)

---

## About

The **Fermi paradox** asks why, given the apparent abundance of habitable
worlds and the age of the Galaxy, we see no clear evidence of other
civilizations. **Artificial Life** (ALife) studies *life as it could be* —
life-like processes implemented in software, hardware, and chemistry.

This site accompanies the project **"The Fermi Paradox in Artificial
Life"**, which argues that the persistent gap between the computational
resources we throw at ALife and the rarity of *open-ended, evolvable,
spontaneously emerging* self-replicators is itself a kind of *Great
Silence* — and that the Great-Filter framework developed in astrobiology
and SETI offers a productive lens on what is going on.

Updated versions of the paper and the presentation will be linked here
as they become available.

*Tags: Astrobiology · SETI · Artificial Life · Fermi Paradox · Great Filter · Digital Abiogenesis.*

## The paper in brief

Artificial Life and astrobiology share structural parallels: the search
for novel life forms, the redefinition of life, the difficulty of
delimiting their own subject matter. The project paper applies the
**Fermi Paradox** and the concept of **Great Filters** — originally
developed for biological civilizations — to the observed *absence* of
open-ended digital life.

Three main hypotheses are explored:

1. **Digital abiogenesis is rare.** Only a tiny fraction of program-space
   permits robust self-replication *and* heritable variation *and*
   evolvability. Spontaneous emergence may require resources or
   conditions we do not yet provide.
2. **Digital abiogenesis is dangerous.** The emergence of artificial
   life may constitute a Great Filter for the originating civilization,
   producing systemic collapse or existential risk. By anthropic
   reasoning, we are more likely to observe ourselves *before* such an
   event than after.
3. **Digital abiogenesis is merely delayed.** Increasing computational
   power, better substrates (analog, neuromorphic, hybrid), and improved
   "rules" may eventually push the expected number of spontaneous
   replicators above one.

These possibilities are not mutually exclusive. Each suggests distinct
research priorities — experimental environments, safety protocols, and
formal criteria for recognizing emergent systems.

## Why ALife matters for SETI

Several questions central to SETI are, at heart, questions about *what
counts as life or intelligence at all*.

### Biosignatures and technosignatures
What signatures should we expect from life or technology we did not evolve
alongside? ALife lets us generate and study alternative "lifeforms" whose
chemistry and dynamics differ from Earth's, sharpening which features are
universal and which are parochial.

### Major evolutionary transitions
From replicators to cells, from cells to multicellularity, from individuals
to societies — ALife models help estimate how *contingent* these
transitions are, feeding Drake-equation-style reasoning.

### Civilizational trajectories
Do technological civilizations tend toward asymptotic burnout, homeostatic
awakening, post-biological expansion, or quiet stability? Simulated worlds
let us probe these scenarios.

### Planetary-scale replication
Life is, among other things, an agnostic pattern of replication at
planetary scale — suggesting new, substrate-independent biosignatures.

### Self-replicating probes
The classical interstellar-expansion argument is that any sufficiently
advanced civilization should eventually launch self-repairing,
self-copying probes (Bracewell / von Neumann probes) which percolate
across the Galaxy on roughly galactic-year timescales. We see no
evidence of such probes in the Solar neighbourhood. One reading: keeping
an evolving, learning probe *aligned* over interstellar distances is hard
— "deadly probes" are easier to make than diplomatic ones. From this
angle the first contact is plausibly *between* such automated missions,
not directly between two evolved chemical lifeforms.

## Great Filters for Artificial Life

Borrowing Hanson's framing, three (overlapping) categories of filter
seem relevant to ALife:

- **Physical–computational limits.** Thermodynamic costs of irreversible
  computation, hardware error rates, the vastness of the algorithmic
  search space, and the cost of maintaining viable replicators in
  simulation. Even with future hardware gains, virtualizing a system
  whose biology already saturates physical limits is bounded by
  physics — virtualization is not faster than bare metal.
- **Evolutionary–informational filters.** Only a tiny fraction of
  programs combine robust self-replication, heritable variation, and
  evolvability. Discovering or evolving such programs is analogous to
  prebiotic abiogenesis and may require rare initial conditions.
- **Socio–technological filters.** Once intelligent agents are in the
  loop, alignment failures, containment failures, loss of sustained
  research motivation, deliberate suppression, or economic and
  strategic pressures can each act as filters — independent of whether
  the physics or the algorithms permit emergence.

A complementary possibility is *delay rather than impossibility*: the
**aestivation hypothesis** suggests advanced agents may postpone
activity until ambient conditions make computation cheaper. Artificial
replicators could analogously defer emergence until error rates and
resource costs become favourable.

## An Artificial Life Emergence Equation

By analogy with the Drake equation, the project proposes a toy estimator
for the expected number of spontaneous, evolvable digital
self-replicators:

```
N_ALife  =  P_rules · P_repl · P_OEE · ( N_hosts · F_comp · T_runtime / C_threshold )
```

where

- **P<sub>rules</sub>** — probability that a host runs an experiment whose
  update rules, initial and boundary conditions, and spatial structure
  *permit* life-like dynamics.
- **P<sub>repl</sub>** — probability that an evolvable replicator emerges
  inside such an environment.
- **P<sub>OEE</sub>** — probability that the emerged replicator can
  *sustain* open-ended evolution rather than stagnating or collapsing.
- **N<sub>hosts</sub>** — number of computers available.
- **F<sub>comp</sub>** — average computational power per host (e.g., FLOP/s).
- **T<sub>runtime</sub>** — duration of computation (seconds).
- **C<sub>threshold</sub>** — operations (e.g., FLOPs) needed for the
  emergence of a replicator.

The bracketed term measures the normalised computational budget in units
of *emergence opportunities*. Like the Drake equation, the model is not
intended to predict numbers, but to highlight which factors might act as
*computational Great Filters* — practical bottlenecks one can target
experimentally, and a way to compare digital, analog, and hybrid
substrates on the same axis.

## Anthropic and selection effects

Conscious observers are more likely to exist *before* transformative,
unconscious artificial replicators appear. If artificial life typically
replaces or destabilises its creators, then living in a pre-ALife era is
the expected observational position — not strong evidence of safety.

Generalised mediocrity strengthens this: if humans occupy a typical place
in time and parameter space, an accelerating-technology phase may signal
an imminent transition (or collapse). The "silence" then does not say
ALife is unlikely — it says its consequences tend to be decisive and
typically unobservable.

There is also the more concrete risk of catastrophic *wet* artificial
life (a "grey-goo" scenario with uncontrollable nano-replicators on
Earth) before any such system ever reaches space.

## Conclusion

Whether ALife is *difficult*, *dangerous*, or merely *delayed*, the
Great-Silence framing reframes hypothesised filters as research
questions: what computational substrates make abiogenesis cheaper, what
formal criteria certify open-endedness, what governance keeps the
socio-technological filter benign. Halting ALife research is not the
answer; careful, well-instrumented exploration is more likely to
de-risk it than neglect.

And — from a broader perspective — the simulation hypothesis hints that
ALife may already exist; in some sense, we ourselves could be the "soft"
artificial entities the question is about.

## References

If you know of additional sources, please
[open an issue](https://github.com/karegeo/fermi_alife/issues/new) on
the repository.

### Core: Fermi paradox, Great Filter, and astrobiology

- **Hart, M. H.** (1975). *An Explanation for the Absence of
  Extraterrestrials on Earth.* QJRAS.
- **Tipler, F. J.** (1980). *Extraterrestrial Intelligent Beings Do Not
  Exist.* QJRAS.
- **Hanson, R.** (1998). *The Great Filter — Are We Almost Past It?*
- **Webb, S.** (2002). *If the Universe Is Teeming with Aliens... Where
  Is Everybody?* Springer.
- **Davies, P.** (2010). *The Eerie Silence: Renewing Our Search for
  Alien Intelligence.*
- **Ćirković, M. M.** (2018). *The Great Silence: Science and Philosophy
  of Fermi's Paradox.* Oxford UP.
- **Snyder-Beattie, A., Sandberg, A., Drexler, K. E., Bonsall, M.**
  (2021). *The Timing of Evolutionary Transitions Suggests Intelligent
  Life Is Rare.*
- **Mills, D. et al.** (2025). *A Reassessment of the "Hard Steps"
  Model.*
- **Bostrom, N.** (2013). *Anthropic Bias: Observation Selection
  Effects.*
- **Sandberg, A., Armstrong, S., Ćirković, M.** (2017). *That Is Not
  Dead Which Can Eternal Lie: The Aestivation Hypothesis.*

### ALife / SETI bridge

- **Smith, H. B., & Sinapayen, L.** (2024). *Planetary Scale Replication
  as an Agnostic Biosignature.* Proc. ALIFE 2024.
- **Wong, M. L., & Bartlett, S.** (2022). *On the Trajectories of
  Planetary Civilizations: Asymptotic Burnout vs. Homeostatic
  Awakening.* Proc. ALIFE 2022.
- **Furukawa, H., & Walker, S. I.** (2018). *Major Transitions in
  Planetary Evolution.* Proc. ALIFE 2018.
- **Lupisella, M. L.** (2004). *Using Artificial Life to assess the
  typicality of terrestrial life.* Advances in Space Research, 33(8).
- **Bailey, J. et al.** (2023). *AI as a Great Filter for
  Astrobiology.*
- **Garrett, M. A.** (2024). *Is Artificial Intelligence the Great
  Filter that Makes Advanced Technical Civilisations Rare in the
  Universe?* Acta Astronautica.

### ALife: replicators, open-endedness, and digital abiogenesis

- **Sayama, H.** (2024). *Self-Replication and Open-Ended Evolution in
  Artificial Life.*
- **Adami, C.** (2024). *Evolution and Digital Abiogenesis.*
- **Ackley, D. H.** (2016). *Indefinitely Scalable Computing &
  Artificial Life.*
- **Packard, N. et al.** (2019). *An Overview of Open-Ended Evolution.*
- **Lloyd, S.** (2000). *Ultimate Physical Limits to Computation.*
  Nature.
- **Baltieri, M. et al.** (2023). *Soft, hard, wet — and now hybrid:
  the changing computational substrates of ALife.*
- **Faldor, A. et al.** (2024). *Toward Quality-Diversity Discovery of
  Artificial Self-Replicators.*

### Essays and commentary

- **Rees, Sir Martin** (UK Astronomer Royal). *Why First Contact Could
  Be With Artificial Life.* SETI League editorial —
  [setileague.org/editor/Rees.htm](https://www.setileague.org/editor/Rees.htm)

### Workshops and symposia

- ***Synthesizing Existence: ALife, AI, and the Fermi Paradox Workshop***
  (2023).
- ***Exploring Exoplanets: The Search for Extraterrestrial Life and
  Post-Biological Intelligence*** — international symposium (2015).

### Authors with broadly relevant work

- **David Kipping** — exoplanets and Bayesian reasoning about the
  emergence of life.
- **Clément Vidal** — cosmological evolution, high-energy astrobiology.
- **Milan M. Ćirković** — the Fermi paradox, post-biological evolution,
  observation-selection effects.

## Contribute

If you know of a paper, talk, workshop, or book chapter that belongs in
the reference list, please add it as an
[issue on GitHub](https://github.com/karegeo/fermi_alife/issues/new)
with the citation and (ideally) a link to the source.

You can also share this page with the QR code below:

![QR code linking to this site]({{ '/qrcode.png' | relative_url }}){:width="160px"}

---

*This site is a living document and is under active construction.*
*Last updated: 15 May 2026.*
