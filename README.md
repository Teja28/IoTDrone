# IoT-Controlled Drone
This project used the onboard accelerometer on the TI CC3200 in
order to connect to a Pixhawk controlled drone running the PX4
Flight Stack. Communication was done using AWS IoT. A post request was
sent to AWS in order to update a thing shadow. A raspberry pi 3 with
FlytOS was onboard the drone and connected to the drone. The raspberry
pi was running a python script that listened to the AWS thing shadow
and sent the appropriate flight command to the drone. 
