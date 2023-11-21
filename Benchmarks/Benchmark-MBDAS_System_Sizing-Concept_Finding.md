# Benchmark 6. MBADS for System Sizing: Concept Finding

## Introduction

- **Disciplines**: The discipline concerned by . Although engineering design, systems engineering, and product lifecycle management
- **Goal**: This scientific benchmark aims to foster cumulative research and support researchers in the fair and systematic evaluation of competing or complementary research proposals that claim to improve the activity of **concept finding** in the 4-activity **Model-Based Architecture Design Synthesis** (MBADS) process for **system sizing** defined as follows:

|         Activity         |                         Inputs                          | Outputs                                                      |
| :----------------------: | :-----------------------------------------------------: | :----------------------------------------------------------- |
| Requirements development |                Expected system functions                | - Valid set of requirements.<br />- Valid set of design constraints. |
|   **Concept finding**    | **Outputs of the activity "requirements development".** | **- Set of design variables with their data types and range of acceptable values.<br />- Set of design parameters with their data types and values<br />- Set of constants with their types and values.<br />- Preliminary set of relationships between design variables, design parameters, and constants.** |
|    Problem modelling     |       Outputs of the activity "concept finding".        | Complete set of relationships between design variables, design parameters, and constants. |
|     Problem solving      |      Outputs of the activity "problem modelling".       | Values for design variables.                                 |

## Glossary

An agreed-upon glossary of terms used in this benchmark is proposed below. Contributors should reuse existing terms and definitions from existing standards and not invent new ones, unless they have a very specific concept that requires the introduction of a new keyword and definition. Any new keyword and definition must be motivated and explained in the discussion of the repository (e.g. navigate to '*Repositories > Benchmark-0_Template > Discussions*', or [click here](../discussions)).

|                **Keyword**                |                         **Synonyms**                         |                        **Definition**                        | **Source** |
| :---------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|              System concept               | Concept, Design concept, Preliminary design, Under-defined system. | A system concept is an under-defined system definition that satisfies the set of system requirements. |            |
|              Concept finding              | Embodiment design, Conceptual design, Preliminary design, Architecture Design, System Architecting | An activity of the design synthesis process that intends to find preliminary design variables, parameters and constants, so as to define the set of acceptable and feasible conceptual under-defined design solutions. |            |
|         Conceptual design method          |                                                              | The procedure to be followed by the practitioners to generate system concepts by using any modelling method and software. |            |
|                 Constant                  |                                                              | A constant has an unmodifiable value that is constant with respect to time and remains always the same even between two computations. |            |
|             Design constraint             |                                                              | A limitation on the design of a system externally imposed by a stakeholder or an external system. Design constraints cannot be traded off and make certain designs “not allowed” whereas requirements make certain designs inappropriate for their intended use. |            |
|             Design parameter              |                                                              | . A design parameter is a known design variable with a fixed value that is set after a design synthesis iteration concluded by an agreed-upon design decision; therefore, it is not calculated when solving the formal design problem. |            |
|             Design philosophy             |                                                              | The axioms, postulates, assumptions, and convictions taken to be true to serve as a premise or starting point for further reasoning and arguments. |            |
|             Design synthesis              |                                                              | A problem-solving activity that consists in finding a solution to a set of needs |            |
|              Design variable              |                                                              | A design variable is an unknown variable whose value is computed when solving the formal design problem. |            |
| Model-based architecture design synthesis |         Computational architecture design synthesis          | A design process which relies on computer-based automatic problem-solving techniques to generate architecture design solutions that are correct by construction |            |
|       Model-based design synthesis        |                Computational design synthesis                | A design process which relies on computer-based automatic problem-solving techniques to generate design solutions that are correct by construction. |            |
|             Modelling method              | Modelling methodology, modelling process, Modelling guidelines | The procedure to be followed by the practitioners to model the concepts using the preferred modelling language and modelling software. |            |
|            Modelling language             |                    Standardised notation                     | A language or a standardised notation that is used to encode the system concept elaborated with the conceptual design method. |            |
|            Modelling software             |                    Modelling environment                     | A software used by a practitioner to model a system concept using a modelling language. |            |
|                Requirement                |                                                              | An agreed-to expectation for a system to perform a system function at a specified level of performance and under some conditions of use. |            |
|           System configuration            |                                                              | A design synthesis objective that consists in choosing system elements based on a set of compatibility relationships between variants, options and cardinalities |            |
|               System sizing               |                                                              | A design synthesis objective that consists in determining the value of unknown design variables of a system element |            |
|                                           |                                                              |                                                              |            |

