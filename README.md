# AquaAI
**Patterns for aquaculture with embedded AI**

An open source for creating powerful aquaculture solutions. For monitoring water parameters and livestock, controlling devices, automating common aquaculture tasks, and providing insights through artificial intelligence.

The initial focis of this project is making stony coral easier to grow and propogate, but the functionality applies to freshwater and saltwater aquariums and aquaculture.

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
      * Total Dissolved Solids
      * ORP
      * Alkalinity (dKH)
      * Calcium
      * Magnesium
      * Nitrate
      * Phosphate
      * Ammonia
      * Nitrite
      * Copper
      * Trace Elements via ICP tests
  - Water Flow
  - Water Levels
      * Ultrasonic (good between 15cm and 60cm)
      * Infrared
      * Thin film pressure
      * Optical
  - Binary Presence
      * Movement (Passive Infra Red)
      * Water spill detection
  
## Integrations 
Integrations are provided to support propriatery devices and control systems including:
  Ecotech
  
