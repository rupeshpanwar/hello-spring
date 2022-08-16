# Read Me First
The following was discovered as part of building this project:

* The original package name 'com.lpt.hello-spring' is invalid and this project uses 'com.lpt.hellospring' instead.

# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.7.2/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.7.2/maven-plugin/reference/html/#build-image)


<details>
<summary>Introduction</summary>
<br>
  
![](i/20220815120030.png)  

![](i/20220815120332.png)  

![](i/20220815120414.png)  

![](i/20220815120440.png)  

![](i/20220815120531.png)  
![](i/20220815120610.png)  
![](i/20220815120627.png)  

- run the maven project
![](i/20220815120843.png)  

![](i/20220815120946.png)  

![](i/20220815121144.png)  

> mvn clean spring-boot:run
> ./mvnw clean spring-boot:run
> 
![](i/20220815121333.png)  

![](i/20220815121440.png)  
![](i/20220815121454.png)  
</details>

<details>
<summary>MVC</summary>
<br>

  
- Client - Server  model for request/response
![](i/20220815122328.png)  

- adding HTTP dependency
- https://mvnrepository.com/
  
![](i/20220815134156.png)  

![](i/20220815134324.png)  

![](i/20220815135236.png)  


- add HTML boiler plate extension
  ![](i/20220815134757.png)  

- change default port
  
  ![](i/20220815135119.png)  

- MVC
<img width="955" alt="image" src="https://user-images.githubusercontent.com/75510135/184746862-70727b5d-1cb3-4954-a4a6-fbdde3d8b029.png">

<img width="955" alt="image" src="https://user-images.githubusercontent.com/75510135/184747207-71a585c4-a7e5-41c9-809d-d284590e1e6f.png">


<img width="955" alt="image" src="https://user-images.githubusercontent.com/75510135/184747580-bcf0a282-2713-45a0-b62a-d0b1b6de3082.png">


- Annotation
<img width="955" alt="image" src="https://user-images.githubusercontent.com/75510135/184748496-635b4a11-65f1-416c-883f-d45d6701b63b.png">


<img width="955" alt="image" src="https://user-images.githubusercontent.com/75510135/184748660-1ff07080-b4af-4e12-9a8a-fdf49abba35c.png">


<img width="955" alt="image" src="https://user-images.githubusercontent.com/75510135/184749074-f6d538b4-f080-486f-943f-431e5bcd8a82.png">


- Get request(via Controller class)
<img width="955" alt="image" src="https://user-images.githubusercontent.com/75510135/184750678-7d74c528-4d37-445a-be3c-a3acc21f8997.png">


<img width="955" alt="image" src="https://user-images.githubusercontent.com/75510135/184751095-04d12afe-8fab-42ae-9012-4a8992559130.png">


<img width="955" alt="image" src="https://user-images.githubusercontent.com/75510135/184751384-cc0dbf8e-53d6-48a4-8acd-fe19dbf0d5b9.png">

<img width="1009" alt="image" src="https://user-images.githubusercontent.com/75510135/184751659-b337713c-d627-4dc7-bd5f-c1274d8ca42b.png">

- Recap
<img width="1009" alt="image" src="https://user-images.githubusercontent.com/75510135/184752952-e4b74e13-7f99-4cc2-bde7-cc8c9ba421b1.png">

<img width="1009" alt="image" src="https://user-images.githubusercontent.com/75510135/184753069-39517374-7688-4a82-adab-9cb31249dfdd.png">

<img width="1009" alt="image" src="https://user-images.githubusercontent.com/75510135/184753420-3ab8718b-e82a-4b09-ad19-e73c6757e96b.png">

  - Model
  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184817813-873ace07-9f93-4e6d-b9e2-e694906741b6.png">

  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184818004-c6b0399f-8414-43b5-9fea-8a22f4e1fd6b.png">

