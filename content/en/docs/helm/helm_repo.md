---
title: "Helm Repo"
---

## helm repo

add, list, remove, update, and index chart repositories

### Synopsis


This command consists of multiple subcommands to interact with chart repositories.

It can be used to add, remove, list, and index chart repositories.


### Options

```
  -h, --help   help for repo
```

### Options inherited from parent commands

```
      --add-dir-header                   If true, adds the file directory to the header
      --alsologtostderr                  log to standard error as well as files
      --debug                            enable verbose output
      --kube-context string              name of the kubeconfig context to use
      --kubeconfig string                path to the kubeconfig file
      --log-backtrace-at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log-dir string                   If non-empty, write log files in this directory
      --log-file string                  If non-empty, use this log file
      --log-file-max-size uint           Defines the maximum size a log file can grow to. Unit is megabytes. If the value is 0, the maximum file size is unlimited. (default 1800)
      --logtostderr                      log to standard error instead of files (default true)
  -n, --namespace string                 namespace scope for this request
      --registry-config string           path to the registry config file (default "~/.config/helm/registry.json")
      --repository-cache string          path to the file containing cached repository indexes (default "~/.cache/helm/repository")
      --repository-config string         path to the file containing repository names and URLs (default "~/.config/helm/repositories.yaml")
      --skip-headers                     If true, avoid header prefixes in the log messages
      --skip-log-headers                 If true, avoid headers when opening log files
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          number for the log level verbosity
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO

* [helm](../helm)	 - The Helm package manager for Kubernetes.
* [helm repo add](helm_repo_add.md)	 - add a chart repository
* [helm repo index](helm_repo_index.md)	 - generate an index file given a directory containing packaged charts
* [helm repo list](helm_repo_list.md)	 - list chart repositories
* [helm repo remove](helm_repo_remove.md)	 - remove a chart repository
* [helm repo update](helm_repo_update.md)	 - update information of available charts locally from chart repositories

###### Auto generated by spf13/cobra on 4-Feb-2020
