# psych-260-2023-spring

Syllabus for PSYCH 260/BBH 203 taught by Rick Gilmore in the spring of 2023.

This repo contains the code and materials to generate the course syllabus.

We use the `bookdown` package in R to render the site to the `docs/` directory.
Source files are found in `src/`.

To render the site:

1. Clone the repository
2. Run `bookdown::render_book('src')` from the project's root directory.
3. View the locally rendered files/website in `docs/`.

**NOTE**: There is a companion repository with the lecture notes here: <https://github.com/psu-psychology/psych-260-2023-spring-notes>.

## Contents

- `src/`: Source `.Rmd` and supporting files.
- `docs/`: Target/output directory of rendering process. You may view the rendered HTML files here.
