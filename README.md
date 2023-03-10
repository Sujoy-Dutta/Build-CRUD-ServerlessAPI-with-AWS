# Build-CRUD-ServerlessAPI-with-AWS

![image](https://user-images.githubusercontent.com/54211163/224227253-08d418a5-a9b7-410b-8bc7-8089611e09d6.png)

Why Serverless-
  1.No need toprovision or manage the servers.
  2.Horizontal Scaling.
  3.Neverpay for ideal.
  4.More reliable.
  
 Steps:-
  1.Create DynamoDB -
  With DynamoDB, we can create database tables that can store and retrieve any amount of data and serve any level of request traffic.
  
  ![image](https://user-images.githubusercontent.com/54211163/224227616-cc17d8fd-e243-47de-a406-cfd47e634d94.png)
  
  2.Create Lambda Function -
  AWS Lambda allows you to add custom logic to Amazon DynamoDB tables, so you can easily apply compute to data as it enters or moves through the cloud.
  
  ![image](https://user-images.githubusercontent.com/54211163/224229989-fc03966b-b249-46f2-842a-6edb14b4d6cb.png)

    Provide roles to lambda, so that lambda can access dynamodb for any operations-
    
  ![image](https://user-images.githubusercontent.com/54211163/224230145-72767cae-8a0d-4b27-a97f-325ac83c1f3d.png)
  
  ![image](https://user-images.githubusercontent.com/54211163/224231717-b169470c-9d96-4986-9aa2-f3e049fa1cd4.png)

  
  3.Create API Gateway-
  
  API Gateway provides tools for creating and documenting web APIs that route HTTP requests to Lambda functions.
  
  ![image](https://user-images.githubusercontent.com/54211163/224231665-b8e40a54-2ddf-46e1-9659-8a44b9ea1911.png)

![image](https://user-images.githubusercontent.com/54211163/224231681-c04282a9-f891-401f-9f0f-471e87e035fd.png)

![image](https://user-images.githubusercontent.com/54211163/224231692-7e29ad54-231f-4430-8b82-4e671cf89c05.png)

 4.Test Using Postman-
 
 ![image](https://user-images.githubusercontent.com/54211163/224231764-8b1a4dc0-9a85-4fa6-a7fa-ad6bcf604002.png)
 
 ![image](https://user-images.githubusercontent.com/54211163/224231784-f83e6b2e-0250-4bf7-a889-9ec0e98d8e95.png)
 
 ![image](https://user-images.githubusercontent.com/54211163/224231894-8782b294-db80-4ad0-a799-bea25b274eff.png)




  
