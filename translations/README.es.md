<div align = "center">
<img src="https://github.com/andresWeitzel/Amazon_Web_Services_Projects/blob/master/doc/assets/img/aws-img.jpg" >
</div>

<br>

<div align="right">
    <a href="https://github.com/andresWeitzel/Amazon_Web_Services_Projects/blob/master/translations/README.es.md" target="_blank">
      <img src="https://github.com/andresWeitzel/Amazon_Web_Services_Projects/blob/master/doc/assets/img/arg-flag.jpg" width="10%" height="10%" />
  </a> 
   <a href="https://github.com/andresWeitzel/Amazon_Web_Services_Projects" target="_blank">
      <img src="https://github.com/andresWeitzel/Amazon_Web_Services_Projects/blob/master/doc/assets/img/eeuu-flag.jpg" width="10%" height="10%" />
  </a> 
</div>


<div align="center">
  
##  Amazon Web Services 

</div>  


<br>

Repositorio central para proyectos que implementan tecnologías de Amazon Web Services (AWS). Se implementan las siguientes tecnologías.

<br>

* Lenguajes: Javascript, Typecript, otros.
* Frameworks: Serverless, otros.
* Servicios AWS: Lambda, S3, SQS, SNS, RDS, Api Gateway, DynamoDB, otros.
* Tecnologías: Nodejs, otras.
* ORM: Sequelize, otros.
* Bases de datos: MySQL, DynamoDB, otras.
* Bibliotecas: dotenv, cors, aws-sdk-v3, nodemon, otras.
* Herramientas: vsc, cartero, git, otras.

 <br>
 
 <br>

<!------Start Index----->

## Índice 📜

<details>
 <summary> Ver </summary>

 <br>
 
