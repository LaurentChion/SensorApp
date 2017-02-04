# SensorsApp
An app that generate, save and visualize sensors (IoT)

# What does that App ?
* Generate random sensors and send it to a MQTT broker (random-sensor dependency)
* Listen the broker and save data to a mongoDb database (sensors-to-db dependency)
* Create a web service API to retrieve data from database (SensorsWebService dependency)
* Visualize Sensors in live or using the webservice with a React App (ReactMqtt dependency)

# Ports
* MQTT Broker run on port 8080
* React App run on port 3000
* Mongodb run on port 27010
* WebService run on port 8090

# How to run it ?
Clone this repository :
```
git clone https://github.com/LaurentChion/SensorsApp.git
```

In a terminal go into this folder and run :
```
./run.sh
```

# How to close it  ?
In a terminal go into this folder and run :
```
docker-compose down
```

# Troubleshooting
Sometime it happens that webservice or sensors-to-db can't connect to database.
Stop docker and relaunch it :
```
docker-compose down
docker-compose up
```
