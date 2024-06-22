# Mani's Automated Kubernetes and Container Repository Orchestrator (MAKCRO)

Is a script that is meant to glue together the pieces to spin up a single node Kubernetes Cluster and a Container Repository for local development or as part of a CI testing pipeline.

# Usage

`makcro up` - start up a new cluster, container repo, and configure the cluster with the appropriate information to pull images from the container repo
`makcro down` - stop AND delete the cluster and container repo
