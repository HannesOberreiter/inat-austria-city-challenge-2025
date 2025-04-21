# City ChallengeAustria 2025

Repository containing live and post analysis of the Austria City Challenge edition of iNaturalist and Observation.org.

## Tools

- [iNaturalist API](https://www.inaturalist.org/)
- [Observation.org API](https://observation.org)
- [R](https://www.r-project.org/)
- [Quarto](https://quarto.org/)
- [Package version control renv](https://rstudio.github.io/renv/articles/renv.html)

## Build and Hosting

The build is automatically done with github actions and deployed to github pages. Data is fetched on build from the API's which have some usage limits, therefore the build takes quite a while (few tens of minutes). The `renv.lock` file is used to ensure reproducibility of the analysis and build.
