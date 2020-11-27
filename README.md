# dockercompose-efk

： standalone version EFK  launch by docker-compose

> F： Fluent-bit  

This repo  is use to collect  docker app  structure  log， and storage the event to Elasticsearch（ have the data persistence ability）,   
 then you can  analyze the log in kibana.

##  architecture
 1.  your app must generate json structure log .
 2. package your  app in docker
 3. app  in docker set the logging  driver = fluentd
 4. Fluent-bit  use forward  protocol to listen the message
 
 
