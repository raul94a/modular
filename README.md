# Modular

Backend modular hecho en Go.

Primeros pasos
- Configuración del repositorio para docker:
  * dockerfile
  * docker-compose (Go, Keycloak, Database)
    https://blog.logrocket.com/dockerizing-go-application/
    
- Creación de CRUD básico
  * Mock en memoria
  * Integración con base de datos (SQLite, PostgreSQL, etc) -> Drivers
    https://blog.logrocket.com/building-simple-app-go-postgresql/
  * Tests. Podemos hacerlo usando scripts de windows / bash.
  * Curl y jq => https://jqlang.github.io/jq/download/

- Comenzar con la integración de keycloak
   https://www.keycloak.org/server/containers

  client libary for keycloak: https://github.com/Nerzal/gocloak
  https://mikebolshakov.medium.com/keycloak-with-go-web-services-why-not-f806c0bc820a


