# Validation reflection — arother1

Validating Connor Finley's ten assigned projects first required checking the
underlying data. The summary export mislabeled unrelated commits as OpenSphere,
while CausalInference.jl was absent from the final stats and reflections. Joining
the original project/SHA mapping to commit content restored these histories;
deduplicating SHA values prevented inflated counts. Among nine available paired
labels per field, agreement was 88.9% for HasRecovered, 55.6% for WhyRecovered,
and 11.1% for ActivityPattern. ActivityPattern's Cohen's kappa was 0.027. The main
interpretive difference was distinguishing persistent decline from irregular
bursts: OpenCog's annual volume fell from 4,658 commits in 2015 to 112 in 2020
and 19 in 2022. In contrast, libNeuroML's increase from 12 commits in 2020 to 233
in 2021 and 276 in 2022 supported a U-shaped interpretation.

Long gaps were sometimes preceded by stabilization work or migration signals.
OpenCog's pre-gap messages pointed to replacement repositories; BEDOPS had
completed targeted fixes. Recovery involved different kinds of work: Delly
resumed alignment features, NILMTK corrected installation documentation, and
BEDOPS prepared release-related patches. Reviewer-selected labels retain these
observations without treating inferred motivation as proven. For BEDOPS, the
resolution removes the unsupported claim of a scheduled release. For libNeuroML,
it combines the initial README update with the schema/version milestone 40 days
later. Every corrected history contains commits after its longest internal gap,
so gaps did not imply permanent project death. OpenSphere recovered historically
but was Inactive at September 30, 2025; OpenCog was Active under the six-month
commit rule despite its declining volume and obsolete code.

Recurring pitfalls included treating a display-name change as a new contributor,
counting human CI changes as bot work, and classifying generic merges as feature
development. OpenCog's pre- and post-gap author names shared an email, supporting
maintainer continuity. Missing author labels were also kept separate from actual
disagreements: 23 unavailable labels were excluded from paired statistics.
Final reviewer determinations are recorded in AdjudicatedValue; joint agreement
was not measured, so post-discussion statistics are NA. HasRecovered kappa is NA
because one author label falls outside the yes/no codebook and the remaining
valid pairs are uniformly Yes, making kappa undefined. WoC samples can include
non-default branches, so recent-theme judgments describe the available historical
snapshot. Connor's reverse-direction validation log is included as received;
its blank project IDs prevent pairing its records with individual projects,
so it is not used in these statistics. These conventions keep the coding and
agreement measures tied to the evidence actually available.
