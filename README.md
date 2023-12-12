# GitLab
GitLab end 2 end local environment. Need to add in a way to have a local "production" env to deploy too. Either via a minikube/docker desktop  kubernetes GitLab agent, or if possible a docker compose production env (with gitlab agent?)

Currently on Macos this need Docker Desktop to have filesharing set to gRPC FUSE (not the much faster VirtioFS).
Possible workaround for this would be to move to use Docker Volumes.

Tested only on Macos 13 and 14. Docker (desktop) 4.25.2 Engine: 24.0.6, (Compose: v2.23.0-desktop.1, Credential Helper: v0.7.0)

