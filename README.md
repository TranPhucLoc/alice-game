**November 4, 2022:**

*Now that the Hacktoberfest is over, this project is going to progress slowly and steadily. I'm working on setting up some project management tools, an inital project proposal, and delegating parts of the Alice project so that it stays doable for everyone. (No one needs to end up with as sore a head and grumpy as the Red Queen!) I've created and managed other sorts of projects (not software) and a slow and thoughtful start means a much better experience for everyone! The frantic Hacktoberfest pace isn't sustainable year round. ;-)*

*I'm planning to be back actively maintaining this project at the end of the second week of November (11th-14th ish). I'm focusing on getting more freelance writing contracts this week (because we all need to pay the bills!). I've had multiple recruiters contact me in the past 36 hours about technical writing contracts.* **So I'm busy but definatley doing the Futterwacken!** 

*If you want to be ahead of the game when we start posting more issues, have a read and even try to follow along with this awesome, recent article while you're waiting.
[Create Your First Github Project in VSCode. By Jean-Christophe Chouinard, 12 October 2022](https://www.jcchouinard.com/create-your-first-github-project-in-vscode/ )*

**Thank you to everyone who contributed during Hacktoberfest! <br>
Happy Coding, and Welcome to Wonderland! <br>
Liz, GingerKiwi**
___

# **About**

*Welcome to Wonderland!*
The Alice in Wonderland Project is a html/css/vanilla javascript text-based game with an Alice in Wonderland theme. 

This is a repo geared towards new web devs who are learning open source and want to work and socialize with other devs. That includes the maintainer(s)! Most issues and PRs are small. To keep things managable, I'm limiting the contributors to 10 for now. Quality over quantity. 

**If You'd Like to Contribute Please Follow These Three Steps:**
1. Please introduce yourself in the [discussions tab](https://github.com/GingerKiwi/alice-game/discussions/4)
2. Have a quick read through the CONTRIBUTING.md and README.md files
3. Comment in the issue that you'd like to work on.

If we still have contributor spots open I'll assign the issue.

A great example of a text-based game is the classic [Oregon Trail](https://www.smithsonianmag.com/innovation/how-you-wound-playing-em-oregon-trailem-computer-class-180959851). 
Alice will have much better font and graphics, but will still be text-based without animated elements.

## Alice Game Background

This game was orignally created as a python console game as part of a computer science course at Massey University, New Zealand in 2020. Part of the assignment was documenting the thought process using comments. (So there's a lot of comments in the .py file!). The assignment was the classic [Camel game](http://programarcadegames.com/index.php?lang=en&chapter=lab_camel) from "Program Arcade Games and With Python And Pygame" and orginally concevied in 1979 in "More BASIC Computer Games".

However, the premise of the game is both racist and colonlialist - stealing an camel from the "natives" and racing away from them across the Mobi desert. So I changed the theme to Alice from Tim Burton's Alice in Wonderland movie rescuing the Red Queen's Bandersnatch from his imprissionment and racing across Underland to get to the White Queen's castle. I also added a random chance that the player would be attacked by the Jabberwocky, be killed, and the Jabberwocky poem would print on the screen.

## From Python Console to Javascript Text Based Web App

The goal is to take the existing python code and turn it into an accessible text based web game in html, css, and vanilla javascript. The game type is much like the classic text based "Oregon Trail" PC game.

### Repo Started with Minimal Code

The repo is being started with only a small amount of code and the app will not be functional. Instead comments have been added in the project files to show where code blocks should go and what they should do. The point is to collaborate in changing the orginal python file into a fun, working, and accessible web game.

## Supporting Other New Devs Learning Open Source & GitHub

In 2022, I participated in my first Hacktoberfest and Hacksquad while in the Scrimba Frontend Developer Career Path. Starting in open source can be intimidating! Turning this Alice python game into a vanilla javascript text based game web app could be a fun way for new devs like myself to collaborate and learn how to work on an open source project together. 

Version control was completely lacking from the unviersity courses I took in 2020-2021, so maintaining an open source repo geared towards new devs seems a good social way to learn and contrinute to the open source community. I know I will make mistakes (likely many), but that's a good way to learn. I hope others working on this project will bear with me while I learn how to maintain an open source repo.

### Intentionally Small Issues and Pull Requests

Given that this is a repo for us new devs to learn together, I'm aiming for the issues and the PRs that solve them to be small and doable for first time web devs. These can be as simple as adding a single heading and text, a short basic vanilla javascript function, or changing the colour variable in the CSS. This makes contributing to open source accessible for really new devs that are just learning the basics of html and/or markdown, as well as those of us that know more advanced css and javascript.

## Accessibility - Part of Every PR - Not Retrofitted and Refactored

This project is being developed with accessibility in mind from the beginning and at every step. That starts with sematic html, labelling elements, and having a "skip to main content". It also means that even if planned accessibilty features such as theme switching aren't being released in a particular version, the code is still written to make those features easily added.

This is one reason why CSS variables are being used, instead of hard coding colours and font/text attributes. While CSS variables are a more intermediate level skill, they make it easier to switch colours, type/font and implement theme switching instead of having to refactor the entire stylesheet.
