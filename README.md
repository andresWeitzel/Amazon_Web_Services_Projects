
<div align = "center">
<img src="./doc/assets/img/aws-img.jpg" >
</div>

<br>

<div align="right">
    <a href="./translations/README.es.md" target="_blank">
      <img src="./doc/assets/img/arg-flag.jpg" width="10%" height="10%" />
  </a> 
   <a href="https://github.com/andresWeitzel/Amazon_Web_Services_Projects" target="_blank">
      <img src="./doc/assets/img/eeuu-flag.jpg" width="10%" height="10%" />
  </a> 
</div>


<div align="center">
  
## <img width="48" height="48"  src="./doc/assets/gifs/aws/aws.gif" /> Amazon Web Services

</div>  

<br>

Central repository for projects and tutorials that implement Amazon Web Services (AWS) technologies.

 <br>

 * Languages : Javascript, Typescript, others.
 * Frameworks : Serverless, others.
 * AWS Services : Lambda, S3, SQS, SNS, RDS, Api Gateway, DynamoDB, others.
 * Technologies : Nodejs, others.
 * ORM : Sequelize, TypeORM, others.
 * Databases : MySQL, DynamoDB, others.
 * Libraries : dotenv, cors, aws-sdk-v3, nodemon, others.
 * Tools : Vsc, Postman, Git, others.
 * Testing : Jest, Supertest, Mocha & Chai, others.
   
 <br>
 
 <br>

<!------Start Index----->

## Index 📜

<details>
 <summary> See </summary>

 <br>
 