## Research objectives

The primitive research objective pursued by the benchmark community is improving the **concept finding** activity in a **Model-Based Architecture Design Synthesis** process for **system sizing**.

The metrics 

|                           **Name**                           | **Definition** |  **Unit**   |
| :----------------------------------------------------------: | :------------: | :---------: |
|    Number of concepts satisfying the system requirements     |                | Real number |
|                  Number of design variables                  |                | Real number |
|                 Number of design parameters                  |                | Real number |
|                Design space (Product domain)                 |                |             |
| Number of relationships between design variables, design parameters and constants |                |             |
|                     Model-based approach                     |                |             |
|                  Design synthesis objective                  |                |             |
|                  Number of physics explored                  |                |             |
|                 Minimize number of variables                 |                |             |
|                        Learning curve                        |                |             |
|                   Language expressiveness                    |                |             |
|                                                              |                |             |

## Body of knowledge

The body of knowledge is the background knowledge upon which researchers will draw on and contribute in theory or practice. Regarding the activity of concept finding, the background knowledge is relatively broad and vaguely known under different names, such as embodiment design, conceptual design, preliminary design, [...], or system architecture design. Existing works include:

- Albers, A., Sedchaicharn, K., Sauter, C., & Burger, W. (2009). A Method to define a Product Architecture Early in Product Development Using the Contact and Channel Model. In *DS 58-5: Proceedings of ICED 09, the 17th International Conference on Engineering Design, Vol. 5, Design Methods and Tools (pt. 1), Palo Alto, CA, USA, 24.-27.08. 2009* (pp. 241-252).
- Pailhès, J., Sallaou, M., Nadeau, J. P., & Fadel, G. M. (2011). Energy based functional decomposition in preliminary design.
- Suh, N. P., & Suh, N. P. (2001). *Axiomatic design: advances and applications* (Vol. 4). New York: Oxford university press.

This benchmark focuses on a more narrow scope limited to the design approaches supporting the concept finding activity with a model-based approach, which could be part of a Model-Based Architecture Design Synthesis process for automatic solving. Existing works include:

- Albert, A., & Christian, Z. (2013). Extending SysML for engineering designers by integration of the contact & channel–approach (C&C2-A) for function-based modeling of technical systems. *Procedia Computer Science*, *16*, 353-362.
- Barbedienne, R., Penas, O., Choley, J. Y., & Hehenberger, P. (2019). Modeling framework for a consistent integration of geometry knowledge during conceptual design. *Journal of Computing and Information Science in Engineering*, *19*(2), 021009.
- Barbedienne, R., Messaoud, Y. B., Choley, J. Y., Penas, O., Ouslimani, A., & Rivière, A. (2015, September). SAMOS for Spatial Architecture based on Multi-physics and Organisation of Systems in conceptual design. In *2015 IEEE International Symposium on Systems Engineering (ISSE)* (pp. 135-141). IEEE.
- Kharrat, M., Penas, O., Plateaux, R., Trabelsi, H., Choley, J. Y., Louati, J., & Haddar, M. (2017, October). Towards a 3D conceptual architecture framework, based on multi-physical constraints. In *2017 IEEE International Systems Engineering Symposium (ISSE)* (pp. 1-8). IEEE.
- Kharrat, M., Penas, O., Plateaux, R., Choley, J. Y., Trabelsi, H., Louati, J., & Haddar, M. (2020). Integration of electromagnetic constraints as of the conceptual design through an MBSE approach. *IEEE Systems Journal*, *15*(1), 747-758.

However, the design inputs and outputs of the concept finding activity depend on the objective of the Model-Based Architecture Design Synthesis process. This benchmark concentrates on the activity of MBADS for system sizing, which further limits the body of knowledge, although all related works are of interest.

## Proposals

The table below is a collection of research proposals that claim to improve the activity of concepts finding in a model-based architecture design synthesis approach for system sizing.

(e.g., theory, process, method, modelling language, software…) which, once applied to the collection of benchmarks, must provide empirical evidence that the research objectives have been meta collection of contributions 

