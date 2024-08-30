7 Computer Science for JavaScript: Regex Tutorial
Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

At first, this string of characters and symbols may look like writing in Egyptian. But if one analayzes each of the characters and symbols and what they represent in JS, one can easily learn the ins and outs of the code above. 

As a very visual person, something beneficial for this project was placing the regular expression in the website regex pal. From there, users can test strings. 

The expression that we will be diving deeper into is matching an email. Knowing how to match an email can be useful if you aim to create secure apps through authentification. However, first, let us break down what is happening.

This begins with a ',' which indicates a regex starting, followed by the caret ^ symbol. 

In this particular expression, the next item, we see parentheses. Parentheses capture a group. 

So it is multiple tokens together, and then right after that, we have square brackets, which tell us that this is a character set and matches characters shown within this set. 

In the square brackets, any letter between a-z works fine, then 0-9, same thing just talking about your range of options. Any numbers between 0-9 are ok or can occur here. Immediately following the a-z0-9, there is a_which just means_and then you have an Escape character right after 

Regex Pal is an excellent tool if you are trying to break down the different bits and pieces of a regex

Then we have got a set of an end square bracket there. So then we have a quantifier that occurs next, and basically what this qualifier is saying is you need to match between two and six of the preceding tokens because we have curly braces 

Regex Pal is an excellent tool if one is trying to understand pieces of a regex because it can at first look a little bit scary or intimidating just because it is a big extended group of letters, numbers, characters tokens, dashes slashes +’s 




