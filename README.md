# MongoDB and Mongo Express on Kubernetes

This project deploys a MongoDB instance and a Mongo Express web interface on a Kubernetes cluster. MongoDB is a NoSQL database that stores data in flexible, JSON-like documents, while Mongo Express provides a web-based interface for managing the MongoDB database.

## Prerequisites

- Kubernetes cluster
- kubectl installed and configured
- Minikube (if using locally)

## Project Structure

The project consists of the following Kubernetes resources:

- **ConfigMap**: Stores configuration data for the MongoDB service.
- **Secret**: Stores sensitive information, including MongoDB credentials.
- **Deployment**: Deploys the MongoDB and Mongo Express applications.
- **Service**: Exposes the applications to allow external access.

Use this command for minikube(it works a bit differently then the deployment in actaul production environmnet).

```bash
minikube service mongo-express-service
```
