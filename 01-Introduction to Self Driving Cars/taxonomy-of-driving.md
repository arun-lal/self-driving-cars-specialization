# Taxonomy of Self-Driving Cars


## Understanding the Driving Task

The driving task involves three primary sub-tasks:

1. **Perception**: In this task, the vehicle must accurately sense and interpret the environment. For example, it should be capable of identifying moving objects such as other vehicles, pedestrians, and inanimate objects like road signs and the condition of the road surface.

2. **Motion Planning**: This aspect revolves around determining the optimal path to reach a destination safely. For instance, it includes tasks like selecting the most suitable roads, deciding when to change lanes or cross intersections, and handling maneuvers like swerving to avoid obstacles.

3. **Vehicle Control**: Vehicle control focuses on managing the car's position and speed. This entails actions like steering, braking, and acceleration to ensure the vehicle remains in the correct position on the road and travels at the right velocity.

## Operational Design Domain (ODD)

ODD refers to the specific set of conditions under which a self-driving system is designed to operate effectively. It encompasses environmental factors, the time of day, road conditions, and various other variables.

For example, an ODD could define that the system operates optimally in urban settings, during daylight, on paved roads, and in clear weather conditions.

## Classifying Levels of Automation

When classifying levels of automation, several questions need to be addressed:

- **Driver Attention**: To what extent is the driver required to be attentive? For instance, can the driver watch a movie or must they maintain constant attention on the road?

- **Driver Action**: What actions must the driver perform? Is the driver responsible for steering, or does the system take care of speed control, lane keeping, and lane changes?

A specific example of the classification is the:

### SAE Standard J3016

- **Level 0**: No automation. All tasks are the responsibility of the driver.

- **Level 1**: Assisted control. The system handles either lateral or longitudinal control tasks. An example is adaptive cruise control (ACC), where the system controls speed.

- **Level 2**: Partial automation. The system manages both lateral and longitudinal control in specific scenarios. A common example is Tesla's Autopilot.

- **Level 3**: Conditional automation. The system can detect and respond to objects and events, but the driver may need to intervene. An example includes Audi's automation system.

- **Level 4**: High automation. The system can manage emergencies but may require driver takeover. Waymo's self-driving vehicles are an example.

- **Level 5**: Full automation. The system can operate autonomously under any condition, marking a revolutionary change in transportation.



