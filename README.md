# smart-parking-iot
Simulation de stationnement intelligent utilisant ESP32, MicroPython, MQTT et Node-RED.
# Smart Parking 4.0 🚗 Sensor & IoT Simulation

Système complet de gestion et de suivi en temps réel de places de stationnement intelligentes.

## 🚀 Architecture & Fonctionnalités
- **Acquisition de données :** Détection de présence et état des places via microcontrôleurs ESP32.
- **Communication :** Transmission asynchrone légères des événements via protocole MQTT.
- **Supervision :** Tableau de bord interactif sous Node-RED pour le contrôle et la visualisation des flux.

## 🛠️ Stack Technique
- **Hardware / Firmware :** ESP32, MicroPython
- **Protocole & IoT :** MQTT (Mosquitto)
- **Dashboard :** Node-RED

## 📌 Contenu du Dépôt
- `src/` : Scripts MicroPython pour ESP32 (gestion capteurs et client MQTT)
- `node-red/` : Flux et tableaux de bord Node-RED (fichier JSON)
