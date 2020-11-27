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


 ![](https://imgkr2.cn-bj.ufileos.com/42f07fb9-6c64-49e9-8de6-225daf09bcd3.png?UCloudPublicKey=TOKEN_8d8b72be-579a-4e83-bfd0-5f6ce1546f13&Signature=Hr63v6NL45LnYFDXKRdaMMDH8Xo%253D&Expires=1606554844)
