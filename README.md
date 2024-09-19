# Istio Request ID

istio 에서 distribution 로깅을 위해 Request ID 를 사용하는데,
이 ID 의 행동 패턴을 알아보기 위한 프로젝트이다.

## Prerequisite

- [Docker](https://www.docker.com/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- Minikube
- istio

## Installation

```bash
$ brew install minikube
$ minikube start --memory=8192 --cpus=4
$ minikube addons enable istio-provisioner
$ minikube addons enable istio
```
