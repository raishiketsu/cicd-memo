
PW
```
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d && echo
```

https://github.com/argoproj/argocd-example-apps
