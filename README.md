# Matala3

This work contains a simulater that has robots that avoid obstacles and try to reach light in order to increase there battery life and find out there position because these robots do not know there position. There are static robots who are in the light which know there position and are able to send messages to a distance of a certain radius (inputed by the user). The static robots are ment to help the other robots reach light.

The idea in our work is that the regular robots try to find static robots. When this happens they can receive a message from the static robot telling them there position. Following that they will be able to find light at all times and continue to live. If a robot has died then it will send a message saying what he thinks his position is, relying on messages he received from static robots around him.


We included an input .txt file that contains: 

1) Width of arena, Heigt of arena

2) Number of obstacles (positioned randomly)

3) Number of lights (positioned randomly)

4) Number of regular robots (positioned randomly, not on obstacles)

5) Number of static robots

6) Battery life

7) Battery price of every step taken by a robot

8) Battery price of every pause in light

9) Radius of every message sent (based on a probabilty formula)

We have created a GUI that has different buttons:

1) [in tab 'file'] Open text file - used to get an input .txt file from the user

2) Start - drawes our arena including placing all regular robots and static robots

3) Next - does one turn.

4) [in tab 'file'] Next 30 steps - does 30 turns

5) [in tab 'file'] Next X steps - gives the user the option to input how many turns to do

6) [in tab 'file'] Save to CSV file - This is a button that creates an output. The output is composed of two things: a) Gives the user the log of all the robots in the current step as a .csv file. b) Gives the user the amount of dead robots and the amount of robots that found there position in every step.


Regarding the entities and relations in our project - view the ERD and UML diagram included. 



