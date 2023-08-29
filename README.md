# Wordpress w/ minikube
Spin-up *Wordpress* On a Local Single Node Cluster Using *minikube*.
## Deployment
```bash
# Clone The Repository
git clone https://github.com/kemosabe-afk/wordpress-k8s

# cd Into The Repository
cd wordpress-k8s/

# Start Minikube
minikube start

# Create All Objects
kubectl apply -f ./

# Get The URL to Access The Wordpress
minikube service nginx --url
```