#### Projects 
* [Microservice for mercado libre users management](#microservice-for-mercado-libre-user-management-) [ Nodejs, Sequelize, Mysql , others ]
* [Api Rest for the statistical management of bioethanol production and sales](#api-rest-for-the-statistical-management-of-bioethanol-production-and-sales-implemented-with-serverless-framework-api-gateway-nodejs-dynamodb-systems-manager-parameter-store-lambda-others-) [ DynamoDB, Nodejs, Api Gateway , others ]
* [Backup System for mining plant](#backup-system-for-mining-plant-records-implemented-with-sqs-sns-typescript-s3-dynamodb-api-gateway-cloudwatch-systems-manager-parameter-store-serverless-framework-lambda-others-) [ S3, SQS, SNS, others ]
* [CRUD model for managing object with S3 service](#crud-model-for-managing-objects-with-aws-amazon-s3-implemented-with-systems-manager-parameter-store-bucket-s3-api-gateway-serverless-framework-lambda-nodejs-aws-sdk-v3-others-) [ Nodejs, S3, Api Gateway, others ]
* [CRUD model for managing Payments with MercadoPago](#crud-model-for-managing-mercadopago-payment-objects-with-aws-dynamodb-implemented-with-api-gateway-systems-manager-parameter-store-serverless-framework-lambda-typescript-dynamodb-aws-sdk-v3-others-) [ DynamoDB, Typescript, Nodejs, others ]
* [Microservice OpenWeather Nodejs Jest](#microservice-openweather-with-nodejs-jest-api-gateway-systems-manager-parameter-store-serverless-framework-lambda-others-) [ NodeJS, Jest, Serverless-Framework, etc. ]
* [Communication between lambda producer and consumer with SQS service](#communication-between-lambda-producer-and-lambda-consumer-using-the-aws-sqs-service-with-fifo-queues-) [ SQS, Nodejs, Api Gateway, others ]
* [CRUD model for communication between lambdas with SNS service](#crud-model-for-communication-between-lambdas-through-amazon-simple-notification-service-sns-) [ SNS, Nodejs, Api Gateway, others ]

<br>

#### AWS Serverless Tutorials
* [Creating and deploying a lambda function with serverless in AWS ](#creating-and-deploying-a-lambda-function-with-serverless-in-aws-) [ Nodejs, Serverless, Lambda , others ]
* [Creating and deploying a lambda function with serverless, Api gateway and nodejs in AWS](#creating-and-deploying-a-lambda-function-with-serverless-api-gateway-and-nodejs-in-aws-) [ Api Gateway, Serverless, Lambda , others ]

<br>

#### AWS Console Tutorials
* [Create a lambda function with Nodejs from AWS](#create-a-lambda-function-with-nodejs-from-aws-) [ Nodejs, Serverless, Lambda , others ]
* [Create a lambda function with Nodejs and Api Gateway from AWS](#create-a-lambda-function-with-nodejs-and-api-gateway-from-aws-) [ Api Gateway, Serverless, Lambda , others ]

<br>

</details>

<!------Stop Index----->
  
 <br>
 
 <br>
  
<div align="center">
    
 ## Projects 

</div>

<br>
 
 <!------MICROSERVICIO USUARIOS ML AWS------>
 
<div align="center">
  
### Microservice for mercado libre users management. [🔝](#index-)

  <a href="https://github.com/andresWeitzel/Microservice_Mercadolibre_Users_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/Microservice_Mercadolibre_Users_AWS/blob/master/doc/assets/MicroService_Users_ML.drawio.png" >
  </a>

<br>

<br>

 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Microservice_Mercadolibre_Users_AWS" target="_blank">
    <img width="52" height="52" src="./doc/assets/gifs/web-code/file-folder.gif" />
  </a>
   <a href="https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y" target="_blank">
    <img width="60" height="60" src="./doc/assets/gifs/social-network/youtube.gif" />
  </a>
 </div>
  
 ### Used Stack
  
 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="48" height="46" src="./doc/assets/icons/aws/api-gateway.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/nodeJs.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/sequelize.png" />
  <img width="35" height="42" src="./doc/assets/icons/aws/rds.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" />
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div> 
  </div>
<!------FIN MICROSERVICIO USUARIOS ML AWS------>

  
<br>
<br>
<br>
<br>
<br>
<br>


 <!------Api_Bioetanol_Estadisticas_DynamoDB_AWS------>
 
<div align="center">
  
### Api Rest for the statistical management of bioethanol production and sales implemented with Serverless-Framework, Api-Gateway, NodeJs, DynamoDB, Systems Manager Parameter Store, Lambda, others. [🔝](#index-)

  <a href="https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS/blob/master/doc/datos/bioetanolTablas.png" >
  </a>

 ### [[Repository]](https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS) [|]() [[PlayList]](https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/youtubeLogo.gif" />
  </a>
 </div>
  
 ### Used Stack
  
 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/front/typescript.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/DynamoDB.png" />
  <img width="40" height="35" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="43" height="40" src="./doc/assets/icons/aws/api-gateway.png" />
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" /> 
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div>
 </div>
<!------FIN Api_Bioetanol_Estadisticas_DynamoDB_AWS------>

<br>
<br>
<br>
<br>
<br>
<br>


 <!------BackupSystem_SQS_SNS_S3_DynamoDB_AWS ------>
 
<div align="center">
  
### Backup system for mining plant records implemented with SQS, SNS, Typescript, S3, DynamoDB, Api Gateway, Cloudwatch, Systems Manager Parameter Store, Serverless-Framework, Lambda, others. [🔝](#index-)

  <a href="https://github.com/andresWeitzel/BackupSystem_SQS_SNS_S3_DynamoDB_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/BackupSystem_SQS_SNS_S3_DynamoDB_AWS/blob/master/doc/assets/SNS_SQS_DYNAMO_S3.drawio.png" >
  </a>

 ### [[Repository]](https://github.com/andresWeitzel/BackupSystem_SQS_SNS_S3_DynamoDB_AWS) [|]() [[PlayList]](https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/youtubeLogo.gif" />
  </a>
 </div>
  
 ### Used Stack
  
 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/front/typescript.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/DynamoDB.png" />
  <img width="40" height="35" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="43" height="40" src="./doc/assets/icons/aws/api-gateway.png" />
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" /> 
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div>
 </div>
<!------FIN BackupSystem_SQS_SNS_S3_DynamoDB_AWS ------>

  
<br>
<br>
<br>
<br>
<br>
<br>
  
  
<!------CRUD Amazon S3 AWS------>
  
<div align="center">
  
### CRUD model for managing objects with aws amazon s3 implemented with Systems Manager Parameter Store, Bucket S3, Api-Gateway, Serverless-Framework, Lambda, NodeJs, aws-sdk-v3, others. [🔝](#index-)

  <a href="https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS/blob/master/doc/assets/CRUD_Bucket_s3.drawio.png" >
  </a> 

  ###  [[Repository]](https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurDPyOkEXOR6JO-vUnYqd1FW)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurDPyOkEXOR6JO-vUnYqd1FW" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/youtubeLogo.gif" />
  </a>
 </div>

 ### Used Stack
  
 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="48" height="46" src="./doc/assets/icons/aws/api-gateway.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/nodeJs.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/s3.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" /> 
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div>
  </div>
  
<!------FIN CRUD Amazon S3 AWS------>
  
<br>
<br>
<br>
<br>
<br>
<br>
  
<!------CRUD Amazon DynamoDB AWS------>
  
<div align="center">

### CRUD model for managing Mercadopago payment objects with aws DynamoDB implemented with Api-Gateway, Systems Manager Parameter Store, Serverless-Framework, Lambda, Typescript, DynamoDB, aws-sdk-v3, others. [🔝](#index-)
    
  <a href="https://github.com/andresWeitzel/CRUD_Amazon_DynamoDB_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/CRUD_Amazon_DynamoDB_AWS/blob/master/doc/assets/CRUD_Amazon_DynamoDB_AWS.drawio.png" >
  </a> 

  ###  [[Repository]](https://github.com/andresWeitzel/CRUD_Amazon_DynamoDB_AWS) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurBIy51oB_CZa46KSF1cWn9W)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurDPyOkEXOR6JO-vUnYqd1FW" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/youtubeLogo.gif" />
  </a>
 </div>

 ### Used Stack

 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/front/typescript.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/DynamoDB.png" />
  <img width="40" height="35" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="43" height="40" src="./doc/assets/icons/aws/api-gateway.png" />
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" />
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div>
 </div>
  
<!------FIN CRUD Amazon DynamoDB AWS------>


<br>
<br>
<br>
<br>
<br>
<br>
  
<!------Microservice OpenWeather Nodejs Jest ------>
  
<div align="center">

### Microservice OpenWeather with Nodejs, Jest, Api-Gateway, Systems Manager Parameter Store, Serverless-Framework, Lambda, others. [🔝](#index-)
    
  <a href="https://github.com/andresWeitzel/Microservice_OpenWeather_Nodejs_Jest_AWS" target="_blank">
  <img src="https://raw.githubusercontent.com/andresWeitzel/Microservice_OpenWeather_Nodejs_Jest_AWS/master/doc/assets/img/weather-data.png" >
  </a> 

  ###  [[Repository]](https://github.com/andresWeitzel/Microservice_OpenWeather_Nodejs_Jest_AWS) [|]() [[PlayList]]()
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Microservice_OpenWeather_Nodejs_Jest_AWS" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/github.gif" />
  </a>
   <a href="" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/youtubeLogo.gif" />
  </a>
 </div>

 ### Used Stack

 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="48" height="46" src="./doc/assets/icons/aws/api-gateway.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/nodeJs.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/sqs.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" />
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div>
 </div>
  
<!------FIN Microservice OpenWeather Nodejs Jest ------>


<br>
<br>
<br>
<br>
<br>
<br>
  
  
<!------Producer_Consumer_SQS_FIFO_AWS------>
  
<div align="center">

### Communication between lambda producer and lambda consumer using the AWS SQS service with FIFO queues. [🔝](#index-)

  <a href="https://github.com/andresWeitzel/Producer_Consumer_SQS_FIFO_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/Producer_Consumer_SQS_FIFO_AWS/blob/master/doc/assets/img/Producer_Consumer_SQS_FIFO_AWS.drawio.png" >
  </a> 

  ###  [[Repository]](https://github.com/andresWeitzel/Producer_Consumer_SQS_FIFO_AWS) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurCkJNddrHBJ_TUfMlrHuWyb)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Producer_Consumer_SQS_FIFO_AWS" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurCkJNddrHBJ_TUfMlrHuWyb" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/youtubeLogo.gif" />
  </a>
 </div>

 ### Used Stack

 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="48" height="46" src="./doc/assets/icons/aws/api-gateway.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/nodeJs.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/sqs.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" />
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div>
  </div>
  
<!------FIN Producer_Consumer_SQS_FIFO_AWS------>

<br>
<br>
<br>
<br>
<br>
<br>
  
  
<!------ CRUD_SNS_NodeJS_AWS------>
  
<div align="center">

### CRUD model for communication between lambdas through amazon simple notification service (SNS). [🔝](#index-)
    
  <a href="https://github.com/andresWeitzel/CRUD_SNS_NodeJS_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/CRUD_SNS_NodeJS_AWS/blob/master/doc/assets/sns-example.png" >
  </a> 

  ###  [[Repository]](https://github.com/andresWeitzel/CRUD_SNS_NodeJS_AWS) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurCkJNddrHBJ_TUfMlrHuWyb)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/CRUD_SNS_NodeJS_AWS" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurCkJNddrHBJ_TUfMlrHuWyb" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/youtubeLogo.gif" />
  </a>
 </div>

 ### Used Stack
 
 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="48" height="46" src="./doc/assets/icons/aws/api-gateway.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/nodeJs.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/sqs.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" />
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div>
  </div>
  
<!------FIN  CRUD_SNS_NodeJS_AWS------>


<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
  
<div align="center">
    
## AWS Serverless Tutorials

</div>

<!------ Lambda_Serverless_AWS_Example------>
  
<div align="center">

### Creating and deploying a lambda function with serverless in AWS. [🔝](#index-)
    
  <a href="https://github.com/andresWeitzel/Lambda_Serverless_AWS_Example" target="_blank">
  <img src="https://github.com/andresWeitzel/Lambda_Serverless_AWS_Example/blob/master/doc/assets/lambda.png" >
  </a> 

  ###  [[Repository]](https://github.com/andresWeitzel/Lambda_Serverless_AWS_Example) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurBhSQCwGDw7uDd2yAu5tVsV)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Lambda_Serverless_AWS_Example" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurBhSQCwGDw7uDd2yAu5tVsV" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/youtubeLogo.gif" />
  </a>
 </div>

 ### Used Stack
 
 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/nodeJs.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" />
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div>
</div>

<!------FIN  Lambda_Serverless_AWS_Example------>

<br>
 
<br>


<!------ Lambda_Api_Gateway_Serverless_AWS_Example------>
  
<div align="center">

### Creating and deploying a lambda function with serverless, Api gateway and nodejs in AWS. [🔝](#index-)
    
  <a href="https://github.com/andresWeitzel/Lambda_Api_Gateway_Serverless_AWS_Example" target="_blank">
  <img src="https://github.com/andresWeitzel/Lambda_Api_Gateway_Serverless_AWS_Example/blob/master/doc/assets/img/img.png" >
  </a> 

  ###  [[Repository]](https://github.com/andresWeitzel/Lambda_Api_Gateway_Serverless_AWS_Example) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurBhSQCwGDw7uDd2yAu5tVsV)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Lambda_Api_Gateway_Serverless_AWS_Example" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurBhSQCwGDw7uDd2yAu5tVsV" target="_blank">
    <img width="60" height="60" src="./doc/assets/icons/redes/youtubeLogo.gif" />
  </a>
 </div>

 ### Used Stack
 
 <div style="display: inline-block;">
  <img width="35" height="35" src="./doc/assets/icons/aws/lambda.png" />
  <img width="48" height="46" src="./doc/assets/icons/aws/api-gateway.png" />
  <img width="40" height="40" src="./doc/assets/icons/aws/parameterStore.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/nodeJs.png" />
  <img width="40" height="40" src="./doc/assets/icons/front/vsc.png" />
  <img width="40" height="40" src="./doc/assets/icons/back/postman.png" />
  <img width="44" height="40" src="./doc/assets/icons/back/git.png" />
 </div>
</div>

<!------FIN  Lambda_Api_Gateway_Serverless_AWS_Example------>



<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
  
  
<div align="center">
    
## AWS Console Tutorials

</div>

### Create a lambda function with Nodejs from AWS. [🔝](#index-)
[See Tutorial](https://www.youtube.com/watch?v=IwQxkeo1t4U&list=PLCl11UFjHurA0CRPpDpaqDfkhi-NReFzW&ab_channel=Andr%C3%A9sWeitzel%5B.archivo%5D)

<br>

### Create a lambda function with Nodejs and Api Gateway from AWS. [🔝](#index-)
[See Tutorial](https://www.youtube.com/watch?v=-HxTFrNoE58&list=PLCl11UFjHurA0CRPpDpaqDfkhi-NReFzW&index=2&ab_channel=Andr%C3%A9sWeitzel%5B.archivo%5D)

<br>


  
