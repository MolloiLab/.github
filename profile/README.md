# MolloiLab
GitHub Organization for the Imaging Physics Laboratory at UCI

## Structure of Organization
The MolloiLab GitHub organization is structured into two main categories: Packages and Projects.

**Packages**: Key packages are named using "CamelCase" and end with ".jl" to indicate that they are proper Julia packages. These packages contain reusable code and functionality that can be utilized across multiple research projects. They are designed to be modular, well-documented, and easily importable into other projects. The packages are further categorized into three main areas:
1. Imaging Physics
2. Deep Learning
3. Data Engineering

**Projects**: Research projects are named using "kebab-case" and are standalone repositories for individual research endeavors. Examples include `cac-dual-energy` and `hd-loss`. These project repositories typically pull from various Julia packages, including our key packages, to perform analysis and generate results for publication in research papers. Each project repository contains the necessary code, data, and documentation specific to that particular research project.

By organizing our GitHub repositories into Packages and Projects, we aim to promote code reusability, maintain a clear separation between reusable code and project-specific implementations, and facilitate collaboration among lab members. This structure allows us to efficiently develop and maintain our Julia packages while keeping research projects focused and self-contained.

## Key Packages
### Imaging Physics
- **CalciumScoring.jl**: [Package description and purpose]
- **PerfusionImaging.jl**: [Package description and purpose]
- **MaterialDecomposition.jl**: [Package description and purpose]

### Deep Learning
- **DistanceTransforms.jl**: [Package description and purpose]
- **Losers.jl**: [Package description and purpose]
- **ComputerVisionMetrics.jl**: [Package description and purpose]

### Data Engineering
- **OrthancTools.jl**: [Package description and purpose]

## Onboarding
1. **Learn Advanced Scientific Computing**: Watch every video in this 6-part lecture series on [advanced scientific computing](https://www.youtube.com/playlist?list=PL-G47MxHVTewUm5ywggLvmbUCNOD2RbKA). Pay close attention to Git/GitHub and all of the fundamental software engineering best practices. This should only take half a day.

2. **Join a Research Project**: Find the repository associated with the research project you are joining. Make sure you get read access (not write access yet) so that you can fork the repo on your own GitHub.

3. **Contribute to the Project**: Fork the repo, make some changes according to your mentor's recommendation, and once complete, submit a pull request to the main repo (the original one, not your own forked copy) and wait for your mentor to review changes. Repeat this process until you and your mentor are comfortable making you a collaborator on the project.

4. **Improve Main Packages**: After working on the research project for a while, you will hopefully find ways to improve the main packages driving this lab. Once you spot areas of needed improvement, repeat the previous process again - fork the main package, commit changes, submit a PR, wait for review. Eventually, you will be invited to be a direct collaborator on the main packages.

5. **Become a Mentor**: Finally, take the crucial step in becoming a mentor to more junior students and begin this process all over again, this time from the side of a mentor. Help new students onboard, review their pull requests, and guide them through the process of contributing to research projects and main packages.

By following this onboarding process, new lab members will gain a solid foundation in advanced scientific computing, learn how to contribute effectively to research projects and packages, and eventually become mentors themselves, fostering a collaborative and supportive environment within the MolloiLab.