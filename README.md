# flux-helm-flink-operator-interaction
This repository shows an unexpected behaviour in the interaction between the helm-operator of FluxCD and the flink-operator by Lyft. It contains the setup of the flink-operator, a Helm chart with a FlinkApplication custom resource and a workload consisting of a HelmRelease and the same FlinkApplication custom resource (renamed).
