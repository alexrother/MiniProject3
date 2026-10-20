# Disagreement examples — arother1 and cfinley6

Project owner: Connor Finley (cfinley6). Validator: Alex Rother (arother1).
The following are reviewer determinations from the evidence; joint discussion
and agreement were not measured.

## 1. ngageoint_opensphere — HasRecovered

**Author:** N/A (No gap). **Validator:** Yes.

The summary export assigns unrelated commits to OpenSphere using the final loop
variable `prj`. Joining `df_commits.csv` to `df_commit_data.csv` by SHA restores
project membership and reveals seven zero-commit months, April–October 2017.
Commits `ae076a8f54` and `c6fb78c10a` resume time-filter feature work on
November 20, 2017.

**Reviewer resolution:** ValidatorKept; Yes. Activity resumed after the longest
internal gap, even though the project was Inactive at the assessment cutoff.

## 2. neuralensemble_libneuroml — ActivityPattern

**Author:** steady. **Validator:** U-shaped.

Unique annual commits decline from 310 in 2013 to 23 in 2019 and 12 in 2020,
then increase to 233 in 2021 and 276 in 2022. This supports the coding guide's
U-shaped definition: decline followed by recovery. A low number of long gaps
alone does not establish steady activity.

**Reviewer resolution:** ValidatorKept; U-shaped, based on the broad historical
trajectory despite the later slowdown to 150 commits in 2024.

## 3. bedops_bedops — WhyRecovered

**Author:** Recovery occurred to prepare a scheduled release.
**Validator:** Release preparation is supported; a schedule is not established.

April 10, 2025 commits describe general release preparation (`f878c638fb`), a
zlib version update (`51d2adac6a`), and Starch-related patches (`d4d6f4fce3`).
These messages explain the work following the 14-month gap without proving a
planned release date or recurring schedule.

**Reviewer resolution:** Compromise: “Maintenance resumed for release
preparation, Starch-related patches, and a zlib update; a release-related trigger
is inferred from the commit messages.”
