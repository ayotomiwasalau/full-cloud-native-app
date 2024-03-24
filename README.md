## Deploying an app to cloud using Kubernetes 
TechTrends is an online website used as a news sharing platform, that enables consumers to access the latest news within the cloud-native ecosystem. In addition to accessing the available articles, readers are able to create new media articles and share them.

As a platform engineer, The goal of these project is to package and deploy TechTrends to Kubernetes using a CI/CD pipeline.
Tool like Helms, Github actions, ArgoCD and Docker were used.

Refer to the `argocd` folder for the argo deployment yaml, ``helm`` for the charts and manifests and ``kubenetes`` for the components defintitions. ``techtrends`` contains the Docker file and the flask application that was deployed.
