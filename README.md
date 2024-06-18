# cka
certified kubernates administrator


### How to start minikube cluster
```
minukube start
```
![rebase](output-of-minikube-start.jpg)


### What are alterrnatives of minikube

    Rancher, Openshift these are different skin of k8 cluster like AWS and Azure also give theirs. Minikube is by default provided by makers of k8. It's desktop version not advised to use in production. But it has mostly all production ready features.

### How to export current setting of kubectl

```
kubectl view config > config.yaml
```

### How to get minikube url to browse

```
minikube dashboard
```
![rebase](output-of-minikube-dashboard.jpg)

### How to forward a port in k8 to localhost
kubectl port-forward pods/etcd-minikube 2379:2379

### How to install k8 minikube on Ubuntu

### How to install ssh on wsl-ubuntu
```
sudo apt-get install ssh
\\wsl.localhost\Ubuntu
```
![rebase](wsl-ubuntu-ssh-filezilla.jpg)

### How to install etcd on ubuntu

```
sudo apt-get install etcd
```

### How to install podman in ubuntu
```
sudo apt-get -y install podman
```

### How to run minikube with podman
```
minikube config set rootless true
minikube start --driver=podman
```

### How to see all services of ubuntu
```
service --status-all
```

### How can i download and play with etcd, like i used to with mysql

[ETCD documentation site link will help](https://etcd.io/docs/v2.3/api/)

### What is D in etcd
according to their website documentation D means distributed and etc is taken from etc folder of linux where external libraries are kept

### Can you show insert, update, delete and select function like in mysql.

Yes follow this video

### From where i can get installer and run it
From github website go for release link

## Error 
### No help topic for 'version'






