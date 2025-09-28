# Hello world

This is an hello world app to test ArgoCD

On main branch is the app.
On production branch is the helm chart of the application

GHA will be triggered when main is updated. The GHA will create a new docker image and add a commit to production branch with the new docker image SHA.