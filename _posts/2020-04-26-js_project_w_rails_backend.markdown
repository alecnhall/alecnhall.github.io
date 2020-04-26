---
layout: post
title:      "JS Project w/ Rails Backend"
date:       2020-04-26 18:14:54 -0400
permalink:  js_project_w_rails_backend
---


JavaScript was something that I was very excited to get into intially, but the language quickly brought me back down once I started to get further into the concepts surrounding it. I started to feel lost, like I was in a hole that I couldn't get out of. With the project on the horizon I couldn't help but feel dread. When I finally began to dig into the I found that I could do this.

For my project I chose build myself a study aid that I could utilize as well as many others. This morphed into the flashcard application that I created. I kept things extremely simple when it came to models. A category model and a flashcard model, with the category only having a name attribute, and the flashcard model having a question and answer attributes. A category has many flashcards and flashcards belong to a particular category. This limited model helped me feel less initimdated with the process that I laid out in front of me.

I started out by looking around for the best examples of a Rails Api. Luckily I ran into a video from a Flatiron Instructor that put me in the right direction. It gave me comfortability in the foundation of my project, and the structure being proper. Once I had this and I was able to be thoughtful about how to achieve the things I wanted to do. I started out by making sure that I could display and create categories. Next I moved onto the flashcards that are attatched too the categories and being able to display them once the category card is double clicked. They way I fetch my data for the flashcard object allows me to have access to all of my flashcards on the intialization of the page. This allows me to easily filter through all of those objects and match the foreign key to the parent category and then display those that match. At this point only the question displays, with the option to delete right below.

The next task was to display the answer on the double click of the question. This required finding the flashcard and then grabbing the answer from that object then displaying it in the DOM. By double clicking again it goes back to the question. Under each category you can add more questions as well as view all the flashcards belonging to that category. At the bottom of the page there is a category button that allows you to travel back to the category view and choose another topic to study.

Overall, this was quite the challenging project but I found myself feeling more and more comfortable with JavaScript as I went further and further along. This project really did help cement my understanding of concepts that surrond JavaScript and I feel like I can move forward with being successful in my future iterations of using the language.
