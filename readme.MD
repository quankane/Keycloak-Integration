# KeyCloak integration

## Prerequisites

### Install KeyCloak on Docker

`docker pull quay.io/keycloak/keycloak:25.0.0`

Run keyCloak on port 8180

`docker run -d --name keycloak-25.0.0 -p 8180:8080 -e KEYCLOAK_ADMIN=quanducbui2017@gmail.com -e KEYCLOAK_ADMIN_PASSWORD=Quankane1905@ quay.io/keycloak/keycloak:25.0.0 start-dev`
