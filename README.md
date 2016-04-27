# FP7-Slime Volleyball

##Authors
Cameron Oliver

Kenny Sanders

##Overview
The classic browser game Slime Volleyball has been implemented in your favorite functional programming language.  Play as the humble half circle slime in the fight to make the a small yellow circle land on your opponent's side of the screen!  With multiplayer or AI support (Player 1 moves left to right wih A and D and jumps with W, Player 2 if playing uses the arrow keys).

##Screenshot

![alt tag](https://raw.githubusercontent.com/C4m0/FP7-webpage/master/Gamplay.jpg)
![alt tag]https://raw.githubusercontent.com/C4m0/FP7-webpage/master/Architecture.jpg)

##Concepts Demonstrated
Identify the OPL concepts demonstrated in your project. Be brief. A simple list and example is sufficient. 
* **Data abstraction** is used to provide access to the elements of the RSS feed.
* The objects in the OpenGL world are represented with **recursive data structures.**
* **Symbolic language processing techniques** are used in the parser.

##External Technology and Libraries
Briefly describe the existing technology you utilized, and how you used it. Provide a link to that technology(ies).

##Favorite Scheme Expressions
####Mark (a team member)
Each team member should identify a favorite expression or procedure, written by them, and explain what it does. Why is it your favorite? What OPL philosophy does it embody?
Remember code looks something like this:
```scheme
(map (lambda (x) (foldr compose functions)) data)
```
####Lillian (another team member)
This expression reads in a regular expression and elegantly matches it against a pre-existing hashmap....
```scheme
(let* ((expr (convert-to-regexp (read-line my-in-port)))
             (matches (flatten
                       (hash-map *words*
                                 (lambda (key value)
                                   (if (regexp-match expr key) key '()))))))
  matches)
```

##Additional Remarks
Anything else you want to say in your report. Can rename or remove this section.

#How to Download and Run
You may want to link to your latest release for easy downloading by people (such as Mark).

Include what file to run, what to do with that file, how to interact with the app when its running, etc. 

