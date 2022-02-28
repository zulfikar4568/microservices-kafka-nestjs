# Simple Kafka Nest js Microservices
<p align="center">
  <a href="https://github.com/zulfikar4568/" target="blank"><img src="./images/MicroservicesKafkaNestjs.svg" alt="Nest Logo" /></a>
</p>

Open 3 terminal to run application

### Running API Gateway
```bash
cd api-gateway
npm run start:dev
```

### Running Billing Microservice
```bash
cd billing
npm run start:dev
```

### Running Auth Microservice
```bash
cd auth
npm run start:dev
```

### Create Request POST to gateway
```bash
sudo apt-get install curl

curl -X POST http://localhost:3000/ \
   -H 'Content-Type: application/json' \
   -d '{ "userId": "123", "price": 12.323 }'
```

## How this app is made
dependencies
```
npm install @nestjs/microservices kafkajs
```