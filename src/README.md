# Nest.Js
NestJS is a framework for building efficient, scalable Node.js server-side applications.
It uses progressive Javascript.

Nest provides developers and teams to create highly testable, scalable, loosely coupled, and easily maintainable applications.

Technically, Nest is able to work with any Node HTTP framework once an adapter is created.


## Express and Fastify
There are two HTTP platforms supported: express and fastify

Platform-Express: Express is a well-known minimalist web framework for node. It's a battle tested, production-ready library with lots of resources implemented by the community. (Default)

Platform-Fastify: Fastify is a high performance and low overhead framework highly focused on providing maximum efficiency and speed

### Installation

```
  npm i -g @nestjs/cli
  nest new project-name
```
 
src/ directory will be created and populated with several core files.

```
📦src
 ┣ 📜app.controller.spec.ts | The unit tests for the controller.
 ┣ 📜app.controller.ts      | A basic controller with a single route.
 ┣ 📜app.module.ts          | The root module of the application.
 ┣ 📜app.service.ts         | A basic service with a single method.
 ┗ 📜main.ts                | The entry file of the application which uses the core function NestFactory to create a Nest application instance.
```