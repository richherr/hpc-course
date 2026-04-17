# HPC Course on Lonestar6

This repository contains a Bookdown-based HPC course scaffold designed for a Linux-based high-performance computing course centered on TACC Lonestar6 and SLURM.

## Included chapters

1. Introduction to HPC
2. Linux Fundamentals for HPC
3. SLURM: Job Scheduling on HPC Systems
4. Compiling C and C++ on HPC Systems
5. Parallel Computing with MPI and OpenMP
6. Containers and Reproducible HPC
7. Capstone Project: End-to-End HPC Workflow

## Build

Install bookdown in R if needed:

```r
install.packages("bookdown")
```

Then render:

```r
bookdown::render_book("index.Rmd")
```

Output will appear in `_book/`.
