We will be using following ports for running our microservices and components. Copy them and have them handy as we go further in the course!
1. Limits Microservice<br>
   Ports: 8080, 8081, etc.

2. Spring Cloud Config Server<br>
   Port: 8888

3. Currency Exchange Microservice<br>
   Ports: 8000, 8001, 8002, etc.

4. Currency Conversion Microservice<br>
   Ports: 8100, 8101, 8102, etc.

5. Netflix Eureka Naming Server<br>
   Port: 8761

6. API Gateway<br>
   Port: 8765

7. Zipkin Distributed Tracing Server<br>
   Port: 9411

Adhering to these standards ensures smooth interaction and avoids conflicts in a distributed system.

We will make use of these in the next lecture!

URL
http://localhost:8000/currency-exchange/from/USD/to/INR

Response Structure
```json
{
   "id":10001,
   "from":"USD",
   "to":"INR",
   "conversionMultiple":65.00,
   "environment":"8000 instance-id"
}
```