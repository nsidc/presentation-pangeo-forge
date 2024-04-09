---
title: "Pangeo-Forge"
subtitle: "A ⚡ lightning talk ⚡"
date: "2024-04-09"
format: revealjs
author:
  - name: "Trey Stafford"
  - name: "Matt Fisher"
---

## Pangeo-Forge overview

* Inspired by [conda-forge](https://conda-forge.org/).
* Community-driven recipes define pipelines for making datasets analysis-ready
  and cloud optimized (ARCO).
* [Apache Beam](https://beam.apache.org/) as underlying technology. Recently
  switched from [Prefect](https://docs.prefect.io/latest/).


::: {.notes}
We think Apache Beam is a good long-term decision because it provides an
abstraction language to workflows. Prevents lockin to a particular
orchestrator. E.g., Beam can be run on Apache Spark, Google Dataflow, and
others.
:::

## Discussion highlights

* Currently focused on Zarr.
* Focused on NASA as a customer. 
* Governance is in flux. "Do-ocracy".
* Expecting a lot of churn/development over the next few years.

::: {.notes}
QGreenland-Net dev team met with Pangeo-Forge devs for a discussion about how we
might collaborate with pangeo-forge.
:pangeo-forge relateds::


## Resources

* [ESDIS Tech Spotlight on Pangeo-Forge by Yuvi Panda](https://drive.google.com/file/d/1VzQusCJb2Weuunzh6LsvSsKiRFCZbFXO/view?usp=sharing)
* [Pangeo-Forge paper](https://pangeo-forge.readthedocs.io/en/latest/#the-pangeo-forge-paper)
