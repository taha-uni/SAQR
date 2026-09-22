## WRO 2026 Future Engineers
## SAQR Team
Team ID: 6327
## Junior
 Dharan / unischools 

## Team Members :
Leenh Baroud - Sarah alsaleh

## About the robot :
The sumo robot employs an integrated strategy combining sensor usage with motion control to achieve maximum energy efficiency during the match. This strategy is based on a fundamental principle: no component of the robot—whether drive wheels or offensive mechanisms—moves unless in response to actual sensory data, rather than moving automatically or randomly.

## Hardware
- AV3 Robot.
- Sensors Used and Their Roles
Sensor	Function	Action Taken Based on Reading
Color Sensor	Detects the arena boundaries by identifying the color white	Immediately changes direction to move away from the edge and prevent the robot from leaving the arena
Distance Sensor	Detects the presence of the opposing robot in front	Moves directly toward the detected target instead of continuing random movement
- Power Management Plan:
•  When no target is detected, the robot switches to a predefined search pattern (a short pivot of 0.1 turns) instead of moving randomly; each search movement is deliberate and of limited duration.
•  Offensive systems—primarily the firing mechanism—are activated only upon actual detection of the opponent, rather than running continuously, thereby minimizing unnecessary power consumption.
The decision to change direction upon approaching the edge of the arena relies directly on color sensor readings, avoiding unnecessary movement.
• Energy consumption is directly linked to sensor input; no energy is expended on movement that does not serve a clear purpose—such as searching, pursuing, or avoiding going out of bounds.
This integration of sensors and the decision-making mechanism forms a comprehensive energy strategy, based not on a single component but on the continuous interaction between sensory input and motor response throughout the match.

- Confrontation and Clash Management Strategies :
The confrontation strategy relies on combining two offensive tools—the projectile launcher and the shovel—with two sensing systems—a distance sensor and a color sensor—allowing the robot to act flexibly based on the match situation rather than adhering to a single, fixed behavior.
- Tools of Confrontation:
  Shooter Motor : A long-range attack, activated only upon detecting the opponent and in accordance with the program's logic—without random or continuous operation.
  Shovel : Pushing the opposing robot off its path during direct contact, and directing the force of the impact toward a specific point rather than dispersing it across the robot's components.

  - Managing Trauma During Confrontation:
   Upon colliding with an opponent, the robot experiences a sudden impact force. The front-mounted shovel is designed to serve as the primary contact point, ensuring the collision is controlled and predictable rather than occurring haphazardly across various parts of the chassis. Following the impact, the sensors continue to transmit data, allowing the robot to adjust its heading instead of stalling in an ineffective position.

-Strategic flexibility :
To introduce an element of unpredictability to the robot's performance, the program randomly selects between two different movement paths during each execution cycle: one path combining a short axial rotation, sensory scanning, and firing mechanism activation; and another involving a 180-degree turn followed by a longer straight-line advance. This random switching between paths prevents the opposing robot from anticipating the robot's movements, adding a strategic dimension beyond mere immediate sensory response.




