[![Build Status](https://travis-ci.org/stackroute/<repo_name>.svg?branch=master)](https://travis-ci.org/stackroute/<repo_name>)
[![codecov](https://codecov.io/gh/stackroute/<repo_name>/branch/<branch_name>/graph/badge.svg)](https://codecov.io/gh/stackroute/<repo_name>)
![](https://img.shields.io/codecov/c/github/stackroute/<repo_name>.svg?style=flat)

![](https://img.shields.io/snyk/vulnerabilities/github/stackroute/<repo_name>.svg?style=popout)
![](https://img.shields.io/github/issues/stackroute/<repo_name>.svg?style=popout)

![](https://img.shields.io/github/contributors/stackroute/<repo_name>.svg?style=popout)
![](https://img.shields.io/github/last-commit/stackroute/<repo_name>.svg?style=popout)

![](https://img.shields.io/github/repo-size/stackroute/<repo_name>.svg?style=popout)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)


all services running on docker using docker compose

logger present in Playerservice
---- used in --> /playerService/src/main/java/com/stackroute/playerservice/controller

zuul routing routes on :
---- :7788 for player service
---- :7789 for user service

Zuul gateway running on " https " !! run on a browser, doesn't run on postman !

Eureka configured for userservice and Player service ONLY

Config server properties present on github : https://github.com/Farhaan900/config-server-repo



Ports used for all the services :-

>> userService   :7788
>> playerService :7789
>> configServer  :8891
>> zuulGateway   :8000
>> eureka Server :9090
>> mongo server  :27017