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
<img width="1440" alt="Add principal" src="https://user-images.githubusercontent.com/79027915/202631589-e97362ce-ff54-4839-8a36-abfe4c57d888.png">

###### Adding Kubernetes Engine Developer and Storage Admin
<img width="1440" alt="Add roles" src="https://user-images.githubusercontent.com/79027915/202631582-739a5180-ebac-4c20-b0b3-bea77c4618f8.png">

###### Result After Adding Roles 
<img width="1440" alt="Result of grant acess" src="https://user-images.githubusercontent.com/79027915/202631569-94c351e5-ece6-489c-902a-3aa77846e96a.png">

###### 
###### 
###### 
###### 
###### 

