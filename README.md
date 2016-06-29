# Raspberry_Pi_DHT22_Sensor_Python

On Github you find many projects about the DHT22 temperature and humidity sensor for the Raspberry Pi. Most of the codes are written in C or C++. If you want to use OpenElec as Operating System, you don´t have a Compiler to use the source codes. If you want to use them, you need to transfer the c source code in a python script file

# How to install
To use the script, you need only a few steps<br /><br />
1. Install the "unofficial-addons" repository in the addon-browser of your OpenElec Raspberry Pi<br />
2. Install the RPi.GPIO Addon through the addon-browser (Sources can be found here:<br /> https://github.com/OpenELEC/unofficial-addons/tree/master/addons/tools/RPi.GPIO)<br />
3. Open SSH and login with "root" as user and "openelec" as password<br />
4. wget <Link will follow>
 
# How to run
To run the python script you can use this command on SSH<br /><br />
python <will_follow>.py

# Additional Infos
If you want to use the informationen on an addon, feel free to use your own addon. An example addon implementation which uses the DHT22 sensor can be found here:<br /><br />
https://github.com/dani1810/HFU-IoT-Smart-Mirror-SS16/tree/master/addons/script.local.sensor

# Original Source in C:
The origin source in C can be found here: <br /><br />
https://github.com/technion/lol_dht22/blob/master/dht22.c
