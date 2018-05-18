# GADRs for Java

This repository provides "Generalized Architectural Decision Records" (GADRs) for Java.
An [Architectural Decision Record](https://adr.github.io/) (ADR) is recording an architectural decision (AD).
Such a decision might be to use Gradle instead of Maven as build tool.
In another project, Maven might be preferred over Gradle.
The pros and cons of each decision might be somewhat general (appearing in both projects) or local (appearing in the context of one project only).
GADRs are about capturing the general options and their pros and cons.
[Prof. Dr. Olaf Zimmermann](https://www.ifs.hsr.ch/Olaf-Zimmermann.11623.0.html) coined the terms "Decision Required" and "Decisions Made" in his [PhD thesis](http://dx.doi.org/10.18419/opus-2665).
An overview is in the article [Decisions Required vs. Decisiosn Made](http://soadecisions.org/download/zimmermann_chap_mistrik_book.pdf).
He also distinguishes between "Problem Space" and "Solution Space" (see O. Zimmermann et al. [Architectural Decision Guidance across Projects](http://www.ifs.hsr.ch/fileadmin/user_upload/customers/ifs.hsr.ch/Home/projekte/ADMentor-WICSA2015ubmissionv11nc.pdf), IEEE/IFIP WICSA 2015).

| Model Type | Problem Space | Relation | Solution Space |
| -- | -- | -- | -- |
| Reach/Level | Asset (Community) | | Project |
| Owner | Knowledge Engineer | | Software Architect |
| Purpose | Design Guidance | | Decision (Back-)Log |
| Need for Architectural Decision | Problem <br> `\--raises-^` | `--1-instantiates-n-->` | Problem Occurrence |
| Design Candidates | Option | `--1-instantiates-n-->` | Option Occurrence |

This repository collects the Problem Space in context of Java projects in the form of GADRs.
