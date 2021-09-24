# Testapp_config

Kustomize overlays for "testapp"

Kustomize overlays
- dev
- staging

view the overlays -

- oc kustomize overlays/dev
- oc kustomize overlays/staging 

apply the overlays
- oc apply -k overlays/dev
- oc apply -k overlays/staging
