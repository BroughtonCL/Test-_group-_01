# Test-_group-_01
We plan to run the following test cases on each build teseted:
#### Test Case 1 - "smoke" test of the CyberBlitz under the Windows 7 operating system

## Test Details

* Test Case ID:
  * #Number 01 
* Test Case Name: 
  * #Number smoke_01
* Component: 
  * Description
* Test Case Designer:
  * Name
* Creation Date:
  * Date 10/19/17
* Modified By:
  * Name 
* Modified Date:
  * Date
* Requirements Covered:
  * Description
* Test Description/Purpose:
  * DescriptionThe first version of the game wuill run on Windows 7 and 10 in a standalone environment. The tests will occure on 'builds' downloaded and installed on the test machines. The Waffle Group used the Unity game engine to develop this application and as such provides teh drivers to run the game in under Windows 7 (professional) and Windoes 10 (Home Edition).
* Pre-Test Conditions:
  * Description 
  Main Menu should  be able to load  and  display the  menu option . Levels  should be able to load  and  run .
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Main Menu|The game should have the opening scene and provide player options. The quick play should offer a default arena and match. The help option will explain the controls after which you have the quit option which will exit play. | |			
| 2 | Game Setup| The set up should allow the players to select characters, choose play areas, and  | |			
| 3 | SA Neon Arena| | |			
| 4 | Lumnos Cave Arena| | |			
| 5 |Asian Arena | | |			
| 6 |Install, Load Start | | |			
| 7 | | | |			
| 8 | | | |			
| 9 | | | |			
| 10 | | | |			


##### Install, Load Start
|Function |Expected results on Windows 7 OS PC                                     |
|---------|------------------------------------------------------------------------|
|Install game|Zip file extractw without errors - data fiela nd exe in taget location|
|Sart/load game|Double click on exe -after splash screen ask user for display options then starts game load scene|
|Load->Main Menu|Main Menu laods after 5 seconds or user clich (which happens first)|

##### Main Menu (02_MainMenu)
|Button   |Expected action                                                            |
|---------|---------------------------------------------------------------------------|
|Play|Go to the game setup scene (03_GameSetup) Player setup Panel |
|Quick Play|Go to the default scene (Cave Arena) and play the default match|
|Controls|Drops a "Help" panel that explains the controls|
|Settings|Drops a Settings panel that allows the user to change some settings|
|Credits|Drops a panel with game credits and copyrights|
|Quit|Exits the application|
##### Game Setup (03_GameSetup)
This scene consists of two full sized panels, the first "Chooze Your Blitzer" to imput palyer setup options and the second "Match Settings" to enter match options.
The Chose Your Blitzer panel should allow the user to do the following:
1.  Display the default number of players as a function of detected controllers
2.  Change weather the avatar get controlled by the user or the computer
3.  Change the player's avatar.
4.  Change the controller used to control the avatar
5.  Change between two and for players
6.   Go back to the Main Menu
7.  Go to the Match Settings panel

The Match Settings Panel should do the following:
1.  Display the default arena, balls and match time.
2.  Allow the user to select or deselect the match balls
3.  Allow the user to increase or decrease the match time
4.  Allow the user to select the arena to play
5.  Go play game in selected arean
6.  Go back to the player setup panel

##### SA Neon Arena (04_NeanArena)
This scene should:
1.  Start with a camera animation and end focused on the playing surface in the Neon Arena
2.  Display the proper UI for the number opf players
3.  Start the match and match clock
4.  Play the game
5.  Pause the game and drop a Pause panel that allows (Resume, Main Menu, Controls andSettings)
6.  Display score and game over panel at end of match (Main Menu, and Play again)

##### Lumnos Cave Arena (05_CaveArena)
This scene should:
1.  Start with a camera animation and end focused on the playing surface in the Cave Arena
2.  Display the proper UI for the number opf players
3.  Start the match and match clock
4.  Play the game
5.  Pause the game and drop a Pause panel that allows (Resume, Main Menu, Controls andSettings)
6.  Display score and game over panel at end of match (Main Menu, and Play again)

##### Asian Arena (06_AsianArena)
This scene should:
1.  Start with a camera animation and end focused on the playing surface in the Asian Arena
2.  Display the proper UI for the number opf players
3.  Start the match and match clock
4.  Play the game
5.  Pause the game and drop a Pause panel that allows (Resume, Main Menu, Controls andSettings)
6.  Display score and game over panel at end of match (Main Menu, and Play again)
## Overall Test Status:



## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | | | |			
| 2 | | | |			
| 3 | | | |
