# Demo-backend

This is mock backend service which will return a json response like below  
{  
  "greeting" : "hello from cluster Backend",  
  "time" : 1523736543767,  
  "ip" : "10.0.75.1"  
}  
Download the project and run the service from CMD : mvn clean install jetty:run  
You can check the reponse from URL : http://localhost:8080/api/backend?greeting=hello
