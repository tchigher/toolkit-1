## tk reconcile

Reconcile sources and resources

### Synopsis

The reconcile sub-commands trigger a reconciliation of sources and resources.

### Options

```
  -h, --help   help for reconcile
```

### Options inherited from parent commands

```
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
      --namespace string    the namespace scope for this operation (default "gitops-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [tk](tk.md)	 - Command line utility for assembling Kubernetes CD pipelines
* [tk reconcile helmrelease](tk_reconcile_helmrelease.md)	 - Reconcile a HelmRelease resource
* [tk reconcile kustomization](tk_reconcile_kustomization.md)	 - Reconcile a Kustomization resource
* [tk reconcile source](tk_reconcile_source.md)	 - Reconcile sources

