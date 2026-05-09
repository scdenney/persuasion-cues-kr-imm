# Persuasion and Prejudice: Are South Korean Attitudes Toward Immigration Open to Change?

This repository hosts the working paper "Persuasion and Prejudice: Are South Korean Attitudes Toward Immigration Open to Change?"

## Authors

- **Steven Denney** (Leiden University)
- **Isa van Dam** (Leiden University)
- **Christopher Green** (Leiden University)

## Project overview

The paper asks whether the pro-immigration frames the South Korean executive has actually used since 2018 — economic-growth and demographic-decline cues — move public support for liberalisation, and whether they reduce the origin- and religion-based penalties that structure South Korean preferences over which immigrants should be admitted. We field a nationally representative survey experiment (n = 1,999, January 2024) that crosses three between-subjects framing arms with a forced-choice conjoint of immigrant-admission profiles.

**Keywords:** immigration, persuasion, framing, conjoint experiment, status-quo activation, ethnic restoration, South Korea

## Methodology

- **Framing experiment**: three between-subjects arms (control / economic-growth cue / fertility-crisis cue), with a single-choice policy-preference dependent variable (increase / maintain / decrease the foreign-born population).
- **Forced-choice conjoint**: ten paired-profile tasks per respondent across eleven attributes (country of origin, ethnicity, occupation, Korean language, religion, sex, marital status, age, years in Korea, employment history, Korea visit history). The persuasion cue is reinforced after the fourth task.
- **Sample**: 1,999 native-born South Korean respondents, recruited via Qualtrics in January 2024, post-stratified to Statistics Korea marginals on age, sex, education, and region.
- **Estimation**: multinomial logistic regression for the policy-preference outcome (with bootstrap confidence intervals and TOST equivalence tests against a 5-percentage-point smallest effect size of interest); cregg-based AMCEs and marginal means for the conjoint, with respondent-clustered standard errors and survey weights.

## Key findings

The paper reports two intervention effects that revise the standard "framing fails on immigration" reading.

1. **The growth cue polarises along ideological lines.** Centrists and conservatives consolidate Maintain by about 11 percentage points each, while progressives more than double their share selecting Decrease (9.8% to 22.3%) and lose 16 points on Maintain. Growth × Centrist on Maintain: +20.6pp (p = .002); Growth × Conservative: +26.2pp (p < .001). The pattern is inconsistent with parallel-updating, status-quo-activation, and competitive-frames accounts as uniform-population mechanisms. We interpret it as a source-cue effect: progressives reject the executive-branded growth message on partisan source grounds even where its content matches their priors.

2. **The fertility cue activates an ethnic-restoration heuristic.** It rehabilitates unemployed ethnic-Korean profiles in the conjoint (the unemployment penalty for co-ethnics drops from 12 to 4 percentage points; LPM coefficient +5.6pp, p < .001) and produces a 10.6-point Brazil-vs-China swap among low-skill profiles. The pattern concentrates on woman-coded profiles and respondents aged 30-39, the cohort for whom the fertility frame is most biographically accessible. We read this as a demographic-urgency deservingness gate.

Origin and religion penalties (about 10 points for China vs the United States, about 14 points for Muslim vs non-religious profiles) remain stable across cues at magnitudes consistent with cross-national conjoint work.

## Contributions

1. Identifies a boundary condition on the parallel-updating consensus: in elite-consensus contexts where pro-immigration framing is already the official line, source-cue effects can dominate informational ones, producing opposite-direction movement across the ideological spectrum.
2. Specifies a mechanism (the demographic-urgency deservingness gate) by which fertility framing produces selective attitudinal change without producing aggregate movement, complicating both the salience-not-direction account and the standard "no effect" reading of immigration framing nulls.
3. Documents the durability of origin- and religion-based discrimination in a major non-Western democracy, replicating cross-national patterns at higher precision and showing that an explicit anti-discrimination cue ("regardless of background") embedded in both pro-immigration framings does not displace the deepest penalties.

## Repository contents

- `paper/`: Latest working paper (manuscript + Supplementary Information combined into a single PDF).
- `data/`: De-identified replication datasets (to be released upon publication).
- `code/`: Analysis scripts (to be released upon publication).

## Funding

This work was supported by the Academy of Korean Studies under Grant AKS-2023-R-018.

## Contact

**Steven Denney**
Assistant Professor, Institute for Area Studies, Leiden University
📧 s.c.denney@hum.leidenuniv.nl
