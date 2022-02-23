### Volume Assignment: To install this using kubectl apply;
- cd into k8s/ folder
- Update the ingress to desired domain
- Update configmap DEFAULT_DOMAIN to the same domain
- Run kubectl apply.

### To install using helm
- Update ingress defaultDomain and domain in the values.yaml
- Run helm install kutt kutt/

If you are testing the locally and having issue witj browser;
To successfully test;
```
curl domain.com
```
