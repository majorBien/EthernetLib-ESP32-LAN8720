# EthernetLib-ESP32-LAN8720

A simple Ethernet library for the **ESP32** with the **LAN8720** chip using the **ESP-IDF** framework.

## Features

This library provides the following functions:


void ethernet_init(void);
void getIPAddressFromString(IP_ADDR *ip, const char *ipStr);
void ethernetParamConfig(CFG *config);
void setStaticIP(CFG *config);
void eth_app_task(void);

Building and Flashing
Make sure you have ESP-IDF installed and set up.

Then build and flash your project as usual:

bash
Kopiuj
Edytuj
idf.py build
idf.py flash
idf.py monitor
Requirements
ESP-IDF v5.x or newer

ESP32 board with LAN8720 chip
