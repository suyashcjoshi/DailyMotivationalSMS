# Daily Motivational SMS App

A java based Serverless application that runs on Microsoft Azure. It sends SMS every day that consists of a motivational quote using RingCentral SMS API. 

## Pre-Requisite

- [RingCentral Developer Account](https://developers.ringcentral.com/login.html#/)
- [Microsoft Azure Account](https://azure.microsoft.com/en-us/free/)
- [Azure Function Core Tools](https://docs.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=v4%2Cmacos%2Ccsharp%2Cportal%2Cbash#v2)
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- JDK 8 or 11
- Maven
- IDE (Visual Studio Code recommended)

### Setup:

```
$ git clone <this repo>
$ mvn install
```

### Running locally

### Running on Azure

```
$ az login
$ mvn clean package && mvn azure-functions:deploy
```

### References

1. [Azure Function Java Tutorial](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference-java?tabs=bash%2Cconsumption)
2. [RingCentral SMS API Quick Start](https://developers.ringcentral.com/guide/messaging/quick-start)

