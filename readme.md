# service Discovery

The project is composed of a eureka server and 2 microservice (eureka clients) one of them will use the server to communicate with the other

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

java 8+


### Installing

git clone the project

import the project in your favourite IDE

run the eurekaserver first

run the movie-service

run the recommendation-service
## Testing

go to : http://localhost:8050/recommendations

## Explanation
Both services are registred in the discovery server, you can check that out by visiting : http://localhost:8761/ .

The recommendation-service is calling movie-service not directly but using the discovery server (eureka server)