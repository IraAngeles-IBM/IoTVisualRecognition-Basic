
# IoT Fire Alarm using Node-RED and IBM Visual Recognition with Mosquitto MQTT Broker

This project is a how-to guide on using Node-RED and IBM Visual Recognition service to analyse an image and based on a trigger word then send a event command to IoT Device. In this example node-red is used to create an image upload form which sends the image to IBM Visual Recognition and trigger an iot device whenever fire is detected in the image.

1. Login/signup in to your [IBM Cloud Account](https://ibm.biz/BdYtcs)
2. Goto Catalog and create the following services:
    * Install [Node-RED](https://developer.ibm.com/tutorials/how-to-create-a-node-red-starter-application/)
     Note : Please follow the tutorial to install Node-RED in IBM Cloud

    * Create IBM AI [Visual Recognition](docs/create-visual-recognition-svc.md) service

3. [Login to your node-red flows dashboard and import flow](docs/import-flow.md)
4. [Update api key in the visual recognition node-red flow](docs/update-flow)
5. Update the device details in IBM Iot device node {Optional}
6. [Visit node-red-url/upload and upload required image](docs/upload-image.md)
7. Change the string inside includes from trigger action function to set a different trigger
