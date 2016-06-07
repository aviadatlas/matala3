# Matala3

This work contains a simulater that has robots that avoid obstacles and try to reach light in order to increase there battery life. These robots do not know there position. There are static robots who are in the light which know there position and are able to send messages to a distance of a certain redius (inputed by the user). The static robots are ment to help the other robots to reach light.



We included an input .txt file that contains: 

1) width of arena, heigt of arena

2) number of obstacles (positioned randomly)

3) number of lights (positioned randomly)

4) number of regular robots (positioned randomly, not on obstacles)

5) number of static robots

6) battery life

7) battery price of every step taken by a robot

8) battery price of every pause in light

9) radius of every message sent (based on a probabilty formula)

We have created a GUI that has different buttons:
1) [in tab 'file'] open text file - used to get an input .txt file from the user
2) start - drawes our arena including placing all regular robots and static robots
3) next - does one turn.
4) [in tab 'file'] next 30 steps - does 30 turns
5) [in tab 'file'] next X steps - gives the user the option to input how many turns to do
6) [in tab 'file'] save to CSV file - gives the user an option to save the log of all the robots in the current step to a .csv file

Regarding the entities and relations in our project - view the ERD and UML diagram included. 