<img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184818242-dddc7e05-9d5d-4adf-9bdd-5c5a575f85db.png">
  
  - call model
  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184818355-ba84af41-e8a7-4680-9821-eb35adaba01f.png">

  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184819622-ff268cf8-f1d3-44f6-9068-861ec7695cee.png">

  - create model class
  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184819742-761af167-8d61-4396-a264-d51d99f2484c.png">

  <img width="949" alt="image" src="https://user-images.githubusercontent.com/75510135/184819906-405e218c-333f-44d3-ad04-2be414868f19.png">

  <img width="949" alt="image" src="https://user-images.githubusercontent.com/75510135/184820040-a85c3060-cfb5-4ff5-991d-4a4d89f989fb.png">

  <img width="949" alt="image" src="https://user-images.githubusercontent.com/75510135/184820948-10ea4280-ffe6-48f8-baa8-ec18f8393133.png">

  <img width="949" alt="image" src="https://user-images.githubusercontent.com/75510135/184821066-409850fd-b78b-43e8-a22a-8e5ac78a982b.png">

  - add model attribute
  <img width="949" alt="image" src="https://user-images.githubusercontent.com/75510135/184821260-2dd38616-6df8-45d1-bde9-3d8311e5e4d6.png">

  <img width="949" alt="image" src="https://user-images.githubusercontent.com/75510135/184821350-3de420dc-da8c-4ac3-88db-78a56d430e24.png">

  - Testing
 <img width="1015" alt="image" src="https://user-images.githubusercontent.com/75510135/184822764-712721b4-76fe-4acb-9697-81b5e74fe9ca.png">
  
  <img width="1015" alt="image" src="https://user-images.githubusercontent.com/75510135/184823175-c2bac99c-6dcd-4d02-b66a-906031064a48.png">

  - Thymleaf => to merge model into view
  
  <img width="1015" alt="image" src="https://user-images.githubusercontent.com/75510135/184824796-6a0669fb-2435-4152-9271-63ffbc2bc807.png">

  <img width="1015" alt="image" src="https://user-images.githubusercontent.com/75510135/184824916-6db04adf-5a84-4fb3-af23-d8cb9295d803.png">

  <img width="1015" alt="image" src="https://user-images.githubusercontent.com/75510135/184825065-9a03fbfd-596c-4203-8be8-16ccaa038cc9.png">

  <img width="1015" alt="image" src="https://user-images.githubusercontent.com/75510135/184825200-66209d23-d861-4acd-b13b-6fe8da901e1c.png">

  <img width="1015" alt="image" src="https://user-images.githubusercontent.com/75510135/184825272-062df160-22ae-4e4f-8a30-ddf3508f97e4.png">

  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184825383-d33dfa29-b505-4fec-8a05-cc99618513c2.png">

  - practically
  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184825481-0b3e8f03-40a2-4e84-990e-2c1c5e5248d1.png">

  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184825676-3a295b50-07a0-4974-b6e6-760ed3d82374.png">

  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184825704-6c5f39f1-2877-494c-9caa-4d1053b76cb6.png">

  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184825886-fd9fc024-5d3f-4663-ba4b-b28d5aaa3f3f.png">

  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184826486-e8f49ffb-dcc8-40cc-98d1-d012677076f9.png">

  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184826441-1b9dc440-529f-48ea-a63d-75c0e4bdcb35.png">

  - selection
  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184836195-eed94568-05be-49cb-8d78-41a20254ad54.png">

  <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184836300-3faecbbc-0fbb-4a41-9c76-8b4396edf99d.png">
 <img width="923" alt="image" src="https://user-images.githubusercontent.com/75510135/184836724-8a8895ab-674a-435a-b12f-21c1d5780d84.png">

  
  
</details>

<details>
<summary>Reference links</summary>
<br>

  
</details>

- extension
  <img width="949" alt="image" src="https://user-images.githubusercontent.com/75510135/184820138-0c750b63-df3b-426f-9e04-83824bd625ef.png">

  



