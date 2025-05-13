# Benchmark 7. Model-Based Architecture Design Synthesis

> [!NOTE]
>
> *A scientific benchmark repository is an online, version-controlled, and collaborative space where researchers can share a collection of open data along with its revision history.*

## Introduction

> [!NOTE]
>
> *The introduction must be short and include the following items:* 
> *\- The main discipline(s) it contributes to.*
> *\- The type of the claimed contribution to benchmark (theory, process, method, software, algorithm, modelling language...).*
> *\- The expected results.*
> *\- Type of research (does the benchmark intend to be qualitative and/or quantitative)*

- **Disciplines**: This scientific benchmark mainly concerns engineering design, systems engineering, and product lifecycle management communities.
- **Goal**: This scientific benchmark aims to collect and compare competing or complementary contributions that claim to enhance the model-based architecture design synthesis process. In this benchmark, Model-Based Architecture Design Synthesis (MBADS) is a computer-based automatic problem-solving process designed to generate preliminary design solutions that are correct by construction.

## Glossary

> [!NOTE]
>
> *The the glossary aims to clearly define keywords and use them consistently in the benchmark documentation, enabling community members to communicate more effectively. Contributors should reuse existing keywords and definitions from standards rather than inventing new ones, unless they have a very specific concept that necessitates the introduction of a new keyword definition.*

> [!TIP]
>
> Any new keyword and definition must be motivated and explained in the discussion of the repository (e.g. navigate to '*Repositories > Benchmark-0_Template > Discussions*', or [click here](ttps://github.com/GIS-S-mart/Benchmark-7_Design_synthesis-3_Concepts_finding/discussions)).

|                    **Keyword**                    |                         **Synonyms**                         |                        **Definition**                        | **Source** |
| :-----------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|                 Design philosophy                 |                                                              | The axioms, postulates, assumptions, and convictions taken to be true and serve as a premise or starting point for further reasoning and arguments. |            |
|                 Design synthesis                  |                                                              | A problem-solving activity that consists in finding a solution to a set of needs |            |
|                  Design variable                  |                                                              | A design variable is an unknown variable whose value is computed when solving the formal design problem. |            |
|           Model-based design synthesis            |                Computational design synthesis                | A design process which relies on computer-based automatic problem-solving techniques to generate design solutions that are correct by construction. |            |
| Model-based architecture design synthesis (MBADS) |         Computational architecture design synthesis          | A design process that relies on computer-based automatic problem-solving techniques to generate correct architecture design solutions by construction. |            |
|          MBADS for system configuration           |                                                              | An MBADS objective that consists in choosing system elements based on a set of compatibility relationships between variants, options and cardinalities |            |
|              MBADS for system sizing              |                                                              | A MBADS objective objective that consists in determining the value of unknown design variables of a system element |            |
|           MBADS for resource allocation           |                                                              | An MBADS objective that consists in allocating hardware and/or software system elements to system functional requirements. |            |
|            MBADS for space allocation             |                                                              | An MBADS objective that consists in defining the bounding box of the subsystems and their spatial position and orientation within a system. |            |
|           MBADS for interfaces routing            |                                                              | An MBADS objective that consists in defining the path and wrapping each physical interface between two subsystems within the system bounding box. |            |
|         MBADS for architecture generation         |                                                              | An MBADS objective that combines at least two of the previous MBADS objectives, whether a logical, abstract architecture design or a physical one which mirrors the implementation. |            |
|                 Modelling method                  | Modelling methodology, modelling process, Modelling guidelines | The procedure that is to be followed by practitioners to model the concepts using the preferred modelling language and modelling software. |            |
|                Modelling language                 |                    Standardised notation                     | A language or standardised notation used to encode the system concept is elaborated with the conceptual design method. |            |
|                Modelling software                 |                    Modelling environment                     | A software a practitioner uses to model a system concept using a modelling language. |            |


## Research objectives

> [!NOTE]
>
> *A research objective is a measurable goal that is pursued by the benchmark community. Fundamental research objectives in design research are to understand or improve design activities.*

The primary research objective pursued by the benchmark community is to enhance a model-based architecture definition process. This process involves four main activities: 1) requirements development, 2) concept finding, 3) problem modelling, and 4) system sizing.

## Benchmarking

