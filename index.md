## Welcome to My Github Blog

This is my third time revisiting coding and the software engineering space. I started in 2017 with a full stack course on udemy and after that I received a google scholarship and certification in 11/2018. I took a job in another country at the end of that year which put a pause to studying for little over a year. I came back to the US in 01/2020 and started studying again until 08/2020 when I started working again in another industry. After working in another industry for 9 months so far I can clearly see that tech is the far better option for a longterm career.

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

The goal is to repitiously use the command line basics to move around the computer and I have outlined some basic commands to use. 

    1. `cd / cd ../`    
        - will change the directory or file
    2. `open index.html`  
        - will open a file
    3. `ls or ls -a` 
        - will list the folders/ directories/ apps/ 

##### side note
absolute path :/Users/romebell/Documents/profile.png
vs 
relative path : Documents/profile.png

Lets make a directory and add files

1. `mkdir Car_constructor` 
    - creates a F1 Constructors folder
    - cd into the directory

2. `touch drivers.txt`
    - creates a drivers text file

3. `cp drivers.txt salaries.txt`
    - copies drivers file and renames the new file to salaries

4. `ls` 
    - shows me all the files in the directory
    - should show drivers.txt and salaries.txt

5. `rm salaries.txt`
    - delete the salary file from the directory
    - will permanently delete file. 

6. `code drivers.txt`
    - open VS to add information to the file

7. add a list of drivers to drivers.txt
    - copy -> paste -> save

   * [name: Molik Kidd, number: 22, team: Mclaren], 
   * [name: Lewis Ham, number: 44, team: Mercedes], 
   * [name: Rome Bell, number: 77, team: Red Bull]

8. `cat drivers.txt` 
    - open the file and view the contents in the terminal

9. `echo "adding more information about the drivers salaries later" > costcap.txt`
    - write this phrase and add it in the file called costcap, budget cost for the season. 
    - If the file doesn't exist then it will be created.

10. `cat drivers.txt | sort > sorted_drivers.txt`
    - open the file add a pipe so that you can choose which filter use. the sorted filter sorts the contents in alphabetically order.
    - then add your contents to a sorted_drivers file. If it doesn't exist then it will be created.

11. `cat drivers.txt | grep Mclaren`
    - open the drivers file and search for all the files that have Mclaren in the text.

#### Follow the link below for more helpful tips and tricks on command line shortcuts. 

