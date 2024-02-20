# changelogs.md

## v2024.2.1
### 2024/02/20

- improve automations
- frigate: fix retain day and garage cam
- sensors: fan_duration new sensor
- templates: fix energy to power in home calculation
- add folder for remarkable energy days

## v2024.1.1
### 2023/12/20

- sunny_day toggle to automate inverter and boiler
- boiler auto now works with sunny_day
- temp3 sensor as temp_out via MQTT
- new integration for AC toshiba
- lovelace major update for AC, now works scala too.
- minor fix in dashboard
- grafana improvement
- switch box v3 compete and switch A and B for ac works
- update to     
    - Core    2024.1.3
    - Supervisor  2023.12.1
    - Operating System    11.4
    - Frontend    20240104.0

## v2023.12.0.3
### 2023/12/20

- update core and supervisor and all addons
- removed unused automation, the ones with time trigger
- fixed configuration file
- lovelace dashboard 
    - update for AC and new shelly
    - fixed shelly tables
    - home improve
    - minor fix
- sensor.yaml
    - fixed statistics for average
    - fixed history_stats for duration
- template.yaml
    - new ac sensors
    - fixed template for average
    - minor fix and improve
    - remove unused template
- remove unused helpers and removed entities
- restart addsOns integration


## v2023.12.0.1
### 2023/12/19

- remove AC and prepare for new shelly and AC command
- minor fix in dashboard
- update

## v2023.11.0.2
### 2023/11/22

- minor update in dashboard

## v2023.11.0.2
### 2023/11/20

- minor dashboard fix and update
- new shelly PLUS 2PM floor00: 1-ledSala 2-ledEntrata

## v2023.11.0.2
### 2023/11/16

- update sensor for forno and frigo
- improve dashboard main with power bar-card
- some minor fix
- update of integrations and addons
- now fiber liked with 1GBit in all home with CAT7 cable
- update images in readme
- update lovelace dashboard file


## v2023.11.0.1
### 2023/11/10

- update core system
- minor dashboard fix
- update lovelace dashboard file
- fix  state_class: total_increasing for sensor energy
- boiler new states and sensors

## v2023.11.0.0
### 2023/11/03

- fix temp bug for -127 temperature
- update CORE 2023.11.0 and OS 10.5
- minor dashboard fix


## v2023.10.0.2
### 2023/10/28

- update os and core to 

        Home Assistant 2023.10.3
        Supervisor 2023.10.1
        Operating System 10.5
- minor fix
- battery fix

## v2023.10.0.1
### 2023/10/17

- Update core and supervisor
- Update automations
- Fix and improve frigate
- Update dashboard lovelace
- Update readme and documentation

- Add shelly HT
- Add shelly DCbox
- Add shelly BackDerivazione

- Final Install Entrance cam 
- Add gardenSouth camera4


## v2023.8.0.2
### 2023/08/03

- Update appliances card and network card
- Uptime card install and extensive use
- Update dashboard lovelace
- Reduce Stream width in Frigate
    - Try to reduce CPU usage and improve performance
- Notification to iphone test
    - Now not working, need to investigate


## v2023.8.0.2
### 2023/08/02

- Update core and supervisor
- update dashboard lovelace and add file in repo
    - new theme schema and heavy use of mushroom card and grid card
- Frigate notification with node red to iphone test
- some minor fix @ template ane sensor
- upload new images in readme

#### Changed

- 3 camera installation
- Frigate Installation and configuration
    - Recordings and Detection
    - Notifications to TODO


## v2023.8.0.1
### 2023/08/01

#### Changed

- 3 camera installation
- Frigate Installation and configuration
    - Recordings and Detection
    - Notifications to TODO

## v2023.7.1.0
### 2023/07/20

#### Changed

- Update dashboard
- HACS update
- Metro theme install
