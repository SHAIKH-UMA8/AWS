# Installation-of-minikube-kind-and-kubeadm
## MINIKUBE INSTALLATION
## Step 1: Update the package
```
sudo apt update -y  
```
## Step 2:  Install and configure Docker
```
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
sudo usermod -aG docker $USER && newgrp docker
```
## Step 3: These commands are used to download, make executable, and move the Minikube binary to a directory in your system's PATH
```
curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
chmod +x minikube
sudo mv minikube /usr/local/bin/
```
## Step 4: Download and convert the GPG key
```
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://pkgs.k8s.io/core:/stable:/v1.28/deb/Release.key | sudo gpg --dearmor -o /etc/apt/keyrings/kubernetes-apt-keyring.gpg
```
## Step 5: Add the Kubernetes APT repository
```
echo "deb [signed-by=/etc/apt/keyrings/kubernetes-apt-keyring.gpg] https://pkgs.k8s.io/core:/stable:/v1.28/deb/ /" | sudo tee /etc/apt/sources.list.d/kubernetes.list
```
## Step 6: Again update the package
```
sudo apt-get update
```
## Step 7: To install the kubectl package
```
sudo apt-get install kubectl
```
## Step 8: To start a Minikube Kubernetes cluster using Docker as the virtualization driver
```
minikube start --driver=docker
```
## Step 9: To list the nodes in a Kubernetes cluster
```
kubectl get nodes 
```
## Successfully created minikube cluster

![Screenshot 2024-09-12 222219](https://github.com/user-attachments/assets/1e912ab8-bf58-41e5-b222-64d46406238d)


## KIND INSTALLATION
## Step 1: Update the package
```
sudo apt update -y  
```
## Step 2:  Install Docker
```
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
```
## Step 3: This command is used to download the kind binary
```
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.18.0/kind-linux-amd64 
```
## Step 4: This command is used to change the permissions of the kind file to make it executable
```
chmod +x ./kind
```
## Step 5: This command is used to move the kind binary to a directory that is included in your system’s PATH
```
sudo mv ./kind /usr/local/bin/
```
## Step 6: This command is used to create a local Kubernetes cluster using Kind
```
kind create cluster
```
## Successfully created Kind Cluster

![image](https://github.com/user-attachments/assets/dcf09fca-134a-4037-bc33-79b0d8c616fc)
