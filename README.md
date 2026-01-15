# helm starter
Custom helm starter template for `helm create`.

While the default helm chart already covers many use cases, in some situations you need a service with 2 port or need to mount pvcs and use a statefulset instead of deployment.
Therefore, I want to extend the default chart to allow more use cases.

# Feature
- Select between Deployment/Statefulset/DaemonSet, etc.
- Support multiple ConfigMaps and Secrets mounted as env vars or files
- support mutliple pvcs
- support additional deployments
- support custom resources like ServiceMonitor or GrafanaDashboard
- support more than one exposed port
