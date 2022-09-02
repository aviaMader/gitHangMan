Hang Man
    * Description
        A game of Hang Man using python,
        the game starts with some requests from the user about his user_name, preferred figure wardrobe, preferred level and preferred theme,
        the word is being chosen randomly according to the user's preferred theme ,the number of clues are being determined by the user's preferred level,
        each iteration the user is requested to enter a single letter and print whether the letter exist in the word,
        in case the letter was wrong another part is added to the output of the gallows and the figure,
        after 7 wrong attempts (the human is fully hanging) the user gets notify about his failure and the round is over
        in case the user successfully guessed all the letters in the word currently the user gets notify about his success and the round is over,
        in the end of every round the user is asked whether he would like to play another game in addition the user's score is being calculated and stored,
        when the user decide to end the game his final score is calculate and inserted into its current position in the list of scores,
        afterwords the ten top player are printed.
    * Instruction
        - install Pyautogui module from pip 
            in some IDEs (like PyCharm) the option of "os.system('cls'/'clear')" isn't actually cleaning the output screen,
            in order to overcome this obstacle it's to install Pyautogui module,
            afterwords it's necessary to define the keyboard shortcut for "clear all" as 'alt'+'d'
            and then call pyautogui.hotkey('alt'+'d')
        - install Pyfiglet module from pip
            in order to print designed and enlarge output use this module,
            this is the way it's work: print(pyfiglet.figlet_format('the requested word',font = 'the font'))
    * Credit
        Hadar Sarusi
            [LinedIn - hadar-sarusi](https://www.linkedin.com/in/hadar-sarusi) ,[GitHub - HadarSarusi](https://github.com/HadarSarusi)
        Evyatar Baruch 
            [LinedIn - evyatar-baruch](https://www.linkedin.com/in/evyatar-baruch-0947a3244),[GitHub - aviaMader](https://github.com/aviaMader)