# AK8S - Kubernetes Engine Samples
This repository contains sample applications used in introductory Kubernetes labs FOR
[Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine/).

See the following resources to learn more:

- [Google Kubernetes Engine - Quickstart](https://cloud.google.com/kubernetes-engine/docs/quickstart)

# Kubernetes extra cheat sheet

* [kubectl overview](https://kubernetes.io/docs/reference/kubectl/overview/)
* [kubectl cheat sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
* [kubectl reference guide](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#-strong-getting-started-strong-)
* [Kubernetes API reference guide](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.18/)
* [Minikube manual](https://minikube.sigs.k8s.io/docs/)

# Bash extra cheat sheet

* [Bash cheat sheet](https://devhints.io/bash/).

* [Bash internal variables](https://www.gnu.org/software/bash/manual/html_node/Bash-Variables.html/).

* [Bash reference manual](https://www.gnu.org/software/bash/manual/html_node/).

* Get pod ordinal number:
```bash
[[ `hostname` =~ -([0-9]+)$ ]] || exit 1
ordinal=${BASH_REMATCH[1]}
```
# Other cheat sheets

* [JSONPath cheat sheet](https://kubernetes.io/docs/reference/kubectl/jsonpath/)
* [Go template reference guide](https://golang.org/pkg/text/template/#pkg-overview)


# Security guidelines

[Docker/Kubernetes security guidelines](https://cheatsheetseries.owasp.org/cheatsheets/Docker_Security_Cheat_Sheet.html)
