# helm-chart
helm-chart

from: https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417

**https://team-parallax.github.io/helm-charts**

## TODO
create ci/cd to package the charts with:
```
helm lint helm-chart-sources/*
helm package helm-chart-sources/*
helm repo index --url https://mattiaperi.github.io/helm-chart/ .
```
