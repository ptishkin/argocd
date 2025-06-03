To create App in argocd, not use UI, only apply from src
Multi source app, with values from [git]([url](https://argo-cd.readthedocs.io/en/stable/user-guide/multiple_sources/#helm-value-files-from-external-git-repository))
`argocd app create kubeflow-1.0.4-v1.9.1 --file https://raw.githubusercontent.com/ptishkin/argocd/refs/heads/kubeflow-1.0.4-v1.9.1/TheCodingSheikh/charts/kubeflow/multi-src.yaml`
