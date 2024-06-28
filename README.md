# Amamba Demo Examples

- [guestbook source](https://github.com/kubernetes/examples/tree/master/guestbook-go)
- [argocd repo](https://github.com/argoproj/argocd-example-apps)


This repository contains example applications for demoing ArgoCD functionality. Feel free
to register this repository to your ArgoCD instance, or fork this repo and push your own commits
to explore ArgoCD and GitOps!

| Application | Description |
|-------------|-------------|
| [plain-yaml](plain-yaml/) | A hello word guestbook app as plain YAML |
| [helm-guestbook](helm-guestbook/) | The guestbook app as a Helm chart |
| [kustomize-guestbook](kustomize-guestbook/) | The guestbook app as a Kustomize 2 app |
| [helm-dependency](helm-dependency/) | Demonstrates how to customize an OTS (off-the-shelf) helm chart from an upstream repo |
| [replicas-rollouts](replicas-rollouts/) | Demonstrates how to canary rollout by replicas |
| [istio-rollouts](istio-rollouts/) | Demonstrates how to canary rollout by istio |
| [blue-green](blue-green/) | Demonstrates how to blue-green rollout |
