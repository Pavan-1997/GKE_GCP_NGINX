# Deploying Nginx on GCP GKE Cluster

1. Open the console


2. Go to Kubernetes Egine - Clusters


3. Click on create cluster 

Autopilot

Standard - select that for more granularity

Static Version - select that for no automatic updates 

Better to chnage nodes to 2

User N1 series for basic ones

Reduce the Boot disk size to 50GB

* Max pods is 110 per node in GKE


4. Click on create 


5. Check the configs after creation


6. Deploy nginx by clicking deploy and click on deploy


7. Check the configs after deploying


8. Connect to cluster using cloud shell


9. Try increasing pods 

Workloads - Three dots deployment details - actions - scale - edit replicas - desired replicas - scale

Which nginx is running on 5 pods


10. Create a service in service and ingress

or 

Workloads - Three dots deployment details - actions - expose - Loadbalancer - expose

11. Check the endpoint to access the nginx
![image](https://github.com/Pavan-1997/GKE_GCP_NGINX/assets/32020205/af26482e-500c-4259-bf0b-7a1877052830)
