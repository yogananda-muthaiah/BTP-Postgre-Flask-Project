# BTP-Postgre-Flask-Project
SAP BTP Project - Connected to Postgre DB with Flask Python 

#### SAP Community Blog Page Link
* 

## Login to SAP BTP Cloud Foundry
```
cf login --sso
```
## Enable Postgre DB Service in command line
```
cf create-service postgresql-db trial postgres-hyperscaler
```

  ### Just wait for 5mins to execute once above service is up and successfull 
  ```
  cf create-service-key postgres-hyperscaler postgre_key      
  cf service-key postgres-hyperscaler-postgre_key
  ```


## Deployment Steps for SAP BTP Cloud Foundry

```
cf push
```
## After Deployment - Testing with APIs

