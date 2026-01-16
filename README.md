## IMPORTANT
→ ignored due to large file issue in github

#### 1. kubectl
#### 2. minikube-darwin-arm64



## FILE STRUCTURE (screen shot)
<img width="1532" height="454" alt="Screenshot 2026-01-16 at 12 56 57" src="https://github.com/user-attachments/assets/421310cc-687a-42ff-af30-722cce0a7e89" />



## 1. Install kubectl on macOS (macOS Apple Silicon / arm64)

https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/#install-kubectl-on-macos

```bash
### Run these commands in your terminal:

curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/darwin/arm64/kubectl"
```

```bash
╰─ kubectl version

Client Version: v1.34.1
Kustomize Version: v5.7.1
Server Version: v1.34.0
```



## 2. Install minikube-darwin-arm64 on macOS (macOS Apple Silicon / arm64)

https://minikube.sigs.k8s.io/docs/start/?arch=%2Fmacos%2Farm64%2Fstable%2Fbinary+download

```bash
### Run these commands in your terminal:
curl -LO https://github.com/kubernetes/minikube/releases/latest/download/minikube-darwin-arm64
sudo install minikube-darwin-arm64 /usr/local/bin/minikube
```
```bash
╰─ minikube version

minikube version: v1.37.0
commit: 65318f4cfff9c12cc87ec9eb8f4cdd57b25047f3
```





