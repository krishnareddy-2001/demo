# demo
```
sudo su
```
```
apt-get update && apt-get install -y apt-transport-https ca-certificates curl
sudo curl -fsSLo /usr/share/keyrings/kubernetes-archive-keyring.gpg https://dl.k8s.io/apt/doc/apt-key.gpg
```
```
echo "deb [signed-by=/usr/share/keyrings/kubernetes-archive-keyring.gpg] https://apt.kubernetes.io/ kubernetes-xenial main" | sudo tee /etc/apt/sources.list.d/kubernetes.list
```
```
apt-get update
apt-get install docker.io -y
```
```
 sudo apt-get install -y kubelet kubeadm kubectl kubernetes-cni
```
```
kubeadm init
```
