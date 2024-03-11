# taco-fleet

This repo contains an example Flux CD configuration for AKS. The infrastructure folder adds the Bitnami Helm repository.  

The dotnet folder has a configuration deploying a sample ASP Net app using the App Gateway ingress controller.

To use this with an AKS cluster, first install the Flux extension, then add a Flux configuration with two Kustomizations. The first can point at the infrastructure directory and the second should point at the dotnet directory.
