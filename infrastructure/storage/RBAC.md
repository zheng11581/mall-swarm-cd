```shell
# kubectl apply -f nfs-sa.yaml
# kubectl create clusterrolebinding nfs-provisioner --clusterrole=cluster-admin --serviceaccount=default:nfs-provisioner
# kubectl apply -f nfs-provisioner.yaml
# kubectl apply -f nfs-storageclass.yaml
```