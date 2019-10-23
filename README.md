# Azure IoT Edge humidity filter module

[![Build status](https://dev.azure.com/azure-iot-edge-devops/azure-iot-edge-devops-sample/_apis/build/status/humidity-filter-module-CI)](https://dev.azure.com/azure-iot-edge-devops/azure-iot-edge-devops-sample/_build/latest?definitionId=1)

This is a sample module that filters the machine humidity.

## IoT Edge CI/CD Deep Dive Resources
- [Temperature filter module repo](https://github.com/VSChina/azure-iot-edge-temperature-filter-module-sample). This module filters the temperature of machine that above given threshold. VS Code + YAML
- [Humidity filter module repo](https://github.com/VSChina/azure-iot-edge-humidity-filter-module-sample). This module filters the humidity of ambient that above given threshold. Visual Studio + UI
- [Deployment template repo](https://github.com/VSChina/azure-iot-edge-deployment-template-sample).

- [DevOps Project](https://dev.azure.com/azure-iot-edge-devops/azure-iot-edge-devops-sample) 
- [CI pipeline for humidity filter module](https://dev.azure.com/azure-iot-edge-devops/azure-iot-edge-devops-sample/_build?definitionId=1). Uses build id as image tag.
- [Release pipeline for humidity filter module](https://dev.azure.com/azure-iot-edge-devops/azure-iot-edge-devops-sample/_release?_a=releases&view=mine&definitionId=2) 
- [CI pipeline for temperature filter module](https://dev.azure.com/azure-iot-edge-devops/azure-iot-edge-devops-sample/_build?definitionId=2).Uses build id as image tag.
- [Release pipeline for temperature filter module](https://dev.azure.com/azure-iot-edge-devops/azure-iot-edge-devops-sample/_release?_a=releases&view=mine&definitionId=1)
- [Release pipeline for the 2 modules](https://dev.azure.com/azure-iot-edge-devops/azure-iot-edge-devops-sample/_release?_a=releases&view=mine&definitionId=3). Leverages the pipeline variables to define acr address and credentials for different environments.
