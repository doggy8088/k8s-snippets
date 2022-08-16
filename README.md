# Kubernetes Snippets

This extension contains a set of Kubernetes code snippets that helps you write YAML faster and easier. If you'd like to provide ideas or contribute your awesome snippets, please drop me a line by [creating an issue](https://github.com/doggy8088/k8s-snippets/issues).

![Usage Screenshot](https://user-images.githubusercontent.com/88981/99081103-391baa00-25fd-11eb-9e2e-6ae5e2f771ef.png)

## Snippets Included

### [Workloads](https://kubernetes.io/docs/concepts/workloads/)

* `k-deploymment`: k8s [Deployment](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
* `k-pod`: k8s [Pod](https://kubernetes.io/docs/concepts/workloads/pods/)
* `k-job`: k8s [Job](https://kubernetes.io/docs/concepts/workloads/controllers/job/)
* `k-cronjob`: k8s [CronJob](https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/)
* `k-daemonset`: k8s [DaemonSet](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/)
* `k-statefulset`: k8s [StatefulSet](https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/)

### [Network](https://kubernetes.io/docs/concepts/services-networking/)

* `k-service`: k8s [Service](https://kubernetes.io/docs/concepts/services-networking/service/)
* `k-ingress`: k8s [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)
* `k-ingress-tls`: k8s [Ingress with TLS](https://kubernetes.io/docs/concepts/services-networking/ingress/#tls)
* `k-ingress-rewrite`: k8s Ingress with [Rewrite](https://github.com/kubernetes/ingress-nginx/blob/master/docs/examples/rewrite/README.md) rule
* `k-networkpolicy`: k8s [NetworkPolicy](https://kubernetes.io/docs/concepts/services-networking/network-policies/)

### [Configuration](https://kubernetes.io/docs/concepts/configuration/)

* `k-configmap`: k8s [ConfigMaps](https://kubernetes.io/docs/concepts/configuration/configmap/)
* `k-secret`: k8s [Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)

### [Storage](https://kubernetes.io/docs/concepts/storage/)

* `k-pvc`: k8s [PersistentVolumeClaim](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)

### [RBAC](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)

* `k-role`: k8s Role
* `k-clusterrole`: k8s [ClusterRole](https://kubernetes.io/docs/reference/kubernetes-api/authorization-resources/cluster-role-v1/)
* `k-rolebinding`: k8s [RoleBinding](https://kubernetes.io/docs/reference/kubernetes-api/authorization-resources/role-binding-v1/)
* `k-clusterrolebinding`: k8s [ClusterRoleBinding](https://kubernetes.io/docs/reference/kubernetes-api/authorization-resources/cluster-role-binding-v1/)

### [Authentication Resources](https://kubernetes.io/docs/reference/kubernetes-api/authentication-resources/)

* `k-serviceaccount`: k8s [ServiceAccount](https://kubernetes.io/docs/reference/kubernetes-api/authentication-resources/service-account-v1/)

## Extensions Included

This extension bundled with some MUST needed VSCode extensions for Kubernetes developments.

* [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)

    Develop, deploy and debug Kubernetes applications

* [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

    YAML Language Support by Red Hat, with built-in Kubernetes syntax support

* [Kubernetes Apply](https://marketplace.visualstudio.com/items?itemName=ShaiMendel.kubernetesapply)

    Apply and Delete Kubernetes resource files

* [Encode Decode](https://marketplace.visualstudio.com/items?itemName=mitchdenny.ecdc)

    This allows you to quickly convert text selections such as Base64 encode/decode. So much useful for Secrets authoring.

There are some other extensions you may need (Optional)

* [Dapr](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-dapr)

    Makes it easy to run, debug, and interact with Dapr-enabled applications.

* [Azure Kubernetes Service](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-aks-tools)

* [Bridge to Kubernetes](https://marketplace.visualstudio.com/items?itemName=mindaro.mindaro)

* [Open Policy Agent for Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.kubernetes-opa-vscode)

    Work with Open Policy Agent as a Kubernetes admission controller

* [Developer Tools for Azure Kubernetes Service (AKS)](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.aks-devx-tools)

    Create deployment files and configure GitHub Actions workflows to deploy applications to Azure Kubernetes Service (AKS).

* [Kubernetes Pod File System Explorer](https://marketplace.visualstudio.com/items?itemName=sandipchitale.kubernetes-file-system-explorer)

    Kubernetes Pod File System Explorer.

* [Kubernetes Dashboard](https://marketplace.visualstudio.com/items?itemName=sandipchitale.vscode-kubernetes-dashboard)

    Install and Launch Kubernetes Dashboard.

**Enjoy!**
