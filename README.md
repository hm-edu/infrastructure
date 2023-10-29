# k8s Deployment at HM

This repository maintains the deployment of a central k8s cluster hosted at the Munich University of Applied sciences.

In general it utilizes Flux CD and contains definitions:

* System-Upgrade-Controller
* Istio
* PKI-Portal
* Gitlab Runners
* Gitlab Workspaces
* Grafana & Prometheus
* Cert-Manager

To keep the dependencies up-to-date they are updated by the Renovate Bot.
