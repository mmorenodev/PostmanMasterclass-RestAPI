# PostmanMasterclass-RestAPI
Learning about POSTMAN and REST APIs

## Path Parameters
Remember that is a standard/convention to identify the id of a resource directly in the path param when working with REST APIs. 

## Response Headers

<img width="265" alt="image" src="https://user-images.githubusercontent.com/66931789/187983268-824d7d4b-e2ee-4572-aee8-7117875e2c9e.png">

Once we get 'content-encoding: gzip' the browser identifies this request and knows how to unzip this. 

## Cookies and request body 
We don't need to explicitly add the cookies with every request. Cookie parameters are automatically attached with every request. 

One important point to note is when using cookies, we are going attach the cookies of a particular domain. This is how the browser is identified by the server. 

## Request Body
Used when we want to POST data to a server. 

## HTTP PUT vs HTTP PATCH in a REST API
When a client needs to replace an existing Resource entirely, they can use PUT. When they're doing a partial update, they can use HTTP PATCH. 

For instance, when updating a single field of the Resource, sending the complete Resource representation can be cumbersome and uses a lot of unnecessary bandwidth. In such cases, the semantics of PATCH make a lot more sense. 

Another important aspect to consider here is idempotence. PUT is idempotent; PATCH can be idempotent but isn't required to be. So, depending on the semantics of the operation we're impelmenting, we can also choose one or the other based on this characteristic. 

<img width="771" alt="image" src="https://user-images.githubusercontent.com/66931789/187987164-a95b04be-f9c5-46d0-ba48-ad5958ace944.png">

**A RequestBody can be mapped using a 'Map' object, instead of creating a lot of DTO objects.**. This approach gives us more flexibility implementing the API, but we do lose a few things as well, such as validation. 

## Common Response Codes

<img width="540" alt="image" src="https://user-images.githubusercontent.com/66931789/187987441-ec42b8e3-ed99-4937-97f0-48f87c56178c.png">


# POSTMAN
Postman started as a REST-API client but in the present it is more than that. What are the features provided by postman?
- Create API request
- Design API
- Create and Share Documentation
- Collaborate with teams
- API testing


You can organize different Workspaces and inside collections which in fact you can create folders inside. 

## Collection and Global Variables
The different type of variables supported by postman are:
- Global
- Collection
- Environment
- Data
- Local

<img width="898" alt="image" src="https://user-images.githubusercontent.com/66931789/188018479-aa9b3442-d939-4055-93db-47077405a50b.png">

## Dynamic Variables

<img width="498" alt="image" src="https://user-images.githubusercontent.com/66931789/188020200-7eabf31f-6255-414a-82d7-629c58656e36.png">

<img width="584" alt="image" src="https://user-images.githubusercontent.com/66931789/188020441-cc3b2ed8-d2b9-49b8-bc5e-5b9221befafa.png">

## Authentication In Postman








