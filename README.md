<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Run the project for development

1. Clone this repository
2. Install the dependencies, if you're using npm, execute:
```
npm install
```
3. Nest CLI must be installed, run the following script if you don't have it:
```
npm i -g @nestjs/cli
```
4. Run the dockerized database by running the docker-compose command:
```
docker-compose up -d
```
5. Clone the ```.env.template``` and rename it to ```.env```
6. Fill the environment variables with the required data
7. Run the application in development mode:
```
npm run start:dev
```
8. Populate database making an http request to the following seed route
```
http://localhost:3001/api/v2/seed
```
