# taco-fleet

This repo contains an example Flux CD configuration for AKS. The infrastructure folder add the Podinfo Helm repository.  The apps folder has a release of the podinfo app using the Podinfo helm repository.

There are two subfolders for staging and production. Both use the AGIC to expose the podinfo app to the internet.