[Command line short cuts](https://github.com/0nn0/terminal-mac-cheatsheet)

## GIT INTRO

We will be going over the basics of git and how to navigate through the application.

Git is the most popular platform used by the tech community to collaborate on projects, share code and display your personal portfolio to the world or anyone who is interested in your services. 

** We are going to focus on answering these questions. **

1. Define what a version control system does

    git hub would be your server comp. 

    **Situation**: Two people are working on a application together but from seperate computers and local servers. Both are making contributions to each version of the application. Its important to share code effeciently so They both submit their a version of the application to a main server computer (github) which will store and manage the versions from both parties.   

2. Describe why someone would want to use a version control system

    It would be easy to collaborate and share code with people from all over the world and all the changes will be tracked and managed. 

    Other VCS: 
    CVS
    Apache sub version : SVN
    Mercurial : written in python
    Monotone : written in C++


3. Describe git concepts such as pulls, pushes, merges, commits in layman's terms
    - pull : You are requesting/downloading data from a repository
    - push : You're pushing data to a repository
    - merges : moves the commits to the main branch
    - commits : is a snapshot of your repository

4. Identify main git commands to manage files

    `git init` adds a repository to your folder, which is a hidden file that connects to a remote repository. 

    `git add file` tells git which file you want to take a snap shot of then you take a snap shot with `git commit -m "short message about the commit"` then you send your snap shot to the main branch with `git push -u origin main`. Use `git status` along the way to check which branch you are on and if the file you're commited is added. Also use git revert if you run into issues when working with multiple collaborators. In dire cases you may have to use git reset to force the head branch to move to another point in time. caution you may lose data. 

    side note : use present tense when writing a commit message
        ex: update read me / remove two functions / add new color

5. Distinguish between local and remote repositories
    1. Local repo : your computers repos
    2. remote repo : on a remote server for all team members to access

6. Distinguish between git and GitHub
    - git is a version control system
    - github is a social network built around git

Basic git command line commands

    - You can have public and private repositories. 
    - make sure you have an up to date github account with relevant information and no nicknames since it employers will be looking at it. 

things to look out for: 
people may have an issue with their git password login
errors command not found

## DAY 2 HTML & CSS

a pull request is asking git hub to evaluate your code to see if its something you can add to the original code base....

#### Making a pull request ####
* click on pull request in the repository you're wanting data from.
* create pull request 

# HTML

Their are many analogies when it comes to HTML but the best one that I think that applies are bones as in the bones of a building, the foundation, beams and rebar of your application. Adding different attributes to your HTML page will function the same ways as adding walls, windows and doors to your structure. 

When you are setting up your HTML page, you must set your  `<!DOCTYPE html>` Declaration so that the web browser knows what type of information it should be receiving. doctype is supported in all browsers and is a basic setting for HTML.

## DELIVERABLE:

The goal for the exercise to recreate and HTML page from someone elses github. Its a simple page with an image in the header, titles and paragraphs with text. Two of the titles have different colors. Visit the link below to see the page.

`https://taylordarneille.github.io/finished-intro-demo/`

After viewing the page we are suppose to create, I inspected the page to see the html set up. I scanned the page from top to bottom. I saw clicked through the tags in the HTML file and copied them to my `index.html`. 

I saw in the HTML <head> tag that the page was linked to a CSS style sheet. 

`<link href="style.css" type="text/css" rel="stylesheet" media="screen">`

So I `touch style.css` then `ls` to check that it was added to the folder. I opened the style.css in the VS Code with `code style.css`. 

I went back to the example web page and in the inspector I selected the "Style Editior" to see what the CSS style sheet.

I copied and pasted the text in my `style.css`.
I went back to my HTML page and inserted the 
`<link href="style.css" type="text/css" rel="stylesheet" media="screen">` 
in my `<head>` tag

Went back and right-clicked the image --> saved it to the current folder. 
then added changed the path in the image tag

`<header>`
    `<img src="new-york.jpg" alt="New Zork"/>` 
`</header>`

Im having errors with the image tag. The image will not show in the browser. I have the img in the same folder as my index. I will update with a solution. I am sure its simple. 

---- Solution to img tag -----

## CSS SELECTORS Describe the syntactical and functional relationship between selectors, properties, and values
Style all elements of a particular HTML element on a web page
Describe the difference between class and id selectors
Describe the heirarchy (order of precedence) between tag selectors, class selectors, id selectors, and inline-styles
Demonstrate ability to include CSS inline, with a style tag, and from an external file
Apply styles to specific elements by selecting elements with classes and ids
Apply a set of styles to children of a specific class or tag

LECTURE NOTE

CSS : Cascading Style Sheets
determines how the browsers interprets your styling for your application. you're telling the browser what and how to style the application. The browser reads the page from top to bottom and the styling rules you have at the bottom are priority over the ones at the top.

You're mixing content with styling. Inline styling can cause errors with how the browser reads the page. Its not best practices to use inline styling often. 
`<body style="background: red;"></body>`

CSS is the styling for your application, its the color in the walls of your room, the roundness of your bathroom/ kitchen sink, the thickness or width of your your handrails on the stairs. 

You have to tag and name your attributes in html so that you can select them in CSS. Your HTML tags are `selectors` in CSS because you're selecting an attribute from HTML.  

As you're styling your application and adding different properties to your building. you want some elements that have the same styling `Class` like your windows on your house and others with unique styling `id` like your custom front door. Each property has a value associated with it that you can manipulate to your liking such as changing green to blue or the `width` of your refrigerator. 

    `selector {
    property_1: value_1;
    property_2: value_2;
    `}

    `#window {
        border: 1px solid black;
    }`

    `.door {
        background: green;
        border: 3px;
        height: 80px;
    }

you still have to link your CSS page to your HTML page and you would use the <link href="style.css" rel="stylesheet" content="text/css"/>

- a short cut for duplicating code

Select the code you want to mirror then use `shift + alt + down` arrow to duplicate a piece of code.

EXAMPLE CSS
```body {
    background: rgb(0, 217, 255);
  }
  
  p {
    color: orange;
  }
  
  div {
    border: 1px solid black;
  }
  
  .comments {
    font-weight: bold;
    color: #64FE2E; /* green */
  }
  
  #dolphin {
    font-style: italic;
    color: #0040FF; /*blue*/
  }
  
  .first {
    font-size: 40px;
  }
  
  .second {
    color: red;
  }```


