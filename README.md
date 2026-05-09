# Qiaoxin LI - Personal Homepage

This repository hosts my personal academic homepage:

**https://joosenli.github.io/**

It is built with Jekyll and GitHub Pages.

## Acknowledgement

This website was originally built based on the excellent
[AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) repository by RayeRen.
Many thanks to the original author for providing a clean, responsive, and easy-to-customize academic homepage template.

The current version keeps the academic structure of AcadHomepage while adding several more personal and dynamic features.

## What I Added

### Interactive Photo Walls

The homepage includes lightweight photo walls for sharing small pieces of life beyond research, including running, cooking, photography, and travel moments. The galleries are designed to feel warm and personal without distracting from the academic content.

### Personal Footprint Map

A hand-drawn style global map shows places I have lived, studied, visited, and plan to visit. Different pins distinguish home/lived experience, study/work, visited places, and upcoming visits.

### Modular News Board

The News section has been redesigned as a compact announcement board. Recent milestones are highlighted as modular cards, while older updates are folded into an archive to keep the homepage readable.

### Research-Oriented Homepage Content

The main page presents my research interests, publications, selected honors, education, and links to my CV, LinkedIn, and GitHub.

## Local Development

After installing the Ruby/Jekyll environment, run the site locally with:

```bash
bash run_server.sh
```

Then open:

```text
http://127.0.0.1:4000/
```

The main homepage content is edited in:

```text
_pages/about.md
```

Styles are mainly customized in:

```text
_sass/_page.scss
_sass/_sidebar.scss
```

## Credits

This site is based on:

- [RayeRen/acad-homepage.github.io](https://github.com/RayeRen/acad-homepage.github.io)

AcadHomepage is also influenced by:

- [mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)
- [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io)

Additional icons and web assets follow the licenses of their respective upstream projects.
