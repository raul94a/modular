# Modular

Backend modular hecho en Go.

Primeros pasos
- Configuración del repositorio para docker:
  * dockerfile
  * docker-compose (Go, Keycloak, Database)
    https://blog.logrocket.com/dockerizing-go-application/
- Instalar diferentes versiones de Go con gestor de versione goenv
  * goenv tutorial de instalación https://medium.com/@tinchoram/c%C3%B3mo-administrar-diferentes-versiones-de-golang-con-goenv-ca4f2cbb84c5
  * Repositorio oficial de goenv https://github.com/go-nv/goenv
- Creación de CRUD básico
  * Mock en memoria
  * Integración con base de datos (SQLite, PostgreSQL, etc) -> Drivers
    https://blog.logrocket.com/building-simple-app-go-postgresql/
  * Tests. Podemos hacerlo usando scripts de windows / bash.
  * Curl y jq => https://jqlang.github.io/jq/download/
  * ORM para crud => https://gorm.io/docs/

- Comenzar con la integración de keycloak
   https://www.keycloak.org/server/containers

  client libary for keycloak: https://github.com/Nerzal/gocloak
  https://mikebolshakov.medium.com/keycloak-with-go-web-services-why-not-f806c0bc820a


