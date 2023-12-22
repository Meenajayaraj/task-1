"# task-1" 

# Difference between `HTTP1.1` vs `HTTP2`

## HTTP 

**Hypertext transfer protocal** is used to communicate between webbrowser and server.

| > !HTTP1.1 | > !HTTP2 |
|------ | ------ |
| It works on the textual format. | It works on the binary protocol.|
|There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources. | It allows multiplexing so one TCP connection is required for multiple requests. |
| It uses requests resource Inlining for use getting multiple pages |	It uses PUSH frame by server that collects all multiple pages 
| It compresses data by itself.	| It uses HPACK for data compression.