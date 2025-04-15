# k8s-StorageClass
部署StorageClass文件
前提条件：已经部署了安装了nfs

导入镜像 nfs-provisioner.tar 
1 修改nfs-provisioner.yml中nfs的服务地址和路径，kubectl apply -f nfs-provisioner.yml
2 kubectl apply -f nfs-storage-class.yml 



可选
kubectl apply -f volumeClaimTemplates.yml