| Contribution ID | Design Philosophy | Design  Method  | Modelling  Language | Modelling  Software | Modelling  Method |      |
| :-------------: | :---------------: | :-------------: | :-----------------: | :-----------------: | :---------------: | ---- |
|       001       | Lean engineering  | AF + FPPT + SK2 |         UML         |       Eclipse       |   Lionel Method   |      |
|       ...       |        ...        |       ...       |         ...         |         ...         |        ...        |      |

## Claimed contributions



|                           **Name**                           | Contribution ID | ...  |
| :----------------------------------------------------------: | :-------------: | :--: |
|    Number of concepts satisfying the system requirements     |                 |      |
|                  Number of design variables                  |                 |      |
|                 Number of design parameters                  |                 |      |
|                Design space (Product domain)                 |                 |      |
| Number of relationships between design variables, design parameters and constants |                 |      |
|                     Model-based approach                     |                 |      |
|                  Design synthesis objective                  |                 |      |
|                  Number of physics explored                  |                 |      |
|                 Minimize number of variables                 |                 |      |
|                        Learning curve                        |                 |      |
|                   Language expressiveness                    |                 |      |

## Benchmarks Collection

### Benchmark exercises

|                                                              |      |      |      |      |      |
| :----------------------------------------------------------: | :--: | :--: | :--: | :--: | :--: |
| [**Coupling bolt**](../Exercises/Coupling/Exercise-MBDAS_System_Sizing.md) |      |      |      |      |      |
|                        **Flashlight**                        |      |      |      |      |      |
|                          **Camera**                          |      |      |      |      |      |

### Benchmark protocols

Does a benchmark protocol apply to all benchmark exercises, or does each one require its benchmark protocol?

### 

## Empirical evidence

An empirical evidence is a quantitative and/or qualitative performance indicator or metric that measures the degree to which the research goal of concept finding has been achieved. The empirical evidence supporting or countering the belief that the contributions claiming to achieve the goal of concept finding are defined as follows: 

The table below gives access to the open data of each contribution:

|                   |                       Contribution 001                       |      |      |      |      |
| :---------------: | :----------------------------------------------------------: | :--: | :--: | :--: | :--: |
| **Coupling bolt** | [Empirical evidence](../Proposals/FPPT-SK2/Coupling/Coupling.md) |      |      |      |      |
|  **Flashlight**   |                                                              |      |      |      |      |
|    **Camera**     |                                                              |      |      |      |      |



(complete with a bottom-up approach by reviewing metrics in papers containing concept finding contributions)

Authors should use existing metrics and not invent new ones, unless they measure additional aspects not covered by existing ones. Any change to existing empirical evidence must be motivated and explained in the discussion of the repository (e.g. navigate to '*Repositories > Benchmark-0_Template > Discussions*', or [click here](ttps://github.com/GIS-S-mart/Benchmark-7_Design_synthesis-3_Concepts_finding/discussions). Once the suggested change is informally approved by the community, the author shall post on the issues page of the benchmark (e.g. navigate to '*Repositories > Benchmark-0_Template > Issues*', or [click here](ttps://github.com/GIS-S-mart/Benchmark-7_Design_synthesis-3_Concepts_finding/issues)) and briefly outline the new metric.



|                           **Name**                           | **Contribution ID** |      | **???** |
| :----------------------------------------------------------: | :-----------------: | ---- | :-----: |
|    Number of concepts satisfying the system requirements     |         001         |      |         |
|             Number of relevant design variables              |                     |      |         |
|             Number of relevant design parameters             |                     |      |         |
|           Relevant domain of each design variable            |                     |      |         |
|           Relevant domain of each design parameter           |                     |      |         |
|                      Value of constant?                      |                     |      |         |
| Number of relevant relationships between design variables, design parameters and constants |                     |      |         |
|                Minimize number of variables?                 |                     |      |         |
|                 (Number of physics explored)                 |                     |      |         |
|                 (Design synthesis objective)                 |                     |      |         |

## Benchmarking

The table below shows the results of the benchmarking 



The table below gives access to the open data of each contribution:



|                   |    Contribution 001    |      |      |      |      |
| :---------------: | :--------------------: | :--: | :--: | :--: | :--: |
| **Coupling bolt** | [Empirical evidence]() |      |      |      |      |
|  **Flashlight**   |                        |      |      |      |      |
|    **Camera**     |                        |      |      |      |      |



## Meta-Analysis

A meta-analysis is the analysis of all results of the benchmark for the purpose of integrating the findings. Meta-analytic results are the most trustworthy source of evidence.