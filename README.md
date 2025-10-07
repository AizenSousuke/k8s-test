### Setup
- Build container with docker-compose up -d
- Down it with docker-compose down
- Deploy k8s cluster with kubectl create -f deployment.yaml
- Deploy k8s service with kubectl apply -f service.yaml
- Go to http://localhost:8080/ to see the web application