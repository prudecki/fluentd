# fluentd-cisco-wsa


Hello Github community,

I would like to share with you a configuration of fluentd for Cisco Web Security Appliance syslog parsing. 
It includes adding geopoint information and other enhancements.

This config consists of two regexp parsing schemes. First one is to be used with WSA that is not authorizing users, the other one allows additional parsing of domain users. Choose the right one for you.


Plugins used: geoip, record_transformer

For addition I attach template for index mapping in Elasticsearch (es-template-wsa.txt).
You can also find in my repositories dashboards for Grafana.


Use it, fork it, do whatever you like.

![alt text](https://github.com/prudecki/fluentd-cisco-wsa/blob/master/kibana-wsa.png)
