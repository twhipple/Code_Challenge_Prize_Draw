
# Code Challenge: 

![](https://raw.githubusercontent.com/twhipple/Code_Challenge_Good_VS_Evil/master/Images/tom-barrett-7FNOH-qSxMI-unsplash.jpg)

*This sunset reminds of a war between Good and Evil! Source: Tom Barrett, freeimages.com*


## # Code Challenge Prize Draw
This is a Python coding challenge with a kyu of 6. You take in three values and return the correct name in the form of it's original string.


![](https://raw.githubusercontent.com/twhipple/Code_Challenge_Good_VS_Evil/master/Images/mario-dobelmann-QKBc8uYQDH0-unsplash.jpg)

*It's easy to see in this fern the difference of life and death! Source: Mario Dobelmann, freeimages.com*


## Task
To participate in a prize draw each one gives his/her firstname.

Each letter of a firstname has a value which is its rank in the English alphabet. A and a have rank 1, B and b rank 2 and so on.

The length of the firstname is added to the sum of these ranks hence a number som.

An array of random weights is linked to the firstnames and each som is multiplied by its corresponding weight to get what they call a winning number.

Then one can sort the firstnames in decreasing order of the winning numbers. When two people have the same winning number sort them alphabetically by their firstnames.


## Example
Example:

names: "COLIN,AMANDBA,AMANDAB,CAROL,PauL,JOSEPH"
weights: [1, 4, 4, 5, 2, 1]

PauL -> som = length of firstname + 16 + 1 + 21 + 12 = 4 + 50 -> 54
The *weight* associated with PauL is 2 so PauL's *winning number* is 54 * 2 = 108.

names: "COLIN,AMANDBA,AMANDAB,CAROL,PauL,JOSEPH"
weights: [1, 4, 4, 5, 2, 1]
n: 4

The function should return: "PauL"


## Output:
parameters: st a string of firstnames, we an array of weights, n a rank

return: the firstname of the participant whose rank is n (ranks are numbered from 1)


## Additionally

The weight array is at least as long as the number of names, it can be longer.

If st is empty return "No participants".

If n is greater than the number of participants then return "Not enough participants".

See Examples Test Cases for more examples.

This kata was written by: g964


## Summary
At first I thought this was going to be a pretty easy challenge. 
* Set up a dictionary with numbers for each letter in the alphabet.
* Convert each name to a list of numbers and get the total for each name.
* Add the length of the name to this sum.
* Multiply the total for each name by the corresponding weight.
* Then choose the number given and return the original string.

Turned out to be so much more difficult! I had trouble at each step of the way. Sorting the names at the end, coming up a value for each letter took some research, and putting it all together took a lot of time. But I still had fun and learned a lot.


Thank you to Codewars for helping me practice my Python skills.


![](https://raw.githubusercontent.com/twhipple/Code_Challenge_Good_VS_Evil/master/Images/tech-nick-5YuVGW2deMw-unsplash.jpg)

*Silly little Evil guy on a sign - please enter though! Source: Tech-Nick, freeimages.com *