### wordpress

This Example will demonstrate simple wordpress application.

* To deploy it on openshift,

```
kompose up --provider=openshift
INFO We are going to create OpenShift DeploymentConfigs, Services and PersistentVolumeClaims for your Dockerized application.
If you need different kind of resources, use the 'kompose convert' and 'oc create -f' commands instead.

INFO Deploying application in "myproject" namespace
INFO Successfully created Service: db
INFO Successfully created Service: wordpress
INFO Successfully created DeploymentConfig: db
INFO Successfully created ImageStream: db
INFO Successfully created PersistentVolumeClaim: db-data of size 100Mi. If your cluster has dynamic storage provisioning, you don't have to do anything. Otherwise you have to create PersistentVolume to make PVC work
INFO Successfully created DeploymentConfig: wordpress
INFO Successfully created ImageStream: wordpress
INFO Successfully created Route: wordpress

Your application has been deployed to OpenShift. You can run 'oc get dc,svc,is,pvc' for details.
```

* As we have used `kompose.service.expose` label, Please add `wordpress` entry in /etc/hosts as well along with minikube/minishift ip
