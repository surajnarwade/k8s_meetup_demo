### Voting

This example will demonstrate simple wordpress application.

To run this application on kubernetes,

```
kompose up -f docker-voting.yaml 
INFO We are going to create Kubernetes Deployments, Services and PersistentVolumeClaims for your Dockerized application. If you need different kind of resources, use the 'kompose convert' and 'kubectl create -f' commands instead. 
 
INFO Deploying application in "default" namespace 
INFO Successfully created Service: db             
INFO Successfully created Service: redis          
INFO Successfully created Service: result         
INFO Successfully created Service: vote           
INFO Successfully created Service: worker         
INFO Successfully created Deployment: db          
INFO Successfully created Deployment: redis       
INFO Successfully created Deployment: result      
INFO Successfully created Deployment: vote        
INFO Successfully created Deployment: worker      

Your application has been deployed to Kubernetes. You can run 'kubectl get deployment,svc,pods,pvc' for details.
```

