1. Kubernetes Deployment:

* Dockerize the Node.js Application
* Build the Docker Image: Use the Dockerfile to build the Docker image of your Node.js application.
*Kubernetes Deployment Manifest (deployment.yaml): specifying details about the application, including the Docker image to use, ports,      environment variables, etc.
* Apply the deployment YAML using the command (kubectl apply -f deployment.yaml)
* Ensure the deployment is successful by checking the status of pods:(kubectl get pods)

2. Autoscaling with HPA:

Enable Metrics Server:
Ensure the Metrics Server is running in your Kubernetes cluster to provide CPU and memory utilization metrics.
Create an HPA YAML file to define autoscaling behavior based on CPU or memory usage.
Apply the HPA YAML using the command (kubectl apply -f hpa.yaml)
Check the status of HPA:(kubectl get hpa)

3. Version Control and Sharing:
* Uploaded the complete codebase, including Kubernetes deployment manifests, to a public GitHub repository.
* Update the repository's README.md file with documentation
  of the project setup.
