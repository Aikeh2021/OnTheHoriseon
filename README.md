# On The Horiseon


## Table of Contents

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)
* [Adding Semantics](#addingsemantics)
* [Can I See Some IDs](#caniseesomeids)
* [Thorough Condensing](#thoroughcondensing)
* [License](#license)


## Introduction

This project was created to clean up some code for an existing site from a client. While the previous developer did an amazing job creating the visually pleasing final product, I could see that the code needed some alterations.
Personally, I'm a sucker for organization so I was thrilled to have the opportunity to condense the code and straighten out some of the kinks in the website. Not only does it give me the chance to apply my current knowledge of coding, I also get to perfect a project in a way that can hopefully be appreciated by the next developer.

I believe this project stands out because I took time to ensure that this piece was as thoroughly organized as I could possibly get it on my own. I took the time to space out the code, alter elements, and commentate on the initial html file. This was important because the client needed the website to be accessible for users and, in the event that the client changes their direction in the future, any future developers can easily read through the website's code and pick up where I left off.
I believe my attention to detail will greatly serve future developers for this project. Not to mention, the client will be very pleased with the increased accessibility on an already sleek and professional website.


## Installation

Please [click this link](https://aikeh2021.github.io/OnTheHoriseon/) to be redirected to the On The Horiseon Website
![image](https://user-images.githubusercontent.com/69944302/92675620-da307080-f2ed-11ea-9d91-53bc68571d38.png)

If you would like to view the github repository code, [follow this link](https://github.com/Aikeh2021/OnTheHoriseon) to access it.


## Usage

This website discusses the ways in which brands can expand their influence using certain strategies like investing company dollars toward advertising efforts, as well as, utilizing tactics like monitoring the habits of consumers and controlling public perception. 

Use the navigation bar located at the top of the page to be directed to different sections of the website. Once there, you will receive more information explaining how new strategies can be implemented to help your business grow!
![image](https://user-images.githubusercontent.com/69944302/92678818-c9372d80-f2f4-11ea-91a2-f370bf3b2b03.png)

Once you have reviewed all of the topics in the navigation bar, be sure to peruse the information on the far right side of the page. 




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



## Credits

Below are websites used to alter this project:

[Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

[CSS Navigation Bar Syntax](https://www.w3schools.com/css/css_navbar.asp)

[Web Accessibility Checker](https://achecker.ca/checker/index.php)

[Copright Symbol Command](https://www.macintoshhowto.com/pages-and-publishing/how-to-type-the-copyright-symbol.html)

[README.md Hyperlink format](https://www.quora.com/How-do-I-create-a-hyperlink-in-the-README-file-in-my-GitHub-account-which-would-redirect-to-a-new-page-containing-the-project-explanation)

[Licensing](https://choosealicense.com)


Below is a list of Github Profiles for the colleagues with whom I collaborated:

[Elyse Wells](https://github.com/ewells89)

[Stef Lupo](https://github.com/lain7891)





## License

MIT License

Copyright © 2020 Ashley Ikeh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.