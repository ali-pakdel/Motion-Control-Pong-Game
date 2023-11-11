# Motion-Controlled Pong Game

This project endeavors to emulate the timeless Pong game with an innovative twist – control through the accelerometer and gyroscope sensors found in Android smartphones. The gaming environment consists of a `ball` and a `paddle`, employing the Canvas library to display two-dimensional elements on the screen. Physical formulas are implemented to replicate the motion of both the ball and the paddle.

## Basic Mode
In this mode, the device is positioned on a flat surface, such as a table, with the gaming area extending 50 cm in length. The device's movement is limited to 25 cm to the right and 25 cm to the left on the table. The paddle mimics the direction of the device's movement. Additionally, rotating the device around its perpendicular axis results in a corresponding rotation of the paddle.

## Advanced Mode
The advanced mode liberates the device from the confines of a table, allowing users to hold it parallel to the ground. Gravitational acceleration propels the paddle along the X-axis of the screen. Upon collision with the paddle, a sudden upward acceleration in the Z direction boosts the ball's travel distance on the plane. This feature emulates the behavior of a real ping pong paddle, where the force applied upon impact influences the ball's speed. The paddle's rotation in this mode mirrors that of the normal mode and is governed by the gyroscope sensor.
