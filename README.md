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
pdflatex bsc/bsc-thesis.tex
```

## Usage


Change these in `*-thesis.tex`

| Command           | Description                                                       |
|-------------------|-------------------------------------------------------------------|
| `\title`          | May use `\\` to force line breaks                                 |
| `\authors`        | Multiple authors should be separate with `,` and `and`            |


* `Internal Supervisors`, `External Supervisors` and `Reviewers` can be changed in `uis-thesis.cls`
* Depending on BSc or MSc thesis change the text in `uis-thesis.cls` to `Bachelor's` or `Masters's` thesis
