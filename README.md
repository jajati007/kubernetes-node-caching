# kubernetes-node-caching
Kubernetes node caching mechanism for all DNS query

Advanced caching mechanism to handle heavy traffic load.

This feature is available for AKS, Kubcernetes cluster, GKE and any other cloud providers Kubernetes engine.

This repo will bring code to enable local DNS caching on each kubernetes cluster node so that, maximum DNS requests will get resolved by the cluster node itself instead of routing the requests to it's own Coredns pod.
