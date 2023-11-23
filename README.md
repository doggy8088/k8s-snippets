# Kubernetes Snippets

This extension contains a set of Kubernetes code snippets that helps you write YAML faster and easier. If you'd like to provide ideas or contribute your awesome snippets, please drop me a line by [creating an issue](https://github.com/yzdann/k8s-snippets/issues).

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

### [Configuration](https://kubernetes.io/docs/concepts/configuration/)

* `k-configmap`: k8s [ConfigMaps](https://kubernetes.io/docs/concepts/configuration/configmap/)
* `k-secret`: k8s [Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)

### [Storage](https://kubernetes.io/docs/concepts/storage/)

* `k-pvc`: k8s [PersistentVolumeClaim](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)

## Extensions Included

This extension bundled with some MUST needed VSCode extensions for Kubernetes developments.

* [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)

    Develop, deploy and debug Kubernetes applications

* [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

    YAML Language Support by Red Hat, with built-in Kubernetes syntax support

**Enjoy!**
