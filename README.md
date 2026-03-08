## GitOps repository for [cicd-k8s-demo](https://github.com/dannyyyyS/cicd-k8s-demo.git)

### Description
This is the deployment repo of cicd-k8s-demo (minimum ci/cd project), tracking deployment status.

### Files

| Files                   | usage                                              |
|-------------------------|----------------------------------------------------|
| apps/                   | aggregates files by apps                           |
| argocd/application.yaml | tells argocd how to monitor changes                |
| base/ + overlays        | defines how the app should be apply on k8s cluster |

