# Knowledge-based Disease Recommender System

The aim of this project is to aid healthcare practitioners as well as people who want to take the responsibility of their healthcare in their own hands in generating a basic diagnosis. This will help reduce cases of misdiagnosis in cases where healthcare practitioners are less-experienced, patients are from a variety of geographical regions, races and age-groups, and when diseases or symptoms are rare.

<img src="https://github.com/RuchitaGarde/Health-Recommender-System/blob/master/UI.PNG" width="500px" height="350px"/>

We propose a Knowledge-based Disease Recommender System consisting of: (1) A user-interface, (2) A SPARQL query endpoint and (3) The ontology holding the knowledge about diseases and their related symptoms.

This repository contains:
1. The disease-symptom-ontology (owl file) which forms the knowledge base
- We created a mapping between diseases and symptoms, which can be queried using SPARQL to get a list of diseases or symptoms based on your input.
2. ICD-10 Disease Codes
- This ontology contains ICD-10 disease codes. It was important that disease codes are displayed instead of disease names for purposes of accuracy, ease of use and maintainability.
3. GUI
- This folder containes html, css and js files for creating the user interface of the recommender system. Open the index.html file to see the UI. This is work under progress.
4. Research Report
- This report contains detailed information about the aim of the project, problem statement, related work including including knowledge-based systems, ICD10 disease codes, web ontology language, use-case development, project block diagram, implementation, results, data-mining techniques applied for post-processing, screenshots to show as proof and results.
5. Presentation Slides

Thank you  [Manasa Potluri](https://www.linkedin.com/in/manasa-potluri/), [Jay Palan](https://www.linkedin.com/in/jay-palan-325197133/) and [Mingrui Han](https://www.linkedin.com/in/mingrui-ray-han-25bba3107/) for contributing to this project.



