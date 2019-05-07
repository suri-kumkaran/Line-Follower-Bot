# Line-Follower-Bot
This is an autonomous bot which follows a line, either a black line or white line.

Major required components are Arduino, L293D Motor Driver and IR Module.

Working of line follower is very interesting. Line follower robot senses black line by using sensor and then sends the signal to arduino. Then arduino drives the motor according to sensors' output.
Here in this project we are using two IR sensor modules namely left sensor and right sensor. When both left and right sensor senses white then robot move forward.
If left sensor comes on black line then robot turn left side.
If right sensor sense black line then robot turn right side until both sensor comes at white surface. When white surface comes robot starts moving on forward again.
If both sensors comes on black line, robot stops.
