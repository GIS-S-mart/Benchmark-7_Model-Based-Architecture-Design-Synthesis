# Benchmark 6. Concept Finding in a Model-Based Architecture Design Synthesis Process for System Sizing

## Introduction

- **Disciplines**: This scientific benchmark repository concerns mainly the engineering design, systems engineering, and product lifecycle management communities.
- **Goal**: This scientific benchmark aims at collecting and comparing competing or complementary contributions claiming to improve the activity of concept finding in a model-based architecture design synthesis process for system sizing. In this benchmark, model-based architecture design synthesis is a computer-based automatic problem-solving process to generate preliminary design solutions that are correct by construction. A design synthesis process has an objective: system configuration, system sizing, resource allocation, and/or architecture generation.  This benchmark focuses on design synthesis for system sizing. In addition, in a computational design synthesis process for system sizing, this benchmark concentrates on the activity of concept finding.  Starting with a set of validated requirements, concept finding is an activity that intends to find preliminary design variables, parameters and constants, that serve to define the set of acceptable and feasible conceptual design solutions.
- **Type of claimed contributions to benchmark:** This scientific benchmark aims at benchmarking the modelling language?

## Glossary

An agreed-upon glossary of terms used in this benchmark is proposed below. Contributors should reuse existing terms and definitions from existing standards and not invent new ones, unless they have a very specific concept that requires the introduction of a new keyword and definition. Any new keyword and definition must be motivated and explained in the discussion of the repository (e.g. navigate to '*Repositories > Benchmark-0_Template > Discussions*', or [click here](ttps://github.com/GIS-S-mart/Benchmark-7_Design_synthesis-3_Concepts_finding/discussions)).

|         **Keyword**          |                         **Synonyms**                         |                        **Definition**                        | **Source** |
| :--------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|        System concept        | Concept, Design concept, Preliminary design, Under-defined system. | A system concept is an under-defined system definition that satisfies the set of system requirements. |            |
|       Concept finding        |  Embodiement design, Conceptual design, Preliminary design.  | An activity of the design synthesis process that intends to find preliminary design variables, parameters and constants, so as to define the set of acceptable and feasible conceptual under-defined design solutions. |            |
|   Conceptual design method   |                                                              | The procedure to be followed by the practitioners to conceptually design the system-of-interest by using any modelling method and software. |            |
|           Constant           |                                                              | A constant has an unmodifiable value that is constant with respect to time and remains always the same even between two computations. |            |
|       Design parameter       |                                                              | A design parameter is a design variable with a fixed value that is set after initialisation, therefore it cannot be calculated using the time-changing design variables. It is constant with respect to time during one computation but can be modified between two computations. |            |
|       Design variable        |                                                              | A time-changing variable whose value is continuously or discreetly updated at each computation step. |            |
| Model-based design synthesis |                                                              | A design process which relies on computer-based automatic problem-solving techniques to generate preliminary design solutions that are correct by construction. |            |
|       Modelling method       |                                                              | The procedure to be followed by the practitioners to model the concepts using the preferred modelling language and modelling software. |            |
|      Modelling language      |                    Standardized notation                     | Language or notation that is used to encode the concept of the conceptual design method. |            |
|      Modelling software      |                    Modelling environment                     | A software used by a practitioner to model a system concept using a modelling language. |            |
|     System configuration     |                                                              | A design synthesis objective that consists in choosing system elements based on a set of compatibility relationships, variants, options and cardinalities. |            |
|        System sizing         |                                                              | A design synthesis objective that consists in determining unknowns – continuous or discrete – variables of system elements for a given system configuration. |            |
|                              |                                                              |                                                              |            |

## Body of knowledge

Are we benchmarking design method, modelling language, modelling method, modelling software?

## Research Objectives

The fundamental research objective is to find system concepts based on a set of requirements as input data. 

## Empirical evidence

An empirical evidence is a quantitative and/or qualitative performance indicator or metric that measures the degree to which the research goal of concept finding has been achieved. The empirical evidence supporting or countering the belief that the contributions claiming to achieve the goal of concept finding are defined as follows: 

|                           **Name**                           | **Definition** | **Unit** |
| :----------------------------------------------------------: | :------------: | :------: |
|    Number of concepts satisfying the system requirements     |                |          |
|             Number of relevant design variables              |                |          |
|             Number of relevant design parameters             |                |          |
|           Relevant domain of each design variable            |                |          |
|           Relevant domain of each design parameter           |                |          |
|                      Value of constant?                      |                |          |
| Number of relevant relationships between design variables, design parameters and constants |                |          |
|                                                              |                |          |
|                                                              |                |          |
|                                                              |                |          |
|                Minimize number of variables?                 |                |          |
|                 (Number of physics explored)                 |                |          |
|                 (Design synthesis objective)                 |                |          |

(complete with a bottom-up approach by reviewing metrics in papers containing concept finding contributions)

Authors should use existing metrics and not invent new ones, unless they measure additional aspects not covered by existing ones. Any change to existing empirical evidence must be motivated and explained in the discussion of the repository (e.g. navigate to '*Repositories > Benchmark-0_Template > Discussions*', or [click here](ttps://github.com/GIS-S-mart/Benchmark-7_Design_synthesis-3_Concepts_finding/discussions). Once the suggested change is informally approved by the community, the author shall post on the issues page of the benchmark (e.g. navigate to '*Repositories > Benchmark-0_Template > Issues*', or [click here](ttps://github.com/GIS-S-mart/Benchmark-7_Design_synthesis-3_Concepts_finding/issues)) and briefly outline the new metric.

## Benchmarks Collection

The set of benchmark exercises aims to demonstrate the usefulness of each claimed contribution beyond a single benchmark exercise.

### Characteristics of the collection of benchmark exercises

|                                                              | Coupling bolt |       Flashlight        |        Camera        |
| ------------------------------------------------------------ | :-----------: | :---------------------: | :------------------: |
| *Type of design synthesis problem (system sizing, system configuration, resource allocation, architecture generation)* | System sizing | Architecture generation | System configuration |
| *Multi-engineering*                                          |      No       |           Yes           |                      |
| Type of behaviour                                            |  Continuous   |       Continuous        |                      |



### Benchmark exercises

|   **Name**    | **Author(s)** | **Version** | **DOI** |                           **URL**                            | **License** |
| :-----------: | :-----------: | :---------: | :-----: | :----------------------------------------------------------: | :---------: |
| Coupling bolt |               |     V1      |         | [Link](https://github.com/GIS-S-mart/Benchmark-7_Design_synthesis-3_Concepts_finding/blob/main/Benchmark%20exercises/Coupling%20bolt%20system/Coupling%20bolt%20system%20benchmark%20exercise.md) |  CC-BY-SA   |
|  Flashlight   |               |     V1      |         |                           [Link]()                           |  CC-BY-SA   |
|    Camera     |               |     V1      |         |                           [Link]()                           |  CC-BY-SA   |

### Benchmark protocols

Does a benchmark protocol apply to all benchmark exercise or each benchmark exercise requires its own benchmark protocol?

## Claimed contributions

To improve the results of the concept finding activity, one can propose a new design method, modelling method, modelling language or modelling software.

| **Name** |  **Author(s)**   | **Version** | **DOI** | **URL** | **License** | Evidence |
| :------: | :--------------: | :---------: | :-----: | :-----: | :---------: | :------: |
| FPPT&SK2 | Lionel Roucoules |             |         |         |             |          |

## Benchmarking

Benchmark SysML+CatiaMagic... et on fait varier les concepts.



|                           **Name**                           | **FPPT-SK2/UML/Eclipse...** | **???** |
| :----------------------------------------------------------: | :-------------------------: | :-----: |
|    Number of concepts satisfying the system requirements     |                             |         |
|             Number of relevant design variables              |                             |         |
|             Number of relevant design parameters             |                             |         |
|           Relevant domain of each design variable            |                             |         |
|           Relevant domain of each design parameter           |                             |         |
|                      Value of constant?                      |                             |         |
| Number of relevant relationships between design variables, design parameters and constants |                             |         |
|                Minimize number of variables?                 |                             |         |
|                 (Number of physics explored)                 |                             |         |
|                 (Design synthesis objective)                 |                             |         |

## Meta-Analysis

A meta-analysis is the analysis of all results of the benchmark for the purpose of integrating the findings. Meta-analytic results are the most trustworthy source of evidence.

## References

*Guidelines:*

- Please use the Harvard format to list references supporting any data (keyword definition, goal, metric, benchmark exercise, solution, etc.) of the benchmark.
- Make sure to provide the DOI of the document.

*Template:*

- **Book, one author:** Bell, J. (2010) *Doing your research project*. 5th edn. Maidenhead: Open University Press.

- **One author, book, multiple editions:** Hawking, S.W. (1998) *A brief history of time: From the big bang to black holes*. 10th edn. New York: Bantam Doubleday Dell Publishing Group.

- **Chapter in an edited book:** Jewsiewicki, B. (2010). ‘Historical Memory and Representation of New Nations in Africa’, in Diawara, M., Lategan, B., and Rusen, J. (eds.) *Historical memory in Africa: Dealing with the past, reaching for the future in an intercultural context*. New York: Berghahn Books, pp. 53-66.

- **More than three authors, journal article:** Shakoor, J., et al. (2011) ‘A prospective longitudinal study of children’s theory of mind and adolescent involvement in bullying’, *Journal of Child Psychology and Psychiatry*, 53(3), pp. 254–261. doi: 10.1111/j.1469-7610.2011.02488.x.

- **Conference papers:** Drogen, E. (2014) ‘Changing how we think about war: The role of psychology’, *The British Psychological Society 2014 Annual Conference*. The ICC, Birmingham British Psychological Society, 07-09 May 2014.

- **Web page, by an individual:** Moon, M. (2019) *Ubisoft put an official video game design course inside a video game*. Available at https://www.engadget.com/2019/09/25/ubisoft-video-game-design-course/ (Accessed 19 November 2019).

- **Web page, by a company or organization:** RotoBaller (2019) *NFL player news*. Available at https://www.rotoballer.com/player-news?sport=nfl (Accessed 17 September 2019).
