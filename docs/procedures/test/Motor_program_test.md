

# Arduino shield motor assembly procedure 

Purpose: This sheet describes how to test the program  and  the motor.

## 1. Preparation / material needed :

- Arduino 1.8.8 software.
- EMG30 motor x1
- Pololu DRV8835 Dual motor driver shield for Arduino x1
- Arduino Uno x1

## 2. Operating mode :

The purpose of this program is to make the motor rotating 2 secondes in anticlokwise with a
lit led on the Arduino, then to rotate 2 secondes on the normal clockwise, with the OFF Led. 
This led ON/OFF cycle depends of the motor's connection.

- Follow the arduino_motordrivers_motor_assembly_procedure contained in the **docs/ procedures / assembly** folder. 

- Implement the Arduino program, called **motor_control_open_loop**, contained in the **sources** document, and upload it in the Arduino. as well as the different libraries obtained from this link **http://www.pololu.com/product/2511**, and fill the following table : 

| Procedure   | Supposed situation | Observed situation |   Note   |
| :---:         |     :---:      |          :---:       |   :---:  |
| Rotating motor 2s (anticlockwise)   | Rotation + ON LED     |     |      |
| Rotating motor 2s (normal clockwise)     | Rotation + OFF LED       |       |   |

- **If the supposed situation matches with the observed one, we can validate the test of the motor.** 




	
