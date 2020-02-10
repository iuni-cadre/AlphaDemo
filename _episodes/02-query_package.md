---
title: "Demo01: Data access and reproducible packages (Hutchinson)"
teaching: 30
exercises: 0
questions:
- "How can you access the data and analyze them? How can you make your analysis reproducible?"
objectives:
- "Explain how fedreated login system work and CADRE data policy."
- "Explain how CADRE GUI-query builder can help find the data you want."
- "Explain how one can explore and analyze query result in notebooks."
- "Demonstrate the CADRE marketplace."
- "Explain how tools can be built from notebook code"
- "Explain how archives can be created from query results"
- "Explain how to combine tools with archives into reproducible packages"
keypoints:
- Web of Science and Microsoft Academic Graph have different output fields 
- Use the preview functionality in the GUI-query builder to quickly explore the data
- All your query and package results can be viewd in your notebook environment
- Naming your queries, tools, archives and packages will make keeping track of them much easier
- Mix and match tools with archives to explore combinations of code and data
---

> ## Getting Started
>- Login with your BTAA institutional account if you wish to use Web of Science data
>- Start your Jupyter Notebook from [https://cadre.iu.edu/gateway/jupyter](https://cadre.iu.edu/gateway/jupyter)
{: .prereq}

## Notebooks and script files
Notebooks and source code will be automatically downloaded to your personal Jupyter Notebook. They can also be found at the [GitHub repository](https://github.com/iuni-cadre/AlphaDemoCode).

The notebook illustrates a simple analysis step by step.
```
Notebook:  AlphaDemoCode/Demo 01/Feb_demo_01.ipynb
```

The following python script contains the same content but is modified for building CADRE tools.
```
Script:  AlphaDemoCode/Demo 01/Feb_demo_02.py
```

A requirement file is one way to include additional python packages
```
AlphaDemoCode/Demo 01/requirements.txt
```

## CADRE packages and tools
All packages, tools and archives in this demo will be created by you. They can be created and accessed from the CADRE Marketplace. [https://cadre.iu.edu/gateway/rac](https://cadre.iu.edu/gateway/rac) 

{% include links.md %}
