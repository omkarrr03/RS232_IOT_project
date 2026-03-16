# RS232_IOT_project
Data transmission from CNC machines via RS232 port to MQTT..
In this project I have implemented a hardware setup, where data from a CNC machine is to be send to the MQTT server.
For that purpose CNC machines have a dedicated RS232 port from which data can be read. 
There I have connected RS232-to-TTL converter (module) so that data coming from CNC machine could be read.
And after the data is read, implemented a setup where data is send to the MQTT server.
