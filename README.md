### Zabbix Template Alexa version 1.0.0

Tested on Zabbix 4.4

# Introduction
Template for zabbix to check if Alexa echo dot or input responding has they can't be pinged using external script.
It can check:
* If Alexa echo dot ports are opened 
* If Alexa echo input port is opened  

# Requirement
No spefcific requierement

It use **Simple check** zabbix function

# Installation

## Template
You need to import the **frogg_alexa_check.xml** template configuration file in the zabbix web interface in **Template** tab using the import button

The file contains 2 templates:
* Template Alexa echo dot
* Template Alexa echo input

# Template items
![Zabbix ALEXA Template](https://tool.frogg.fr/upload/github/zabbix-alexa/items.png)

# Template triggers
![Zabbix ALEXA Template triggers](https://tool.frogg.fr/upload/github/zabbix-alexa/triggers.png)
