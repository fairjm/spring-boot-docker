# spring-boot-docker  
It's a simple REST server.  
change `dockerHost` and `certPath` in `pom.xml` and use `mvn clean package -Dmaven.test.skip=true docker:build` to build.  
use `docker-machine env` to get the above value if you use `docker toolbox`.  

---  
plugin repo:  
https://github.com/fabric8io/docker-maven-plugin
