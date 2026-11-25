# Python Programming for Pharmaceutical Applications

**Add-on Certificate Course · 30 contact hours · B. Pharm First and Second Year**

Slides, hands-on notebooks and practice material for a beginner-friendly course that teaches Python from scratch and then applies it to pharmaceutical problems: calculations, data handling, visualization and statistics, cheminformatics, pharmacokinetics and an introduction to AI in drug discovery.

**New here? Start with the [Setup guide](docs/setup/setup-guide.md)** to install Python, VS Code or open Google Colab.

**Prakash Ukhalkar** · Educator · Mentor · Machine Learning, AI & Innovation  
Assistant Professor (MCA), PCCoE, Pune

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Prakash%20Ukhalkar-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prakash-ukhalkar) [![GitHub](https://img.shields.io/badge/GitHub-prakash--ukhalkar-181717?logo=github&logoColor=white)](https://github.com/prakash-ukhalkar) [![Website](https://img.shields.io/badge/Website-prakash--ukhalkar.github.io-0B2E59?logo=githubpages&logoColor=white)](https://prakash-ukhalkar.github.io)  
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/downloads/) [![VS Code](https://img.shields.io/badge/VS%20Code-Python%20%26%20Jupyter-007ACC?logo=visualstudiocode&logoColor=white)](https://code.visualstudio.com/docs/python/python-tutorial) [![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/documentation) [![Google Colab](https://img.shields.io/badge/Google%20Colab-free%20cloud%20notebooks-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/) [![License](https://img.shields.io/badge/License-see%20LICENSE.md-blue?logo=creativecommons&logoColor=white)](LICENSE.md)

Delivered with **[Spectratix Pharma Pvt. Ltd.](https://spectratixpharma.in/)**

---

## Course at a glance

| Module | Title | Hours |
|---|---|---|
| [1](modules/module-01-getting-started-with-python/) | Getting started with Python | 4 |
| [2](modules/module-02-programming-fundamentals-with-pharmacy-examples/) | Programming fundamentals with pharmacy examples | 5 |
| [3](modules/module-03-numpy-and-pandas-for-pharmaceutical-data/) | Handling pharmaceutical data with NumPy and Pandas | 5 |
| [4](modules/module-04-data-visualization-and-statistics-for-pharma/) | Data visualization and statistics for pharma | 5 |
| [5](modules/module-05-drug-discovery-pharmacokinetics-and-ai/) | Python in drug discovery, pharmacokinetics and AI | 6 |
| [6](modules/module-06-capstone-mini-project-and-assessment/) | Capstone mini-project and assessment | 5 |
| | **Total** | **30** |

Each module folder contains the **presentation** (PowerPoint), the hands-on **notebook** (Jupyter), and folders for **datasets** and **exercises**.

## How to use this repository

1. **Pick the tool you will use** (see the [setup guide](docs/setup/setup-guide.md)):
   * **Google Colab:** nothing to install, works in the browser.
   * **VS Code + Python + Jupyter extension:** recommended for your own laptop.
2. **Open the module notebook** and run the cells from top to bottom with `Shift + Enter`.
3. **Open in Colab:** in Colab choose *File ▸ Open notebook ▸ GitHub*, paste this repository's URL and pick the notebook.
   Direct links (one per module, added as each module is published):

   | Module | Notebook |
   |---|---|
   | 1 · Getting started with Python | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prakash-ukhalkar/python-for-pharmaceutical-applications/blob/main/modules/module-01-getting-started-with-python/notebook/Module_1_Getting_Started_with_Python.ipynb) |

   For later modules, use the same address and change the folder and file name:
   `https://colab.research.google.com/github/prakash-ukhalkar/python-for-pharmaceutical-applications/blob/main/modules/<module-folder>/notebook/<notebook-name>.ipynb`
4. **Local setup for later modules** (NumPy, Pandas, Matplotlib and so on):
   ```bash
   python -m venv .venv
   .venv\Scripts\activate          # Windows   (macOS/Linux: source .venv/bin/activate)
   pip install -r requirements.txt
   ```

## Repository structure

```text
.
├── README.md                     <- you are here
├── LICENSE.md                    <- CC BY-NC-SA 4.0 (content) and MIT (code)
├── requirements.txt              <- Python packages for the whole course
├── .gitignore
├── docs/
│   ├── course-material/          <- course guidelines (modules, outcomes, hours)
│   ├── course-outline.md         <- objectives, outcomes and curriculum summary
│   └── setup/setup-guide.md      <- install Python, VS Code, Colab, Anaconda
└── modules/
    ├── module-01-getting-started-with-python/
    │   ├── README.md
    │   ├── presentation/         <- .pptx slides
    │   ├── notebook/             <- .ipynb hands-on notebook
    │   ├── datasets/             <- data files used by the module
    │   └── exercises/            <- extra practice problems
    ├── module-02-.../            <- same layout for modules 2 to 6
    └── ...
```

## Learning approach

* Short concept explanation, then live coding and lab practice. About **70 % of the time is hands-on**.
* **Python first, pharmacy later:** the first session teaches the language with everyday examples; pharmaceutical problems are added step by step.
* Every notebook explains each code cell **before and after** running it, and ends with practice problems, a self-check and public references.

## Important note

The calculators and examples in this repository are **teaching examples**. Do not use them for real patient dosing, formulation or quality decisions without verified references and professional checks.

## License

Course material (slides, notebook text, documents) is licensed under **CC BY-NC-SA 4.0** and source code under the **MIT License**. See [LICENSE.md](LICENSE.md) for details.

---

<div align="center">

### Prakash Ukhalkar
**Educator · Mentor · Machine Learning, AI & Innovation**  
Assistant Professor (MCA), PCCoE, Pune

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Prakash%20Ukhalkar-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prakash-ukhalkar) [![GitHub](https://img.shields.io/badge/GitHub-prakash--ukhalkar-181717?logo=github&logoColor=white)](https://github.com/prakash-ukhalkar) [![Website](https://img.shields.io/badge/Website-prakash--ukhalkar.github.io-0B2E59?logo=githubpages&logoColor=white)](https://prakash-ukhalkar.github.io)

*Python Programming for Pharmaceutical Applications · Add-on Certificate Course with [Spectratix Pharma Pvt. Ltd.](https://spectratixpharma.in/)*  
© 2026 Prakash Ukhalkar

[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0%20%7C%20MIT-blue?logo=creativecommons&logoColor=white)](LICENSE.md)

</div>

---

<div align="center">

## For more details, contact

**[Spectratix Pharma Pvt. Ltd.](https://spectratixpharma.in/)**, Pune

[![Website](https://img.shields.io/badge/Website-spectratixpharma.in-1F5C4F)](https://spectratixpharma.in/) [![Email](https://img.shields.io/badge/Email-contact%40spectratixpharma.in-B98A2E)](mailto:contact@spectratixpharma.in) [![Phone](https://img.shields.io/badge/Phone-9579159287-0B2E59)](tel:+919579159287)

</div>
