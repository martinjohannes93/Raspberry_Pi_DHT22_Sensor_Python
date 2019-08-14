# DHT22_Sensor_Python

On Github you will find many projects about the DHT22 temperature and humidity sensor for the Raspberry Pi. Most codes are written in C or C++. However, if you want to use OpenElec as your operating system, programs are typically run in Python. Therefore we converted one of the DHT22 scripts to Python as part of a university project.

## How to install on OpenElec

To use the script, you need only a few steps
1. Install the repository *unofficial-addons* in the addon browser of your OpenElec Raspberry Pi.
2. Install the RPi.GPIO addon via the addon browser (sources can be found [here](https://github.com/OpenELEC/unofficial-addons/tree/master/addons/tools/RPi.GPIO))
3. Open ssh and login with *root* as user and *openelec* as password
4. `wget https://github.com/martinjohannes93/Raspberry_Pi_DHT22_Sensor_Python/raw/master/dht22.py`

## How to run

To execute the Python script you can use this command inside your ssh terminal.
```bash
python dht22.py
```

## Additional information

If you want to use the the addon instead, you are welcome to our sample implementation of this addon which was created by Daniel and me SS16. This repo only has the pure python file. See [here](https://github.com/dani1810/HFU-IoT-Smart-Mirror-SS16/tree/master/addons/script.local.sensor) (Thx to Daniel for using his git account^^)

## Original source in C

The original source in C can be found [here](https://github.com/technion/lol_dht22/blob/master/dht22.c)
