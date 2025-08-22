# MUDE workbook 2025

This repository contains MUDE Files from the 2025-2026 academic year. MUDE stands for Modelling, Uncertainty and Data for Engineers, a required module in the MSc programs from the faculty of Civil Engineering and Geosciences at Delft University of Technology in the Netherlands. Note that the MUDE Textbook is published separately: for the 2025-26 academic year, see [mude.citg.tudelft.nl/book/2025](https://mude.citg.tudelft.nl/book/2025).

The primary purpose of this repository is to share the weekly assignments and solutions: programming assignments (PA), workshops (WS) and group assignments (GA). This is almost entirely Jupyter Notebooks. We have really shared everything, work in progress and all, so while there is a tremendous amount of material here, it will certainly take some time to sort through it if you are not intimately familiar with MUDE. To help with this matter, you might want to have a look at the presentation the presentation _Enhancing Student Experience While Modernizing the Curriculum,_ available at [doi.org/10.5281/zenodo.10879193](https://doi.org/10.5281/zenodo.10879193): the target audience was TU Delft staff in other faculties, but there is a general overview of MUDE that may be helpful.

The assignments mentioned above (PA, WS, GA) are located in directory `book/`. During the academic year, these are included as private submodules, release the assignments one-by-one. At the end of the course, the assignment repository will be made public.

## Contact

If you encounter any issues, report it by clicking the GitHub icon and lightbulb on the top right corner of this page. Or contribute directly by creating a pull request in the [repository](https://github.com/TUDelft-MUDE/book).

If you have questions on the content, contact the MUDE team at MUDE-CEG@tudelft.nl. If you have technical questions regarding this book, contact the IT-coordinator of MUDE (Tom): T.R.vanWoudenberg@tudelft.nl

## Versions and Releases

As the book consists of source code and a rendered website (HTML), versioning, releases and archives are handled in several ways. The README describes technical aspects of the book source code and supplemental publishing websites (e.g., Zenodo, PURE), whereas the [Credits Page](https://mude.citg.tudelft.nl/workbook-2025/credits) of the book describes copyright and citation information of the book contents (remember to adjust the URL for the appropriate year as needed). In general, the GitHub repository [TUDelft-MUDE/workbook-2025](https:github.com/TUDelft-MUDE/workbook-2025) and book URL [mude.citg.tudelft.nl/workbook-2025](https://github.com/TUDelft-MUDE/workbook-2025) should be used as primary links for the book and its source code, whereas Zenodo is used as an archive and DOI publisher.

[TeachBooks Versioning](https://teachbooks.io/manual/features/versioning.html) is used (a special type of semantic numbering for educational purposes) with generic format `v<academic_year>.<additions>.<errata>`, with an additional `.pre-release` added for incomplete books (e.g., `v2024.1.0` is the first complete version for 2024, while v2025.0.1.pre-release is an incomplete version for 2025). Releases on GitHub and Zenodo are only made for non-`.pre-release` versions.

Source code is versioned using Git and stored on GitHub in repository [TUDelft-MUDE/workbook-2025](https://github.com/TUDelft-MUDE/workbook-2025). Zenodo is used to archive the source code when the repository is complete. The metadata for this Zenodo record comes from the file `CITATION.cff`; besides updating the list of editors and the appropriate DOI for the Zenodo book record, no metadata should be changed in this file (use the README, Credits page and/or Zenodo book record instead).

A PDF of the book will eventually be generated and uploaded to the TU Delft Repository (PURE). The PDF is intended only for archival purposes in PURE and is not intended to be read.

Note that there are effectively two numeric ways of versioning the book: the version number (defined by git tags and GitHub Releases manually, according to the rules above) and the Zenodo-generated DOI. There should be a one-to-one correspondence between the two, but the Zenodo DOI will not necessarily be sequential. Because the Zenodo DOI is both a permanent identifier _and_ a hyperlink, it is used in the recommended citation format for the book and its chapters. If desired, the book version can also be used, but this should only be necessary if it is important to distinguish between two versions of the book that were published for the same academic year (e.g., if a major change was made after the first release of the book for that year).

## Using MUDE Materials with Your Students

We understand that it can be distracting to students to include information about licenses and references in the materials you share with them. To avoid such distractions, yet still conform to the terms of use described above, we recommend that you do the following:

1. On any file that is derived from MUDE Files, include a small note such as: "MUDE (2025)" or "Made with MUDE Materials (2025)," depending on the extent to which materials have been reused.
2. On the course syllabus, website or within other general course information, include the reference (as described on [the Credits Page](https://mude.citg.tudelft.nl/workbook-2025/credits)), as well as an explanation about which files were used and how they were modified (if at all).

More information on 'How to MUDE?' is available on [this website](https://mude.citg.tudelft.nl/teacher)

Finally, if you use MUDE materials, please let us know! We are sharing them with an open license because we think they are useful, but we also hope that it will encourage others to do the same. Pull requests or emails (MUDE-CEG@tudelft.nl) are always welcome.

## How to View and Use the Files Herein

The easiest way to view the contents of the assignments is to open the website: https://mude.citg.tudelft.nl/workbook-2025. Note that during the academic year, assignments are released one-by-one. At the end of the course, the assignment repository will be made public.

The most complete way to view the contents of this repository is to clone it and use an IDE that is capable of rendering Jupyter notebooks, HTML, Markdown and Python files. For example, Visual Studio Code or Jupyter Lab.

The Jupyter notebooks were designed to be executed by students on their personal computers using a Conda environment created during week 1 of the module and used regularly by students throughout the semester; a specification can be found in the [programming assignment of that week](https://github.com/MUDE-2025/PA1.1/blob/main/environment.yml). Note that packages were added sequentially in each week on an as-needed basis, so you may need to add packages manually for some assignments. In some cases, a new environment was created for a particular week, and instructions can typically be found in the various assignment files.