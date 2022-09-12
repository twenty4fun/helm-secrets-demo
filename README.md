# helm-chart

## helm的chart仓库地址为：https://twenty4fun.github.io/helm-secrets-demo

## 本Chart仓库的使用方法

1、添加chart仓库
```
# helm repo add myrepo https://twenty4fun.github.io/helm-secrets-demo
```

2、添加成功
```
# helm repo list
NAME  	URL                                   
myrepo	https://twenty4fun.github.io/helm-secrets-demo
```

3、搜索chart包
```
# helm search repo
NAME                              	CHART VERSION	APP VERSION	DESCRIPTION                                   
myrepo/edgex                      	0.1.0        	1.0        	A Helm chart for EdgeX Geneva                 
myrepo/kubernetes-dashboard       	2.3.0        	2.0.3      	General-purpose web UI for Kubernetes clusters
myrepo/sample-chart                       	0.1.0        	1.16.0     	A Helm chart for Kubernetes 
```

4、安装chart包
```
# helm install xxx myrepo/sample-chart
```

xxx为relaese名字
