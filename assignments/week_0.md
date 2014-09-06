## Week 0 Assignment

Welcome to Introduction to Web Development!  This first assignment is just going to be geared toward helping you set up your environment on your computer so that you will be ready to hit the ground running with writing HTML and CSS.

### Installing Sublime Text

To write HTML, CSS, and code in other languages we use an *editor*, which is a tool that makes writing and reading code easier.  Just like it is easier to write essays in Microsoft Word than it is to write them in Wordpad / TextEdit, it is easier to write code using an editor than to write code with Notepad (doesn't really have a Mac equivalent).  The editor that we are going to be using is called [Sublime Text](http://www.sublimetext.com/3).  Please install it.

When you open Sublime Text you will see that it has a really minimalist interface - there are no toolbars, and it just opens an empty tab for you to start writing code.  Sublime Text is highly customizable, and we will be making just a few of these customizations.  You can feel free to read more about Sublime Text online and customize it as much as you'd like.

Sublime Text is currently a free product, but they still want you to purchase a license to support them, so they will nag you from time to time.  Feel free to close any popups you get from them (a message will appear on every 20th `File > Save` or so).  To get rid of these messages quickly just tap the `escape` key and the window will vanish.  You will also see the word UNREGISTERED in the corner to indicate that you have not purchaseFd a license.  Again, not purchasing a license will not affect your ability to use the software - the license is (as of now) entirely optional and is really a token of support / appreciation of the product.

Please remember that Sublime Text is not essential to writing code or building websites - it is just a convenient editor for writing code.  Don't think it has any special functionality that somehow makes websites run - it doesn't.

Next you should install the [Package Manager plugin](https://sublime.wbond.net/installation).  Instructions for installing it can be found on the linked page.  Try the "simple" approach before the "manual" one.

The shortcut `CMD-SHIFT-P` or `CTRL-SHIFT-P` will open up Sublime's "Command Pallete."  Once you have package manager installed you should be able to select "Package Control: Install Package" as an option.  To see this option start typing its name and it will quickly float to the top.  Select this option and you can see all the packages / plugins available to you that you can add to Sublime Text.  Please add the `SideBarEnhancements` plugin.

To open a file or folder with Sublime Text, you should be able to just drag it over the application's icon (you can also use `File > Open`).  Feel free to customize the color scheme using `Sublime Text > Preferences > Color Scheme`.

### Testing some HTML

We want to make sure that you can get HTML to display correctly in a browser on your machine before we start really diving into it next week.  First, create a new folder that will hold all your work for this course.  Then copy the code below into Sublime Text and save the file as `homepage.html`.
```
<!DOCTYPE html>
<html>
  <!-- This is my first webpage! -->
  <head>
    <title>My Website</title>
  </head>
  <body>
    <h2>Welcome to my site!</h2>
    <p>
      This site will be updated soon.  Prepare for something amazing...
    </p>
  </body>
</html>
```
Once you've saved it, exit Sublime Text and double click on the file.  It should open in a web browser and you should see something like this:
![My Website](http://cl.ly/image/23392X1I2S22/Image%202014-09-06%20at%206.13.18%20PM.png)

This completes the assignment.  Please email daniel.dickstein@yale.edu if you have any questions, comments, or concerns.  There is no need to turn in your `homepage.html` file.
