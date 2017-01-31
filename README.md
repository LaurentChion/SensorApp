# SensorsApp
An app that generate, save and visualize sensors (IoT)

# What does that App ?
* Generate random sensors and send it to a MQTT broker (random-sensor dependency)
* Listen the broker and save data to a mongoDb database (sensors-to-db dependency)
* Visualize Sensors in live or using the database with a React App (ReactMqtt dependency)
