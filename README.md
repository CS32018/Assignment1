# Assignment1 (20%)
Sensor collection application
10 sensor nodes (sources)
1 collector
Star network
sensors are all within reach of collector
Sources collect data periodically
Actual sensor (temp, hum, light, etc) is up to you
Collection rate is also up to you
Periodically the collector must get an average of the last X samples from all the sensors
The collector must ask all the nodes for their data
The nodes will reply with the average - the value of X is your choice

Tips/Info
Make use of RIME broadcast and Unicast communication
Sensing application similar to the lab 3 example
 Augment this with communication capabilities
Collector sends a message to the sensors
Sensors compute the average and send only upon receiving the query from the collector
Deploy your network in Cooja
Due date: 8th November, in lab demo/interview
Please commit your code and push to GitHub

