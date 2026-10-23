---
layout: page
title: Hybrid LLM–Human Relevance Judgments
description: Combining LLM and human relevance judgments to evaluate the best retrieval systems. MSc thesis at UCL; paper submitted to ECIR 2027.
importance: 1
category: research
related_publications: true
---

Test collections used to benchmark retrieval systems rely on relevance judgments: grades that a human assessor gives to each query–passage pair. These are expensive to produce, and LLMs are increasingly used in place of human assessors. Rankings of retrieval systems built from LLM grades agree closely with human-based rankings overall, but the agreement drops when the comparison is restricted to the best systems.

This project asks how to combine humans and LLMs efficiently so that the ranking of the top systems stays close to the one a fully human-graded collection would give. The effect of a single LLM grading error on the system ranking can be decomposed into how wrong the grade is and how differently the systems ranked that passage. That decomposition gives a rule for which pairs to send to a human assessor first. Sending only 9 to 14 percent of the pairs (in four of the five years studied) to a human assessor under this policy, the ranking of the twenty best systems agrees with the fully human ranking at a Kendall τ of 0.95.

MSc thesis at University College London, supervised by Prof. Ingemar Cox. A paper based on this work has been submitted to ECIR 2027.

<a href="{{ '/assets/pdf/barao2026thesis.pdf' | relative_url }}">Read the thesis (PDF)</a>
