# SensorsApp
An app that generate, save and visualize sensors (IoT)

# What does that App ?
* Generate random sensors and send it to a MQTT broker (random-sensor dependency)
* Listen the broker and save data to a mongoDb database (sensors-to-db dependency)
* Create a web service API to retrieve data from database (SensorsWebService dependency)
* Visualize Sensors in live or using the webservice with a React App (ReactMqtt dependency)
