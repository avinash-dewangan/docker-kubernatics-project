# Step

## in Window
* install docker desktop
* inside doecker go to setting and the click kubernates and enable kubernates


## create image
docker build -t your-node-app .
### docker process command
docker ps                                             
### docker list of images
docker images



## run below command
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml


## kubernatic dashboard open
* kubectl proxy

## open this link
http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/.

## for token genrate command
kubectl -n kubernetes-dashboard create token admin-user

## get pods
kubectl get pods                                        
