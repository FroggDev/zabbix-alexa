### Zabbix Template Alexa version 1.0.1

Tested on Zabbix 4.4

# Introduction
Template for zabbix to check if Alexa echo dot or input is responding, as they can't be pinged, using simple check.
It can check:
* If Alexa echo dot ports are opened 
* If Alexa echo input port is opened  

# Requirement
No specific requierement

It use **Simple check** zabbix function

# Installation

## Template
You need to import the **frogg_alexa_check.xml** template configuration file in the zabbix web interface in **Template** tab using the import button

The file contains 2 templates:
* Template Alexa echo dot
* Template Alexa echo input

# Template items
* Alexa echo dot
![Zabbix ALEXA DOT Template](https://tool.frogg.fr/upload/github/zabbix-alexa/items-echo-dot.png)
* Alexa echo input
![Zabbix ALEXA DOT Template](https://tool.frogg.fr/upload/github/zabbix-alexa/items-echo-input.png)
# Template triggers
* Alexa echo dot
![Zabbix ALEXA INPUT Template triggers](https://tool.frogg.fr/upload/github/zabbix-alexa/triggers-echo-dot.png)

* Alexa echo input
![Zabbix ALEXA INPUT Template triggers](https://tool.frogg.fr/upload/github/zabbix-alexa/triggers-echo-input.png)
