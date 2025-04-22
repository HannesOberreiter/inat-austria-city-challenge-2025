# City Challenge Austria 2025 Analysis

Dieses Repository enthält Live- und Post-Analysen der österreichischen City Challenge von iNaturalist und Observation.org.

## Verwendete Tools

- [iNaturalist API](https://www.inaturalist.org/)
- [Observation.org API](https://observation.org)
- [R](https://www.r-project.org/)
- [Quarto](https://quarto.org/)
- [Paketversionskontrolle mit renv](https://rstudio.github.io/renv/articles/renv.html)

## Build und Hosting

Der Build-Prozess wird automatisch über GitHub Actions ausgeführt und auf GitHub Pages bereitgestellt. Die Daten werden während des Builds von den APIs abgerufen. Aufgrund von Nutzungslimits der APIs kann der Build-Vorgang einige Zeit in Anspruch nehmen (mehrere zehn Minuten). Die Datei `renv.lock` stellt die Reproduzierbarkeit der Analyse und des Builds sicher.
