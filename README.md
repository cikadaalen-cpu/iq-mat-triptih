# iQ MAT Triptych v1.0

**Author:** Alen Čikada Cicada  
**Status:** Locked triptych + exploratory Appendix B  
**Date:** 28 June 2026  
**License:** CC BY-NC-SA 4.0

## Overview

iQ MAT is a bounded mathematical framework for expressing signal reliability under uncertainty, noise, contradiction, and incomplete information.

Core form:

\[
iQ = \frac{Signal}{Signal + Noise + \varepsilon}
\]

with:

\[
Signal = K \cdot S \cdot T
\]

and:

\[
Noise = U
\]

The framework separates numerical reliability from safety gating:

\[
iQ \neq decision
\]

\[
iQ = reliability\ score
\]

\[
HumanOverride = safety\ gate
\]

\[
HumanOverride = 1 \Rightarrow MachineSilence
\]

## Repository contents

| File | Status | Purpose |
|---|---|---|
| `IQ_MAT_1.md` | Locked Reference Version | Mathematical and conceptual review layer |
| `IQ_MAT_2.md` | Working locked version v1.0 | Calibration, thresholds, and safety logic |
| `IQ_MAT_Appendix_A.md` | Companion computational appendix v1.0 | Synthetic calibration and epsilon sensitivity |
| `IQ_MAT_Appendix_B.md` | Exploratory validation-planning appendix v0.1 | Comparative validation methodology planning |
| `IQ_MAT_ALL.md` | Combined document | Full readable package |

## Non-claims

This repository does **not** claim that iQ MAT is clinically validated, diagnostic, therapeutic, a medical device, a replacement for expert judgment, or a decision-making system.

The framework is methodological and mathematical. Any applied validation would require real data, defined reference standards, threshold calibration, and external review.

## Authorship and AI use

The conceptual framework, notation, and iQ MAT documents are attributed to:

**Alen Čikada Cicada**

AI systems were used only as editorial and analytical tools, not as authors.

## Version boundary

Locked documents:

```text
MAT-1 = mathematical core
MAT-2 = calibration / thresholds / safety logic
Appendix A = synthetic computation / epsilon audit
