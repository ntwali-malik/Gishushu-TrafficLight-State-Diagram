# Gishushu-TrafficLight-State-Diagram

This repository contains the state diagram for the Gishushu traffic light system, created using PlantUML. The design includes the primary states for controlling vehicle and pedestrian traffic flow.

## Specifications

### States:
1. **Red Light**: Stops vehicle traffic.
2. **Green Light**: Allows vehicle traffic to proceed.
3. **Yellow Light**: Prepares traffic to stop.
4. **Pedestrian Cross**: Allows pedestrians to cross safely.

### Transitions:
- **Red to Green**: Changes when the timer expires.
- **Green to Yellow**: Changes when the green timer expires.
- **Yellow to Red**: Prepares vehicles to stop and returns to Red.
- **Red to Pedestrian Cross**: If a pedestrian button is pressed.
- **Pedestrian Cross to Red**: Returns to Red after a crossing timer expires.
