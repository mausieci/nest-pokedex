<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

 # Ejecutar en desarrollo

 1. Clonar el repositorio
 2. Ejecutar 
 ```
 yarn install
 ```
 3. Tener Nest CLI instalado, de lo contrario instalarlo 
 ```
 npm i -g @nestj/cli
 ```
 4. Levantar la BD
 ```
 docker-compose up -d
 ```
 5. Reconstruir la BD con el modulo de semilla
 ```
 http://localhost:3000/api/v1/seed
 ```

 ## Stack usado
 * MongoDB
 * Nest