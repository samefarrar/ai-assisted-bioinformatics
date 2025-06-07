## Project Overview

This project is a template repository for a workshop I will be giving to my lab members about doing AI-assisted bioinformatics.

### Intended Use

1) Members of the lab can visit the repository link (on GitHub), and click the "Open in GitHub Codespaces"
2) They will then get access to a GitHub Codespaces with this repository, and will receive an API key from me.
3) From then, they will have the opportunity to try AI assisted bioinformatics with a few "example datasets".

The aim of this repository is to make it as easy for them to get started (even for people with little bioinformatics experience) as possible.
We're trying to minimize "time to first a-ha moment", where they realise how powerful these models are.

## Workflow

Users are used to using Snakemake. This is a pipeline-ing package that helps to build reproducible scientific results.

-   The main workflow is defined in `workflow/Snakefile`.
-   Configuration is in `config/config.yaml` and `config/samples.tsv`.
-   Conda environments for pipeline steps are in `workflow/envs/`.
