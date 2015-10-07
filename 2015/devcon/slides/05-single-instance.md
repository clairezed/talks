## 🔎

@@@

## Multiplication!

~~~~

```
docker inspect -f '{{range $p, $conf := .NetworkSettings.Ports}}{{(index $conf 0).HostPort}}{{end}}' $(docker ps -q)
```
