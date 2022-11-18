# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11

## Screenshots of your "full" desktop for the Part 1 (CI) and Part 2 (CD)
#### 	This criterion is linked to a Learning Outcome Screenshots (in Markdown README.md) for CI Workflow (Part 1)
###### Updating the gralde.yaml
<img width="1440" alt="gradle" src="https://user-images.githubusercontent.com/79027915/202624802-dc95a658-c464-4165-b4b7-829db909d65e.png">

###### Action of Changing Deployment.yaml on github
<img width="1440" alt="deployment change 1" src="https://user-images.githubusercontent.com/79027915/202624796-fd355651-45df-43ab-992e-2dedf2ad5c8b.png">

###### Result for  Action of Changing Deployment.yaml
<img width="1440" alt="deployment change2" src="https://user-images.githubusercontent.com/79027915/202624801-98183701-b259-40d1-9833-ba91b94a822c.png">
<img width="1440" alt="Deployment change 3" src="https://user-images.githubusercontent.com/79027915/202624799-625bedd0-8762-48b1-9950-1119ea710ac7.png">

####	This criterion is linked to a Learning Outcome Screenshots (in Markdown README.md) for CD Workflow (Part 2)
###### Create the GKE cluster on GCP
<img width="1440" alt="Cluster2" src="https://user-images.githubusercontent.com/79027915/202627271-481145da-293f-4c67-9165-fb32d3e999d6.png">
<img width="1440" alt="Cluster3" src="https://user-images.githubusercontent.com/79027915/202627276-beb550dd-3ad1-4c6c-98c0-21dd3ffec23d.png">
<img width="1440" alt="Cluster1" src="https://user-images.githubusercontent.com/79027915/202627737-6b295522-8348-4743-8d0a-ea075be5877e.png">

###### Enable the Kubernetes Engine and Container Registry APIs.
<img width="1440" alt="API1" src="https://user-images.githubusercontent.com/79027915/202628447-47ef45ee-889a-4ab6-9fd2-a69087254587.png">

###### Enable the Container Register & Google Kubernetes Engine API Links to an external site..
<img width="1440" alt="API2" src="https://user-images.githubusercontent.com/79027915/202628459-74e3d292-893b-4261-ad8f-280e21442c15.png">
<img width="1440" alt="API3" src="https://user-images.githubusercontent.com/79027915/202628461-5d364e9c-2422-4eef-a479-0cc263f3883e.png">

###### Navigate to Cloud Overview / Dashboard
<img width="1440" alt="Secret1" src="https://user-images.githubusercontent.com/79027915/202631606-0290c627-8633-47a8-867c-1b74bc7d1ef2.png">

###### Note the "Project ID" in upper left Project Info section
<img width="1440" alt="Secret2" src="https://user-images.githubusercontent.com/79027915/202631603-16d77fde-3c34-4499-b38f-5467df4d2e61.png">

###### Create Service Account with name as "spring-gumball"
<img width="1440" alt="Create Service" src="https://user-images.githubusercontent.com/79027915/202631601-9c1b8d12-6edf-41dd-9a47-04158b841f36.png">
<img width="1440" alt="Create Service 1" src="https://user-images.githubusercontent.com/79027915/202631598-e51cf776-37f7-47a1-b719-d4da54b92858.png">

###### Enable Resource Manger API
<img width="1440" alt="Resource Manager API" src="https://user-images.githubusercontent.com/79027915/202631595-935482e6-4ca7-4bb2-a869-64e9b472bcd5.png">

###### Grant Access / Select Service Account "spring-gumball"
<img width="1440" alt="Navigation" src="https://user-images.githubusercontent.com/79027915/202631593-7e69cd63-6f00-47aa-94f6-42b91a489645.png">
<img width="1440" alt="Acess1" src="https://user-images.githubusercontent.com/79027915/202641066-65d6c970-e46d-4414-b1d5-03e611522bad.png">

###### Adding Kubernetes Engine Developer and Storage Admin
<img width="1440" alt="Access2" src="https://user-images.githubusercontent.com/79027915/202641059-919bffe7-3958-4811-b563-d4e7c62df070.png">

###### Result After Adding Roles 
<img width="1440" alt="Access3" src="https://user-images.githubusercontent.com/79027915/202641051-05c6d24d-6c7a-4cb3-9d88-ffaa7f936c03.png">

###### Enable AMI API
<img width="1440" alt="AMI API" src="https://user-images.githubusercontent.com/79027915/202635030-db039dda-37e8-4c07-94a3-349460687773.png">

###### Navivation / IAM & Admin / IAM / Service Account
<img width="1440" alt="key1" src="https://user-images.githubusercontent.com/79027915/202635028-2324a155-dee8-4681-aae1-c297b87b606d.png">

