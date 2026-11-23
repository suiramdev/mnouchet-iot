# mnouchet-iot

Public GitOps source for Inception-of-Things Part 3.
Argo CD (namespace `argocd`) watches `p3/confs/app` and deploys it into the `dev` namespace.

Switch version: edit the image tag `wil42/playground:v1` <-> `v2` in
`p3/confs/app/deployment.yaml`, commit and push.
