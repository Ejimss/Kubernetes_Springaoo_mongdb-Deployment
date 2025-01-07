# Kubernetes_Springapp_mongdb-Deployment
For this project, two separate deployment would be carried out;
    i) spring app deployment
    ii) mongodb deployment for data storage.
For the Spring app deployment, the resource kind is "Deployment" while the resouce kind for the mongodb is ReplicaSet.
NodePort and ClusterIP Service type are used for Service Discovery respectively.
Configure the environmental variables for appropriate communication between the two applications.
The HorizontalAutoScaler(Hpa) appropriately scales the springapp based on traffic...
