# The Art of Motion
Every robot I've ever made had one thing for sure: Wheels (as do a very vast majority of competitive Vex robots). Arguably the most important mechanism, the drivetrain moves the entire robot itself from point A to point B, so making sure that it can move *well* is always important.

But what does moving *well* really mean? Everytime you code a movement (even a simple one, like move forward for 3.0 metres), you expect it to move forward 3.0 metres. But in reality, it will not move exactly 3.0 metres; it might be close, but usually it's going to be above or below by a little bit due to uncontrollable aspects like inertia, friction, and even the time the robot brain takes to communicate with motors.

There are different ways a robot can move 3.0 metres in terms of acceleration and deceleration, such as moving 3.0 metres by accelerating and reaching full speed very quickly, or maybe even accelerating a little slower but eventually still reaching full speed. These different methods can be graphed and integrated, from which the expected value can be calculated, as to how much a robot *should* move. The next step is to program the robot for each style of movement, and then to compare the different methods of movement to see which one is the closest to the expected value.

The repository only contains movement code, but the full publication is available at: 
https://www.dropbox.com/s/9wr8hm0i71syk5g/Tejas-Wilkhoo-The-Art-Of-Motion.pdf?dl=0
