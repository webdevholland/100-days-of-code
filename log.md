# 100 Days Of Code - Log

### Days 7 & 8: September 8, 2019* - PRELIMINARY ENTRY

***Background**:  Meant to do Day 7 last night, but didn't which was why it got combined with Day 8 today.

***I know I'm not following the rules of this challenge to a T.  I don't want to get bogged down by rules so I'm modifying them a bit to better suit my lifestyle.  I think it's more important that I consistently learn & build every day regardless of what day or time it is.  I'll explain this later in the README.md as well as the Rules and FAQ sections of this repo.***

**Today's Summary Progress**:  Watched "Scope & Context (Part 2)" in Brad Schiff's JavaScript course (see Links for the day).

**Quick Notes**:  
* 
* 
* 
* 
* 
* 
* 
* 
* 
* Refer to CodePen #10 (see Links for the day).

**Thoughts:**
* 
* 

**Links:**
* Udemy course:  [Learn JavaScript: Full-Stack from Scratch](https://www.udemy.com/share/101qIyAkoedF9STQ==/)
* CodePen #10:  [Scope & Context - day 2](https://codepen.io/webdevholland/pen/PoYQqxq) - To see in action, follow instructions commented out with forward slashes '//' in JS editor of Pen.



### Day 6: September 7, 2019*

***Background**:  Went to bed last night as opposed to falling asleep on the couch & getting up in the wee hours of the morning.  So, instead of working on this overnight like I have been doing every day since I started #100DaysOfCode, I'm working on this now at a time when most start their day.  If I can come back to work on another round of this challenge later tonight, I'm counting it as Day 7.

***I know I'm not following the rules of this challenge to a T.  I don't want to get bogged down by rules so I'm modifying them a bit to better suit my lifestyle.  I think it's more important that I consistently learn & build every day regardless of what day or time it is.  I'll explain this later in the README.md as well as the Rules and FAQ sections of this repo.***

**Today's Summary Progress**:  Continued from yesterday & finished "Scope & Context (Part 1)" in Brad Schiff's JavaScript course (see Links for the day).  Wrapped up on Scope concepts.  (Part 2 of lesson will be on Context.)

**Quick Notes**:  
* Possible to modify or mutate variable in global scope from within local scope.
* "Scope moves in one direction.  It is a one-way street." (starting from within the inside and then going out.)
* Declare variable = create variable.
* 'let' didn't exist until about 3 or 4 years ago.  If looking at someone else's older code, may see 'var' instead of 'let'.
* 'let' uses block scope... code looks for nearest enclosing block as defined by curly brackets '{ }'.
* 'var' uses function scope... only cares about curly brackets '{ }' of a function.
* Block scope is what most developers use & are familiar with esp. in other programming languages.  Block scope leads to less problems & confusion.
* Recommended to never use 'var'.
* If code isn't working, might want to check your scope & make sure variables are pointing towards what you think they should be pointing towards.  Can always use console.log to check value/result.
* Refer to CodePen #9 (see Links for the day).

**Thoughts:**
* Helped to pause & rewind video as often as I needed not only to work on CodePen #9, but to take notes too!
* Connected with & understood material better when I took notes (was probably the case as well when I was in college ages ago).

**Links:**
* Udemy course:  [Learn JavaScript: Full-Stack from Scratch](https://www.udemy.com/share/101qIyAkoedF9STQ==/)
* CodePen #9:  [Scope & Context pt 1 - day 2](https://codepen.io/webdevholland/pen/PoYQqxq) - To see in action, follow instructions commented out with forward slashes '//' in JS editor of Pen.



### Day 5: September 5-6, 2019 (worked overnight into AM)*

***Background**:  Never went to bed!  Dozed off on couch, got up around 3 am & started working on computer (first spent time documenting my other challenge, [#100DaysOfFitness](http://bit.ly/100DaysOfFitnessFullLog).

**Today's Summary Progress**:  Moved on to next video in Brad Schiff's JavaScript course (see Links for the day).  "Scope & Context (Part 1)".

**Quick Notes**:
* Scope --> variables.  Context --> objects.
* Global vs local scope --> when code is executed, variables are read from the inside out, going up one level at a time.
* Same label name can be used for variables at different levels of scope.
* Refer to CodePen #8 (see Links for the day).

**Thoughts:**
* Feel like things are starting to make more sense to me (i.e. global vs local scope).  Various levels of scope makes me think of a staircase.
* TGIF!!!  Starting tomorrow, hope to get back to a better schedule where I'm actually recording what I do ON THE SAME DAY I begin an activity!

**Links:**
* Udemy course:  [Learn JavaScript: Full-Stack from Scratch](https://www.udemy.com/share/101qIyAkoedF9STQ==/)
* CodePen #8:  [Scope & Context pt 1 - day 1](https://codepen.io/webdevholland/pen/YzKYvYM) - To see in action, follow instructions commented out with forward slashes '//' in JS editor of Pen.



### Day 4: September 4-5, 2019 (worked overnight into AM)

**Today's Summary Progress**: Continued watching video in Brad Schiff's JavaScript course (see Links for the day).  Same topic- returning vs mutating.

**Quick Notes**:  
* Picked right back up with two array methods that are extremely valuable even though all they do is return values, not mutate array:  array.map() & array.filter().
* Forked yesterday's Pen to create CodePen #7 (see Links for the day).
* '.map()' is higher-order function:  it accepts another function as an argument.  '.map()' function returns a brand new array.
* '.filter()' is another higher-order function that also returns a brand new array.
* '.map()' & '.filter()' can become incredibly powerful because they can be chained together as in this example:  let babyDogNames = pets.filter(onlyDogs).filter(onlyBabies).map(nameOnly).
* More examples to come of chaining of data types; this isn't limited to arrays only.

**Thoughts:**
* Bookmark feature available with video is very helpful... knew exactly where to pick right up from yesterday.
* Found myself replaying video at certain points because I nodded off... not because material is boring, but because it's 4 am... again...
* Caught in vicious cycle of working overnight... hope to break free of this pattern this coming weekend (just two more days!) 

**Links:**
* Course:  [Learn JavaScript: Full-Stack from Scratch](https://www.udemy.com/share/101qIyAkoedF9STQ==/)
* CodePen #7:  [Returning vs mutating2](https://codepen.io/webdevholland/pen/NWKwVxN?editors=0010) - Follow instructions that are commented out with forward slashes '//' in JS editor of Pen to see in action.



### Day 3: September 3-4, 2019 (worked overnight into AM)

**Today's Summary Progress**: Started to watch next video in Brad Schiff's JavaScript course (see Links for the day).  Difference between returning & mutating covered.  Didn't finish watching video; will continue in Day 4.

**Quick Notes**:  
* Recall from previous lesson '.push' method to add to an array. This changes or mutates array.
* In Pen #6 (see Links for the day), '.push' not only mutated array, but also returned number of items/objects in array (in this case, four animals in 'pets' array).
* Recall '.map' & '.filter' methods first mentioned in last video watched. These two methods extremely useful even though they only return number of items in array, not mutate array.

**Thoughts:**
* Will include pic of Pen #6 when I tweet today's progress at [@webdevholland](https://twitter.com/webdevholland).
* Will also tweet link to Collection of pens I've created so far.
* Soooooo glad I'll be working my day job from home (starts in several hours).
* Gotta go to sleep!!! 

**Links:**
* Course:  [Learn JavaScript: Full-Stack from Scratch](https://www.udemy.com/share/101qIyAkoedF9STQ==/)
* CodePen #6:  [Returning vs mutating](https://codepen.io/webdevholland/pen/pozdEbJ?editors=0010) - Instructions in lines 7, 12 & 18 in JS editor of Pen to see in action.



### Day 2: September 2-3, 2019 (worked overnight into AM)

**Today's Summary Progress**: Watched next three videos in Brad Schiff's JavaScript course (see Links for the day). Arrays, making decisions and higher-order functions covered.

**Quick Notes**:  
* Array = collection (see Links for the day). Square brackets used to hold array of items '[ ]'. Add to an array with '.push'. Remove from array with '.splice'. These are examples of methods (method = ability).
* 'If' / 'else' statement introduced. 'If' statement can stand on its own without 'else' block.
* Higher-order function, part I: function accepting another function as an argument. To see example, scroll down to Day 1 of this Log and within Links, click next to CodePen #2 or "Object example" hyperlink.  See line 1 in JS editor of Object example Pen which shows function called 'ChristinesFunction' passed as argument. Higher-order function, part II: function returning another function as a result (see CodePen #5 under Links for Day 2) '.forEach' method introduced & demonstrated with example using array. '.map' and '.filter' other methods mentioned.

**Thoughts:**
* Heard of array before, also thought of it as list of items.
* Brad acknowledges that lessons not too exciting so far. Like he's saying, "I know this has been tough to go through, but hang in there". Foundation being laid for more exciting things to come- like building own application! Looking forward to progressing through rest of course :-)
* I hope I can function today (no pun intended), haven't gotten much sleep ZZZzzzz

**Links:**
* Course:  [Learn JavaScript: Full-Stack from Scratch](https://www.udemy.com/share/101qIyAkoedF9STQ==/)
* CodePen #3:  [Working with Arrays](https://codepen.io/webdevholland/pen/yLBzpmz?editors=0010) - Instructions in lines 4, 6, 13, 19 in JS editor of Pen to see in action.
* CodePen #4:  [Making decisions in our code](https://codepen.io/webdevholland/pen/ExYwEQK?editors=0010) - Instructions in lines 1, 11, 15, 24, 28, 37 in JS editor of Pen to see in action.
* CodePen #5:  [Higher-order function](https://codepen.io/webdevholland/pen/zYOEaOa?editors=0010) - Instructions in lines 13 - 15 in JS editor of Pen to see in action.



### Day 1: September 1-2, 2019 (worked overnight into AM)

**Today's Summary Progress**: Started Brad Schiff's JavaScript course on Udemy (see Links for the day).  Watched videos on course preview, introductory lesson, functions and objects.

**Quick Notes**:  
* Course preview differentiates language (syntax) from environment (web browser, Node.js, MongoDB).  Need to learn syntax first before worrying about environments language is used in.
* Played with JavaScript in console of Chrome (see Links for the day).  Keywords *let* and *variable* introduced.
* Created functions (see Links for the day):  came up with own names for functions (arguments) and defined functions with "recipe".
* Think of object (see Links for the day) as container which stores properties inside curly brackets '{ }'.  Can look inside object with a dot '.'. For example in cat.name, cat is the object and name is the property stored inside.

**Thoughts:**
* Heard of Node.js, but no prior knowledge of or experience with it.  Took MongoDB course a while ago when Code School used to exist (it's now Pluralsight).
* First time playing around with JS in console; previously only tinkered with HTML & CSS in Developer tools.  Recall *let* and *variable* from Grasshopper app.
* Happy to be using CodePen.  Later on, would love to experiment with others' Pens or have fun with CodePen Challenges.

**Links:**
* Course:  [Learn JavaScript: Full-Stack from Scratch](https://www.udemy.com/share/101qIyAkoedF9STQ==/)
* Screen shot:  [Played with JS in console of Chrome](https://drive.google.com/open?id=1JsvwvYGR34TGex3mpJhUefDklJ9PUf1d)
* CodePen #1:  [Function tests](https://codepen.io/webdevholland/pen/GRKMRKM) - See instructions in lines 5, 6 & 14 in JS editor of Pen to activate.
* CodePen #2:  [Object example](https://codepen.io/webdevholland/pen/PoYJoey?editors=0010) - See instruction in line 5 in JS editor of Pen to activate.

