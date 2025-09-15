# rollout-demo2
1. ArgoCD Repository

ArgoCD console > Settings > Repositories

+Connect repo:

- Via SSH
- Name: rollout-demo2
- Project: default
- Repository URL: https://github.com/cotcaru-org/rollout-demo2.git

Connect

2. Create Application

Click on three dots close to repository > Create application

- App name: rollout-with-mesh
- Project: default
- Sync policy: Manual
- Auto-create namespace
- Source Repository URL: https://github.com/cotcaru-org/rollout-demo2.git
- path: .

- cluster URL: https://kubernetes.default.svc
- Namespace: rollout-test2
