# blabs-k8s-workshop
## Kubernates workshop


1. Minikube commands
    ```
    1. docker build -t <IMAGE_NAME> .
    2. docker run -p 3000:3000 <IMAGE_NAME>
    3. minikube start
    4. minikube dashboard
    5. minikube image load <IMAGE_NAME>
    6. minikube image build -t <IMAGE_NAME> .
    7. kubectl apply -f deployment.yaml
    8. kubectl apply -f service.yaml
    9. kubectl get pods
    10. kubectl get services
    11. kubectl port-forward deployment/<DEPLOYMENT_NAME> 3000:3000
    12. sudo kill -9 `sudo lsof -t -i:PORT`
    ```

2. Enable Docker environment: Set the Docker environment variables to point to the Minikube Docker daemon by running the following command:
    ```
    eval $(minikube docker-env)
    ```

