# Automaton

Automaton is brand new, thus the sparse amount of code. The idea behind it is as follows.

Automation is pretty well non existent in the current offerings out on the market. Some systems may claim to be automation but are really just smart controllers. Automaton aims to change that by using several API's from Android and Google Play services. 

First we need a way to inteligently talk to devices. So, a cheap hub is needed. Right now I am using a Raspberry Pi with Android loaded to it as a central hub. This central hub can act as a gateway to "dumb" devices that may not know how to speak the appropriate Google Play Services API talk to communicate with the handset or with the analytics engine directly. 

Second we need "modules" on the hub to communicate with these different end devices. RS232. IP, IR, HTTP, TCP, SSH etc... These modules help to determine the state of the environment and all things connected to the hub. 

Third we need to establish a pub/sub architecture for publishing and responding to events or actions. These messages are how we establish true automation. The predication engine can use these messages to automate tasks based on probabilities. 

There is a lot to be done so if you are interested in helping just drop me a line!
