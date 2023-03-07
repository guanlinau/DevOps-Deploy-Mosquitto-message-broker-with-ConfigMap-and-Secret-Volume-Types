### Deploy Mosquitto message broker with ConfigMap and Secret Volume Types

### Technologies Used:

Kubernetes, Docker, Mosquitto

### Project Description:

1-Define configuration and passwords for Mosquitto message broker with ConfigMap and Secret Volume types.

### Instructions:

###### Step 1: Configure a mosquitto deployment without persistent volumes.

1- Enter into the mosquitto container inside mosquitto pod and get the location of config folder.

###### Step 2: Create a mosquitto configMap yaml file and create the configmap deployment

###### Step 3: Create a mosquitto secret yaml file and create the secret deployment

###### Step 4: Bind mount mosquitto configMap yaml file and mosquitto secret yaml file to mosquitto
