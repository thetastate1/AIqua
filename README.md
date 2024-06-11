# AIqua
**Patterns for aquaculture with embedded AI**

An open source for creating powerful aquaculture solutions. For monitoring water parameters and livestock, controlling devices, automating common aquaculture tasks, and providing insights through artificial intelligence.

The initial focus of this project is making stony coral easier to grow and propogate, but the functionality applies to freshwater and saltwater aquariums and aquaculture.

AIqua is intended to be a powerful, scalable, and more cost effective solution than propritarty solutions available on the market. 

## Can I use AIqua?
AIqua can be used by anyone regardless of your technical or coding experience.

We welcome contributions to this project. You don't have to have coding experience to develop super useful Templates, Automations, and Dashboards.

Templates are typicaly built using simple YAML structures. No coding experience required.

Dashboards and Automations are built using the Home Assistant user interface.

If you are after a turn key solution, AIqua can provide all the hardware and software you need as well as the services to configure it for your needs.

## Foundations
AIqua uses [esphome](https://esphome.io/index.html) for sensors and [Home Assistant](https://www.home-assistant.io) for automation and control. 

## Sensor Templates
Sensor Templates are selected that apply to your use case. For example, you may not require monitoring of trace elements or integration with an Apex controller. You just use the templates that support your use case.

Each template provides the code, examples of the hardware, and use cases.

AIqua provides sensor templates for monitoring:
  - Water Parameters
      * Temperature (3 wire dallas and 2 wire thermistor)
      * pH (analog and digital)
      * Salinity / Conductivity
      * Total Dissolved Solids (TDS)
      * Oxygenation Reduction Potential (ORP)
      * Alkalinity (dKH)
      * Calcium
      * Magnesium
      * Nitrate
      * Phosphate
      * Ammonia
      * Nitrite
      * Copper
      * Trace elements via ICP tests
  - Water Flow
      * Hall effect
      * 433MHz smart meters (with integration)
  - Water Levels
      * Ultrasonic
      * Infrared
      * Thin film pressure
      * Optical
  - Binary Presence
      * Movement (Passive Infra Red)
      * Water spill detection
  
## Integrations 
AIqua provides integrations to hardware and software outside the esphome and Home Assistant native [integrations](https://www.home-assistant.io/integrations/).

Integrations are provided to support propriatery devices and control systems including:
  - Ecotech Mobius using [MobiusMQTT <link>](https://github.com/thetastate1/MobiusMQTT)
      * Versa
      * Vortech
      * Radion
      * Nero
      * AI Prime
    
  - Neptune Apex
  - Reef Kinetics
      * Reefbot 1
      * Reefbot 2
  - RedSea ReefBeat
  - 0 - 10v controls

## Recorder
AIqua through native Home Assistant functionality provides a comprehensive solution for recording the [history](https://www.home-assistant.io/integrations/history/) of water parameters and control events. Statictics can be reported using the supplied Dashboards. 

## Automations
AIqua provides a powerful [automation](https://www.home-assistant.io/docs/automation/) engine undrepinned by Home Assistant.

The library of AIqua automation blueprints currently includes:
  - Alerts (dashboard and txt to one or more mobile phones)
      * Water spill
      * Water level (too high, too low)
      * Water parameter out of range (e.g. Temperature, pH)
      * Device offline (e.g. return pump offline)
      * Device out of tolerance (e.g. return pump low power consumption)
      * Chilled food low
      * Chilled food temperature
      * Enter feed mode
      * Reminders (e.g. time to manually test water parameters or preventitive maintenance / service equipment)
  - Feed Mode
  - Feedling Schedule (for feeding automation with the Yumi frozen feeder or IoT enabled dry food feeder)
  - Water Change Mode
  - Automatic Water Changes
  - Suppliment Control (e.g. increase alkalinity suppliment by x ml when parameter out of target range)
  - Temperature Control (e.g. turn heaters and chillers off and on when paramter out of target range)

## Controls
AIqua uses Home Assistant [integrations](https://www.home-assistant.io/integrations/) to control the power supply to smart devices including:
- Power Sockets
    * Individual power sockets
    * Power boards
    * USB 5v
- Lights
- Fans
- Covers

Protocols supported include:
  - WiFi
  - Matter / Thread
  - Zigbee
  - Zwave
  - Bluetooth
  - MQTT

Wherever possible we reccomend using local rather than cloud controlled integrations as you'll see better responsiveness and reliability.

## Getting Started

## Limitations

## Support
