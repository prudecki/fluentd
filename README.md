# fluentd-cisco-wsa
 fluentd configuration guide for Cisco Web Security Appliance (WSA) 
 
Hello Github community,

I would like to share with you a configuration of fluentd for Cisco Web Security Appliance syslog parsing. 
It includes adding geopoint information and other enhancements.

This config consists of two regexp parsing schemes. First one is to be used with WSA that is not authorizing users, the other one with domain authorization.

Plugins used: geoip, record_transformer

Use it, fork it, do whatever you like.
