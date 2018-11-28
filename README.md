# aws-auth-proxy

Based on repository [abutaha/aws-es-proxy](https://github.com/abutaha/aws-es-proxy)

## Differences:
1. Added support aws cn endpoint: 

  e.g. https://yourname.region.es.amazonaws.com.cn

2. Added support base path: 

  e.g. pass endpoint https://yourname.region.es.amazonaws.com.cn/_plugin/kibana , when you access proxy as root url (http://host:9200), the proxy will redirect the request as "http://host:9200/_plugkin/kibana"
