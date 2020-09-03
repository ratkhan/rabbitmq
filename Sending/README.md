Sender sends data to a message server at localhost

Compiling
javac -cp amqp-client-5.7.1.jar Send.java

Running (for linux machine have to change semicolons to colons)
java -cp .;amqp-client-5.7.1.jar;slf4j-api-1.7.26.jar;slf4j-simple-1.7.26.jar Send

