Networks
==

* Messages transmitted at speed of light from fiber optic cables
* Networks and computers were NOT developped at the same time
* Networks helped share information and physical resources (like printers)
* LAN = Local Area Network (a closed network of several computers, eg ethernet)
* CSMA = Carrier Sense Multiple Access
* Bandwith = rate at which computers can transmit data
* Collision = two computers trying to transmit data at once
  * Solution: each computer waits a random amount of time, so transmissions are staggered
  * This random amount of time gets bigger after each time (exponential backoff)
* Collision domain = using a network switch to transmit between two smaller networks
* Routing = having individual paths linking different spots (circuit switching, based off of telephone lines)
  * Inflexible and expensive
  * Militaries and banks still have their own circuits
  * Message switching (how the postage system worked)
    * Going to many "stops"
    * Hop count = how many "stops" the message makes
    * Downside = big messages
      * Big messages are split up into packets
      * Monitored by Internet Protocol (IP)
      * This is called PACKET SWITCHING, and is what the internet uses today
        * No centralization
ARPANET = the original system
