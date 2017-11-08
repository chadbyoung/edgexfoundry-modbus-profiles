[//]: # (Created on: October 30, 2017)
[//]: # (Author: Chad Young)
[//]: # (Contact: chad.young@dell.com)


# Readme for DataNab MBUS_RTH_LCD
The DataNab MBUS_RTH_LCD is a Modbus Enabled Room Temperature/Humidity Sensor
with LCD and Dual 0~10V Out.  

| Variable         | Unit    | Add. Hex | Add. Dec | Format | Size | Status |
| :---             | :---:   | :---:    | :---:    | :---:  | :---:| :---:  |
| Device Address   |         | 0x0000   | 254      |        | 1    | Read   |
| Degrees F        | F       | 0x0065   | 101      | Float  | 1    | Read   |
| Degrees C        | C       | 0x0066   | 102      | Float  | 1    | Read   |
| Precent Humidity | RH      | 0x0067   | 103      | Float  | 1    | Read   |


Mode details can be found here:  
http://www.datanab.com/sensors/modbus_rth_lcd.php  
http://www.datanab.com/zc/docs/sensors/MBus_RTH_LCD.pdf  

The adderess listed in the PDF is wrong 





