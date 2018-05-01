# Connect4: A jharon Project

##Intro and Motivation

I've just finished off my last year of study of Computer Engineering at Queen's university and between job searching and "vacationing" I've been getting a little bored quite frankly. Seeing as I dont want this expensive degree to go to waste I figure might was well develop a software project to keep myself entertained, brush up on some old skills and hopefully learn a few new ones: I've decided to make a simple Connect4 game.

Preferably I want to keep this project as original as I can so I wont be directly following any step by step guides on building a particular Connect4 application but I probably will end up looking at some guides to work on particular modules I am less familiar with (i.e. programming AI, Using visual C++/C# ect ...).

###Approach

I will be programming this in C++ partly because its my favourite language and partly because a lot of the resources I've found online are assuming Cpp.

The IDE I will be working with is XCode, mainly because I'm developing on a Mac and I find it to be a pretty good free compiler all things considered.

I will also attempt to apply good SWQA unit-testing procedures after each phase of the project to ensure things are working correctly and doing my due dilligence for the overall quality of the project. For each particular unit test an input for the program will be written along with an expected output. These will all be kept in the "tests" folder with thier associated batch script file to run and compare the actual output with expected output.

##Objectives & Requirements

I will be attempting to follow a high level requirements list to give an order as to what needs to be developed next. This list may change through development.

###Phase 1: Get a Basic Game Working
- Develop a Connect4 grid class for the game to be played on
- Store the class on the heap (I'm not sure this is necessary but why not since I havent done this in a while) and have appropriate constructors and destructors for this
- Within the Connect4 Class have functions for legal moves and win checking
- Have a main menu to select either a 1 or 2 player game (Only 2 player for now since AI will be developed in the next phase) or to exit the program
- CMD line is cleared and Connect4 Grid is displayed on the command line interface
- User inputs a number to indicate which column they want to drop thier piece and program performs a Win Check


### Phase 2: Develop an AI
- Develop a Easy, Medium, Hard and Impossible AI to be selected from a 1 player game
- Each of these difficulties could be thier own classes, storing likely next moves and having functions that return choices to be input into the Connect4 game
- This may be a little tricky to implement on my own so I may have to read up on Connect4 strategy guides and derive logic from them

### Phase 3: Add on Extras
- Use arrow keys to change cols and spacebar to drop a piece
- Add ability to save games to a text file and load save games
- Completed match history stored in a text file for possible data analysis later on (i.e. pie chart displaying won games, user's favourite opening moves ... This could be linked to the AI for it to predict where the user will go next)

### Phase 4: Make a Desktop Application
- Use the SDL tutorial linked below to develop a windowed application for Mac

### Phase 5: Possible Stretch Goals?
- Make this into a web application and host it on a personal website
- Make this into an iOS app to be downloaded and hosted on iPhones

##Resources Used
I will be posting links to resources I've used during the course of development below. This will most definitely be changing as I run into walls or things I dont know:

1. [Atlassian Git Commands](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)	Because I really need to practice my skills with Git ... (Just using the desktop app is way too easy!)
2. [John Gruber's Markdown Syntax Guide from Daring Fireball](https://daringfireball.net/projects/markdown/basics)	Because Markdown is such an enigma I must learn its secrets ...
3. Object-Oriented Programming in C++: Second Edition be Robert Lafore	 Because I happen to have the book with me so might as well use it as I get stuck
4. [Lazy Foo's SDL Tutorial](http://www.lazyfoo.net/tutorials/SDL/index.php)	Because in later phases I probably want to make a desktop appication