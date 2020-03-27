# Synitheia Prototypes

A habit-forming application prototyped on **Figma** by Team 2 (Nicole Vavrukh, Erica Ho, Grace Luo, Kassymkhan Bekbolatov, Harry Cui)

The target file for this Readme.md can be found [here](https://github.com/Kassymkhan919/Synitheia/blob/master/README.md)

## Getting Started

The below steps will get a copy of the project running on the browser.

### Steps

* Navigate to the prototype’s link (found in the subsection of this document) to open the project file. No download or installation of the project is necessary. Internet connection and a Figma account are required

* The link will open the prototype’s start page. 

* Explore the available options on the screen. Pressing any part of the screen highlights available options in blue:

![Interactions highlighted in blue after click](https://i.imgur.com/bF9csBT.png
"Hotspot Highlight")
<br>
Figure 1: Hotspot Highlighting in Figma

### Navigation Notes

Several items to consider while navigating through the prototypes:

* __Text boxes__ are rounded grey boxes. Typing interactions were not available on Figma. To “type” into a text box, click on the text box and the interaction will be simulated with the correct information.

![Grey text box](https://i.imgur.com/r8qFPXr.png
 "Text box")
 <br>
Figure 2: A text box

<br/>

* __Back buttons__ bring users to the prior screen if cancelling an action. Due to Figma’s constraints on the interaction feature, the back button may not show the expected page. The issue is a rare occurrence to be aware of.

![Back button](https://i.imgur.com/RQzW9Hh.png
 "Back button")
 <br>
 Figure 3: A back button

<br/>
<br/>

## Horizontal Prototype

This prototype can be found [here](https://www.figma.com/proto/0OSdUWi3Fc56jVILHRzNYm/Horizontal?node-id=432%3A1391&scaling=scale-down) (shorturl.at/pHT34)

### Start Screen
![Horizontal starting screen](https://i.imgur.com/zKbUA2V.png
"Starting Screen")
<br>
Figure 4: Horizontal Start Screen

If the above is not what opens after clicking the link, use the arrows found directly below the prototype to navigate to this screen.

### Sequence of Tasks Executed by User

1. Login
   * Enter login and password by clicking on the corresponding fields
   * Press the Login button
   
<br>

2. Check-In Tennis Practice
   * Press yes to check-in
   
<br>

3. Add Habit 
   * *I want to...*: Click on text field and select read everyday
   * *I plan to...*: Click on text box to fill in
   * Click on ‘Select’ drop-down
   * Click on weekly option for check-in 
     * Select Monday
   * Choose the book icon and click next
   * Select ‘Scan in calendar’ and take photo
   * Found Time screen
     * Select any times between 11am-1pm on Sunday
     * Select any times between 12am-1:30pm on Tuesday
     * Proceed 
   * Select ‘no thanks’ when prompted to set up reminders
   
<br>

4. Click on sleep early and use arrows to swipe through cards
   * Swipe to Diet
     * Click on notification bell to view notification settings for the habit 
     * User should be able to edit their notifications here however such interactivity has not been implemented in this prototype
     * Click the Back button to go to home page
   
<br>

5. Community 
   * Search 
     * Click on the search bar to fill in and search for ‘Advice on weight loss’ 
     * Go back
   * Communities
     * Click on the ‘Sports and Exercise category’
     * Click on the search bar to fill in and search for ‘Advice on weight loss’ 
     * Go back
     * Select the second post: ‘Advice on Weight loss activities??’
   * Advice on weight loss post
     * Add a comment under the post by clicking on the plus button in bottom right corner
     * Click on text box to write comment and press return on keyboard
     * Submit
     * Go back
   
<br>

6. Calendar 
   * Select the calendar icon in the bottom navigation bar
   * Select between Carrot, Book and Trumpet icons to view streaks
   * Navigate back to Home screen
   
<br>

7. Settings
   * Select settings icon 
   * Drag toggle button to preview night mode and drag back to return to light mode
   
<br>

8. Completed habits
   * View completed habits by tapping on trophy icon

<br/>
<br/>

## Vertical Prototype

This prototype can be found [here](https://www.figma.com/proto/c9NGarXAzAXSp0dCksAqlE/Vertical-add-habit?node-id=173%3A408&scaling=scale-down) (shorturl.at/czJQ0)

### Start Screen
![Vertical starting screen](https://i.imgur.com/JE3H5EZ.png
"Starting Screen")
<br>
Figure 5: Vertical Start Screen

If the above is not what opens after clicking the link, use the arrows found directly below the prototype to navigate to this screen.

### Vertical Tasks

* User checks into a pre-existing habit goal
* User creates a new habit goal

### Sequence of Tasks Executed by User

### How Vertical Is the Prototype?

WIP

**Checking In**
* If user checks in and presses "No" on the prompt...
  * If it's the final check in, send a prompt asking if user would like to push back deadline by 2 (two) weeks
    * If user agrees,  send a confirmation and push deadline back by 2 (two) weeks and modify progress accordingly
    * If user does not agree, send a confirmation and delete the habit goal
  * If it's a regualar check in, send an encouraging message meant to motivate the user and **do not** increase progress for the habit goal

* If user checks in and presses "Yes" on the prompt...
  * If it's the final check in, send a "Congrats!" message and move the habit goal into Completed section
  * If it's a regular check in, send a confirmation message and increase progress for the habit goal appropriately

**Creation of habit goal**

*When user starts creating a habit:*

* If user does not type a title for the habit and scrolls downwards, the title textbox's outline becomes red with a helpful message below
* If user does not put in information about habit in the description box, the textbox's outline becomes red with a helpful message below
* If user does not choose the regularity of the habit, the icons will turn red with a helpful message below
* If user does not select the day(s) to complete the habit, the buttons' outlines will turn red with a helpful message below
* If user does not select the habit icon and presses they greyed out Next button, an error message appears with a helpful comment

*On the calendar integration screen:*

If user chooses to integrate their calendar...
* If user does not select time to get notifications then the button "Done" will be greyed out and an error message will appear with a helpful comment when pressed
* If user unselects all available time slots found then the button "Done" will be greyed out and an error message will appear with a helpful comment when pressed

If user does not choose to integrate their calendar...
* A prompt asks if user wants to get notifications
  * If user presses "yes", they can manually select notification time
  * If user presses "no", redirect to completed addition prompt



