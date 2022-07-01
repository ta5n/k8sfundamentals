# Kubernetes Notes

## Pods

> Start kubernetes cluster either `minikube` or whatever you like

```sh
$ minikube start
```

---

- Watch pods continuously on a second terminal tab

```sh
$ kubectl get pods -w
# or
$ kubectl get pods --watch
```

- run a pod with given yaml configuration

```sh
$ kubectl apply --filename podlife1.yaml
```
