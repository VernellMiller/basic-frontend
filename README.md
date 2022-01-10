# VS CODE Tutorial

<Strong>VS CODE basics and Setting up a basic FrontEnd Project:</Strong> <br>

    Now that we are in our editor VS CODE, lets take a quick look around.

<Strong> Editor: </Strong>

    This large open space in front of you is called the Editor. As you could probably guessed, this is where you will edit your code once you have created your files.

    Here on the far left is your Activity Bar.
    
<Strong> ACTIVITY BAR: </Strong>

    Everyone's activity bar might look a little different depending on the Extensions that are installed. We will talk more about extensions in a moment. For now, lets talk about the first icon you see in your activity bar. The Explorer.

<Strong> Explorer: </Strong>

    EXPLORER is used to browse, open and manage all of the files in your project.

    If you click on your EXPLORER icon it will open up and display all the files you have in your project.

    Now since we're not working on any particular project right now. This is a great opportunity to start a project and the project we are going to create is our very first basic Frontend Project.
 
## <font color="#FD6F47"> <Strong > Does anyone have any questions? </Strong> </font>

<br>

## <font color="#37CB97"> <Strong > OK, GREAT </Strong> </font>

<br>

<Strong> FRONTEND PROJECT SETUP: </Strong>

    Now, if you notice here in your explorer, it tells you that you have not yet opened a folder. Folders are also called Directories and typically you would begin a project by creating your directories and files from your terminal. However, today we are just going to click on the open folder button.
  
    This will open your computer's file explorer and here you can also create your directories and files.
  
    Lets start by navigating to your desktop and creating a new directory called whatever you'd like. I'm going to call mine basicFrontEnd. 
  
    Now go ahead and select that directory and notice in your VS CODE EXPLORER, it displays your project and all of its files.
  
    For right now you just have the directory that you created.

## <font color="#FD6F47"> <Strong > How's everyone doing with that? Any questions? </Strong> </font>

<br>

## <font color="#37CB97"> <Strong > OK, GREAT </Strong> </font>

<br>

    For a basic frontend project you will need to set up 3 files:
        - HTML
        - CSS
        - JS
    
    HTML - is a HYPER TEXT MARKUP LANGUAGE and its one onf the most basic building blocks of the web.

    We will talk more in depth about HTML but for now lets create an html file.

    If you hover over the directory that you created, 4 icons will pop up on the right of the file.

    The first one is for creating a new file. Click on new file and create a index.html file.

    This will display your html file in the editor and we can write html here.

    Notice down in your status bar it also displays the language of the file you are currently working in.

## <font color="#FD6F47"> <Strong > Any questions? </Strong> </font>

<br>

## <font color="#37CB97"> <Strong > OK, GREAT </Strong> </font>

<br>

<Strong> HTML: </Strong>

    As I referenced before HTML is the standard markup language of a web page.

    It consists of a series of elements that tells the browser how to display the content on the page.

    Lets explore this a little further by setting up the HTML boiler plate.

    This can be done in many ways. Lets try typing "html" in your html file. Notice that VS CODE will try to help you by using its Emmet Abbriviation to predict what you are trying to do. In this case, we want the html 5 boilerplate. So after typing "html" you can click on or arrow down to "html:5" and hit tab or enter.

    We now have our html boiler plate.

    Again we will go further in depth about HTML but for now lets focus on the head and body elements.


<Strong> HTML ELEMENTS: </Strong>

    Elements are written with opening and closing tags.

    Example: For the body element here is the opening tag and here is the closing tag, and everything written in between those two tags are considered a child of this parent tag.

## <font color="#FD6F47"> <Strong > Any questions? </Strong> </font>

<br>

## <font color="#37CB97"> <Strong > OK, GREAT </Strong> </font>

<br>

    Lets write your first HTML ELEMENT.

    In between the opening and closing body tags create a header tag by typing h1.

    The Emmet Abbreviation will assist you again and you can select the h1.

    It will then place your courser in the middle of that h1 element and you can begin writing what is called the innerHTML of an element.

    Lets type Hello World and save.

## <font color="#FD6F47"> <Strong > How's everyone doing with that? Do you have questions? </Strong> </font>

<br>

## <font color="#37CB97"> <Strong > OK, GREAT </Strong> </font>

