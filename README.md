# sos-drone-project
Offline emergency communication system built using ESP32 and NRF24L01 modules. The system creates a local WiFi network with a captive portal where users can submit SOS messages without internet access. Messages are transmitted wirelessly to a central hub ESP32 for real-time monitoring and emergency response management.

 Problem Statement
We wanted to build an emergency communication system that works even when internet or cellular networks are unavailable, like during disasters or in remote areas.

 Core Idea
We used ESP32 modules to create local WiFi access points where nearby users could connect and send SOS messages through a captive portal webpage.

User Phone → ESP32 Access Point → NRF24 → Hub ESP32 → Admin Dashboard