Once applied to the collection of benchmarks, the claimed contributions must provide empirical evidence that the research objectives have been met. The design inputs for each activity of the Model-Based Architecture Design Synthesis process vary according to the MBADS objective. For instance, a research proposal can contribute to MBADS for system sizing without contributing to MBADS for interface routing. Additionally, a research proposal can contribute to one activity of the MBADS process (e.g., concept finding) without contributing to other activities.

Hence, the MBADS benchmark is decomposed into 6 benchmarks.

<table class="tg">
<thead>
<tr style="height: 63px;">

<th class="tg-2eyt" style="height: 63px;">&nbsp;</th>
<th class="tg-44qx" style="height: 63px;">MBADS for System Configuration</th>
<th class="tg-44qx" style="height: 63px;" colspan="2">MBADS for System Sizing</th>
<th class="tg-44qx" style="height: 63px;">MBADS for Resource Allocation</th>
<th class="tg-44qx" style="height: 63px;">MBADS for Space Allocation</th>
<th class="tg-44qx" style="height: 63px;">MBADS for Interface Routing</th>
<th class="tg-44qx" style="height: 63px;" colspan="2">MBADS for Architecture Generation</th>
</tr>
</thead>
<tbody>
<tr style="height: 23.5px;">
<td class="tg-lboi" style="height: 46.5px;" rowspan="2"><strong>Requirements
development</strong></td>
<td class="tg-9wq8" style="height: 23.5px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23.5px;">PBR</td>
<td class="tg-0lax" style="height: 46.5px;" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_System_Sizing-Requirements_Development.md">Benchmark</a></td>
<td class="tg-9wq8" style="height: 23.5px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23.5px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23.5px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23.5px;">???</td>
<td class="tg-0lax" style="height: 46.5px;" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_Architecture_Generation-Requirements_Development.md">Benchmark</a></td>
</tr>
<tr style="height: 23px;">
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">???</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">???</td>
</tr>
<tr style="height: 23px;">
<td class="tg-lboi" style="height: 46px;" rowspan="2"><strong>Concept finding</strong></td>
<td class="tg-9wq8" style="height: 23px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23px;">Lean</td>
<td class="tg-0lax" style="height: 46px;" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_System_Sizing-Concept_Finding.md">Benchmark</a></td>
<td class="tg-9wq8" style="height: 23px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23px;">???</td>
<td class="tg-0lax" style="height: 46px;" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_Architecture_Generation-Concept_Finding.md">Benchmark</a></td>
</tr>
<tr style="height: 23px;">
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">C&amp;CA</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">C&amp;CA</td>
</tr>
<tr style="height: 23px;">
<td class="tg-lboi" style="height: 46px;" rowspan="2"><strong>Problem modelling</strong></td>
<td class="tg-9wq8" style="height: 23px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23px;">DEPS</td>
<td class="tg-0lax" style="height: 46px;" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_System_Sizing-Problem_Modeling.md">Benchmark</a></td>
<td class="tg-0lax" style="height: 23px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 23px;">&nbsp;</td>
  <td class="tg-9wq8" style="height: 23px;">???</td>
  <td class="tg-0lax" style="height: 46px;" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_Architecture_Generation-Problem_Modeling.md">Benchmark</a></td>
</tr>
<tr style="height: 23px;">
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">Ibex?</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
  <td class="tg-9wq8" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">???</td>
</tr>
<tr style="height: 43px;">
<td class="tg-lboi" style="height: 66px;" rowspan="2"><strong>Problem solving</strong></td>
<td class="tg-9wq8" style="height: 43px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 43px;">DEPS + DEPS Studio</td>
<td class="tg-0lax" style="height: 66px;" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_System_Sizing-Problem_Solving.md">Benchmark</a></td>
<td class="tg-9wq8" style="height: 43px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 43px;">&nbsp;</td>
<td class="tg-9wq8" style="height: 43px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">???</td>
<td class="tg-0lax" style="height: 46px;" rowspan="2"><a href="Benchmarks/Benchmark-MBADS_Architecture_Generation-Problem_Solving.md">Benchmark</a></td>
</tr>
<tr style="height: 23px;">
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">DEPS + Ibex</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">&nbsp;</td>
<td class="tg-0pky" style="height: 23px;">???</td>

## Meta-Analysis

> [!NOTE]
>
> A meta-analysis is the analysis of all results of the benchmark for the purpose of integrating the findings. Meta-analytic results are the most trustworthy source of evidence.

## References

...

