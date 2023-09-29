# Helm Charts repo for ClrSlate platform with dependencies

## Add helm chart to the repo

```bash
helm pull oci://registry-1.docker.io/bitnamicharts/keycloak --untar
helm package ./keycloak
helm repo index ./charts --url https://clrslate.github.io/helm-repo/
```
