# MG3
## Devlog
1. int - The default value is zero, which makes sense because you have to change the number yourself in the Inspector to set the integer value.

	float - The default value is zero, which makes sense because you have to set the number yourself in the Inspector. 

	bool - The default value is an unchecked box that you can check and uncheck, which makes sense because that demonstrates the true/false nature of the bool variable. Check = true, uncheck = false. 

	string - The default value is an empty text box that you can write whatever you need in, which makes sense because string is for text.

2. I write the Update method once in the code but the method is called every single time the frame of the game changes, which makes it useful for coding ongoing processes that happen while the player is interacting with the game. 

3. TimerText.cs uses the timer by associating methods that were defined in Timer.cs with the _gameTimer variable. I did this in the Start method by using the "." and calling BeginTimer. That took the method BeginTimer from Timer.cs in order to set the initial time which was 30 seconds. In the Update method, I called IsFinished from Timer.cs in the if statement to determine when to display the game over screen. So, calling IsFinished made the computer check whether the if statment in IsFinished would return true or false, and if it was true, then the GameOver method would be called, ending the game. So overall in TimerText.cs the timer was used to determine the starting and ending time of the game, establishing the length of the minigame.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)