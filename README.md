## Test: "smoke" test of the CyberBlitz under the Windows 7 operating system
### Team_E(xcellence) G. Broughton, B. Heath, T. Womack
### 10/24/17
### Ver. 0.8
* Test Case ID: 
  * 001
* Test Case Name:
  * Test Case 001 - "smoke" test of the CyberBlitz under the Windows 7 operating system
* Component: 
  * The build that tests this version of the game on Windows 7 in a standalone environment.
* Test Case Designer:
  * Travis Womack
* Creation Date:
  * 10/17/2017
* Modified By:
  * Travis Womack
* Modified Date:
  * 10/24/2017
* Requirements Covered:
  * Install, Load Start Install game on PC
  * Main Menu (02_MainMenu) Main Menu and all buttons function
  * Game Setup (03_GameSetup) Player selection and Match Settings buttons work correctly
  * SA Neon Arena (04_NeanArena) Game plays on this arena
  * Lumnos Cave Arena (05_CaveArena) Game plays on this arena
  * Asian Arena (06_AsianArena) Game plays on this arena
* Test Description/Purpose:
  * Install and run the game from the provided 'build' file folder
  * Main Menu test the button functionality ab navigation of this scene
  * Game Setup - This scene consists of two full sized panels
    * First "Chooze Your Blitzer" to imput palyer setup options
    * Second "Match Settings" to enter match options.
  * SA Neon Arena (04_NeanArena) - show camera animations, appropriate UI, show match time move avatars in response to player input.
  * Lumnos Cave Arena (05_CaveArena) - show camera animations, appropriate UI, show match time move avatars in response to player input.
  * Asian Arena (06_AsianArena) - show camera animations, appropriate UI, show match time move avatars in response to player input.

* Pre-Test Conditions:
  * The first version of the game wuill run on Windows 7 in a standalone environment.  The tests will occure on 'builds' downloaded and installed on the test machines.  The Waffle Group used the Unity game engine to develop this application and as such provides the drivers to run the game in under Windows 7 (professional).

The testing will occur in a class room environment using PCs running the Window operating system.
## Test Steps: 
#### Install, Load Start Install game on PC
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Install game | Zip file extracts without errors - data file and exe in taget location | √ |			
| 2 | Sart/load game | Double click on exe -after splash screen ask user for display options then starts game load scene | √ |		
| 3 | Load->Main Menu | Main Menu laods after 5 seconds or user clich (which happens first)| √ |

####  Main Menu (02_MainMenu) Main Menu and all buttons function
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Play       | Go to the game setup scene (03_GameSetup) Player setup Panel | √ |			
| 2 | Quick Play | Go to the default scene (Cave Arena) and play the default match | √ |			
| 3 | Controls   | Drops a "Help" panel that explains the controls | √ |			
| 4 | Settings   | Drops a Settings panel that allows the user to change some settings | √ |			
| 5 | Credits    | Drops a panel with game credits and copyrights | √ |			
| 6 | Quit       | Exits the application | √ |			
#### Game Setup (03_GameSetup) Player selection buttons work correctly
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Players shown            | Display the default number of players as a function of detected controllers | √ |			
| 2 | Click on Player header   | Change weather the avatar get controlled by the user or the computer | √ |			
| 3 | Click on Players picture | Change the player's avatar. | √ |			
| 4 | Select drop down         | Change the controller used to control the avatar | √ |			
| 5 | Click on 2 or 4 players  | Change between two and for players | √ |			
| 6 | Click on Main Menu       | Go back to the Main Menu | √ |			
| 7 | Click on Next            | Go to the Match Settings panel | √ |			
#### Game Setup (03_GameSetup) Match Settings buttons work correctly
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Display | Display the default arena, balls and match time.       | √ |			
| 2 | Click on balls | Allow the user to select or deselect the match balls | √ |			
| 3 | Click on time arrows | Allow the user to increase or decrease the match time | √ |			
| 4 | Click on Arena | Allow the user to select the arena to play | √ |			
| 5 | Click on Blitz | Go play game in selected arean | √ |			
| 6 | Click on Back | Go back to the player setup panel | √ |			
#### SA Neon Arena (04_NeanArena) Game plays on this arena
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Scene Loads | Start with a camera animation and end focused on the playing surface in the Neon Arena       | √ |			
| 2 | Game Display | Display the proper UI for the number of players | √ |			
| 3 | Game Display | Start the match and match clock | √ |			
| 4 | User input - Keyboard mouse or controller | Play the game | √ |			
| 5 | Esc key or Pause button | Pause the game and drop a Pause panel that allows (Resume, Main Menu, Controls andSettings) | √ |			
| 6 | Time == 0:00 | Display score and game over panel at end of match (Main Menu, and Play again) | √ |			
#### Lumnos Cave Arena (05_CaveArena) Game plays on this arena
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Scene Loads | Start with a camera animation and end focused on the playing surface in the Cave Arena       | √ |			
| 2 | Game Display | Display the proper UI for the number of players | √ |			
| 3 | Game Display | Start the match and match clock | √ |			
| 4 | User input - Keyboard mouse or controller | Play the game | √ |			
| 5 | Esc key or Pause button | Pause the game and drop a Pause panel that allows (Resume, Main Menu, Controls andSettings) | √ |			
| 6 | Time == 0:00 | Display score and game over panel at end of match (Main Menu, and Play again) | √ |			
#### Asian Arena (06_AsianArena) Game plays on this arena
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Scene Loads | Start with a camera animation and end focused on the playing surface in the Asian Arena       | √ |			
| 2 | Game Display | Display the proper UI for the number of players | √ |			
| 3 | Game Display | Start the match and match clock | √ |			
| 4 | User input - Keyboard mouse or controller | Play the game | √ |			
| 5 | Esc key or Pause button | Pause the game and drop a Pause panel that allows (Resume, Main Menu, Controls andSettings) | √ |			
| 6 | Time == 0:00 | Display score and game over panel at end of match (Main Menu, and Play again) | √ |			

## Overall Test Status:
Main Menu Cyber Blitz appears over all drop downs - minor bug


## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 06, Nov. 2017 | T. Womack | Pass with minor bug (see above) |			
| 2 | | | |			
| 3 | | | |	

