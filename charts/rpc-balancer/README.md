# Ethereum RPC balancer

A Helm chart to deploy [Ethereum RPC balancer](https://github.com/ai-ia-org/rpc-balancer) to kubernetes cluster

## Prerequisites

- Kubernetes 1.19+
- Helm 3+

## Get Helm Repository Info

```console
helm repo add ai-ia https://ai-ia-org.github.io/helm-charts
helm repo update
```

_See [`helm repo`](https://helm.sh/docs/helm/helm_repo/) for command documentation._

## Install Helm Chart

```console
helm install [RELEASE_NAME] ai-ia/rpc-balancer
```
_See [configuration](#configuration) below._
_See [helm install](https://helm.sh/docs/helm/helm_install/) for command documentation._
## Uninstall Helm Chart

```console
helm uninstall [RELEASE_NAME]
```
_See [helm uninstall](https://helm.sh/docs/helm/helm_uninstall/) for command documentation._
This removes all the Kubernetes components associated with the chart and deletes the release.

## Upgrading Chart

```console
helm upgrade [RELEASE_NAME] ai-ia/rpc-balancer
```

## Configuration

See [Customizing the Chart Before Installing](https://helm.sh/docs/intro/using_helm/#customizing-the-chart-before-installing). To see all configurable options with detailed comments:

```console
helm show values ai-ia/rpc-balancer
```
