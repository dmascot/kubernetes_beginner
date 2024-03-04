# My POD

commands used for the first hands on lesson for PODs

- generate POD yaml using kubectl

```bash
$kubectl run mypod --image=nginx:latest --dry-run=client -o yaml > mypod.yaml
```

- apply pod config

```bash
$kubectl apply -f mypod.yaml
```

- get pods

```bash
$kubectl get pods
```

- delete pod

```bash
$kubectl delete pod mypod
```
