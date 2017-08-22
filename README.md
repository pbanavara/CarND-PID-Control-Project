# CarND-Controls-PID
Self-Driving Car Engineer Nanodegree Program

To run the program:
./pid -0.25 0 -0.9

These are the parameters that I manually tuned based on the project tutorial
video by David.

The proportinal and differential parameters are what drives the accuracy of the
steering control. This has been my observation. So setting a negative value for
the proportional value helps in turning the steering in the opposite direction
in the simulator.
The same applies to the diifferntial parameter as well.
However, the higher the differential parameter the more is the steering
oscillation. So I manually adjusted the parameters accordingly.

