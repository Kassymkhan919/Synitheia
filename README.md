# CMPT 376W Assignment 3
<br>

## Criteria
For this project, assume the reader has prior background knowledge of Computer Science and Prototyping. The goal of the README.md is to instruct the Professor and Teaching Assistants (TAs) on how to start the created prototypes. This file **must** include the team number and the full names of each member.
In the words of the Professor:
> "The README is just for helping us figure out how to run your project. It doesn't have to be too extensive.
>
> Since many of you are using different types of software and different versions, just make things easy for us and clearly state what you used. A lot of tools now allow you to generate a web-based link for your prototype so you can just share that, but again, make it clear which is the first screen we should be looking at."

This differs from the rubric given for CMPT 376W's Assignment 3 greatly (~95% difference). As such, the given rubric has been remodeled to illustrate the changes. 

#### The Original
*Introduction*
* Motivation
* Task Description
* Objective
* Describing task as a machine learning problem

*Problem Analysis*
* User Requirements
* User’s Goals

*Project Management*
* Software Development
* Programming Language(s) Used
* Development Platform
* Milestones & Schedule

#### The New Rubric
*Introduction*
* Team Number
* Team Member's Full Names 
(These have been replaced with arbitrary "Name #"s due to the submission guidelines of Assignment 3: *"[submissions] should not include your name or student number in the pdf"*)
* Software Used
* Clear general instructions as to how to open and operate the prototypes

*Horizontal Prototype*
* Working link to prototype
* Clear starting screen
* List of major user tasks implemented (in order)

*Vertical Prototype*
* Working link to prototype
* Clear starting screen
* Description of what tasks is vertical
* To what extent is the verticality implemented? 

<br><br>

To summarize, here is a list of the similarities and differences:

#### Differences
* Replace Problem Analysis and Project Management sections with Horizontal Prototype and Vertical Prototype
* Introduction is entirely reworked

#### Similarities
* Introduction section exists
* Name of software (Development Platform) is listed


<br>

***
<br>

# Synitheia Prototypes

A habit-forming application prototyped on **Figma** by Team 2 (Name 1, Name 2, Name 3, Name 4, Name 5)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Steps

* Navigate to the appropriate link (found in the subsection of this document). This will open the project file. No download or installation is necessary. Internet connection and a Figma account are required.

* The link will open the prototype's starting page. No furthur steps are required to open the project.

* Explore the available options on the screen. If stuck, click anywhere on the screen and available options will be highlighted in blue:

![Interactions highlighted in blue after click](https://i.imgur.com/bF9csBT.png
"Hotspot Highlight")

### Navigation Notes

There are several items to keep in mind while navigating through the prototypes.

* __Text boxes...__

![Grey text box](https://i.imgur.com/r8qFPXr.png
 "Text box")
 
...are rounded grey boxes. Due to the constraints of Figma, typing interactions were not able to be as fluid. Therefore, to type into a textbox simply click on the textbox and the project will navigate as though the information was typed out.

<br/>

* __Back buttons...__

![Back button](https://i.imgur.com/RQzW9Hh.png
 "Back button")
 
...are used to navigate users back to the proper screen if they wish to cancel their actions. Once again, due to Figma constraints, the back button may not navigate back to the page expected. This is a rare occurance, but one to keep in mind while exploring Synitheia.

<br/>
<br/>

## Horizontal Prototype

This prototype can be found [here](https://www.figma.com/proto/0OSdUWi3Fc56jVILHRzNYm/Horizontal?node-id=432%3A1391&scaling=scale-down)

### Starting Screen
![Horizontal starting screen](https://i.imgur.com/zKbUA2V.png
"Starting Screen")

If the above screen is not what appears, please use the arrows directly below the prototype to naivgate to screen #1.

### Major User Tasks Implemented

1. User can log in
2. User can check in on a habit
3. User can create a new weekly habit goal
   * User can set date and time for reminder to check in (??)
   * User can scan physical calendar or import a digital calendar
     * App shows when user can do the habit based on free time in Synitheia's calendar
4. User can examine pre-existing habits 
5. User can visually see the streak of habits on calendar
6. User can see and interact with communities and recently viewed posts
   * User can create a new post and write comments to existing posts
7. User can toggle night mode in Settings
8. User can see completed habits
<br/>
<br/>

## Vertical Prototype

This prototype can be found [here](https://www.figma.com/proto/c9NGarXAzAXSp0dCksAqlE/Vertical-add-habit?node-id=173%3A408&scaling=scale-down)

### Starting Screen
![Vertical starting screen](https://i.imgur.com/JEzoCEe.png
"Starting Screen")

If the above screen is not what appears, please use the arrows directly below the prototype to naivgate to screen #1.

### Vertical Task(s)

* User creates a new habit goal
* User checks into a pre-existing habit goal

#### How Vertical Is It?

**Creation of habit goal**

When user starts creating a habit:
* If user does not select title of the habit they cannot proceed further
* If user does not put in information about habit in the description box they cannot get to the next step
* If user does not choose time and regularity of the habit they do not see the next task
* If user does not select the habit icon they cannot go to the next step

If user does not click "Next" button then error message appears on the screen

On the calendar integration screen: 

If user does not click choose to integrate physical or digital calendar 
* If user chooses one of the calendars then they can integrate them
 *  On the time found time page if button "Done" is greyed out then user needs to choose at least one time slot to get notifications
 * allows user to select and unselect the time on the calendar to do the habit

If not, then app will ask again they want to get notifications


**Checking In**
* If User checks in and presses "No" on the prompt...
  * If it's the final check in, send a prompt asking if user would like to push back deadline by 2 (two) weeks
    * If user agrees,  send a confirmation and push deadline back by 2 (two) weeks and modify progress accordingly
    * If user does not agree, send a confirmation and delete the habit goal
  * If it's a regualar check in, send an encouraging message meant to motivate the user and **do not** increase progress for the habit goal

* If User checks in and presses "yes" on the prompt...
  * If it's the final check in, send a "Congrats!" message and move the habit goal into Completed section
  * If it's a regualar check in, send a confirmation message and increase progress for the habit goal appropriately



