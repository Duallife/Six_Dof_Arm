[![License: MIT][MIT-License-sheild]][MIT-License-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
# Ultra Low Cost 6Dof Robot Arm
The project aims to create a ultra low cost robot arm with steppers and 3d printed cycloidal reducer. The total cost of the ARM currently goes under 250 CNY (35 USD). Project material are sourced in China.

## Material list
- NEMA17 stepper motors (39mm) * 3
- NEMA11 stepper motors (31mm) * 2
- NEMA11 stepper motors with 16:1 reducer * 1
- Esp32 wroom-32 38pins
- TMC2208/TMC2209/A4988 stepper motor controller * 6
- 128*80 SPI TFT screen
- EC11B series encoder (through hole)
- 24V3A DC power supply or above
- Some through hole LED
- Some through hole Resistors
- Lubricating Oil 
#### Bearings
| Inner Diameter (mm)  | Outer Diameter (mm)  | Width (mm) | Quantity |
|----------------------|----------------------|------------|----------|
| 3                    | 6                    | 2.5        | 10       |
| 4                    | 7                    | 2.5        | 36       |
| 6                    | 10                   | 3          | 2        |
| 5                    | 10                   | 4          | 3        |
| 10                   | 15                   | 4          | 6        |
| 8                    | 16                   | 5          | 10       |
| 55                   | 72                   | 9          | 1        |
#### Knurled shaft
| Diameter  (mm)       |Length (mm)  | Quantity |
|----------------------|-------------|----------|
| 2                    | 16          | 23       |
| 2                    | 35          | 1        |
| 2                    | 45          | 1        |


#### 3D printed Material Used
- PETG for main components (The project use JAYO PETG)
- High strength material fpr shafts, output discs of reducer, Highly recommender(The project use Timory PETG-CF)
- (Bambu Lab A1mini is used)
- (Recommended printing parameter will be list inside <strong>/Hardware</strong>)

## System Requirement
- PlatformIO environment
- A Linux Distro (For ROS2 Control)
  - ROS2 Humble
  - Rviz2
  - Moveit2!
  - Gazebo
  - Other Common dependencies

## TODO -->
- Structure integrity improvements for joints
- GUI application
- Close loop position control, speed control of motors with low cost


### Project is under MIT Licence
[MIT-License-sheild]: https://img.shields.io/badge/License-MIT-green.svg
[MIT-License-url]: https://opensource.org/licenses/MIT
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-blue.svg
[linkedin-url]: https://www.linkedin.com/in/yui-kai-tse-499029231