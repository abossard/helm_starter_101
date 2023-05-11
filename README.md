# How to install it

'master' refers to the folder name master, not related to git or anything else.


```bash
helm dependency update master
helm upgrade --install myrelease master --namespace mynamespace --create-namespace -f master/values.prod.yaml --dry-run
```