###### Select JSON Key
<img width="1440" alt="json" src="https://user-images.githubusercontent.com/79027915/202635024-35988fec-bfa6-4870-83d7-92168f3e9ae6.png">

###### Download JSON Key File
<img width="1440" alt="private key" src="https://user-images.githubusercontent.com/79027915/202635020-4eb80c31-0abf-4436-a001-69a8aa712004.png">
<img width="1440" alt="key result" src="https://user-images.githubusercontent.com/79027915/202635019-88bce6ec-af25-45b2-a8ba-fcc67d70d3d0.png">

###### GitHub / Repo / Settings / Secrets / Action Secrets
<img width="1440" alt="git secret1" src="https://user-images.githubusercontent.com/79027915/202635016-0bd41487-51cc-4e62-884a-02e66b4a3279.png">

###### New Repository Secret: GKE_PROJECT
<img width="1440" alt="gke key" src="https://user-images.githubusercontent.com/79027915/202635013-0fce41b8-5678-48b6-bb38-ac6f6397813c.png">
<img width="1440" alt="gke1" src="https://user-images.githubusercontent.com/79027915/202635010-2445199e-e306-45f2-927b-3b373c5af1ef.png">

###### New Repository Secret: GKE_SA_KEY
<img width="1440" alt="jSON file" src="https://user-images.githubusercontent.com/79027915/202635801-e8ce25ce-18be-4f1a-8963-8d65773063b8.png">
<img width="1440" alt="gke sa" src="https://user-images.githubusercontent.com/79027915/202635005-47e2254c-8ec3-4d05-9bac-859b8bf1094b.png">

###### Results of ADDING Repository Secrets
<img width="1440" alt="resultt gke keys" src="https://user-images.githubusercontent.com/79027915/202634984-aaf3f3b0-72ee-4439-b2c7-c75d03a5dd9a.png">

###### GKE Deployment Before Pushing Release
<img width="1440" alt="Deploy1" src="https://user-images.githubusercontent.com/79027915/202647727-b790e83e-3230-479f-bcfd-e94f636a81b3.png">

###### Pushing 2.3 RELEASE
<img width="1440" alt="2 31" src="https://user-images.githubusercontent.com/79027915/202647718-b71adfc9-dca9-4689-9b81-21cf48d27f1b.png">
<img width="1440" alt="2 32" src="https://user-images.githubusercontent.com/79027915/202647714-b5aeac0c-4065-41f7-9ba7-047cf2f7c74c.png">
<img width="1440" alt="2 33" src="https://user-images.githubusercontent.com/79027915/202647708-34e0f036-5aad-4ea7-96a5-605917e63c66.png">
<img width="1440" alt="2 34" src="https://user-images.githubusercontent.com/79027915/202647703-2e39e2a9-9a6e-45ad-b271-054fc3d49dce.png">
<img width="1440" alt="2 35" src="https://user-images.githubusercontent.com/79027915/202647700-a744251b-c727-4a8c-8534-b3fc7ca56026.png">
<img width="1440" alt="2 36" src="https://user-images.githubusercontent.com/79027915/202647695-737704f3-6cb8-4b8b-9012-b0f832023d6e.png">

###### Create google.yml
<img width="1440" alt="Create google" src="https://user-images.githubusercontent.com/79027915/202650176-f5267637-e506-46ec-bc1f-dc0a91850dca.png">

###### Change the values for the GKE_ZONE, GKE_CLUSTER, IMAGE, and DEPLOYMENT_NAME environment variables
<img width="1440" alt="Edit google" src="https://user-images.githubusercontent.com/79027915/202650184-271e7935-0191-4780-ba37-e83633ee2b6f.png">

###### New GKE Deployment
<img width="1440" alt="Depl" src="https://user-images.githubusercontent.com/79027915/202647689-f336a149-020d-4385-9cf1-f017b6758f2b.png">

###### GKE Service
<img width="1440" alt="Sv1" src="https://user-images.githubusercontent.com/79027915/202647687-99ca8eea-5a2b-4aef-8c36-2c6a8f7d2651.png">

###### GKE Ingress
<img width="1440" alt="I1" src="https://user-images.githubusercontent.com/79027915/202647683-2e06b526-4621-43b6-9fdb-68d607e8837a.png">
<img width="1440" alt="Ingress" src="https://user-images.githubusercontent.com/79027915/202648786-5752b742-4a0d-44ad-9138-3fcf0b0b399f.png">

###### Web UI  on Load Balancer's External IP 
<img width="1440" alt="lb external" src="https://user-images.githubusercontent.com/79027915/202649005-23aad05e-f6cb-430c-93a3-c8a55c2d9a33.png">

