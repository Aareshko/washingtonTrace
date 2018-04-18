# WashingtonTractorTRWebapp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.
## Screen

### Login Page

![enter image description here](https://github.com/seniorfullstackdev/washingtonTrace/blob/master/images/Screen%20Shot%202018-04-18%20at%206.03.05%20AM.png?raw=true)!

### Main Pages
(https://github.com/seniorfullstackdev/washingtonTrace/blob/master/images/Screen%20Shot%202018-04-18%20at%206.03.21%20AM.png?raw=true)

## Development server

Run `npm run start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `npm run build-dev` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `npm run build` for a production build.

## Prod Environment build

To build WashingtonTractor-frontend `sh build-application.sh` in prod server.

## Prod Environment run

Run nginx docker container `sudo docker-compose up -d` after build this one in prod server.

## important

If you are running backend and frontend on the same server instance, please make sure that

frontend running on the port different from the backend. You may want to change port is

port: 
	-"80:80"

And then You may want to check backend url (url), OAuth secret (secret) and OAuth client.
 ### Implement Table Drag and Drop
 npm install table-dragger --save