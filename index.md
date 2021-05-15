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

### EXAMPLE CSS
    ```
    body {
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
    }
    ```

## LECTURE NOTES

* What is margin?

    * It is the area out side of the element. 
    * You can change the width and height of the margin to create or remove space around elements. It can also move the element as well. 

    * margin does not have a background color. 

    ```
        div {
            margin-top: 1px;
            margin-right: 2px;
            margin-bottom: 3px;
            margin-left: 4px;
        }
        or 

        div {
            margin: 1px 2px 3px 4px;
        }
    ```
* border
    * inside the element 
    * goes around the padding and content 

* padding
    * inside the element 
    * creates spacing between and around elements 

* content 
    * where your text and images appear
    * elements color property changes the text

## CSS BOX MODEL

You can inspect the elements of your web page by going to your settings and selecting developer tools then select the option for page inspection. 

Look through the HTML file and notice how many links to css and js files are on the page. Notice the different elements used and how they are used. You can also change css and html text in inspection mode. It will not be saved on their servers. 

## CSS GRID

The CSS Grid is self explainatory, its a grid like the grid paper you use to connect lines to make curves which lead to interesting designs like 4 pointed stars and 8 pointed stars and others as well, but we arent making stars. The cells of the grid can be added or separated to make larger or smaller grids. A group of cells in a row or column is called a track. 

You can name and tag your grids in HTML and customize them CSS the same way you would a normal element.

Examples

body {
    display: grid;
    min-height: 100%;
  }

<body>
  <header></header>
  <aside></aside>
  <main></main>
  <footer></footer>
</body>

body {
  display: grid;
  min-height: 100%;
  grid-template-rows: 200px 1fr 120px;
  grid-template-columns: 180px 1fr;
}  

header {
  grid-area: header;
}
aside {
  grid-area: sidebar;
}
main {
  grid-area: main;
}
footer {
  grid-area: footer:
}

### DELIVERABLE

Recreate a page from Airbnb using the flex - grid and css/html page provided in the css-airbnb/ 

1.) I cloned the deliverable from the class repository on github then I opened code index.html then cd css/style.css I looked at the solution.jpg to see how the finished page is suppose to look.

- Observation:

It looks like a grid a `column` with the content centered in the middle and it also has a button to see all the options. Their is another `row` grid of pictures with a text overlay. 

### Breakdown: Based off the sample

2.) I started by adding the necessary html elements I saw on the sample page . <h1>, <p>, <div>, <img> and <button>.

3.) I made two elements for the description/ picture/ button combination. I wrapped both of the sections in a container that I labeled class="item".

4.) I started working on the CSS stylesheet. Added to the css sheet. 

`    .item {
    display: flex;
    flex-direction: column;
    align-items: center;
    }`

which will take the div container .item container and center all its contents from top to bottom. 

5.) Added another grid for the photos which evenly spaced them through the container. I added padding around the to closely match the sample website. 

`    .photo_grid {
    display: inline-flex;
    justify-content: space-between;
    position: relative;
    padding-bottom: 2%; 
    padding-top: .5%;
    max-width: 70%;
    
    }`

6.) The photos were all different sizes but the ones on the bottom were larger than the top photos. I assumed it was a padding, margin or grid size issue, so I selected the img element in CSS and attempted to gave all the imgs the same height and width. 

    ``img {
    height: 500px;
    width: 400px; 
    padding: 20px;
        margin: 1px;
    }

    button {
    width: 400px;
    height: 3em;
    margin-bottom: 1%;
    border-radius: 0px;
    font-family: calibri;
    font-size:20px;
    }``

### Side Note
- Excellent website for Flex Grid
* http://flexboxfroggy.com/
* http://cssgridgarden.com/
* https://www.sketchingwithcss.com/samplechapter/cheatsheet.html


## JS ARRAYS/ OBJECTS/ FUNCTIONS

The best way to store information such as numbers, booleans, text is in an array. This allows us to grab the information for analysis and other computations. You can store arrays in a variable. Its like a tubberware container for your information. You can attach different methods to your variable to manipulate the contents. 

const friends = ['Joe', 'Bena','Ho'];
let afriend = friends[1]
=> 'Bena';

const favorites = "cars,travel,nature,goodfood,beaches";

Object.assign([], favorites);


## FAST FORWARD TO EXPRESS AUTHENTICATION


Do you remember the last time you used authentication?

We use authentication on a regular basis to login into our accounts online or game on your phone. You are inputting your user name and password into an application, the application will take your combination of strings and integers and search for a matching pair because your username and password are unique and AUTHENTIC to your profile. Once the password and username are found, the account is AUTHENTICATED. 

Why is authentication important?

It is important for security purposes because if you didnt verify information then anyone can acccess anyone elses information without restriction. Authentication is also important for locating profiles and accounts. How would you know who's account is who if you didnt verify that the username or password is linked to a specific user. 

We will be using Express JS to interact with our application. 

PASSPORT JS:
popular.
Authentication middle ware used in node. authenticates users and request, basically checking if the inserted information is valid before moving to the next steps of logging in.  

Their are many avenues or strategies we can use to authenticate our information, such as ....FACEBOOK, TWITTER, GOOGLE, GITHUB...

How many different ways are their to authenticate a user? "520"
go to passportjs.org

Passport-local:
we will be creating our own strategy to authenticate a user instead of the main stream google, fb and github methods. 

Express-Sessions:
We will be using sessions to keep users logged in. 
Once youre logged in, a cookie is sent to a user and everytime a user makes a request while logged in, that cookie is sent back to the application, in the process verifying the user every step of the way. NO COOKIE, NO ACCESS.  All companies do this process. 

Cookie : a string that will be passed back and forth. 
Some cookies have expirations. If you stay on a website too long then you may get a prompt asking if you're still there otherwise you will be logged out. 

Cookies can track your movement on websites and store the information which can be used for advertisements on other applications. For example, you have a couple tabs open in your browser and you're searching for workout supplements on Amazon. You scroll through a couple products and didnt find anything you where interested in, so you go back to the youtube rabbit hole of watching road rage compilations. Next thing you know, you have weight lifting supplements advertising showing at the bottom of your videos. 

The cookies from your amazon was tracking what websites/applications you have open in your browser, communicated with the application and placed an advertisement based on your searches from its site. 

Node.brcypt.js:

Do not store plain text passwords in your database. We store hash passwords in the database. bcrypt runs your password through a hash function that encrypts it into a set of characters that are hard to decypher. It is a lock on your proverbial door. 

BlowFish Cipher: is algorithm that will encrypt the information for you. 

FOLLOW THE INSTRUCTIONS ON THE README FOR INSTALLING YOUR APP.