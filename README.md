# Awesome Crop Steering

Curated by [IXYZ](https://intergalactic-xyz.com/) list of OpenSource projects in indoor/outdoor agriculture automation, crop steering and cannabis cultivation

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Build Status](https://github.com/Intergalactic-XYZ/awesome-cropsteering/actions/workflows/awesome-bot.yml/badge.svg)](https://github.com/Intergalactic-XYZ/awesome-cropsteering/actions/workflows/awesome-bot.yml)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/Intergalactic-XYZ/awesome-cropsteering/)

## **Contents**

- [Awesome Crop Steering](#awesome-crop-steering)
  - [Contents](#contents)
  - [AI/ML](#aiml)
  - [Grow Automation](#grow-automation)
  - [Calculators](#calculators)
  - [General automation](#general-automation)
    - [Node RED](#node-red)
      - [Node RED flows](#node-red-flows)
    - [Home Assistant](#home-assistant)
      - [Home Assistant Automation](#home-assistant-automation)
      - [Home Assistant UI](#home-assistant-ui)
  - [Facility management](#facility-management)
  - [Irrigation](#irrigation)
  - [Frameworks](#frameworks)
    - [ESPHome](#esphome)
      - [ESPHome Configs](#esphome-configs)
    - [Tasmota](#tasmota)
      - [Tasmota Configs](#tasmota-configs)
  - [Hardware](#hardware)
    - [Components](#components)
    - [DIY](#diy)
  - [Metrics and Logging](#metrics-and-logging)
  - [Mixers and Dosers](#mixers-and-dosers)
  - [MQTT](#mqtt)
  - [Relay and power control](#relay-and-power-control)
  - [Storing Data](#storing-data)
  - [Visualization](#visualization)
    - [Visualization Libraries](#visualization-libraries)
    - [Visualization platforms](#visualization-platforms)
  - [Zigbee](#zigbee)
  - [Reading](#reading)
    - [Crop Steering Guides](#crop-steering-guides)
  - [Other Awesome Lists](#other-awesome-lists)

## **AI/ML**

- [OpenWeedLocator](https://github.com/geezacoleman/OpenWeedLocator) - Opensource hardware and software weed detector that uses entirely off-the-shelf componentry, very simple green-detection algorithms (with capacity to upgrade to in-crop detection) and 3D printable parts
- [Plant disease](https://github.com/morenoh149/plantdisease) - Predictive model for cannabis sickness. One source identifies 30 types of cannabis ailments.
- [PlantCV](https://github.com/danforthcenter/plantcv) - Open-source plant phenotyping and image analysis library from the Danforth Plant Science Center
- [PlantVillage Dataset](https://github.com/spMohanty/PlantVillage-Dataset) - Open dataset of 54k+ images of healthy and diseased plant leaves across 14 crop species and 26 diseases
- [PlantDoc Dataset](https://github.com/pratikkayal/PlantDoc-Dataset) - Dataset for visual plant disease detection in real (non-lab) conditions
- [AgML](https://github.com/Project-AgML/AgML) - Centralized framework for agricultural machine learning: public datasets, benchmarks, pretrained models and synthetic data generation

**[⬆ back to top](#contents)**

## **Grow Automation**

- [DROMatic OS](https://github.com/drolsen/DRO-Matic) - The DRO-Matic OS has been built to automate nearly every aspect of hydroponic farming for you! From nutrient dosing to pH / EC drift fixing, feeding types to draining, top-offs and even timers; we have quantified everything you need to automate successful crops.

- [MudPi](https://github.com/mudpi/mudpi-core) - A python package to gather sensor readings, trigger components, control devices and more in an event based system that can be run on a linux SBC, including Raspberry Pi

- [Mycodo](https://github.com/kizniche/Mycodo) - Mycodo is open source software for the Raspberry Pi that couples inputs and outputs in interesting ways to sense and manipulate the environment

- [gardenAutomation](https://github.com/ledgardener/gardenAutomation) - Garden Automation toolkit by [LedGardener](https://ledgardener.com/category/builds/)

- [WEGA-Box](https://github.com/WEGA-project/wegabox) - Hydroponic system management toolkit

- [Potnanny](https://github.com/potnanny/application) - Potnanny turns your Raspberry Pi into powerful grow-room automation system using inexpensive, off-the-shelf Bluetooth sensors, power outlets, and other devices

- [FarmBot OS](https://github.com/FarmBot/farmbot_os) - Operating system for FarmBot, the open-source CNC farming robot, running on Raspberry Pi

- [reef-pi](https://github.com/reef-pi/reef-pi) - Raspberry Pi based controller with pH monitoring, dosing pumps, ATO and timers. Aquarium-focused but directly reusable for hydroponic reservoir control

- [TerrariumPI](https://github.com/theyosh/TerrariumPI) - Raspberry Pi automation for enclosed environments: climate, lighting, watering and webcams

- [SuperGreenOS](https://github.com/supergreenlab/SuperGreenOS) - ESP32 all-in-one grow controller firmware with mobile app control

- [Hydruino](https://github.com/NachtRaveVL/Simple-Hydroponics-Arduino) - Fully configurable hydroponics automation controller for Arduino-compatible MCUs, offline with no cloud dependency

- [Isley](https://github.com/dwot/isley) - Self-hosted cannabis grow journal with sensor tracking for AC Infinity controllers and Ecowitt soil sensors

**[⬆ back to top](#contents)**

## **Calculators**

- [WEGA-HPG](https://github.com/WEGA-project/wega-hpg) - HPG Calculator
- [HydroBuddy](https://github.com/danielfppps/hydrobuddy) - Open-source hydroponic nutrient solution calculator
- [Athena Batch Tank Nutrient Calculator](https://github.com/JakeTheRabbit/Athena-Batch-Tank-Nutrient-Calculator) - Self-hosted offline dosing calculator for the Athena nutrient and foliar range
- [Trym VPD Calculator](https://trym.io/vpd-calculator/) - Free VPD calculator with leaf-temperature offset and stage-specific target charts
- [Pulse VPD Guide and Calculator](https://pulsegrow.com/blogs/learn/vpd) - Detailed VPD explainer with interactive calculator and charts

**[⬆ back to top](#contents)**

## **General automation**

### Node RED

- [Node-RED](https://github.com/node-red/node-red) - Low-code programming for event-driven applications

#### Node RED flows

- [Home Automation Repository](https://github.com/njhughes-01/nodeRed-HA-GrowingFunctions) - repository contains configuration files for a home automation system, including various sensors, inputs, and automation scripts

**[⬆ back to top](#contents)**

### Home Assistant

- [Home Assistant](https://github.com/home-assistant/core) - Open source home automation that puts local control and privacy first. Powered by a worldwide community of tinkerers and DIY enthusiasts

#### Home Assistant Automation

- [HAGR](https://github.com/JakeTheRabbit/HAGR) - Home Assistant Grow Room is a repository for grow automation related things for Home Assistant
- [HA-Irrigation-Strategy](https://github.com/JakeTheRabbit/HA-Irrigation-Strategy) - Crop steering irrigation strategy (P0-P3 phases) for Home Assistant with GUI blueprint configuration
- [Home Assistant Plant](https://github.com/Olen/homeassistant-plant) - Alternative Plant component with thresholds, species data and daily light integral
- [OpenPlantbook integration](https://github.com/Olen/home-assistant-openplantbook) - Fetches per-species care thresholds from OpenPlantbook.io
- [Smart Irrigation](https://github.com/altmenorg/HAsmartirrigation) - Calculates irrigation duration and volume from evapotranspiration data
- [Irrigation Unlimited](https://github.com/rgc99/irrigation_unlimited) - Feature-rich irrigation controller: unlimited zones, sequences, seasonal adjustment
- [AC Infinity integration](https://github.com/dalinicus/homeassistant-acinfinity) - Home Assistant integration for AC Infinity UIS grow-tent controllers
- [OpenGrowBox-HA](https://github.com/OpenGrow-Box/OpenGrowBox-HA) - Autonomous grow-room control: VPD, climate, lighting, CO2 and irrigation over Zigbee/ESPHome/Tasmota/MQTT

#### Home Assistant UI

- [Lovelace Flower Card](https://github.com/Olen/lovelace-flower-card) - Flower card matching the custom plant integration
- [VPD Chart Card](https://github.com/vpdchart/vpdchart-card) - Lovelace VPD chart card for grow rooms

**[⬆ back to top](#contents)**

## **Facility management**

- [OpenTHC](https://github.com/openthc/docker) - OpenTHC is an environment of web-based applications focused on helping Cannabis/Hemp and Organic Horticulture industry participants meet their regulatory requirements

- [farmOS](https://github.com/farmOS/farmOS) - Web-based farm record keeping and management application

- [Cannlytics](https://github.com/cannlytics/cannlytics) - Open-source cannabis data pipelines and lab analytics tooling

**[⬆ back to top](#contents)**

## **Irrigation**

- [OpenSprinkler AVR/RPI/BBB Firmware](https://github.com/OpenSprinkler/OpenSprinkler-Firmware) - This is a unified OpenSprinkler firmware for Arduino, and Linux-based OpenSprinklers such as OpenSprinkler Pi

- [OpenMinder](https://github.com/autogrow/openminder) -  Allows anyone to build a device that can monitor the rootzone of their plants to make the most optimum use of water and fertigation ingredients to ensure a happy plant. This is done by measuring the water going into the plants on the irrigation side, as well as coming out on the runoff side, thus allowing comparisons

**[⬆ back to top](#contents)**

## **Frameworks**

### ESPHome

- [ESPHome](https://github.com/esphome/esphome) - ESPHome is a system to control your microcontrollers by simple yet powerful configuration files and control them remotely through Home Automation systems
- [PLF10](https://github.com/KaufHA/PLF10/tree/main) - KAUF Power Monitoring Smart Plug (PLF10)

#### ESPHome Configs

- [Aquaponics-Kit](https://github.com/TheRealFalseReality/Aquaponics_Pool_Kit-AtlasScientific) - Code for Atlas Scientific Wi-Fi Aquaponics Kit to be compatible with ESPHome and HomeAssistant using Adafruit HUZZAH32 – ESP32 Feather Board
- [sdi12-esphome](https://github.com/fraxinas/sdi12-esphome) - SDI-12 sensor interface component for ESPHome
- [Growlink Terralink for ESPHome](https://github.com/JakeTheRabbit/Grownlink-Terralink-Substrate-Sensor-for-ESP-Home) - ESP32/ESPHome reading a Growlink Terralink TDR substrate sensor over SDI-12, exposing VWC/pwEC/temp to Home Assistant for coco and rockwool

**[⬆ back to top](#contents)**

### Tasmota

- [Tasmota](https://github.com/arendst/Tasmota) - Alternative firmware for ESP8266 and ESP32 based devices with easy configuration using webUI, OTA updates, automation using timers or rules, expandability and entirely local control over MQTT, HTTP, Serial or KNX

#### Tasmota Configs

- [Tasmota-Hydroponics-Controller](https://github.com/LucidEye/Tasmota-Hydroponics-Controller) - Tasmota Berry scripts for grow-tent and hydro VPD control: lights, pump, humidifier, PWM fans

**[⬆ back to top](#contents)**

## **Hardware**

### Components

- [Seeed Studio](https://www.seeedstudio.com/) - various modules and components based on ESP32 and other MCU

- [LILYGO](https://www.lilygo.cc/) - various modules and components. Good relay boards based on ESP32

- [Adafruit](https://www.adafruit.com/category/946) - Adafruit ESP32 modules

- [M5 Stack](https://m5stack.com/) - Standard 5×5cm functionally stacking modularized components hardware system

#### Sensors

- [Atlas Scientific](https://atlas-scientific.com/probes/) - T/H, Pressure, pH, EC, ORP probes and interface boards. Dosing pumps, flowmeters. Lab grade.

#### MCU and SOC

- [ESP32](https://www.espressif.com/en/products/socs/esp32) - A feature-rich MCU with integrated Wi-Fi and Bluetooth connectivity for a wide-range of applications

- [Particle](https://www.particle.io/) - hardware modules for IoT

#### Modular systems

- [WisBlock by RAK Wireless](https://www.rakwireless.com/en-us/products/wisblock) - Create your own hardware with WisBlock Core, WisBlock Base and other WisBlock Modules

**[⬆ back to top](#contents)**

### DIY

- [OpenSprinkler Hardware](https://github.com/OpenSprinkler/OpenSprinkler-Hardware) - OpenSprinkler Hardware Design files, made in EagleCAD software

- [SENTSOR Core ESP32-EMBED](https://github.com/adamalfath/sentsor-core-esp32embed) - all-in-one, super low power development board based on latest revision of ESP32 chip. BOM, easyEDA PCB blueprints
  
- [Hydromisc](https://github.com/hydromisc/hydromisc) - A single PCBA with all the necessary I/O to automate a typical small to mid-size hydroponic grow, controllable over Wifi. It may also be suitable for aquariums, ponds, or any other biological or chemical process involving water treatment

- [b-parasite](https://github.com/rbaron/b-parasite) - Open-hardware wireless (BLE/Zigbee) soil moisture, temperature/humidity and light sensor with PCB and firmware

- [Chirp i2c-moisture-sensor](https://github.com/Miceuz/i2c-moisture-sensor) - The canonical open-hardware I2C capacitive soil moisture sensor

- [Makerfabs LoRa Soil Moisture Sensor](https://github.com/Makerfabs/Lora-Soil-Moisture-Sensor) - Open hardware and firmware LoRa capacitive soil moisture node, LoRaWAN variant available

**[⬆ back to top](#contents)**

## **Metrics and Logging**

- [OS-RS485](https://github.com/cropsteering/OS-RS485) - OpenSteering-RS485 Data logger

- [OpenSteering-SDI12](https://github.com/cropsteering/OS-SDI12) - SDI-12 Data logger, up to 62 addresses
- [TDR-Sensor](https://github.com/Emperiusm/TDR-Sensor) - A TDR sensor that measures moisture content, EC, and temperature for Rockwool Substrates or Soil Substrates
- [Arduino-SDI-12](https://github.com/EnviroDIY/Arduino-SDI-12) - The de-facto Arduino library for SDI-12 communication with environmental sensors, no extra hardware needed
- [ModularSensors](https://github.com/EnviroDIY/ModularSensors) - Arduino library giving environmental sensors (including SDI-12 and Modbus soil probes) a common datalogger interface
- [ESP32-SDI12](https://github.com/HarveyBates/ESP32-SDI12) - SDI-12 library for ESP32 microcontrollers
- [Industrial-Soil-Sensor-RS485](https://github.com/myduino/Industrial-Soil-Sensor-RS485) - ESP32 sketches for industrial RS485 Modbus soil moisture/temp/EC/pH/NPK probes
- [Telegraf](https://github.com/influxdata/telegraf) - Plugin-driven agent for collecting and shipping metrics (MQTT, Modbus, sensors) to InfluxDB and others

**[⬆ back to top](#contents)**

## **Mixers and Dosers**

- [WEGA-Mixer](https://github.com/WEGA-project/wega-mixer) - WEGA-Mixer is a device for the automatic preparation of two-component complex fertilizers in liquids by precisely mixing their composition (RU, requires google translate).

**[⬆ back to top](#contents)**

## **MQTT**

- [Mosquitto](https://github.com/eclipse-mosquitto/mosquitto) - Mosquitto is an open source implementation of a server for version 5.0, 3.1.1, and 3.1 of the MQTT protocol
- [EMQX](https://github.com/emqx/emqx) - EMQX is the world's most scalable open-source MQTT broker with a high performance that connects 100M+ IoT devices in 1 cluster, while maintaining 1M message per second throughput and sub-millisecond latency.
- [OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) - ESP32 MQTT gateway bridging BLE (Mi Flora, b-parasite), 433MHz, IR and LoRa sensors to your broker
- [Theengs Gateway](https://github.com/theengs/gateway) - Multi-platform BLE-to-MQTT gateway decoding hundreds of sensors, with Home Assistant auto-discovery
- [miflora-mqtt-daemon](https://github.com/ThomDietrich/miflora-mqtt-daemon) - Linux daemon pushing Xiaomi Mi Flora plant sensor data to MQTT

**[⬆ back to top](#contents)**

## **Relay and power control**

- [EC-POWERCONTROL](https://github.com/cropsteering/EC-POWERCONTROL) - Edge controller power control for esp32

**[⬆ back to top](#contents)**

## **Storing Data**

- [InfluxDB](https://github.com/influxdata/influxdb) - InfluxDB is an open source time series database
- [Open TSDB](https://github.com/OpenTSDB/opentsdb) - OpenTSDB is a distributed, scalable Time Series Database (TSDB) written on
top of HBase
- [TimescaleDB](https://github.com/timescale/timescaledb) - Time-series database packaged as a Postgres extension, well suited to sensor telemetry
- [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - Fast, cost-effective time-series database and monitoring solution
- [QuestDB](https://github.com/questdb/questdb) - High-performance open-source time-series database with SQL and InfluxDB line protocol support
- [Apache IoTDB](https://github.com/apache/iotdb) - Time-series database designed for IoT: edge-to-cloud sync and high-frequency sensor ingestion

**[⬆ back to top](#contents)**

## **Visualization**

### Visualization Libraries

- [Giraffe](https://github.com/influxdata/giraffe) - A React-based visualization library powering the data visualizations in the InfluxDB 2.0 UI

- [D3.js](https://github.com/d3/d3) - D3 (or D3.js) is a free, open-source JavaScript library for visualizing data. Its low-level approach built on web standards offers unparalleled flexibility in authoring dynamic, data-driven graphics

**[⬆ back to top](#contents)**

### Visualization platforms

- [Grafana](https://github.com/grafana/grafana) - The open-source platform for monitoring and observability

- [InfluxDB](https://github.com/influxdata/influxdb) - InfluxDB is an open source time series database

- [ThingsBoard](https://github.com/thingsboard/thingsboard) - Open-source IoT platform: device management, MQTT data collection, rule engine and dashboards

**[⬆ back to top](#contents)**

## **Zigbee**

- [Zigbee2MQTT](https://github.com/Koenkk/zigbee2mqtt) - It bridges events and allows you to control your Zigbee devices via MQTT. In this way you can integrate your Zigbee devices with whatever smart home infrastructure you are using.

**[⬆ back to top](#contents)**

## Reading

### Crop Steering Guides

- [AGROWTEK Crop Steering Guide](https://static.intergalactic-xyz.com/cropsteering/files/AN_CropSteering.pdf)

- [Growlink Crop Steering E-Book V1.4](https://static.intergalactic-xyz.com/cropsteering/files/Growlink%20Crop%20Steering%20E-Book%20V1.4.pdf)

- [Some useful reading and links from Open Steering project](https://cropsteering.xyz/)

- [AROYA Crop Steering Guide](https://aroya.io/en/resources/crop-steering) - In-depth free guide on substrate sensors, dryback strategy and P1/P2/P3 irrigation phases from METER Group's AROYA team

- [Cornell CEA](https://cea.cals.cornell.edu/) - Cornell University's Controlled Environment Agriculture program: free research publications on greenhouse engineering, hydroponics and lighting

**[⬆ back to top](#contents)**

## **Other Awesome Lists**

- [Awesome Agriculture](https://github.com/brycejohnston/awesome-agriculture)
- [Awesome ESP](https://github.com/agucova/awesome-esp)
- [Awesome Home Assistant](https://github.com/frenck/awesome-home-assistant)
- [Awesome InfluxDB](https://github.com/mark-rushakoff/awesome-influxdb)
- [Awesome IoT](https://github.com/HQarroum/awesome-iot)
- [Awesome IoT & Hybrid](https://github.com/weblancaster/awesome-IoT-hybrid)
- [Awesome Open IoT](https://github.com/Agile-IoT/awesome-open-iot)
- [Awesome Precision Agriculture](https://github.com/px39n/Awesome-Precision-Agriculture)
- [Awesome MQTT](https://github.com/awesome-mqtt/awesome-mqtt)
- [Awesome Open Hardware](https://github.com/delftopenhardware/awesome-open-hardware)
- [Awesome Raspberry Pi](https://github.com/thibmaek/awesome-raspberry-pi)

**[⬆ back to top](#contents)**
