# argocd-config
K8s specs that control Argo CD configurations in the cluster

* `argocd-cm.yaml`: Contains user account info. Add any new user accounts here.
* `argocd-rbac.yaml`: ConfigMap spec which contains the `policy.csv` that defines RBAC for various roles & users.

Refer to the following for information on:
* Managing users: https://argo-cd.readthedocs.io/en/stable/operator-manual/user-management/
* Managing RBAC: https://argo-cd.readthedocs.io/en/stable/operator-manual/rbac/

