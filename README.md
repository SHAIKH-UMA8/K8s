# KUBERNETES K8s

##Namespaces

##Kubernetes namespaces can be presented
as directories, that help to group resourc-
es logically. The default namespace is
used by default. The kube-system name-
space is typically used for cluster resourc-
es.
```
kubectl get ns
```
 gets a list of all name-
spaces


##kubectl create ns jenkins creates a
namespace named jenkins

##The default namespace will be used in
every command by default. To change this
behaviour, use 
```
--namespace=<name>
```
 and
```
--all-namespaces flags
```

