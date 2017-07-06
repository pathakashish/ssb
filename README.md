# SSB
**Smart Switch Board** for controlling home appliannces
This project aims at writing software(firmware, web APIs and Android mobile app) for Smart Switch Board to control home appliances remotely.

#### Responsibilities of each software under this project
##### Firmware
 * Allow user to configure Smart Switch Board
 * Allow user to turn ON any switch
 * Allow user to turn OFF any switch
 * Allow user to toggle any switch
 * Support UPnP discovery and control but also provide fallback where UPnP is disabled
 * Subscribe to authorized server for commands

##### Web APIs
 * Allow client to register users
 * Authenticate and authorize users
 * Allow authorized SSB to subscribe for commands
 * Allow authorized clients to publish commands to authorized SSB
 * Maintain configuration and state of each SSB
 * Integrate third parties like IFTTT, Alexa Skill, Google Actions etc

##### Android mobile app
 * Allow user to register and login to server
 * Allow user to confgigure SSB and update state of SSB on server
 * Allow user to control single or multiple switches from the board
 * Control SSB offline when on same network
 * Control SSB via web server by publishing message to server when not on same network
