# kubernetes-dashboard-amd64

拉取 k8s.gcr.io 镜像

```shell
docker push kainonly/kubernetes-dashboard-amd64:v1.10.1
// or
docker pull ccr.ccs.tencentyun.com/kainonly/kubernetes-dashboard-amd64:v1.10.1
```

重命名镜像

```shell
docker tag kainonly/kubernetes-dashboard-amd64:v1.10.1 k8s.gcr.io/kubernetes-dashboard-amd64:v1.10.1
// or
docker tag ccr.ccs.tencentyun.com/kainonly/kubernetes-dashboard-amd64:v1.10.1 k8s.gcr.io/kubernetes-dashboard-amd64:v1.10.1
```