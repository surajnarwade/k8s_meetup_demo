### wordpress

This Example will demonstrate simple wordpress application.

* Before deploying, Make sure you have already login to dockerhub.

```bash
docker login
```

* To deploy it,

```
kompose up
INFO Build key detected. Attempting to build and push image 'docker.io/surajnarwade/count' 
INFO Building image 'docker.io/surajnarwade/count' from directory 'build-push' 
INFO Image 'docker.io/surajnarwade/count' from directory 'build-push' built successfully 
INFO Pushing image 'surajnarwade/count:latest' to registry 'docker.io' 
INFO Attempting authentication credentials 'https://index.docker.io/v1/ 
INFO Successfully pushed image 'surajnarwade/count:latest' to registry 'docker.io' 
INFO We are going to create Kubernetes Deployments, Services and PersistentVolumeClaims for your Dockerized application. If you need different kind of resources, use the 'kompose convert' and 'kubectl create -f' commands instead. 
 
INFO Deploying application in "myproject" namespace 
INFO Successfully created Service: redis          
INFO Successfully created Service: web            
INFO Successfully created Deployment: redis       
INFO Successfully created Deployment: web         

Your application has been deployed to Kubernetes. You can run 'kubectl get deployment,svc,pods,pvc' for details.
```

