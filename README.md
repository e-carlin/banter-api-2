aws dynamodb create-table --table-name Customer --attribute-definitions AttributeName=Id,AttributeType=S --key-schema AttributeName=Id,KeyType=HASH --provisioned-throughput ReadCapacityUnits=1,WriteCapacityUnits=1 --endpoint-url http://localhost:8000
aws dynamodb create-table --table-name InstitutionTokens --attribute-definitions AttributeName=itemId,AttributeType=S --key-schema AttributeName=itemId,KeyType=HASH --provisioned-throughput ReadCapacityUnits=1,WriteCapacityUnits=1 --endpoint-url http://localhost:8000


Validation handling
http://www.naturalprogrammer.com/spring-framework-rest-api-validation/
