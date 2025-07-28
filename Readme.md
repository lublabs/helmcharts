# LubLabs Helm Charts

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/lublabs-charts)](https://artifacthub.io/packages/search?repo=lublabs-charts)

## Development

1. Modify/extend chart.
2. Adjust documentation.
3. Adjust changelog.
4. Adjust Chart.yaml
5. `helm package -d docs ./lublabs-generic`
6. `helm repo index --url https://lublabs.github.io/helmcharts ./docs`
