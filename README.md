# Distributed-Tracing-and-Monitoring
Tracing and Monitoring microservices using Jaeger, Zipkin and Micrometer

Implemented distributed tracing by following the below links -

## Jaeger:
https://guides.micronaut.io/micronaut-microservices-distributed-tracing-jaeger/guide/index.html

## Zipkin:

https://guides.micronaut.io/micronaut-microservices-distributed-tracing-zipkin-groovy/guide/index.html

### Screenshots
All the testing and output screenshots are in screenshots folder

### Results

#### Jaeger
1.  All services are running and made a curl request to get book recommendations
![ ](/screenshots/running-microservices-jaeger-tracing.png?raw=true "All Services are up and running")

2. Jaeger UI showing different requests
![ ](/screenshots/jaeger-UI.png?raw=true "Jaeger UI")

3. Jaeger UI tracing parallel requests
![ ](/screenshots/bookinventory-parallel-requests-jaeger-tracing.png?raw=true "Jaeger UI tracing parallel requests")


#### Zipkin
1.  All services are running and made a curl request to get book recommendations
![ ](/screenshots/running-microservices-zipkin-tracing.png?raw=true "All Services are up and running")

2. Zipkin UI tracing parallel requests
![ ](/screenshots/book-inventory-parallel-requests-zipkin-UI.png?raw=true "Zipkin UI tracing parallel requests")

3. Zipkin UI showing details of a span
![ ](/screenshots/detail-span-zipkin-tracing.png?raw=true "Zipkin UI showing detail span")

4. Zipkin UI showing book inventory span for one isbn
![ ](/screenshots/books-stock-isbn-span-zipkin-tracing.png?raw=true "Zipkin UI showing isbn span")



