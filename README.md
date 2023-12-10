# misAlignment
(mis)Alignment is a computational system that takes **simple** agent behaviours and game mechanics to produce engaging visuals. It is built on top of my previous project Entropy

The system simulates agents. These agents have an angle and move according to that angle and a defined speed. Agents leave "pheromone" trails behind that fade with time.

Display, spawn and collision mechanics are **customizable**. Look at customizable sections of code (indicated with comments) to **create your own simulation** !
New features include spawn options on the vertical & horizontal lines, with different options for spawn angle distribution, creating unique visuals !

The software is written to function in the Processing environment.

There is a recording mode in which you can handle larger computations not executable in real time. It saves all the frames in a folder.

The frames can be stitched together to create a video. FFmpeg is a tool that allows that. To create videos :

1. Install FFmpeg
2. Change directory to fodler containing recorded frames
3. Type command printed in console after recording (looks like this : FFmpeg -framerate 60 -i frames-%04d.png -c:v libx264 -pix_fmt yuv420p output.mp4)

https://github.com/pr0jestisle/misAlignment/assets/72268260/196d197f-dbf9-42d5-abbe-725221931bf6

Please reference this repository if you use it ;)



