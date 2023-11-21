# Benchmark 6. Model-Based Architecture Design Synthesis

[TOC]

## Introduction

- **Disciplines**: This scientific benchmark repository concerns mainly the engineering design, systems engineering, and product lifecycle management communities.
- **Goal**: This scientific benchmark aims at collecting and comparing competing or complementary contributions claiming to improve the model-based architecture design synthesis process. In this benchmark, Model-Based Architecture Design Synthesis (MBADS) is a computer-based automatic problem-solving process to generate preliminary design solutions that are correct by construction.
- **Type of claimed contributions to benchmark:** ...

## Glossary

An agreed-upon glossary of terms used in this benchmark is proposed below. Contributors should reuse existing terms and definitions from existing standards and not invent new ones, unless they have a very specific concept that requires the introduction of a new keyword and definition. Any new keyword and definition must be motivated and explained in the discussion of the repository (e.g. navigate to '*Repositories > Benchmark-0_Template > Discussions*', or [click here](ttps://github.com/GIS-S-mart/Benchmark-7_Design_synthesis-3_Concepts_finding/discussions)).

|                    **Keyword**                    |                         **Synonyms**                         |                        **Definition**                        | **Source** |
| :-----------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|                 Design philosophy                 |                                                              | The axioms, postulates, assumptions, and convictions taken to be true to serve as a premise or starting point for further reasoning and arguments. |            |
|                 Design synthesis                  |                                                              | A problem-solving activity that consists in finding a solution to a set of needs |            |
|                  Design variable                  |                                                              | A design variable is an unknown variable whose value is computed when solving the formal design problem. |            |
|           Model-based design synthesis            |                Computational design synthesis                | A design process which relies on computer-based automatic problem-solving techniques to generate design solutions that are correct by construction. |            |
| Model-based architecture design synthesis (MBADS) |         Computational architecture design synthesis          | A design process which relies on computer-based automatic problem-solving techniques to generate architecture design solutions that are correct by construction. |            |
|          MBADS for system configuration           |                                                              | A MBADS objective that consists in choosing system elements based on a set of compatibility relationships between variants, options and cardinalities |            |
|              MBADS for system sizing              |                                                              | A MBADS objective objective that consists in determining the value of unknown design variables of a system element |            |
|           MBADS for resource allocation           |                                                              | A MBADS objective that consists in allocating hardware and/or software system elements to system functional requirements. |            |
|            MBADS for space allocation             |                                                              | A MBADS objective that consists in defining the bounding box of the subsystems and their spatial position and orientation within a system. |            |
|           MBADS for interfaces routing            |                                                              | A MBADS objective that consists in defining the path and wrapping each physical interface between two subsystems within the system bounding box. |            |
|         MBADS for architecture generation         |                                                              | A MBADS objective that combines at least two of the previous MBADS objectives, whether a logical, abstract architecture design or a physical one which mirrors the implementation. |            |
|                 Modelling method                  | Modelling methodology, modelling process, Modelling guidelines | The procedure to be followed by the practitioners to model the concepts using the preferred modelling language and modelling software. |            |
|                Modelling language                 |                    Standardised notation                     | A language or a standardised notation that is used to encode the system concept elaborated with the conceptual design method. |            |
|                Modelling software                 |                    Modelling environment                     | A software used by a practitioner to model a system concept using a modelling language. |            |

## Body of knowledge

The body of knowledge is the background knowledge upon which researchers will draw on and contribute in theory or practice. This benchmark aims to increase the knowledge of the MBADS process.

- Hartmann, C., Chenouard, R., Mermoz, E., & Bernard, A. (2018). A framework for automatic architectural synthesis in conceptual design phase. *Journal of Engineering Design*, *29*(11), 665-689.
- Menu, J., Nicolai, M., & Zeller, M. (2018, July). Designing fail-safe architectures for aircraft electrical power systems. In *2018 AIAA/IEEE Electric Aircraft Technologies Symposium (EATS)* (pp. 1-14). IEEE.
- Menu, J., & Nicolai, M. (2017). A Framework for Automated Design, Verification, and Simulation of Electrical Power Systems for Aircraft. In *Proceedings of 6th International Workshop on Aircraft System Technologies (AST 2017)* (pp. 135-144).
- Rosich, A., Berx, K., & Pinte, G. (2016). Model-based design synthesis: application to optimal air-compressor system design. *IFAC-PapersOnLine*, *49*(21), 416-422.
- dos Santos, C. A. R., Saleh, A. H., Schrijvers, T., & Nicolai, M. (2019, September). CONDEnSe: contract based design synthesis. In *2019 ACM/IEEE 22nd International Conference on Model Driven Engineering Languages and Systems (MODELS)* (pp. 250-260). IEEE.
- Yvars, P. A., & Zimmer, L. (2022). Towards a correct by construction design of complex systems: The MBSS approach. *Procedia CIRP*, *109*, 269-274.
- Yvars, P. A., & Zimmer, L. (2021). A model-based synthesis approach to system design correct by construction under environmental impact requirements. *Procedia CIRP*, *103*, 85-90.

## Research objectives

The primitive research objective pursued by the benchmark community is to improve a model-based architecture design synthesis process, which includes four main activities: 1) requirements definition, 2) concept finding, 3) problem modelling, and 4) system sizing.

## Claimed contributions

The list of claimed contributions gathers candidate research proposals combining a design philosophy, design method, modelling language, modelling software, and modelling method, which claim to improve the end-to-end model-based architecture design synthesis process. 

| Contribution ID | **Benchmark exercise** | **Version** | **DOI** |                           **URL**                            | **License** |
| :-------------: | :--------------------: | :---------: | :-----: | :----------------------------------------------------------: | :---------: |
|       001       |     Coupling bolt      |      1      |         | [Open data](Claimed%20contributions/Lean%20engineering/Coupling%20bolt/0001.md) |             |
|       001       |       Flashlight       |      1      |         | [Open data](Claimed%20contributions/Lean%20engineering/Flashlight/0001.md) |     ...     |

## Benchmarks

Once applied to the collection of benchmarks, the claimed contributions must provide empirical evidence that the research objectives have been met. The design inputs of each activity of the Model-Based Architecture Design Synthesis process change according to the MBADS objective. For instance, a research proposal can contribute to MBADS for system sizing without contributing to MBADS for interfaces routing. In addition, a research proposal can contribute to one activity of the MBADS process (e.g., concept finding) without contributing to other activities.

Hence, the MBADS benchmark is decomposed into 6 benchmarks.

|                              | MBADS for System Configuration |                   MBADS for System Sizing                    | MBADS for Resource Allocation | MBADS for Space Allocation | MBADS for Interface Routing | MBADS for Architecture |
| ---------------------------- | :----------------------------: | :----------------------------------------------------------: | :---------------------------: | :------------------------: | :-------------------------: | :--------------------: |
| **Requirements development** |                                |                                                              |                               |                            |                             |                        |
| **Concept finding**          |                                | [Benchmark](Benchmarks/Benchmark-MBDAS_System_Sizing-Concept_Finding.md) |                               |                            |                             |                        |
| **Problem modelling**        |                                |                                                              |                               |                            |                             |                        |
| **Problem solving**          |                                |                                                              |                               |                            |                             |                        |



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

