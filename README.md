# Discovery Service

The discovery service is responsible for maintaining a registry of service information in the cluster environment. Each service will register with this application when they start up in the cluster, and provide network information of where that service can be contacted.

The OpenShift `diy` cartridge documentation can be found at:

http://openshift.github.io/documentation/oo_cartridge_guide.html#diy

# Eureka Server Sample

Run this project as a Spring Boot app (e.g. import into IDE and run
main method, or use "mvn spring-boot:run"). It will start up on port
8761 and serve the Eureka API from "/eureka".

## Resources

| Path             | Description  |
|------------------|--------------|
| /                        | Home page (HTML UI) listing service registrations          |
| /eureka/apps         | Raw registration metadata |

