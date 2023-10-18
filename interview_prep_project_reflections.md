# M1 Project Reflections

## Warmup Project - Flashcards

### Flashcards Project Overview

#### List out the tools you used:
1. RSpec
2. Pry
3. VS Code
4. Terminal

#### Write a 1-2 sentence synopsis of what this project does:
This project has 6 code files and spec files with 6 different classes, and a runner file. I hard coded some questions into the runner file, and calling the start method on round will initiate a game of four questions in three different categories where the user is able to input answers into the terminal, and the project keeps track of the score. The game ends once all four questions have been answered, and the user gets to see their total result, as well as result by category.


### Reflection Questions: 
**1. How do you approach solving something when you don’t have all the information?**<br />

When I don't have all the information that I need to solve a problem, I first look at what I do have, and then I try to clarify what it is that I am solving.

Once I understand what it is that I am expected to solve, and I don't know how to solve it, that's when I refer to google. After googling and finding something that may work, I refer to Ruby Docs, and then I google a more general description to try and connect the dots between the two resources until I understand the Ruby Docs.

**2. What was your most effective strategy for getting through blockers during this project? How did this help your process?**<br />

Sleep helped me a lot! It was important to take time off when I was stuck and step away from the screen. Coming in with a fresh perspective helped me see things in a new light.

**3. Tell us about a time that you found yourself in an unproductive struggle, how did you get out of it?**<br />

I was in a bit of an unproductive struggle with #take_turn, so I zoomed out of the method, and looked at the whole class in order to reorganize myself and make sure that things were making sense. I noticed that I was trying to make too many unnecessary instance variables, and once I deleted them, it helped me to get back on track.


**4. What was the benefit of using TDD while building out this project?**<br />

Honestly, I didn't do TDD until Iteration 4, but I can see how it could have been really useful for me in figuring out how to tackle #take_turn. Going with a TDD method breaks down a difficult task into smaller parts, and it would have helped me organize things better.

## Solo Project - Beat Box

### Beat Box Project Overview

#### List out the tools you used:
1. RSpec
2. Pry
3. VS Code
4. Terminal

#### Write a 1-2 sentence synopsis of what this project does:
The Beat Box project has 3 code files, 3 test files, and 1 runner file. It can create a BeatBox object that has a LinkedList which you can attach Node objects to. When a user attaches a beat sound to the list, the list will check to ensure that the beat is a valid beat before attaching itself. Once the beat is attached to the list, it can be played through the terminal by using the #play on BeatBox. The rate at which the beats are played can be adjusted with the #rate, and voices can also be adjusted with the #voice. 


### Reflection Questions: 
**1. How do you approach solving something when you don’t have all the information?**<br />

Usually, if it is a new topic, I try to google the question, and as I'm googling and looking through answers, I try to keep an eye out for what could be the correct technical term to describe my question. However if I am completely stumped and getting nowhere, I usually reach out to an instructor.

**2. What was your most effective strategy for getting through blockers during this project? How did this help your process?**<br />

The most effective strategy on this project was looking for an outside eye. Having someone else take a look at my code and question why I was doing things the way I was helped me to process the information better. Most of the time I knew that I was going about something incorrectly, but my brain just couldn't process it yet, so that was frustrating!

**3. Tell us about a time that you found yourself in an unproductive struggle, how did you get out of it?**<br />

I was in a really unproductive struggle when I was trying to wrap my head around cycling through the nodes. And to be honest, when I think about it, it still gives me a headache sometime. I had to draw it out on my iPad, and I even used real world items to simulate moving from one node to another! Taking a break and coming back the next day to tackle the problem helped me.


**4. What was the benefit of using TDD while building out this project?**<br />

I think I still need to work on my TDD workflow. I was originally using it as a way to sort of pseudo code, but sometimes it caused me some confusing. I would jump ahead and try to test all the functionality of a method when that was something I was supposed to revisit later, or even when it wasn't a necessary function. So I found myself sometimes getting in that rabbit hole. 

On the other side of this, I would try to pull back from testing, and end up building out other codes before even thinking about the test, and then I'd have to go back and test it. 
