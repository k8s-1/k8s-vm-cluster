# Kubernetes-ready Vagrant VM cluster

* Kernel bridge-networking configured
* CRI installed (cri-o)
* base-packages installed
* iptables configured
* swap is off

## Get started
```
vagrant up

vagrant ssh cp

# install and bootstrap kubernetes with e.g. kubeadm

vagrant destroy -f
```

## Post-bootstrap DIY
* Install kubernetes
* Install a CNI e.g. calico / flannel / weave
