[![docs](https://github.com/dienerlab/template/actions/workflows/docs.yml/badge.svg)](https://github.com/dienerlab/template)

# 🦠🧬💻 Project Title

This repository contains scripts and additional data for XYZ.

The manuscript can be found at

> Title <br>
B Baggins, G The Gray <br>
bioRxiv 202X.Y; doi: https://doi.org/XYZ

## Repository organization

```bash
[project root]
├─ step1.rmd      # individual analysis steps
├─ step2.rmd
├─ data           # contains additional and generated data
│  ├─ data.csv
│  ├─ ...
├─ figures        # generated figures
│  ├─ fig1.png
│  └─ ...
└─ docs
   ├─ step1.html  # rendered and executed notebooks
   └─ step2.html
```

## Setup and installation

You will need a working miniforge or miniconda to start. You can follow the [installation
instructions here](https://github.com/conda-forge/miniforge?tab=readme-ov-file#install). After
create an environment with the included conda environment file.

Start by cloning the repository and cd-ing into it.

```bash
git clone https://github.com/dienerlab/[REPO]
cd [REPO]
```

```bash
conda env create -f conda.yml
```

After that activate the environment.

```bash
conda activate [NAME]
```

## Reproduce the analysis

### 1 - Preprocess the data | 📓 [notebook](step1.rmd) | 📊 [output](https://dienerlab.github.io/[REPO]/step1.html)

Aliqua magna nulla nulla laboris ipsum minim ad eu ipsum. Duis mollit sunt amet ex velit proident culpa dolor enim nostrud. Esse anim consequat minim aute proident reprehenderit in excepteur aliquip. Irure veniam elit elit do officia.

### 2 - Run the analysis for Figure 1 | 📓 [notebook](step2.rmd) | 📊 [output](https://dienerlab.github.io/[REPO]/step2.html)

Aliqua magna nulla nulla laboris ipsum minim ad eu ipsum. Duis mollit sunt amet ex velit proident culpa dolor enim nostrud. Esse anim consequat minim aute proident reprehenderit in excepteur aliquip. Irure veniam elit elit do officia.

## Getting help

For bug reports or feature request please submit [an issue](issues).

For general questions or getting help you can open a [discussion topic](discussions).