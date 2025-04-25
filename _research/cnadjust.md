---
title: "CNAdjust: Enhancing CNA Calling Accuracy through Systematic Baseline Adjustment"
collection: research
order: 3
permalink: /research/cnadjust
codeurl: https://github.com/baudisgroup/CNAdjust
excerpt: a Nextflow pipeline for adjusting baselines in CNV segment profiles to improve CNA calling accuracy
---

It is a modular pipeline designed to improve the accuracy of copy number alteration (CNA) calling by systematically detecting and correcting baseline shifts in CNV segment data.

The method identifies likely misassigned baselines by evaluating signal characteristics indicative of calling artifacts. A Bayesian framework is then applied to recalibrate these baselines, leveraging cohort-specific CNA patterns and intra-study sample comparisons. This approach ensures that the adjusted CNA profiles are more consistent with underlying biological structures and study-specific characteristics.
