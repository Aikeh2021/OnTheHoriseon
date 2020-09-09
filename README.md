# On The Horiseon


## Table of Contents

* [Introduction](#introduction)
* [Adding Semantics](#addingsemantics)
* [Can I See Some IDs](#caniseesomeids)
* [Style](#style) 

## Introduction

This project was created to clean up some code for an existing site from a client. While the previous developer did an amazing job creating the visually pleasing final product, I could see that the code needed some alterations.
Personally, I'm a sucker for organization so I was thrilled to have the opportunity to condense the code and straighten out some of the kinks in the website. Not only does it give me the chance to apply my current knowledge of coding, I also get to perfect a project in a way that can hopefully be appreciated by the next developer.

I believe this project stands out because I took time to ensure that this piece was as thoroughly organized as I could possibly get it on my own. I took the time to space out the code, alter elements, and commentate on the initial html file. This was important because the client needed the website to be accessible for users and, in the event that the client changes their direction in the future, any future developers can easily read through the website's code and pick up where I left off.
I believe my attention to detail will greatly serve future developers for this project. Not to mention, the client will be very pleased with the increased accessibility on an already sleek and professional website.


## Adding Semantics

Upon first glance, I could see more semantic elements were needed. Each section of the website was separated by div tags. All I could see were div tags, within div tags, separated by more, you guessed it, div tags. 
While there isn’t anything wrong with div tags, things got pretty confusing when I tried to add notes to my code in github. Since every section started out as a div, it got confusing trying to specify which section received which changes. I had to put more detail after each div change because if I didn’t, it would look like I was replacing the same div with several different semantic elements. 
Not only did adding more semantic elements make it easier to differentiate each section, it also helped to define the purpose of the different parts of the website. After adding the semantic elements, I realized the website had a navigation bar and a footer! Elements I never would have noticed or appreciated without the proper tags.


## Can I See Some IDs
In the beginning stages of alterations, I noticed the section tags in the Optimization, Management, and Marketing section included both classes and id's. After reviewing the CSS sheet, I realized only the classes were being modified. Thinking this was another item that needed to be condensed, I removed the id's because I thought they were redundant. 
In hindsight, I should have made this modification in the web browser first just to see what the alteration would effect. It wasn't until I thought I had finished the project and went to review the requirements sent over by the client that I realized that I still had one unmet criteria: ensure all links are functioning correctly.
Thankfully, with the help of a colleague, we saw that the reason the links in my navigator bar were not working correctly was because they had nothing to act on. When I initially clicked the links as the beginning of the project, the previous developer did not designate the proper semantic tag. Instead of a div, a nav tag should have been used so the computer knows that the links in the unordered list were supposed to navigate the user to another place on the website when clicked. It made perfect sense that nothing happened when I initially clicked the links in the navigator. 
Because I had already included the nav tag inside of my header tag, all I had to do was add the id's back to the Optimization, Managment, and Marketing section. Once I completed this task, the section finally worked!

## Thorough Condensing
Condensing the HTML and CSS files was by far the most tricky and time consuming task in remodeling the website. If I forgot to change one class name, the entire layout of the website was completely thrown off. During this task, I employed a particular peice of advise I remember hearing my professor say when debugging someone else's code: "Make your changes one by one so if there is an error, you can go back and see exactly where it occurred."
I spent lots of time making modifications by the pair; if I changed it in the HTML file, I turned around and changed it in the CSS sheet. At times, this tactic did not work and I got discouraged. After a break and some thought, I remembered that the same class name can be used more than once. As a result, the same class name could be listed several times on the same CSS sheet. In addition, the previous developer combined classes and elements to specify where each modification went. 
I solved this issue by changing the class names to identical names if the same modifications were being made for several features of the website. Then I combed through the CSS to ensure I changed the old classes to the new class name. This way, when I refreshed my page, the old layout remained untouched while making the CSS and HTML easier to read.
At times, this meant breaking my rule of going pair by pair however, it led me to a new method of keeping track. Now that I had a common class name, I could remember exactly where the new changes had been made.

## Style
At a minimum, your project README:
 a short description explaining: 
    What was your motivation? Why did you build this project? (Note: The answer is not "Because it was a homework assignment.") 
    What problem does it solve? What did you learn? 
    What makes your project stand out? 
    
    
    
    
    
    
    
    
    If your project has a lot of features, consider adding a heading called "Features" and listing them here.

    If your README is very long, add a table of contents to make it easy for users to find what they need.