<br>

<Strong> RECAP: </Strong>

    Up to this point we have created a:

        1: Project
        2: A directory in our project
        3: A HTML file in that directory
        4: A HTML Element in that HTML file.

    With everything that we've done so far we are now at the point where we should be able to view our content on or local server. We can do this by installing the LIVE SERVER extension.

<Strong> Extensions: </Strong>

    I mentioned extensions earlier and if you look in your ACTIVITY BAR on the left, here is where you can find the extensions for VS CODE. Lets take a look.

    Here oyu will see all of the extension you have installed or extensions that VS CODE recommends.

    Lets search for LIVE SERVER.

<Strong> Live Server: </Strong>

    LIVE SERVER - is an extension that allows you to launch a development local server, with live reload feature for static and dynamic pages.

    Lets go ahead and install LIVE SERVER.

## <font color="#FD6F47"> <Strong > Does anyone have any questions? </Strong> </font>

<br>

## <font color="#37CB97"> <Strong > OK, GREAT </Strong> </font>

    Once installed you can verify this by looking down in your status bar athe the botome of VS CODE. You should see a "GO LIVE" button.

    Click on that and it should open up in your browser.

## <Strong > Hello World! </Strong> </font> 
    
    Give a quick thumbs up once you have your LIVE SERVER installed and you can see Hello World in your browser.

    We will move forward once everyone has it.

## <font color="#37CB97"> <Strong > OK, Congrats </Strong> </font>

<br>

# Next Steps: Adding CSS and Javascript

<Strong> Internal vs External: CSS and Javascript </Strong>

    There are 2 ways you can add CSS and JavaSCript to your project. There is Internal CSS: Where you can add style attributes to your elements.

    Like so: Add background color to body

    You can also add Internal JavaScript by adding script tags at the bottom of your body element.

    Like so: add script tags to body and alert JavaScript is working.

    However I prefer to use External CSS and JavaScript files.

## <font color="#FD6F47"> <Strong > Does anyone have any questions? </Strong> </font>

<br>

## <font color="#37CB97"> <Strong > OK, GREAT </Strong> </font>

<br>

<Strong> External CSS: </Strong>

    Lets start with External CSS

    CSS (Cascading Style Sheets) - Is the language used to style an HTML Document.

    To create an external css file you need to:
        1: create a css directory.
        2: create a styles.css file in your css directory.

    You can do this by Clicking on the second icon called new folder in explorer and name it css.

    Now click on that css directory and add a new file to it called styles.css.

    Notice you now have a styles.css file inside a css directory inside your project directory.

    And the last step is to link your styles.css to your index.html file.

    navigate to your index.html file and inside the head element under the title element you can Link your css by:

        1: typing link and selecting link from the Emmet Abbrevations.

        2: In the href attribute you want to go one level into your project by typing ./

        then select your css directory

        then select your styles.css file.

    What I like to do is go into my styles.css file and change the background color to make sure that I have link the files properly.

    Lets try it out.

    Navigate to your styles.css file and change the background color.

    We will talk more in depth about css syntax another time but for now try this out.

## <font color="#FD6F47"> <Strong > How's everyone doing with that? Do you have questions? </Strong> </font>

<br>

## <font color="#37CB97"> <Strong > OK, GREAT </Strong> </font>

<br>

    Now lets do the same for your JavaScript file.

<Strong> External JavaScript: </Strong>

    JavaScript is the worlds most popular programming language.

    We will talk more about JS in later tutorials but for now lets connect an external js file to your project by following similar steps taken in when you added your external css.

        1: In your project directory, select new folder and name it js.

        2: Inside your js directory, select new file and name it script.js

    Notice you now have a script.js file inside a js directory inside your project directory.

    navigate to your index.html file and inside the head element under the link element you can add your js by:

        1: typing script and selecting scsript:src from the Emmet Abbrevations.

        2: In the src attribute you want to go one level into your project by typing ./

        then select your js directory

        then select your script.js file.

    save the file and in your browser you should see your alert.

## <font color="#FD6F47"> <Strong > How's everyone doing with that? Do you have questions? </Strong> </font>

<br>

## <font color="#37CB97"> <Strong > OK, GREAT </Strong> </font>

<br>

# <Strong> THE END <Strong>  

















