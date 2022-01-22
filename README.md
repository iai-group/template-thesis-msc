# IAI thesis template
This repository provides template for BSc and MSc theses. This repository is synced with the Overleaf project https://www.overleaf.com/read/mtmtjzbtbwbm

* If you prefer working on Overleaf, 
  - Make a copy of the project by going one level up (click up arrow) and select the `IAI thesis template` project and select `More -> Make a Copy`
  - Rename the project to reflect your thesis (e.g, include your names or title and year Bsc-2022-Jane-Jon)
  - In the Overleaf change the main file by navigating to `Menu -> Settings -> Main document` to `bsc/bsc-thesis.tex` or `msc/msc-thesis.tex` depending on if you are working BSc or MSc thesis.
* If you prefer using own editor and compiler you can clone this repository and use the template.
  - In the cloned GitHub repo compile the `bsc/bsc-thesis.tex` or `msc/msc-thesis.tex` depending on if you are working BSc or MSc thesis.
  - Rename the repository to reflect your thesis (e.g, include your names or title and year Bsc-2022-Jane-Jon)

## Compiling


```shell
pdflatex example
```


### Package Commands

The package supports the following commands:

| Command           | Description                                                       |
|-------------------|-------------------------------------------------------------------|
| `\title`          | May use `\\` to force line breaks                                 |
| `\authors`        | Multiple authors should be separate with `,` and `and`            |
| `\specialization` | Currently, only `cs, ds, ee, med` are supported; more to be added |
| `\uiscover`       | Display cover page, values 1-9 provide different color schemes    |
| `\uisbackcover`   | Display back cover using the same color schemes as front cover    |
| `\faculty`        | Currently, only `tn` is supported                                 |
| `\restricted`     | Use to print `Restricted Access` on cover page                    |
