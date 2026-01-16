## IMPORTANT
→ ignored due to large file issue in github

#### 1. kubectl
#### 2. minikube-darwin-arm64



## FILE STRUCTURE (screen shot)
<img width="644" height="430" alt="Screenshot 2026-01-16 at 14 28 40" src="https://github.com/user-attachments/assets/4a549eb0-abcd-4efe-b25c-9b7a0331cd83" />




## TO INSTALL (git ignored) "kubectl" and "minikube"

```bash
## Get inside project folder
cd kubernetes-demo
```

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




## TO RUN THE PROJECT

```bash
## Get inside project folder
cd kubernetes-demo

minikube start

npm run deploy

## minikube service <service_NAME>  
minikube service kubernetes-demo-api-service
```


## I/P
<img width="1024" height="1057" alt="Screenshot 2026-01-16 at 16 53 00" src="https://github.com/user-attachments/assets/21f44236-23b6-4f42-8d78-abc13e4dc064" />

## O/P
<img width="674" height="529" alt="Screenshot 2026-01-16 at 16 38 14" src="https://github.com/user-attachments/assets/93615760-eb25-45d5-9686-96fea1c6949c" />


