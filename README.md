# MicroPython-MQTT

sudo apt-get install mosquitto mosquitto-clients

$ python -c 'from uuid import uuid4; print(uuid4())'

dd9a00db-a4eb-4c57-ab8d-3a2e403e9d26

import upip
upip.install('micropython-umqtt.robust')



from umqtt.robust import MQTTClient

client = MQTTClient('db56c5f0-bb68-4a36-ab59-0e9c14da6dc9', 'test.mosquitto.org')

client.connect()

client.publish('boneskull/test/temperature/fahrenheit', 72)


esptool.py --chip esp32 -p /dev/ttyUSB0 write_flash -z 0x1000 esp32-20180816-v1.9.4-465-g056e0b629.bin
