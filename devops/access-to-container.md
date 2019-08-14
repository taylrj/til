### How to access containers ?

```bash
kubectl get pods
```

Then, there will be a list of pods like ...

NAME         READY     STATUS    RESTARTS   AGE
twreporter   1/1       Running   0         7d15h

Say, I want to access pod named `twreporter`

```bash
kubectl exect -it twreporter bash
```

And if I want to quit, just type

```bash
exit
```