* [Microservicio para gestión de usuarios de mercado libre](#microservicio-para-gestión-de-usuarios-ml-implementado-con-systems-manager-parameter-store-api-gateway-serverless-framework-lambda-nodejs-sequelize-mysql-amazon-rds-otros-)[Nodejs, Sequelize, Mysql, otros]
* [Api Rest para la gestión estadística de la producción y venta de bioetanol](#api-rest-para-la-gestión-estadística-de-la-producción-y-venta-de-bioetanol-implementada-con-serverless-framework-api-gateway-nodejs-dynamodb-systems-manager-parameter-store-lambda-others-)[ DynamoDB, Nodejs, Api Gateway, otros]
* [Sistema de respaldo para planta minera](#sistema-de-copia-de-seguridad-para-registros-de-planta-minera-implementado-con-sqs-sns-typescript-s3-dynamodb-api-gateway-cloudwatch-systems-manager-parameter-store-serverless-framework-lambda-otros-)[ S3, SQS, SNS, otros ]
* [Modelo CRUD para administrar objetos con servicio S3](#crud-model-for-managing-objects-with-aws-amazon-s3-implemented-with-systems-manager-parameter-store-bucket-s3-api-gateway-serverless-framework-lambda-nodejs-aws-sdk-v3-others-)[ Nodejs, S3, Api Gateway, otros ]
* [Modelo CRUD para gestionar Pagos con MercadoPago](#modelo-crud-para-administrar-objetos-de-pago-mercadopago-con-aws-dynamodb-implementado-con-api-gateway-systems-manager-parameter-store-serverless-framework-lambda-typescript-dynamodb-aws-sdk-v3-others-)[ DynamoDB, Typescript, Nodejs, otros]
* [Comunicación entre productor y consumidor lambda con servicio SQS](#comunicación-entre-productor-y-consumidor-lambda-usando-el-servicio-aws-sqs-con-fifo-colas-)[ SQS, Nodejs, Api Gateway, otros]
* [Modelo CRUD para comunicación entre lambdas con servicio SQS](#crud-model-for-communication-between-lambdas-through-amazon-simple-notification-service-sns-)[ SNS, Nodejs, Api Gateway, otros ]
  
<br>

</details>

<!------Stop Index----->
  
 <br>
 
 <br>

 <!------MICROSERVICIO USUARIOS ML AWS------>
 
<div align="center">
  
 ### Microservicio para la gestión de usuarios (ML) implementado con Systems Manager Parameter Store, Api-Gateway, Serverless-Framework, Lambda, NodeJs, Sequelize, Mysql, Amazon RDS, otros. [🔝](#índice-)
 
  <a href="https://github.com/andresWeitzel/Microservice_Mercadolibre_Users_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/Microservice_Mercadolibre_Users_AWS/blob/master/doc/assets/MicroService_Users_ML.drawio.png" >
  </a>

 ### [[Repositorio]](https://github.com/andresWeitzel/Microservice_Mercadolibre_Users_AWS) [|]() [[PlayList]](https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Microservice_Mercadolibre_Users_AWS" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/youtubeLogo.gif" />
  </a>
 </div>
  
 ###  Stack implementado
  
 <div style="display: inline-block;">
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/lambda.png" />
  <img width="48" height="46" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/api-gateway.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/parameterStore.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/nodeJs.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/sequelize.png" />
  <img width="35" height="42" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/rds.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/vsc.png" />
  <img width="40" height="40" src="https://cdn.icon-icons.com/icons2/3053/PNG/512/postman_alt_macos_bigsur_icon_189814.png" />
  <img width="44" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/git.png" />
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
  
 ### Api Rest para el manejo estadístico de producción y ventas de bioetanol implementado con Serverless-Framework, Api-Gateway, NodeJs, DynamoDB, Systems Manager Parameter Store, Lambda, otros. [🔝](#índice-)
 
  <a href="https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS/blob/master/doc/datos/bioetanolTablas.png" >
  </a>

 ### [[Repositorio]](https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS) [|]() [[PlayList]](https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/youtubeLogo.gif" />
  </a>
 </div>
  
 ###  Stack implementado
  
 <div style="display: inline-block;">
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/typescript.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/vsc.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/DynamoDB.png" />
  <img width="40" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/parameterStore.png" />
  <img width="43" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/api-gateway.png" />
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/lambda.png" />
  <img width="40" height="40" src="https://cdn.icon-icons.com/icons2/3053/PNG/512/postman_alt_macos_bigsur_icon_189814.png" /> 
  <img width="44" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/git.png" />
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
  
 ### Sistema de respaldo para registros de plantas mineras implementado con SQS, SNS, Typescript, S3, DynamoDB, Api Gateway, Cloudwatch, Systems Manager Parameter Store, Serverless-Framework, Lambda, otros. [🔝](#índice-)
 
  <a href="https://github.com/andresWeitzel/BackupSystem_SQS_SNS_S3_DynamoDB_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/BackupSystem_SQS_SNS_S3_DynamoDB_AWS/blob/master/doc/assets/SNS_SQS_DYNAMO_S3.drawio.png" >
  </a>

 ### [[Repositorio]](https://github.com/andresWeitzel/BackupSystem_SQS_SNS_S3_DynamoDB_AWS) [|]() [[PlayList]](https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Api_Bioetanol_Estadisticas_DynamoDB_AWS" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/watch?v=oLSrmqMq0Zs&list=PLCl11UFjHurB9JzGtm5e8-yp52IcZDs5y" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/youtubeLogo.gif" />
  </a>
 </div>
  
 ###  Stack implementado
  
 <div style="display: inline-block;">
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/typescript.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/vsc.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/DynamoDB.png" />
  <img width="40" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/parameterStore.png" />
  <img width="43" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/api-gateway.png" />
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/lambda.png" />
  <img width="40" height="40" src="https://cdn.icon-icons.com/icons2/3053/PNG/512/postman_alt_macos_bigsur_icon_189814.png" /> 
  <img width="44" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/git.png" />
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
  
 ### Modelo CRUD para el manejo de objetos con amazon s3 de aws implementado con Systems Manager Parameter Store, Bucket S3, Api-Gateway, Serverless-Framework, Lambda, NodeJs, aws-sdk-v3, otros. [🔝](#índice-)
 
  <a href="https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS/blob/master/doc/assets/CRUD_Bucket_s3.drawio.png" >
  </a> 

  ###  [[Repositorio]](https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurDPyOkEXOR6JO-vUnYqd1FW)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurDPyOkEXOR6JO-vUnYqd1FW" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/youtubeLogo.gif" />
  </a>
 </div>

 ###  Stack implementado
  
 <div style="display: inline-block;">
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/lambda.png" />
  <img width="48" height="46" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/api-gateway.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/parameterStore.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/nodeJs.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/vsc.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/s3.png" />
  <img width="40" height="40" src="https://cdn.icon-icons.com/icons2/3053/PNG/512/postman_alt_macos_bigsur_icon_189814.png" /> 
  <img width="44" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/git.png" />
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
  
 ### Modelo CRUD para el manejo de objetos payments de mercadopago con DynamoDB de aws implementado con Api-Gateway, Systems Manager Parameter Store, Serverless-Framework, Lambda, Typescript, DynamoDB, aws-sdk-v3, otros. [🔝](#índice-)
 
  <a href="https://github.com/andresWeitzel/CRUD_Amazon_DynamoDB_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/CRUD_Amazon_DynamoDB_AWS/blob/master/doc/assets/CRUD_Amazon_DynamoDB_AWS.drawio.png" >
  </a> 

  ###  [[Repositorio]](https://github.com/andresWeitzel/CRUD_Amazon_DynamoDB_AWS) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurBIy51oB_CZa46KSF1cWn9W)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/CRUD_Amazon_S3_AWS" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurDPyOkEXOR6JO-vUnYqd1FW" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/youtubeLogo.gif" />
  </a>
 </div>

 ###  Stack implementado

 <div style="display: inline-block;">
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/typescript.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/vsc.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/DynamoDB.png" />
  <img width="40" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/parameterStore.png" />
  <img width="43" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/api-gateway.png" />
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/lambda.png" />
  <img width="40" height="40" src="https://cdn.icon-icons.com/icons2/3053/PNG/512/postman_alt_macos_bigsur_icon_189814.png" />
  <img width="44" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/git.png" />
 </div>
 </div>
  
<!------FIN CRUD Amazon DynamoDB AWS------>


<br>
<br>
<br>
<br>
<br>
<br>
  
  
<!------Producer_Consumer_SQS_FIFO_AWS------>
  
<div align="center">

 ### Comunicación entre lambda producer y lambda consumer utilizando el servicio SQS de AWS con colas FIFO. [🔝](#índice-)
 
  <a href="https://github.com/andresWeitzel/Producer_Consumer_SQS_FIFO_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/Producer_Consumer_SQS_FIFO_AWS/blob/master/doc/assets/img/Producer_Consumer_SQS_FIFO_AWS.drawio.png" >
  </a> 

  ###  [[Repositorio]](https://github.com/andresWeitzel/Producer_Consumer_SQS_FIFO_AWS) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurCkJNddrHBJ_TUfMlrHuWyb)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/Producer_Consumer_SQS_FIFO_AWS" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurCkJNddrHBJ_TUfMlrHuWyb" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/youtubeLogo.gif" />
  </a>
 </div>

 ###  Stack implementado

 <div style="display: inline-block;">
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/lambda.png" />
  <img width="48" height="46" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/api-gateway.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/parameterStore.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/nodeJs.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/vsc.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/sqs.png" />
  <img width="40" height="40" src="https://cdn.icon-icons.com/icons2/3053/PNG/512/postman_alt_macos_bigsur_icon_189814.png" />
  <img width="44" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/git.png" />
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

 ### Modelo CRUD para la comunicación entre lambdas a través de amazon simple notification service (SNS). [🔝](#índice-)
 
  <a href="https://github.com/andresWeitzel/CRUD_SNS_NodeJS_AWS" target="_blank">
  <img src="https://github.com/andresWeitzel/CRUD_SNS_NodeJS_AWS/blob/master/doc/assets/sns-example.png" >
  </a> 

  ###  [[Repositorio]](https://github.com/andresWeitzel/CRUD_SNS_NodeJS_AWS) [|]() [[PlayList]](https://www.youtube.com/playlist?list=PLCl11UFjHurCkJNddrHBJ_TUfMlrHuWyb)
  
 <div style="display: inline-block;"> 
  <a href="https://github.com/andresWeitzel/CRUD_SNS_NodeJS_AWS" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/github.gif" />
  </a>
   <a href="https://www.youtube.com/playlist?list=PLCl11UFjHurCkJNddrHBJ_TUfMlrHuWyb" target="_blank">
    <img width="60" height="60" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/redes/youtubeLogo.gif" />
  </a>
 </div>

 ###  Stack implementado

 <div style="display: inline-block;">
  <img width="35" height="35" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/lambda.png" />
  <img width="48" height="46" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/api-gateway.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/parameterStore.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/nodeJs.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/front/vsc.png" />
  <img width="40" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/aws/sqs.png" />
  <img width="40" height="40" src="https://cdn.icon-icons.com/icons2/3053/PNG/512/postman_alt_macos_bigsur_icon_189814.png" />
  <img width="44" height="40" src="https://github.com/andresWeitzel/Graphics/blob/master/GithubReadme/back/git.png" />
 </div>
  </div>
  
<!------FIN  CRUD_SNS_NodeJS_AWS------>

<!--<<<<<<<<<<<<<<<<<<<<<<<<<<<<FIN SECCIÓN AWS>>>>>>>>>>>>>>>>>>>>>>>>>>>>-->


<br>
<br>
<br>
<br>

  
