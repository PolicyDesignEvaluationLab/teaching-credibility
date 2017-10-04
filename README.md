# About this Project
These files are part of a teaching module developed by the Policy Design and Evaluation Lab ([PDEL](https://pdel.ucsd.edu/)) at UCSD. The module is intended for use in graduate-level social science methodology courses—including those in political science, economics, sociology, and psychology—at UCSD and beyond. It covers the main causes of the credibility crisis in social science, as well as practical solutions for individual researchers to address these issues in their own work.

All materials are available online at PDEL's [GitHub page](https://github.com/PolicyDesignEvaluationLab/teaching-credibility/). Funding for this project was generously provided by the Berkeley Initiative for Transparency in the Social Sciences ([BITSS](http://www.bitss.org/)) through a [Catalyst Grant](http://www.bitss.org/catalysts).

## Material
The goal of this module is to (1) demonstrate the existence of a credibility crisis in the social sciences, caused by a variety of incentives and practices at both the disciplinary and individual levels, and (2) provide practical steps for researchers to improve the credibility of their work throughout the lifecycle of a project.

### Presentation
The presentation ("`pdel_credibility_solutions.tex`") includes enough material for approximately six hours of instruction, and is divided into five parts:

1. **The Problem (27 slides).** This section discusses the credibility crisis in the social sciences, focusing on the evidence and causes of four common problems: (1) the *replication crisis*, (2) *publication bias*, (3) *p-hacking* (aka, fishing, researcher degrees of freedom, etc.), and (4) *misconduct and fraud*. It ends with a slide on how individual-level solutions can address some of these issues during the various stages of the research lifecycle, including *design*, *analysis*, and *dissemination* of results.
2. **Solutions I: Design (18 slides).** This section covers important steps to take during the research design phase, including (1) *registration* of studies in order to combat publication bias, and (2) *pre-analysis plans* to limit researcher degrees of freedom and p-hacking. It also flags the importance of IRB requirements during this phase.
3. **Solutions II: Analysis (38 slides).** This section covers how researchers can maintain the integrity of their data and files during the data analysis phase in order to ensure that their work is reproducible. This includes best practices for (3) *file management*, (4) *literate programming*, and (5) *version control* including a (very) beginner tutorial in GitHub. The use of *dynamic documents* is also mentioned but not covered in detail.
4. **Solutions III: Dissemination (36 slides).** This section covers basic steps for disseminating completed research in a way that enables others to replicate and build off of your work, including (6) *preparing files for replication*, and (7) *sharing data and code* in a way that is usable and *protects personally identifying information (PII)*. This section also offers a very basic introduction to (8) *meta-analysis*.
5. **Extra (5 slides).** This section briefly highlights some additional solutions to address the credibility crisis at the *institutional level*, and also presents a brief bibliography.  

Instructors should feel free to add/delete/edit/divide/reorder material as necessary to highlight the most salient issues and solutions for their courses.

### Activities
Suggestions for making this material more interactive include:

- **The Problem:** Have students play around with "p-hacking" tools, such as https://fivethirtyeight.com/features/science-isnt-broken/, http://www.nicebread.de/introducing-p-hacker/, or https://macartan.shinyapps.io/fish/.
- **Solutions I: Design:** Have students spend some time on the AEA, EGAP, and/or OSF websites, creating and setting up an account, and exploring the format of existing projects and pre-analysis plans.
- **Solutions II: Analysis:** Expand the very brief GitHub exercise, creating a course repository and having students experiment with forking, branching, and collaborating.
- **Solutions III: Dissemination:**  Have students set up accounts on Harvard's Dataverse or OSF, and/or have them walk through some of the *preparing for replication* steps with their own files.

### Assignments
Suggested assignments include:
- **Replicating a paper:** Have students replicate a paper following the methods in *Solutions III: Analysis, prepping files for replication*, and report whether or not it replicates and what issues they had. The assignment could also include tweaking or extending the original models to illustrate researcher degrees of freedom, or analyzing a sample of the original data to see if it replicates the results of the full dataset.
- **Analyzing an instructor provided dataset.** Give all students the same dataset and ask them to develop an appropriate model to test an instructor-provided hypothesis, submitting their code and results. Aggregating the results across the class will illustrate researcher degrees of freedom in action (assuming students don't share code :)).
- **Reviewing a potential journal article.** Have students review a working paper and submit a short write-up regarding why it should be accepted/rejected. Students could be directed to pay specific attention to the author's choices (degrees of freedom) and how these may have affected the results. The paper could also be censored for some/all of the class (like "design-based publication") to hide the results, forcing the reviewers to assess the paper on theory and design only.

## Folder Contents
This teaching module includes the following files and folders:

- **presentation/**
  - `images/` — Folder containing images used in presentation. The Beamer presentation will fail to compile unless these images are available in the "images/" directory.
  - `pdel_credibility_solutions.tex/pdf` — Presentation of teaching modules in Beamer slide format.
  - `pdel_credibility_solutions_notes.md/pdf` — Notes to accompany presentation in Markdown and PDF format.
- `README.md` — This Markdown file!

*These materials are licensed under Creative Commons BY-NC 4.0. You are free to share and adapt them for any non-commercial purpose with proper attribution. Please cite as: Clark, J., Desposato, S., and McIntosh, C. 2017. "How to improve the credibility of (your) social science: A practical guide for researchers." Policy Design and Evaluation Lab (PDEL). University of California, San Diego.*
