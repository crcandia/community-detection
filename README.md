# Community Detection in Networks

An interactive educational website on **community detection in complex networks**, developed as part of the course **Networks and Complex Systems** by **Cristian Candia, Ph.D.** and published through **CRiSS Lab**. The site combines theory, mathematical intuition, and interactive visualizations to explain how communities emerge in graphs and how different algorithms identify them.

## Overview

This resource introduces the core ideas behind community detection in network science. It covers both **objective-function approaches** and **probabilistic/generative approaches**, moving from classical methods based on **modularity optimization** to more advanced ideas such as **spectral methods** and **stochastic block models**.

The site includes:

- A **theory section** with conceptual explanations, equations, and algorithmic intuition
- An interactive **visualization section** to compare methods and graph topologies
- A bilingual interface (**Spanish / English**)
- A responsive layout for desktop and mobile

## Topics Covered

The website covers the following topics:

- Introduction to the community detection problem
- Modularity and the modularity matrix
- Greedy modularity optimization
- Spectral methods
- Girvan–Newman
- Louvain
- Leiden
- Infomap
- Label Propagation
- Stochastic Block Models (SBM)
- Robustness and comparison of methods

## Educational Goal

The goal of this website is to provide a rigorous but intuitive introduction to community detection for students and researchers working in:

- Network science
- Complex systems
- Computational social science
- Data science
- Applied graph analysis

It is designed not only to explain **how algorithms work**, but also **when their assumptions differ**, **what their limitations are**, and **why different methods may produce different partitions on the same graph**.

## Features

- Interactive article format
- Mathematical notation rendered with **MathJax**
- Dynamic network visualizations
- Responsive user interface
- Language switch between Spanish and English
- Structured navigation across theoretical and algorithmic sections
- Metadata and social preview support for web sharing

## Tech Stack

This site is built as a static web resource using:

- **HTML**
- **CSS**
- **Vanilla JavaScript**
- **SVG** for explanatory diagrams and network illustrations
- **MathJax** for equations
- **Google Fonts** for typography

## Repository Structure

A typical structure for deployment is:

```text
.
├── index.html
├── index-en.html
├── assets/
├── site.webmanifest
└── README.md
```

## Acknowledgment

This website was created as an educational resource for teaching community detection in networks, with an emphasis on combining formal rigor, visual intuition, and algorithmic understanding.