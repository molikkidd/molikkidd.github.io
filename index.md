## Welcome to My Github Blog

## ORIENTATION
It was an over view of what the company has to offer their students. Their are many people who will support the students as they learn how to code. For the class size their are a lot people around who can help. Various people from different roles in the company spoke about their background and journey into the tech space. 
People from the arts, customer service, hospitality and many more have made the switch to and seem very satisfied with their choice. Amongst the students who spoke many are embarking on a career change so that they can change the directory of their lives. 

## INSTALL FEST
You are installing the necessary software so that we can run and test our applications. 

- depending on which system you are running the instructions will vary slightly in regards to how you install the software but the overall theme will be the same, which is using the terminal and command line. 

##### 1ST INSTALL
1. Slack
    * Will be used for communicating throughout the course. It is also used by a large section of the tech community as a spring board to network, post jobs and collab. 
2. Homebrew
    * It installs a directory on your computer then symlinks their files to the local user, so you can download and install other software and applications. 
    * Its a package manager, which means its a collection of software tools that automates the process of installing, upgrading, configuring, and removing computer programs
3. iTerm
    * A terminal app that you can customize and will be our new command line interface for Mac.
4. Oh my ZSH
    * Its a shell that we will use on top of iterm to help with the visual affects of the code. A shell is an interface to our computer.
5. VS Code
    * Use it to code in any programming language, without switching editors. 
    * Visual Studio Code highlights keywords in your code in different colors to help you easily identify coding patterns and learn faster
    * You can also use the debugger in VS Code to step through each line of code and understand what is happening
6. Git/ GitHub
    * Its a platform that allows people to collaborate on projects/ applications, while maintaining the histoy/workflow (version) of the code. 

## COMMAND LINE

* The instructor told us to get comfortable with using the terminal and command line a lot more because its more effecient to work from the command line. It involves less steps especially if you know where everything is. 

The goal is to repitiously use the command line basics to move around the computer and I have outlined some basic responses to use. 

    1. cd / cd ../  :  will change the directory or file
    2. open index.html : will open a file
    3. ls or ls -a : will list the folders/ directories/ apps/ 

##### side note
absolute path :/Users/romebell/Documents/profile.png
vs 
relative path : Documents/profile.png

Lets make a directory and add files

1. mkdir Car_constructor 
    - creates a F1 Constructors folder
    - cd into the directory

2. touch drivers.txt
    - create a drivers text file

3. cp drivers.txt salaries.txt
    - copy and rename a new file

4. ls 
    - shows me all the files in the directory
    - should show drivers.txt and salaries.txt

5. rm salaries.txt
    - delete the salary file from the directory
    - will permanently delete file. 

6. code drivers.txt
    - open VS to add information to the file

7. add a list of drivers to drivers.txt
    - copy -> paste -> save

[name: Molik Kidd, number: 22, team: Mclaren], [name: Lewis Ham, number: 44, team: Mercedes] , [name: Rome Bell, number: 77, team: Red Bull]

8. cat drivers.txt 
    - open the file and view the contents in the terminal

9. echo "adding more information about the drivers salaries later" > costcap.txt
    - write this phrase and add it in the file called costcap, budget cost for the season. 

10. cat drivers.txt | sort > sorted_drivers.txt
    - open the file add a pipe so that you can choose which filter use. the sorted filter sorts the contents in alphabetically order.
    - then add your contents to a sorted_drivers file. If it doesn't exist then it will be created.

11. cat drivers.txt | grep Mclaren
    - open the drivers file and search for all the files that have Mclaren in the text.
