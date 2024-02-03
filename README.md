# AquaAI
**Patterns for aquaculture with embedded AI**

An open source for creating powerful aquaculture solutions. For monitoring water parameters and livestock, controlling devices, automating common aquaculture tasks, and providing insights through artificial intelligence.

The initial focus of this project is making stony coral easier to grow and propogate, but the functionality applies to freshwater and saltwater aquariums and aquaculture.

## Can I use AquaAI?
AquaAI can be used by anyone regardless of your technical or coding experience.

We welcome contributions to this project. You don't have to have coding experience to develop super useful Templates, Automations, and Dashboard.

Templates are typicaly built using simple YAML structures. No coding experience required.

Dashboards and Automations are built using the Home Assistant user interface.

If you are after a turn key solution, AquaAI can provide all the hardware and software you need as well as the services to configure it for your needs.

## Foundations
AquaAI uses esphome for sensors and Home Assistant for automation and control. 

## Templates
Templates are selected that apply to your use case. For example, you may not require monitoring of trace elements or integration with an Apex controller. You just use the templates that support your use case.

Each template provides the code, examples of the hardware, and use cases.

AquaAI provides sensor templates for monitoring:
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
AquaAI provides integrations to hardware and software outside the esphome and Home Assistant native integrations.

Integrations are provided to support propriatery devices and control systems including:
  - Ecotech
      * Versa
      * Vortech
  - Neptune Apex
  - Reef Kinetics
      * Reefbot 1
      * Reefbot 2
  - RedSea ReefBeat

## Recorder
AquaAI through native Home Assistant functionality provides a comprehensive solution for recording the history of water parameters and control events. Statictics can be reported using the supplied Dashboards

## Automations
AquaAI provides a powerful automation engine undrepinned by Home Assistant. 
