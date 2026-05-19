# Pyrolysis-Experiment-

![Status](https://img.shields.io/badge/Status-Prototype_Built-success)
![Domain](https://img.shields.io/badge/Domain-Waste_to_Energy-blue)
![Method](https://img.shields.io/badge/Method-Batch_Pyrolysis-orange)
![Incubation](https://img.shields.io/badge/Incubated-CSIR_NIIST_%26_Maker_Village-purple)
 
A lab-scale **plastic pyrolysis reactor** designed and fabricated for converting mixed plastic waste into pyrolysis oil, syngas, and carbon black through controlled thermal decomposition in an oxygen-free environment. Originated as a feasible entry point toward a longer-term **methane pyrolysis** concept (biogas → green hydrogen + sequestered solid carbon).
 
## Overview
 
Kerala generates ~600 tonnes of plastic waste per day, of which only ~20% is collected. Multi-layer plastics, LDPE bags, and polystyrene containers cannot be mechanically recycled. Pyrolysis offers a thermal decomposition path that recovers fuel-equivalent products from feedstock that would otherwise reach landfill or incineration.
 
The project was developed under the working name **Neuflow Energy** and incubated at:
 
- **CSIR-NIIST** — Council of Scientific and Industrial Research, Govt. of India
- **Maker Village** — Ministry of Electronics, Govt. of India
 
## Origin
 
The original concept was **methane pyrolysis** — converting biogas-derived methane into green hydrogen and solid carbon, providing clean fuel and permanent carbon sequestration in one process. The required quartz reactor, controlled microwave heating, inert gas handling, and hydrogen analysers were beyond independent build capability at that stage. Plastic pyrolysis was selected as a feasible entry point to build real fabrication and process engineering experience with pyrolysis at lower complexity.
 
## Highlights
 
- **7 kg batch capacity** lab-scale reactor designed and fabricated
- PID-controlled resistive heating, **400–500 °C** optimal pyrolysis range
- Water-cooled condensation system for liquid oil recovery
- Demonstrated **flammable gaseous fraction recovery**
- **Partial liquid oil collection** achieved
- Incubated at CSIR-NIIST and Maker Village (Govt. of India)
- Presented at Vruthi Conclave
 

 
## Methodology
 
1. Reactor design: cylindrical carbon steel vessel with ceramic wool, refractory cement, and clay tile insulation
2. Heating: ~550 °C resistance coil with PID temperature control
3. Inert gas purge for oxygen displacement before heating
4. Water-cooled condenser for vapour-to-liquid product recovery
5. Batch testing with mixed plastic feedstock
6. Run logging and product fraction observation
 
## Results & Lessons Learned
 
- Reactor reached target operating temperatures
- Flammable gaseous fractions recovered consistently
- Liquid oil partially collected through condenser system
- **Identified clogging issue:** softened plastic blocked the reactor base during heating — a known issue with batch pyrolysis of mixed plastic feedstock
- This points clearly toward the next engineering iteration: feedstock handling with agitation, or alternative reactor geometry (e.g. screw-fed continuous reactor)
 
## Repository Structure
 
- `/design/` — reactor CAD and fabrication drawings
- `/build/` — fabrication photos and build documentation
- `/testing/` — experimental run logs and observations
- `/concept/` — methane pyrolysis follow-on concept documentation
- `/pitch/` — Neuflow Energy pitch materials
- `README.md`
 
## Tech Stack
 
- **CAD:** SolidWorks, AutoCAD
- **Control:** PID temperature controller
- **Hardware:** Carbon steel reactor, resistance heating coil, water-cooled condenser, inert gas purge
 
## Status
 
Prototype built and tested. Clogging issue identified — informs the next design iteration. Methane pyrolysis remains the longer-term target as fabrication experience scales.
 
 
