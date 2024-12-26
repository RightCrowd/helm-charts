# Public RightCrowd Helm charts
This repository houses all public Helm charts by RightCrowd.

# Example
To install the Keycloak Realm operator, run the command below:
```sh
helm repo add rightcrowd https://rightcrowd.github.io/helm-charts
helm repo update
helm install keycloak-realm-operator rightcrowd/keycloak-realm-operator
```
