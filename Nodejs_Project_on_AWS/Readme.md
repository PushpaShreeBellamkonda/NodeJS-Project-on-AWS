## Steps to be followed 

**step1: Cloning the repository and entering into the visual studio code** 


![Screenshot (1049)](https://github.com/user-attachments/assets/cd12f507-22fa-4ced-83a1-ba2bdd8b1cd2)


**step2: Creating a file called .env and setting up the environment variables needed** 


![Screenshot (1050)](https://github.com/user-attachments/assets/15a8214e-1cfd-4471-ac6c-0dd7a714af9b)


**step3: installing npm , the sdk for Nodejs**


![Screenshot (1051)](https://github.com/user-attachments/assets/8f14f0eb-6d6c-4460-af79-58eb2febffa6)


**step4: running the application by giving following command**


```
npm run start
```


![Screenshot (1052)](https://github.com/user-attachments/assets/053de062-94cf-4963-a8db-4c55b47e284b)



**Here is the application we deployed**



![Screenshot (1053)](https://github.com/user-attachments/assets/2040acb9-74b2-4f9a-8617-f582f458efc8)



## Now Lets deploy this in AWS using an EC2 instance


**step1 create an ec2 instance and provide inbound rule**


![Screenshot (1065)](https://github.com/user-attachments/assets/ccb32fd7-e9af-4874-8f9c-39615d57d33b)



**step2 login to the ec2 instance**


![Screenshot (1054)](https://github.com/user-attachments/assets/b8ebc032-65d3-44e8-8ff1-d5e91df68341)



**step3 install git , nodejs , npm using following commands**



```
sudo apt install nodejs
sudo apt install npm
```



![Screenshot (1060)](https://github.com/user-attachments/assets/96258fff-41d8-46c4-bd59-d3ca60af8eaa)



**step4 Clone the repository



![Screenshot (1061)](https://github.com/user-attachments/assets/3459b50b-ea0b-4b5c-919b-48f6e07c12c8)



**step5 Create a .env file**


![Screenshot (1063)](https://github.com/user-attachments/assets/4592300f-1812-423a-a75c-bfbd340f4fe8)



**step6 Setting up the evironment variables inside .env file**



![Screenshot (1062)](https://github.com/user-attachments/assets/94f92f35-7f2a-49f8-bddf-5211cb874393)




**step7 Run the following command to get the url for the application**



```
npm run staart

```




![Screenshot (1064)](https://github.com/user-attachments/assets/df931673-8790-4398-8a1d-597ec0b343a5)




**Browising the url we will get the output**




![Screenshot (1066)](https://github.com/user-attachments/assets/061f8b46-daef-442f-aa7a-d04883142aa3)














