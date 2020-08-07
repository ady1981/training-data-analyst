# AK8S - Kubernetes Engine Samples
This repository contains sample applications used in introductory Kubernetes labs FOR
[Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine/).

See the following resources to learn more:

- [Google Kubernetes Engine - Quickstart](https://cloud.google.com/kubernetes-engine/docs/quickstart)

# Bash extra cheat sheet

* [Bash cheat sheet](https://devhints.io/bash/).

* [Bash internal variables](https://www.gnu.org/software/bash/manual/html_node/Bash-Variables.html/).

* [Bash reference manual](https://www.gnu.org/software/bash/manual/html_node/).

* Get pod ordinal number:
```bash
[[ `hostname` =~ -([0-9]+)$ ]] || exit 1
ordinal=${BASH_REMATCH[1]}
```
