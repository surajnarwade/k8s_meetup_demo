### guestbook

This example will illustrate famous guestbook example from kubernetes documentation.

Tu run this example,

```
kompose up
INFO We are going to create Kubernetes Deployments, Services and PersistentVolumeClaims for your Dockerized application. If you need different kind of resources, use the 'kompose convert' and 'kubectl create -f' commands instead.

INFO Deploying application in "myproject" namespace
INFO Successfully created Service: frontend
INFO Successfully created Service: redis-master
INFO Successfully created Service: redis-slave
INFO Successfully created Deployment: frontend
INFO Successfully created Deployment: redis-master
INFO Successfully created Deployment: redis-slave

Your application has been deployed to Kubernetes. You can run 'kubectl get deployment,svc,pods,pvc' for details.
```
