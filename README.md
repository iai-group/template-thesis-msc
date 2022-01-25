# IAI thesis template

This repository provides a template for an MSc thesis. This repository is synced with the Overleaf project [IAI thesis template - master](https://www.overleaf.com/read/mtmtjzbtbwbm).

* If you prefer working on Overleaf, 
  - Make a copy of the project by going one level up (click up arrow) and select the `IAI thesis template` project and select `More -> Make a Copy`
  - Rename the project to reflect your thesis (e.g, include your names or title and year MSc-2022-Jane-Jon)
* If you prefer using own editor and compiler you can create new GitHub repo based on this template repository.
  - In the cloned GitHub repo the main file is `msc-thesis.tex`.
  - Rename the repository to reflect your thesis (e.g, include your names or title and year MSc-2022-Jane-Jon)

## Compiling


```shell
pdflatex msc-thesis.tex
```

## Usage


Change these in `*-thesis.tex`

| Command           | Description                                                       |
|-------------------|-------------------------------------------------------------------|
| `\title`          | May use `\\` to force line breaks                                 |
| `\authors`        | Multiple authors should be separate with `,` and `and`            |


* `Internal Supervisors`, `External Supervisors` can be changed in `uis-thesis.cls`
* If you only have one `Internal Supervisor` remove the second supervisor. 
* If you do not have any `External Supervisors` you may remove it.