# HPC Course on Lonestar6

This repository contains a Bookdown-based HPC course scaffold for a Linux-based high-performance computing course centered on TACC Lonestar6 and SLURM.

## Build

Install bookdown if needed:

```r
install.packages("bookdown")
```

Then render:

```r
bookdown::render_book("index.Rmd")
```

The rendered site will appear in `docs/`.
