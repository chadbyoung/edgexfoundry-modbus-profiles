[//]: # (Created on: October 30, 2017)
[//]: # (Author: Chad Young)
[//]: # (Contact: chad.young@dell.com)


# Readme for DataNab MBUS_RTH_LCD
The DataNab MBUS_RTH_LCD is a Modbus Enabled Room Temperature/Humidity Sensor
with LCD and Dual 0~10V Out.  

| Variable       | Unit    | Add. Hex | Add. Dec | Format | Size | Status |
| :---           | :---:   | :---:    | :---:    | :---:  | :---:| :---:  |
| Device Address |         | 0x0000   | 6        | Int    | 2    | Read   |
| Degrees F      | F x 10  | 0x0064   | 100      | Int    | 2    | Read   |
| Device Register | C x 10  | 0x0065   | 101      | Int    | 2    | Read   |
| Device Register | RH x 10 | 0x0066   | 102      | Int    | 2    | Read   |


Mode details can be found here:  
http://www.datanab.com/sensors/modbus_rth_lcd.php  
http://www.datanab.com/zc/docs/sensors/MBus_RTH_LCD.pdf  






