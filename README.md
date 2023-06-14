**__Jordan's "Stay Under" Dev Progress__**
- Created Square game object that moves back and forth on a platform on screen and stays within the boundary of the camera
- Created rain using the particle system that triggers game over when the rain touches the square
- Created and umbrella for the player to control with their mouse to protect the square from the rain
- Created a Game Over Screen with "Play Again" and "Home" button that either restart the game or take you back to the Title Screen
- Created a Pause Game Screen that pauses the game when the escape key is pressed
- On the Pause Game Screen are buttons labeled "Escape" (which closes the program), "Resume" (which resumes the game), and "Home" (which brings you back to the title screen)
- Created a stopwatch in the top right corner of the screen that tracks how long the player can keep the square protected
- Created a High Score value for the game over screen that displays the player's longest time keeping the square protected
**__BUGS TO FIX__** 
- Able to pause the game while game over screen is active **(FIXED)**
- high score stays at 00:00 when game over screen is activated **(WORK IN PROGRESS)**
- After pressing the resume button on the pause screen it then takes two escape key clicks to pause the game again **(FIXED)**
- Stopwatch does not stop when the game over screen is active **(FIXED)**
- When the home button is pressed from the pause menu you must press the escape key to unpause the game **(FIXED)**
