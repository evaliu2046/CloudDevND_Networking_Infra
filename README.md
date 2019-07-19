# CloudDevND_Networking_Infra
Used Lucidchart to implement cloud architecture diagram, created a multi-Availability Zone Cloud container with Virtual Private Cloud(VPC) included, added public/private subnets and internet gateway to control traffic; 

Implemented basic Networking Infrastructure using CloudFormation code in YAM, added Routing method at the end to configure network routing rules. 

## AWS CLI CMD
Create the server with AWS CLI command line. 
```
 ./create.sh infrastack server.yml server_para.json 
```
Update the server once we have some changes made, done by AWS CLI command line. 
```
 ./update.sh infrastack server.yml server_para.json 
