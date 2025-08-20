# MUDE workbook 2025

This repository contains MUDE Files from the 2025-2026 academic year. MUDE stands for Modelling, Uncertainty and Data for Engineers, a required module in the MSc programs from the faculty of Civil Engineering and Geosciences at Delft University of Technology in the Netherlands. Note that the MUDE Textbook is published separately: for the 2025-26 academic year, see [mude.citg.tudelft.nl/book/2025](https://mude.citg.tudelft.nl/book/2025).

The primary purpose of this repository is to share the weekly assignments and solutions: programming assignments (PA), workshops (WS) and group assignments (GA). This is almost entirely Jupyter Notebooks. We have really shared everything, work in progress and all, so while there is a tremendous amount of material here, it will certainly take some time to sort through it if you are not intimately familiar with MUDE. To help with this matter, you might want to have a look at the presentation the presentation _Enhancing Student Experience While Modernizing the Curriculum,_ available at [doi.org/10.5281/zenodo.10879193](https://doi.org/10.5281/zenodo.10879193): the target audience was TU Delft staff in other faculties, but there is a general overview of MUDE that may be helpful.

The assignments mentioned above (PA, WS, GA) are located in directory `book/`. During the academic year, these are included as private submodules, release the assignments one-by-one. At the end of the course, the assignment repository will be made public.

The explanation in this file is written by Robert Lanzafame, the MUDE Module Manager for the 2023-24 and 2024-25 academic years, and Tom van Woudenberg, the IT Coordinator for the 2025-26 academic years. For questions or additional information about MUDE, please get in touch with the current MUDE Team at MUDE-CEG@tudelft.nl.

## License and Referencing

Unless otherwise specified herein, all files in this repository are released under a Creative Commons Attribution 4.0 International (CC BY 4.0) license. This means that you can share and adapt the material in any medium or format, even for commercial purposes, as long as you give appropriate credit, provide a link to the license, and indicate if changes were made. Please note that because of grading, the assignments are private during the academic year and releases on a weekly basis. At the end of the course, all material will be released publicly.

In general, we ask that you use the following citation when referencing these materials:

> MUDE Team (2025) Modelling, Uncertainty and Data for Engineers (MUDE) Files. https://github.com/TUDelft-MUDE/workbook-2025. CC BY 4.0 License.

A complete list of contributors is maintained in the file `CITATION.cff`, and can be used in place of "MUDE Team" in the citation above, as desired. If you wish to refer to a subset of files, please refer to a specific _topic_ in its entirety, using the following format:

> `<AUTHORS>` (2025) `<TOPIC>` Files from Modelling, Uncertainty and Data for Engineers (MUDE). https://github.com/TUDelft-MUDE/workbook-2025. CC BY 4.0 License.

Due to the complex nature of MUDE and the large size of the MUDE Team, the metadata associated with this release of files is likely to require correction; therefore versioning is used to document updates to the source code. The version number has format `v2025.B.C` where minor corections will advance C and more significant updates (e.g., adding missing authors, updating licensing information, etc.) will advance B. The "2025" part of the version number will never change, as this will help distinguish releases in future years, as well as to be comparable with the MUDE Textbook, which uses a similar versioning scheme (e.g., MUDE Textbook and MUDE Files from the 2025-26 academic year are both versioned as `v2024.B.C`). A complete list of versions can be found in the GitHub Releases page. As we are not editing the contents of the files, only the metadata associated with them, we do not anticipate that it is necessary to include the version number in the citation recommended above.

### Using MUDE Materials with Your Students

We understand that it can be distracting to students to include information about licenses and references in the materials you share with them. To avoid such distractions, yet still conform to the terms of use described above, we recommend that you do the following:

1. On any file that is derived from MUDE Files, include a small note such as: "MUDE (2025)" or "Made with MUDE Materials (2025)," depending on the extent to which materials have been reused.
2. On the course syllabus, website or within other general course information, include the reference (as described above), as well as an explanation about which files were used and how they were modified (if at all). 

More information on 'How to MUDE?' is available on [this website](https://mude.citg.tudelft.nl/teacher)

Finally, if you use MUDE materials, please let us know! We are sharing them with an open license because we think they are useful, but we also hope that it will encourage others to do the same. Pull requests or emails (MUDE-CEG@tudelft.nl) are always welcome.

### How to View and Use the Files Herein

The easiest way to view the contents of the assignments is to open the website: https://mude.citg.tudelft.nl/workbook-2025. Note that during the academic year, assignments are released one-by-one. At the end of the course, the assignment repository will be made public.

The most complete way to view the contents of this repository is to clone it and use an IDE that is capable of rendering Jupyter notebooks, HTML, Markdown and Python files. For example, Visual Studio Code or Jupyter Lab.

The Jupyter notebooks were designed to be executed by students on their personal computers using a Conda environment created during week 1 of the module and used regularly by students throughout the semester; a specification can be found in the [programming assignment of that week](https://github.com/MUDE-2025/PA1.1/blob/main/environment.yml). Note that packages were added sequentially in each week on an as-needed basis, so you may need to add packages manually for some assignments. In some cases, a new environment was created for a particular week, and instructions can typically be found in the various assignment files.

### Acknowledgements

In addition to the generous support of the faculty of Civil Engineering and Geosciences at Delft University of Technology (as also described on the [Credits page of the MUDE Textbook](https://mude.citg.tudelft.nl/book/2025/credits)), a tremendous thank you goes out to our MUDE students for their role in the constant refinement of MUDE materials. In particular: the first year students whose constant feedback helped influence the redesign of MUDE for year 2 (2023-24); as well as the many MUDE teaching assistants: for those in the first year (2022-23) who, like the MUDE teachers themselves had no idea what MUDE was (yet!); and the brave students from the first and second years who were motivated to help teachers make MUDE even better for the next generation of students. Finally, a special thank you goes to the colleagues who overcame fears and challenges associated with the "new" (to us) way of working with Jupyter ecosystem: your willingness to learn and adapt to improve your teaching is truly inspiring!

Rok Stular developed the original web server and CI/CD pipeline concepts for the 2023-24 academic year. These were completely revised and set up for the 2024-25 academic year by Kwangjin Lee.

Tom van Woudenberg gets a special mention for his thorough review of every file in all of the weeks he was involved in MUDE as a teacher, which was most of them (far above average). Robert Lanzafame was responsible for implementing many of the changes in year 2 that gave MUDE its unique (albeit complicated) character: for example, a consistent notebook structure, assignment types and use of open source websites. Sandra Verhagen is a hero for leading the MUDE Team as Module Manager of year 1: keeping over 50 colleagues on track to deliver a brand new module based on Jupyter notebooks and Python when very few of us had any experience with it, during a year where the entire curriculum was new, all while keeping students satisfied and producing overall positive results---miraculous.

As it is impossible to indicate the contributions of all MUDE TA's individually, they are listed [here](https://mude.citg.tudelft.nl/teacher/topics_people.html)

## Overview of MUDE Topics

This is a list of topics, each of which has its own subsection herein containing lists of authors, contributors and materials that are _not_ included in the CC BY license of this repository, along with any additional information that may be relevant. The topics are listed here in weekly order as they were covered during the 2024-25 academic year. The numbering "Week Q.W," where "Q" refers to Quarter 1 or 2, each of which has 8 weeks of instruction ("W").

For an overview of the content (no author / contribution details), see the [2025 overview page](https://mude.citg.tudelft.nl/2025/overview.html).

Note that a Programming Assignments (PA) is provided each week, but are collectively considered a unique topic. This has to do with the way programming is integrated into the other topics of MUDE; for a pedagogical discussion of this (as well as a general overview of MUDE), see the presentation _Enhancing Student Experience While Modernizing the Curriculum,_ available at [doi.org/10.5281/zenodo.10879193](https://doi.org/10.5281/zenodo.10879193).

Unless otherwise noted, authors typically were teachers, PhD's and postdocs that played a significant role in designing and developing the materials, whereas contributors played a valuable role, albeit a relatively minor one, for example: reviewing materials, suggesting case studies, formatting digital files and (especially for teaching assistants) giving valuable feedback as to the appropriate level of difficulty and quality of the assignments.

to be written