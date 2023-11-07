### build docker image and push to docker hub
docker build . -f ./Briefbox.Microservice.Api/Dockerfile -t klarasmartai/business-api:dev
### docker push
docker push klarasmartai/business-api:dev

### build docker image and push to docker hub
docker build . -f ./Briefbox.Microservice.Api/Dockerfile -t klarasmartai/identity-api:dev
### docker push
docker push klarasmartai/identity-api:dev