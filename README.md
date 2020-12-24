# hue-cheerlights
Automatically set your Philips Hue light(s) to the current Cheerlights color

https://cheerlights.com/cheerlights-now-supports-mqtt/

https://cheerlights.com/cheerlights-api/


## Requirements
pip3 install paho-mqtt requests


## Usage
These API guides are an easy way to get started figuring out the Hue bridge local API

https://developers.meethue.com/develop/get-started-2/

https://www.burgestrand.se/hue-api/api/lights/


* Set your Hue bridge hostname / IP [here](hue-cheerlights.py#L13)

* Set your Hue bridge local API key [here](hue-cheerlights.py#L17)

* Set which lights / groups you want to control [here](hue-cheerlights.py#L329)

I am currently just running this from a screen terminal session, but I'll probably build it into a Docker container shortly so it's easier to manage.


## Acknowledgements

Thanks to [benknight](https://github.com/benknight) for the fantastic RGB to XY converter https://github.com/benknight/hue-python-rgb-converter

MQTT library and examples from https://github.com/eclipse/paho.mqtt.python
