
4/22/2018:

Matt:  Working on getting inputs from the microbit in python to my machine using serialization.  If it provrs to time comsuming we willl collect our raw data using processing from our hardware.  I allso helped write a script that boots up our emulator for street fighter in the backround using pyautogui

Robert: Made UI call control via another function, and hooked that up to the combo scripts so that it can exectue combos when a certain wekintaor output is recived. Removed the control section from the UI so now the launch game is simpler and got the radio button character selector to pass a variable to the new separate control module. 



Week of 4/16/2018:

Robert: So I actually have been forgetting to fill out change logs because I wasn't paying attention to group texts, but you can ask my group memebers, I have been doing my fair share of work for sure. This week I moved the control into the python UI and made the part that takes wek input launchable from the UI. Partially solved backlog problem from last week, but failed to implement a break in the infinite loop of the control script.  

Matt:  Worked on writing combo scripts for differnt characters in street fighter 2.  

Link to video of testing two different Ryu combos: https://youtu.be/mlgFNF2yPGg 

Also helped Robert and Tanner with launching the application to run street fighter from within our tkinter GUI, but most of that work was done by Robert and Tanner.

Nick: Working on a multi-level gesture recognition model using two instances of Wekinator. The first instance classifies basic gestures and sends the classifier outputs to the second instance of wekinator. The second instance of Wekinator takes the basic gesture classifications as inputs, then uses DTW to distinguish multi-part gestures, which are made up of a combination of simple gestures. Simple gesture classification is working well. The multi-part recognition still needs some smoothing to eliminate noise.

Kevin: Created two new character scripts for Sagat and M. Bison. Was only able to get a couple moves for each character, as most of the combos could not be accurately triggered. The combos that were created work pretty much 100% of the time.

Week of 4/9/2018:

Robert: made Microbit talk to the Wek, and then fed the Wek into python. Had issues with pace in each of the programs that remained unresolved. 

Matt: Lots of testing for scripts and other softwares to reproduce the fireball combo in street fighter 2

link to youtube update on combos: https://youtu.be/_QDbjUIh3ug

Kevin: Found new emulator to allow keypresses to be used as input. Now able to use street fighter as our main game. Attempted to also make scripts for street fighter by using real life keyboard timing presses and delays in input, but was unsuccessful doing so. Will finish Myoband mapping if it has not been finished yet. Successfully executed combo with script.

Updates as of 4/1/2018:

Proof of concept has been implemented; it consists of controlling game input and performing a combo in Super Smash Bros with Python.

Nicholas Fentekes researched into methods of implementation; found that controlling keyboard and mouse input directly with 
a Python library, pyautogui, would be a more versatile implementation than hard coding for specific games or emulators.

Matt Kaiser, Tanner Quigley, and Kevin Flynn implemented the proof of concept program, demoing a combo move innitiated with Python.

Robert Perez designed and created a UI.

The youtube video is gameplay where we have code complete combo moves and defeat a level two opponent.

The ability of the bot for comboing moves is reason for us to believe this goal is achieveable to then use a piece of hardware to trigger combos and make the game usuable for persons who do have have the ability to use a keyboard or game controller.

Tanner: Made basic script to control python with osc. Launch chrome within UI

youtube video link: https://youtu.be/Pnx7VfZEdAQ

4/24

Tanner: Refactored OSC code to work on my comp with other Library.

