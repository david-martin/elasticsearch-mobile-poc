# elasticsearch-mobile-poc

See https://github.com/david-martin/elasticappproxy for how to setup the backend part of this poc app.

On App startup, a call will be made to the elastic app proxy server with some device info.

**IMPORTANT** Make sure to change the IP/host of where the elastic app proxy is running.

MainActivity.java
```java
private static final String ELASTIC_APP_PROXY_URL = "http://10.201.82.209:9090";
```
