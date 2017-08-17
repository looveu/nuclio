## nuctl build

Build a function

### Synopsis


Build a function

```
nuctl build function-name [options] [flags]
```

### Options

```
  -h, --help                    help for build
  -i, --image string            Container image to use, will use function name if not specified
      --nuclio-src-dir string   Local directory with nuclio sources (avoid cloning)
      --nuclio-src-url string   nuclio sources url for git clone (default "git@github.com:nuclio/nuclio.git")
  -o, --output string           Build output type - docker|binary (default "docker")
  -p, --path string             Function source code path
  -r, --registry string         URL of container registry (for push)
```

### Options inherited from parent commands

```
  -k, --kubeconfig string   Path to Kubernetes config (admin.conf) (default "C:\\Users\\yaron\\.kube\\config")
  -n, --namespace string    Kubernetes namespace (default "default")
  -v, --verbose             verbose output
```

### SEE ALSO
* [nuctl](nuctl.md)	 - nuclio command line interface

###### Auto generated by spf13/cobra on 17-Aug-2017