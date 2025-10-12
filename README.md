# osa-stick
This project is currently just an attempt to offer an inexpensive and modular arcade stick as open source that anyone can assemble at home and adapt to their needs. 
I develop everything in my free time and use my own money for it without any financial interests. 
Therefore, I do not give any guarantees and ask for your understanding if something is not absolutely perfect.

My goal is to create a modifiable arcade stick that is affordable and can compete with the best on the market. 
This goal is very ambitious and requires a lot of testing, a lot of time and a lot of patience.

If you like my project, you are welcome to donate some money or hardware to support further development.

![CC BY NC SA 4.0](./Images/cc-by-nc-sa-icon-border-200x72.png "CC BY NC SA 4.0")

## Interfaces
### OSAS-Interface V1
The OSAS interface V1 is based on the DB25 connector and has the following pin assignment:

| Pin | Purpose      | Comment                         |
|-----|--------------|---------------------------------|
| 1   | Up           |                                 |
| 2   | Down         |                                 |
| 3   | Left         |                                 |
| 4   | Right        |                                 |
| 5   | Ground 1     | Ground for joystick and buttons |
| 6   | Button 1     |                                 |
| 7   | Button 2     |                                 |
| 8   | Button 3     |                                 |
| 9   | Button 4     |                                 |
| 10  | Button 5     |                                 |
| 11  | Button 6     |                                 |
| 12  | Button 7     |                                 |
| 13  | Button 8     |                                 |
| 14  | NC           | Reserved for I2C                |
| 15  | NC           | Reserved for I2C                |
| 16  | NC           | Reserved for I2C                |
| 17  | Ground 2     | Ground for Button LEDs          |
| 18  | LED Button 1 |                                 |
| 19  | LED Button 2 |                                 |
| 20  | LED Button 3 |                                 |
| 21  | LED Button 4 |                                 |
| 22  | LED Button 5 |                                 |
| 23  | LED Button 6 |                                 |
| 24  | LED Button 7 |                                 |
| 25  | LED Button 8 |                                 |



### OSAS-Interface V2-Full
The upcoming interface will be a PCB edge connector, similar to those found in old game cartridges.
This will have 44 contacts, expanding the first version with new functionality such as analog sticks.


### OSAS-Interface V2-Small
This will be a smaller version of the full interface with less contacts.
This reduced interface is intended for small controllers such as gamepads or joysticks with few buttons.
