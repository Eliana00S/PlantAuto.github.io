# PlantAuto

This project is a plant monitor website that is connected to an Arduino and is dysplaying real time data from the Arduino

**Arduino Uno WiFi Rev2** with:
  - DHT11 Temperature & Humidity Sensor
  - Soil Moisture Sensor
  - Water Pump + LEDs
- Firebase Realtime Database (backend)
- HTML, CSS, JavaScript (frontend)
- GitHub Pages (hosting)

# How It Works

1. The Arduino reads sensor data (temperature, humidity, and soil moisture).
2. The Water pump turns on and off depending on the humidity, temperature, soil moisture, and user input.
3. It uploads that data every few seconds to Firebase Realtime Database.
4. The website connects to Firebase and updates the UI instantly.
