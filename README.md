# IAS Website Redesign — Preview

Temporary preview of the redesigned IAS website. Served via GitHub Pages at:

**https://innovative-assessment-solutions.github.io/ias-website-preview/**

This repo exists only to give reviewers a stakeholder-shareable URL for the
in-progress redesign. It is **not** the production site. The production site
lives at [innovativeassessmentsolutions.com](https://innovativeassessmentsolutions.com)
and is served from the [main website repo](https://github.com/innovative-assessment-solutions/website).

## Notes for reviewers

- The site is under active revision. Anything can change day-to-day.
- Feedback is welcome by contacting Jonathan Templin directly.

## Notes for maintainers

- The site is built with [Quarto](https://quarto.org). To preview locally:
  `quarto preview`
- GitHub Actions renders and deploys on every push to `main`.
- Content mirrors the `redesign` branch of the main website repo, minus the
  CNAME file (so this repo serves at the default github.io URL instead of the
  custom domain).
