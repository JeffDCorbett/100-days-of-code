# 100 Days Of Code - Log

### Day 0: April 15, 2021

**Today's Progress**: My first day of learning JavaScript involved setting the foundation for a basic Battleship game.  

- battleship.html
- battleship.js

**Thoughts:** I think it is going to be very easy to get brackets, { }, out of place. This should be a very  
interesting process. 

**Link to work:** [Battleship](https://github.com/JeffDCorbett/battleship)

### Known Bugs:
**Hits** - Once a hit location is found entering the same number two more times results in sunken ship. Need to record  
and compare against guessed numbers.

### Day 1: April 16, 2021

**Today's Progress**: The focus was on functions; the basics of how to structure them, call them, pass arguments, and return values.  
I'm learning JavaScript using the book "Head First JavaScript Programming" 

- calculate_area.js

**Thoughts:** Most of today's work seemed redundant as I am not completely new to programming. I've written a full-stack app  
in Python/Flask that is currently in use, so the concepts are not new, but I feel I need a deep dive into JS.

### Day 2: April 17, 2021

**Today's Progress**: The focus was on arrays and iterating over them with while and for loops. I created two new files for examples.  

- arrayWhileLoop.js
- arrayForLoop.js  

The for loop contains improvements over the while loop example such as post-increment operator, empty array creation, and  
array push functionality.

**Thoughts:** Today's work was much more interesting than yesterday. As I mentioned before, I'm using "Head First JavaScript Programming"  
as my guide, and some conventions in the book are outdated.

- VAR vs Let to define variables
- == vs === to prevent type coercion  

I'm using (and learning) the IDE Webstorm which is very good at pointing out the differences between conventions. A quick look at  
tomorrow's lesson involves refactoring the arrays. It's hard to stop for the night, but it's family time.

### Day 3: April 18, 2021

**Today's Progress**: Continued with work on arrays, functions, and iteration. Added parallel arrays to find the best cost for the highest score.

- bubbles.html

**Thoughts**: I struggled with the logic a bit on connecting the dots between the parallel arrays in the getMostCostEffectiveSolution function.  
For the most part my head just wasn't in it today, but I did manage to get through with a little Google assistance.  
I expanded on the example a bit by displaying the cost in the final result.  

Currently, everything I'm coding is going into my [Battleship](https://github.com/JeffDCorbett/battleship) project, which I do not like, but I'm assuming these extra examples will play a role in the game at some point.

### Day 4: April 19, 2021

**Today's Progress**: Performed some very basic tinkering with objects. It was definitely more reading than coding, but I'm sure there is more to come.  

- cars.js

**Thoughts**: The work this evening was not very intriguing and I feel like I missed the point of it. I will go over it again tomorrow before diving in to more.  

### Day 5: April 20, 2021

**Today's Progress**: Expanded on yesterday's object examples to include automation using Math.random().  

-auto_o_matic.html

**Thoughts**: I need to explore options for applying these techniques to real world situations. I know I will have issues making these concepts stick until I can apply them in a meaningful way.  

### Day 6: April 21, 2021

**Today's Progress**: Today I covered a lot more in regard to objects by adding methods and learning the use of "this" to access properties.  

- carWithDrive.html
- eightBall.js
- eightBall.html
- crackTheCode.js
- crackTheCode.html

**Thoughts**: The final example, crackTheCode, felt more like object oriented programming and it feels great to be getting started down this path. I'm happier with today's progress and looking forward to moving forward.  

### Day 7: April 22, 2021

**Today's Progress**: I took some time to review and reflect. The Magic 8 Ball example, eightBall.js, didn't make sense to me. It's not a situation where you would want to iterate through responses, so I updated it to use Math.random.  

Moved on to learn about DOM, getElementById, and window.onload with init function.  

- planets.html

**Thoughts**: Feels like I'm starting to move out of the simple beginner stuff and really starting to find ways to manipulate pages with JS. Feels like it is going to start getting fun!  

### Day 8: April 23, 2021

**Today's Progress**: Got more practice manipulating static pages by getting an element id in the DOM

- myPlaylist.html

**Thoughts**: I'm interested in seeing where this is going. I'm looking forward to progressing further in the book and, hopefully, getting into a project.  

### Day 9: April 24, 2021

**Today's Progress**: Today was some additional manipulation of the DOM via JS code. Updated planet.html to change an attribute to add CSS styling.  

- planets.html

**Thoughts**: I'm not sure if I'm helping or sabotaging my learning... Some of the examples in the book "Head First JS Programming" don't make sense to me. For example, the planet.html page changes the text of a paragraph tag using a function and window.onload. The change happens so fast that you never see the original text.  

I looked up setTimeout and changed the code to run the function after 10 seconds. You get to see the original text and then 10 seconds later BOOM the magic happens.  

In the Magic 8 Ball example, responses were iterated through which didn't make sense to me especially since the "car" examples used Math.random. I updated the Magic 8 Ball example to use random responses instead of iteration.  

###Day 10: April 25, 2021  

**Today's Progress**: I deviated from the JS path to do a little Python. Created a function that finds unique words in two separate sentences.  

ex: sentence a = "the pancakes taste sweet"  
ex: sentence b = "the pancakes taste salty"  
result: ['sweet', 'salty']  

I then rewrote the function to reduce the number of lines.  

- unique_words.py
- unique_words_improved.py  

**Thoughts**: I felt like I needed a break from the JS examples I've been doing and spend a little time on Python. I really enjoy Python and look forward to moving forward with it.  

### Day 11: April 26, 2021  

**Today's Progress**: Learned about types and the use of typeOf. Interesting information about NaN, Truthy, and Falsy. Two files added today.  

- typeOf.js
- lieDetectorTest.js  

**Thoughts**: I'm progressing through Head First JS Programming, about 46% complete, and the concepts are beginning to get a little more involved. I'm interested to see how this plays out. I'm hoping for a tangible project before the end.  

### Day 12: April 27, 2021  

**Today's Progress**: I read more Head First JS Programming and reviewed everything I've covered so far in the book's exercises. Then I worked on Python code challenges on Pythonista Cafe and HackerRank.  

- I scored 20 points in the Print Function challenge on HackerRank https://www.hackerrank.com//challenges/python-print/submissions/code/210779333  

**Thoughts**: I completed the introductory Python code challenges on HackerRank. The challenges really make you think. Love it!

### Day 13: April 28, 2021  

**Today's Progress**: Definitely more productive. Today begins real work on the Battleship game so I completely restructured the project, removed testing examples, and did a lot of coding.  

- Created HTML, CSS, and JS directories
- a new Battleship.html
- Battleship.css
- Battleship.js  

Coded quite a bit of CSS and JS for the project. Battleship.js contains view and model objects with a controller object on the way.  

**Thoughts**: This feels more like a project and I definitely got into it. I've been working on this for nearly 3 hours and I can tell that I will be anxious to get back to it.  

I'm not following the example exactly... Currently, the example has all of the css code in the html file, but I broke it out into its own file. The structure makes more sense to me and it's easier to keep track of what's going on in the html.  

### Day 14: April 29, 2021  

**Today's Progress**: I coded for about 3 hours again today and made great strides on my Battleship game. At this point it can be played, but there are some things to work out yet.  

- many updates to battleship.js

**Thoughts**: I gave serious consideration to giving up on JavaScript and going back to Python and I decided that I'm going to work through the rest of this book. I'm not a big fan of JS at this point, but maybe something will change before the end. Also, I'm sure there will be times that I'm going to have to do some level of JS in my projects so might as well continue on and learn what I can of it.  

### Day 15: April 30, 2021  

**Today's Progress**: Today's progress was non-existent. As I've stated previously, I am using the book Head Start JavaScript Programming and things have now shifted back to short exercises that fail to engage me. Most of my time spent today was on reading, viewing a few lines of code, reading, more reading, another line of code. I have no files to add today.  

**Thoughts**: I'm struggling to keep on with JS. My desire is to become an expert at Python/Django, but I felt that I needed some JS regardless. I really feel like I'm wasting time on it.  

### Day 16: May 1, 2021

**Today's Progress**: Not so good at all... After going through the process of building out a basic Battleship project, the examples have dropped back to basic examples rather than extending the Battleship project.  

60% of the way through the book now and this is the latest example:  

function compareNumbers(num1, num2) {  
if (num1 > num2) {  
    return 1;  
} else if (num1 === num2) {  
return 0;  
} else {  
return -1;  
}  
}  

var numbersArray = [60, 50, 62, 58, 54, 54];  
numbersArray.sort(compareNumbers);  
console.log(numbersArray);  

To get some sense of accomplishment, I went over to Hacker Rank and completed a Python List Comprehension exercise.  

**Thoughts**: I'm going to finish reading the book because I bought the book, but I will no longer be using it for my coding source for #100DaysOfCode. I will instead be switching to a Python source.  

### Day 17: May 2, 2021  

**Today's Progress**: Today was my first day working from "Python Basics: A Practical Introduction to Python 3" by the @realpython tutorial team. While it was basic, "Hello World", stuff it was great to be working with Python.  

- print("Hello, world")
- variables
- assignment operator =
- runtime errors
- syntax errors
- name errors
- comments  

The book comes with a learning path that includes online content and quizzes. I worked through the first 3 chapters and completed the quiz assigned at the end of chapter 3 with a 100%.  

**Thoughts**: While the first 3 chapters are basic Python material, the lessons have been logical and play well to my learning style.  


