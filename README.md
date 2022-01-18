# sample-crd

```bash
> kubebuilder init --domain example.com --skip-go-version-check
> kubebuilder edit --multigroup=true
> kubebuilder create api --group core --version v1alpha1 --kind App
> make generate manifests fmt
> ./hack/update-codegen.sh
```
