## Helm Charts react-environment-app demo repository

### Get started 

How to install :

- namespace: origin-dev
  `helm install react-environment-demo-dev -n origin-dev -f environment/origin-dev/values.yaml ./` or 
  `helm install react-environment-demo-dev -f environment/origin-dev/values.yaml ./`

- namespace: origin-stage
  `helm install react-environment-demo-stage -n origin-stage -f environment/origin-stage/values.yaml ./` or
  `helm install react-environment-demo-stage -f environment/origin-stage/values.yaml ./`

- namespace: origin-stage
  `helm install react-environment-demo-prod -n origin-prod -f environment/origin-prod/values.yaml ./` or
  `helm install react-environment-demo-prod -f environment/origin-prod/values.yaml ./`
