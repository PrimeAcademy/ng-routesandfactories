# Fictional Character High Five-Off

In this assignment, you'll be making a making an app to high five fictional characters. However, each fictional character's skill with high-fiving will be randomly generated. And each high five may or may not work!

You'll be using Angular Routes to display make a separate view for each of 3 different fictional characters of your choice. Your page should have a static header and footer of some kind, and 3 navigation buttons to swap out the content of the characters.

## Setup

Run `npm install` to get Express. Angular and Bootstrap are included.

## On each page:
Display a character image, their name, and something about them (ya know, it's good to have an introduction before high-fiving strangers).
Note: Feel free to use Google for the content or make up your own! Include some images and give it your best styling effort.

Have a button for the user to click to give the character a high five. When clicked, generate a random number to compare against the character's high-five skill.

Display a statement about many high fives the current character has received as a fraction of how many high fives have been given to all characters.

For example: "I've successfully made 4 of the 11 successful high fives!"
 
## High Five Logistics
Randomly generate a high-five skill for each character. Note: this will mean the characters' skills will be different each time the app is run.

When a user clicks to give the character a high-five, randomly generate the quality of that high five.  If the high-five quality => character's high-five skill, the high five is successfull.

If a highfive is successful, undate the highfive count.

You will need to find a way to share the total number of high fives across your controllers.
Make only one random number generator in your application instead of writing the random number generator in two different places for each controller (for the skill and the quality).

![](http://i.giphy.com/TEFplLVRDMWBi.gif)

## Hard Mode
Use ng-show, ng-hide, ng-if, or ng-animate to add some creative, dynamic elements to your views when users click on things.

## Pro Mode
Make the whole experience responsive with media queries or by using a library such as Skeleton or the built-in CSS3 option: Flexbox.
