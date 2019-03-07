# Arduino shield motor assembly procedure 


Purpose: This sheet describes how to mount the motor driver to the arduino and then assembly the motor.


## 1. Preparation / material needed :

- EMG30 motor x1
- Flat screwdriver x1
- Pololu DRV8835 Dual motor driver shield for Arduino x1
- Arduino Uno x1
- Pololu DRV8835's jumper x1


## 2. Operating mode :

Put the **jumper** on the V_out pins, and the **Pololu DRV8835** on the Arduino. The **Pololu**'s pins are paires as follows : The V_cc and the 5V ; The Ground with the Ground, and the V_in to the AV_in. (see picture).

The motor's alimentation wires are put in the **Arduino's** connectors to let the **Arduino** and the **motor** communicating (see picture).

A led is placed on the **Arduino**, and is supposed to light on when the**motor**'s axis rotating in a definite sense, and is lit off when rotating in the opposite sense. 



## 3. Criterion of acceptability and refusal :

To approve the **motor**, **Arduino** and **pololu** assembly, we must notice that no pin are broken, each wires are well sunk into the connectors, and 




