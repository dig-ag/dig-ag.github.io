---
layout: page
title: Module 1
parent: Introduction to Agricultural Informatics
grand_parent: Course Catalog
nav_order: 1
---
# Module 1: Web Design

## Lecture Notes

Source code for the slides is in this folder. The slides are live here:

- Lecture 1.1 [in-person]: www.aginformaticslab.org/ag-informatics-course/module1/lecture1.1.html 
   - Additionally, watch the following videos before the next class.
      - Watch in detail the CS50 video on HTML and CSS: [Harvard CS50 week 0](https://cs50.harvard.edu/web/2020/weeks/0/).
      - Skim through the CS50 video on Git: [Harvard CS50 week 1](https://cs50.harvard.edu/web/2020/weeks/1/).
- Lecture 1.2 [in-person]: [Module 1 - Lecture 1.2](https://www.aginformaticslab.org/ag-informatics-course/module1/lecture1.2.html)
- Lecture 1.3 [in-person]: [Module 1 - Lecture 1.3](https://www.aginformaticslab.org/ag-informatics-course/module1/lecture1.3.html)
- Lecture 1.4 [in-person]: Case Study: [Module 1 - Lecture 1.4](https://www.aginformaticslab.org/ag-informatics-course/module1/lecture1.4.html)

## Labs

Instructions for the Labs, including submission instructions, can be found inside the lab sub-folders. Navigate to "lab1.1" to begin the lab for Module 1, Week 1. Make sure you watch the videos prior to coming to the lab.

Make sure you complete both Lab 1.1 and Lab 1.2 before submission.

**Academic Integrity Reminder:** Make sure your lab Github repositories are "private" for the duration of the course, to prevent others from simply copying your code. I trust that you will work independently, and will evaluate your work based on your "commit" history (i.e., you should NOT just commit the ENTIRE lab 5 minutes before the deadline). In general, writing code with the help of the internet is permissable, i.e., you can ask questions on Stack Overflow, discuss the problems with each other on Slack. Ultimately, I have a policy in which I trust that you are doing the right thing, unless I see evidence to the contrary.

# Module 1, Lab 1, Part 1

## BEFORE THE LAB

Watch the CS50 video on HTML: https://cs50.harvard.edu/web/2020/weeks/0/

Watch the CS50 video on Git: https://cs50.harvard.edu/web/2020/weeks/1/. We will not be using Git as comprehensively as introduced in this video, but you will need to understand how to use the following commands at minimum:
- `git clone "url"` to clone a remote repository to your local machine
- `git pull` to pull changes to a remote repository
- `git init` to initialize a repository
- `git add .` to add all (".") changes here to my local version of the repository.
- `git commit -m "message here"` to commit all your changes with a message
- `git push` to send all my local changes to the remote repository.

Setup Github:
- If you haven't already, create an account on www.github.com. If you already have a GitHub account, feel free to use it. We will be using github to share our code with each other - You'll recieve your labs this way, and I will expect you to submit your labs this way too.
- Install github on your computer using this tutorial: https://github.com/git-guides/install-git

## Use Git to access class materials (we'll do this in-class too!)

1. Clone this repository using `git clone https://github.com/ag-informatics/ag-informatics-course'` You can view the repository URL here: 
	
![Clone Repo](/assets/images/git1.png)

2. Every week, I will update this repository with new things. You can update your local repository by `git pull` the changes from the web. When you navigate to the folder containing the repository on your local machine, you will be able to see the changes.

## Introduction to HTML and CSS

In this lab, you will create a basic webpage to demonstrate your understanding of HTML. 

**File Structure** 
- Create a folder titled "Lab1". 
- In this folder create a file called "profile.html". You will be making a basic web page to showcase your work.
- Create a file called "styles.css". This will contain all the CSS for your webpage. Make sure you link it in the "head" section of your profile.html web page.
- Create a folder called "img", this will contain any images that you use on the webpage.

### Mockup
You will create state Profile Webpage that looks similar to the mockup below:

![Ankita Mockup](/assets/images/mockup.jpg)

1. Create a `<div>` with the ID name "header". This division should contain introduction header text, e.g., "Hi! I'm Ankita". 
		- Give the header a minimum height (e.g., 40px).
		- Center the text within the header division.
		- Change the font style and size to something that is different from the rest of the page. 
		- Use CSS header to make your header text "small caps".

2. Create a `<div>` with the ID name "about".  This division should contain a photo of yourself with a description of what you do.
  a. In your styles.css file, add code to style this section as follows:
     - Photo has a black border of 2px. 
     - Change the description font and size to one of your choosing.
     
  b. Include at least 3 hyperlinks to your github repository and any other links you may want to share (e.g., Linked In). 
  	- Select an "mail" icon from the Noun Project, available publicly here: <a href="https://thenounproject.com/search/?q=mail">https://thenounproject.com/search/?q=mail</a>. Use a "mailto" to activate my default mail client and send an email to you. 

3. Create a `<div>` with the ID name "work-samples". This division should contain a "flexbox", "table", or "grid" layout consisting of three sub-elements. Each sub-element should contain a placeholder image and some descriptive text of your work. 
	a. Your styles.css file should contain relevant styling for this section. At minimum:
		- Change the font style and size.
		- 
	b. You must use either an ordered or unordered list element to lay out the description text for each work sample. 
		- Use CSS to remove the bullet symbols.
		- Ensure that the text is vertically aligned with the image.

4. Create a `<div>` with the ID name "footer". This division should contain a footer with your name, and the date this page was last updated.
		- Use CSS to give the footer a solid background color. 

5. Your html and css files should contain the appropriate code to:
	a. Center your content in the browser.
	b. Use the correct "veiwport" to make your webpage "responsive", i.e. it should be scale for device size.

## Use Git to submit your labs
1. Create a new repository called "YOURNAME-ASM591-Labs". Mine would be, for example "Ankita-ASM591-Labs". You will create a subfolder for your lab submissions. If you have trouble contact me ASAP.
	- MAKE SURE THIS REPOSITORY IS "PRIVATE". See [Academic Integrity Statement](https://github.com/ag-informatics/ag-informatics-course#academic-integrity) in syllabus.
	- Add @sudokita (Ankita, Instructor) and @StevenDoylePurdue
 (Steve, TA) as collaborators on your repository so that we can access your work and grade it.
	- I expect to see an appropriate number of distinct "commits" in your repository history per lab (i.e., >5 commits for lab 1.1 alone), with appropriate comments, demonstrating that you have been working on your project over a period of time.

2. For this module's lab, place the folder containing your HTML code, "Lab1" into this repository. This will be the first part of your submission next week! You should see something like the screenshot below:

	![Lab1 Repo](/assets/images/lab1.png)

## Future Learning Pathways 

To learn more about Github by digging in here:
- Basics on Git: - https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository
- Visualization of how git works: https://onlywei.github.io/explain-git-with-d3/#commit
- Full github training module: https://lab.github.com/githubtraining/introduction-to-github

To learn more about HTML and CSS, use these resources:
- W3Schools HTML Reference: https://www.w3schools.com/tags/default.asp
- Mozilla Foundation HTML References: https://developer.mozilla.org/en-US/docs/Web/HTML 





# Module 1, Lab 1, Part 2

<!-- By this point you should have a github repository titled "YOURNAME-ASM591-Labs", containing one folder titled "Lab1", inside which there are 2 files (profile.html, styles.css) and one folder (img) containing any images. The image below shows the contents of my example lab1 repository!

	![Lab1](img/lab1-contents.png) -->

In this week's lab, you will conduct a brief design exercise, given your knowledge of what is possible using HTML and CSS.

## BEFORE THE LAB

Get familiar with the common components of websites. 

1. [Material Components for the Web](https://material.io/components?platform=web): This is a design framework developed by designers at Google used to unify the aesthetic and layout of user interfaces on Google products. It is commonly used by many developers, especially those of Android mobile applications.

2. [Bootstrap Components for Web](https://react-bootstrap.github.io/components/alerts): I chose this one to share since the website actually has visuals for you to look at. [Bootstrap](https://getbootstrap.com/) is a front-end library, originally to help style simple HTML websites, but now written in a variety of languages.

3. [Dribble for Design Inspiration](https://dribbble.com/search): Designers showcase and share their work on this website - one can also use it to find and hire designers. I use the search function to get inspiration. Try search for "food", for example, and see ideas for how folks imagine apps for food delivery, cooking websites, nutrition apps and more. Remember: these are design professionals and aspiring web designers :)


<!-- ## Lab Content Here -->

## Design Prompt
Given what you have learned about HTML & CSS, and your general knowledge of websites, you will be practicing a set of design exercises to envision what a simple online farm shop might look like.

In particular, we will focus on the design of a **Product Availability Page** that would appear on a Farm's website, enabling farmers to sell their food directly to consumers online!

## Brainstorming!

1. Watch the video to learn how to use the Crazy 8s Process: https://www.youtube.com/watch?v=UXOLJy0E7Pg. Given that we are designing a website, you are welcome to reduce the number of squares to 4. If this is your first time doing this sort of thing, feel free to give yourself 2x or 3x the amount of time recommended. Ultimately, you will want to set a short timer otherwise you may get stuck overthinking details in this brainstorming phase.

2. I suggest practicing the Crazy8s method to layout parts of your web page several times to warm up your pen and brain! Don't worry about how it looks, it's not your drawing skill that matters, but the logical layout of information does. Other suggestions:
	- Consider creating an actual "storyboard" in your first couple of attempts, it will help you think through the actual process you want the user to go through as they first arrive at the website, look for products, and ultimately buy them.
	- Consider breaking up your website into several parts and using each of the squares so you're not packing the whole page into one area, but imagining how the user would digest different parts of the site as they move through.

3. You will submit 3 of your Crazy8 Sketches that represent your favourite versions of the website. Take a photo of your sketches, title them "solution-sketch1" and so on. Place it in your Lab1 folder and don't forget to git add, commit, and push!


## Create Wireframes
1. You can use a whiteboarding app like [Miro](miro.com/), layout a fake "web page" in Microsoft Powerpoint or Google Slides, or a wireframing tool like [Balsamiq](https://balsamiq.com/) or [Pencil](https://pencil.evolus.vn/).

2. Create a mockup of the web page, based on your 3 Crazy8 Sketches, that demonstrates how you would layout your ideal farm product availability.

3. Save your solution as a PDF titled "solution-mockup" and place it in your Lab1 folder. Save your work to your Github Repository.

## Solution Description
1. Navigate to your Lab1 folder and create a file called "README.md". This is a "markdown" file that we will use to describe your solution to the design prompt. Your text will be "formatted" using a simple code, described in this [Markdown tutorial here](https://guides.github.com/features/mastering-markdown/). This is very similar to how we used a combination of HTML and CSS to "mark up" our text last week.

2. Enter the following text exactly in your "README.md" file:
		
		#Design Prompt

		**Design:** A Product Availability Webpage

		**For:** A Farm Website

		**To Help:** Farmers sell food to Consumers!

		#My Solution

3. Save the file, and be sure to git add, commit, and push! It should look like the image below:


4. Under the "My Solution" heading, provide a 1 paragraph description of your solution, and why you chose to lay out the information in the way you did.

Note: the storyboard and wireframes are not going to be graded based on artistic quality - that doesn't matter. You will be graded on attempting the design exercises and putting together a **logcial flow of information**.

## How to Submit your Lab
Make sure all your work for this week is inside the "Lab1" folder within your repository titled "YOURNAME-ASM591-Labs". Remember to use the git commands "add", "commit", and finally "push" to add your files, commit the changes with a comment, and push the changes to the Github website.

Your github repository should now look like this:

![Lab1.2 Contents](/assets/images/lab1.2-contents.png)

GO TO BRIGHTSPACE, submit the link to your repository in Lab1. You are now done! 

Hurray, you rocked Module 1!


# Future Learning Pathways
Whiteboard Challenges: https://medium.com/tradecraft-traction/the-beginners-guide-to-the-whiteboard-challenge-538289536a72 Learn how more ways to do design challenges. Try this out using the next link.

Design prompt generator: https://designercize.com/. This is a fun tool that randomly generates design prompts that you can use to practice design skills.




# Quiz

The quiz for this module is available via Brightspace. 

## License
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

<!-- This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa] -->

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

  "Introduction to Agricultural Informatics Course" by [Ankita Raturi, Purdue University](https://github.com/ag-informatics/ag-informatics-course) is licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.](http://creativecommons.org/licenses/by-nc-sa/4.0/)
