ai_assisted_bioinformatics
==============================

A template repository for AI-assisted Bioinformatics

Project Organization
------------
```
├── README.md          <- The top-level README for developers using this project.
├── config             <- Configuration options for the analysis.
|   ├── config.yaml    <- Snakemake config file.
|   └── samples.tsv    <- A metadata table for all the samples run in the analysis.
├── notebooks          <- Jupyter or Rmd notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
├── resources          <- Place for data. By default excluded from the git repository.
│   ├── external       <- Data from third party sources.
│   └── raw_data       <- The original, immutable data dump.
├── results            <- Final output of the data processing pipeline. By default excluded from the git repository.
├── sandbox            <- A place to test scripts and ideas. By default excluded from the git repository.
├── workflow           <- Place to store the main pipeline for rerunning all the analysis.
│   ├── envs           <- Contains different conda environments in .yaml format for running the pipeline.
│   ├── rules          <- Contains .smk files that are included by the main Snakefile, including common.smk for functions.
│   ├── scripts        <- Contains different R or python scripts used by the script: directive in Snakemake.
│   ├── Snakefile      <- Contains the main entrypoint to the pipeline.
├── workspace          <- Space for intermediate results in the pipeline. By default excluded from the git repository.
--------
```
