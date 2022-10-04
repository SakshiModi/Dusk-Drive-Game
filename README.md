# Dusk-Drive-Game

A game called Dusk Drive is made with Python, which is completed using the Pygame library. The project file contains python scripts, image files, and sound files. The gameplay graphics are of high quality, and the controls are too simple for the users. There are only two keys needed to play the game - the left key and the right one. Also, there are two types of cars - the player car and the obstacle cars. Moreover, the game is programmed such that obstacle cars are randomly generated on different lanes.<br><br>
In this game, the player car needs to be dodged left or right to avoid collision with obstacle cars. The player has to be as quick as possible. Whenever the player touches the obstacles, it crashes, and the game is over which takes the player to the welcome screen. The main objective of this game is to avoid the obstacles. The gameplay design is so simple that the player won’t find it challenging to use and navigate.<br><br>
To develop this project, various operations were performed like the blitting of images, moving the cars and the road strips, crashing cases, sound effects, score calculation and random generation of obstacle cars on different lanes. 

https://user-images.githubusercontent.com/29822270/193432981-0b1f63f9-df43-4c9f-b02a-5b286e1b2dbc.mp4

There are two windows in the game - 
#### 1) Welcome Screen
Welcome Screen is the initial or the first window that opens at the very beginning. A message displayed on the screen asks if you dare to drive this car then press the enter button. This screen has its importance because there is a need for a screen from where the game starts and ends.<br><br>
The name of the game, i.e., Dusk Drive is also displayed on the welcome screen. To develop this screen different images are used like road image, car image and the message image.

<img width="372" alt="Welcome" src="https://user-images.githubusercontent.com/29822270/193433051-8ee5ad36-a6fe-49f9-b7c4-4b5d1711ee2c.png">

#### 2) Gameplay Screen
Gameplay Screen appears after an enter key is pressed on the welcome screen. This a dynamic screen as it has moving cars and road strips. This is the screen where a user dodges the player car to avoid the obstacle cars, but if the player car collides with obstacle car then a crash case is true and the game stops. So, all such operations are observed on this screen.<br><br>
The number of obstacle cars avoided by the player car is calculated to be the score. This screen also has sound effects - background sound and crashing sound along with high-quality graphics. Moreover, the obstacle cars are generated on random lanes, possible due to the random package imported in the project.

<img width="372" alt="Gameplay" src="https://user-images.githubusercontent.com/29822270/193433054-c5552309-5b49-423e-aa82-6c2431e5912e.png">

There can be many levels in this game -
1) Varying the speed of car.
2) Varying the number of obstacles and their speed.
3) Adding more effects and sound.

