# Math-Operations-Gravity-Exercise
This program calculates the distance a suspended object falls given a user input gravity constant and time

We have learned how to make basic python programs. One of these programs calculated the time taken for an object to fall to the ground from a user defined height and gravity.However, we also know that our games run in a loop.We can define the number of times the screen is updated each second (Frames Per Second)and this will determine the duration ofa specific loop(or frame). If we keep track of how many loops we’ve ran though, it will tell us how much time has passed. Therefore, it would be more useful to determine how far anobject has movedin a certain gravity over aspecified periodof time, allowing us to draw the object on the screen during each frame.That way we can animatethe object for a given gravity.  Assume the object is stationary at the beginning of the simulation.

Requirements:
The program shall:
1.Have a header comment that includes the author, date, and description of the program.
2.Print a description of what it doesand how it works.
3.Ask the user for the gravity value (in pixels per second^2) and input it.
4.Ask the user for the frames per second (FPS) of the program.
5.Ask the user for the desired frame number(which is equal to the number of loops we’ve ran through)6.Calculate the number of pixels the object will have fallen by the time we reachthe given frame number.
HINT:  Use the FPS and number of frames to find how many seconds the object has been falling.

Have the students use the web to seek out the correct formula.  If they cannot, then the correct equation is:Distance = 1/2 * gravity * time2


Guide:
print("This program calculates the distance a suspended object falls","given a gravity and time")
# Get gravity from user
# Convert string to int
# Get fps from user
# Convert string to int
# Get number of frames from user
# Convert string to int
# Calculate time object is falling
# Calculate distance in pixels objecthas fallen
print("It will drop", distance, "pixels in", time, "seconds")   # Output time to user
