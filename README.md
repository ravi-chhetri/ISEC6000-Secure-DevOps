# SecureDevops- Assignment
The  README provides the overview of setup of google Cloud setup for Secure Devops Project
## Task1: setup Up Initial Infrastructure

### Create a kubernates cluster on GKE

1. Log in to your Google Cloud Console.
 https://console.cloud.google.com/welcome/new?project=bright-fastness-398205

2. Navigate to the Kubernetes Engine section and click "Create Cluster."
 In Google cloud, goto Kubernetes Engine, Create a cluster
 
> 3. Cluster Name - devops

 Location- us-central1
  
  
4. Kubernetes version-1.27.3-gke.100
  

 Click on create to  finalize the creation of Cluster.



### 2. Install and Configure kubectl

After creating the GKE cluster, we will configure the  kubectl
we will click on the connect link and get the command for authentication which is below:

*"gcloud container clusters get-credentials devops --region us-central1 --project bright-fastness-398205"*



### 3. Set Up a Private GitHub Repository
 Create a new GitHub repository by visiting [GitHub](https://github.com/) and clicking the '+' icon at the top right corner of the dashboard.
 
 
 Now we choose ISEC6000 Secure Devops as a project name. we set git repo in a public. After that we create Repository.
