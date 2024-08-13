# k3s-mystnodes

Firstly create the **myst** namespace in k3s.

```bash
kubectl create namespace myst
```

Then create your pod.

```bash
kubectl apply -f mystnodes.yml
```