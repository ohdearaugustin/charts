Helm Charts
===========

This repository (will) contain(s) several different helm charts.

- trilium-notes ([zadam/trilium](https://github.com/zadam/trilium))

Usage
-----
This section describes the usage of this repository.

How to add repo
***************
```
helm repo add ohdearaugustin https://ohdearaugustin.github.io/charts/
"ohdearaugustin" has been added to your repositories
```

How to install a chart
***************
Just `helm install ohdearaugustin/<chart>`.

For more information on using Helm, refer to the Helm documentation.

CI
--
All charts are tested on pull requests, with the following versions of Kubernetes:

- v1.17.11
- v1.18.8
- v1.19.4

This will change over the time.
