# NodeJs, helloworld API for test propouses.

This is a simple API that returns a welcome message.

## Cabe resaltar que para que el job automatico funcione se debe agregar una deploy key en github, previamente generada desde el usuario de jenkins en la consolad de ubuntu.
## A continuacion se detallan los pasos que realiza el pipeline del archivo Jenkinsfile, el cual es testeado por un job automatico en jenkins cuando se hacen push y PR:


## Run your local environment

### Clone the repository
```bash
git clone https://github.com/edgaregonzalez/nodejs-helloworld-api.git
```

### Install dependencies
```bash
npm install
```

### Run the tests
```bash
npm test
```

### Start the server
```bash
npm start
```

### Make a request
```bash
curl http://localhost:3000
```
# test job
