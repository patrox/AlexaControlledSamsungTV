to run you will need Python3 with the following pip packages installed


samsungctl    
websocket-client     
AWSIoTPythonSDK

to setup. first you will need an online account. create one at alexasmarttv.tk

Then turn on your TV and run the following commands to get up and running

```
python3 alexasmartcli.py scan
```

It should output the ip, mac address, and model.    
put those into the tvconfig.py file and then run:

```
python3 alexasmartcli.py login
python3 alexasmartcli.py register
python3 alexasmartcli.py setup_cable
python3 alexasmartcli.py start
```

Then just install the alexa smart skill (Unofficial Samsung SmartTV Controller), discover devices and you will be on your way.
<br>
<br>
Link to alexa skill: https://www.amazon.com/dp/B07886XNK8
<br>
<br>
Tutorial:<br>
[![Alexa Setup Tutorial](https://img.youtube.com/vi/-uhd33FiEUM/0.jpg)](https://www.youtube.com/watch?v=-uhd33FiEUM)

Currently supports the following commands:
* Alexa turn on the TV    (Only supported on K,M, and QLED TVS (2016 and newer))
* Alexa turn off the TV

* Alexa (un)mute the TV
* Alexa turn up/down the volume on TV

* Alexa change the channel to 25 on the TV
* Alexa change the channel to ESPN on the TV

* Alexa Play/Pause/Stop the TV


Disclaimer:
1) H and J series TVs are currently unsupported but are being worked on to support it

2) If you have a cable box, in order to change the channel the alexa sends a command to the smart remote which sends it back to the cable box over RF. Because of this for the command 'alexa change the channel' to work the remote needs to have line of sight with the cable box

