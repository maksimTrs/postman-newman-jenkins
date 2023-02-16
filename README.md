# postman-newman-jenkins
newman run "petstore.swagger.io.postman_collection.json" -e "PetShopEnv.postman_environment.json" -d "WH_Mercury_Lection4.csv" --reporters htmlextra --reporter-htmlextra-omitHeaders
