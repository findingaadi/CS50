# Introduction

This was the first day of CS50 class, and the initial lecture was an introduction to computing from the base up.

- Just to remember when i come back here for revision, these are the bullet points.
- Unary is single digit. Binary means what can represent two digits i.e., 1 or 0.
- bit is 0 or 1, remember the bulb example.
- those bulb concept here is in computer transisters, i.e., it passes electricity, 0 being off and 1 being on. There are million such transisters in a computer system we have today.
- Patterns of 8 bits represent a byte and a pattern of bytes is the base of a computer system.
- ASCII chart can be used to map alphabets starting from 64 in decimal. It also got other symbols.

This is the ASCII chart: 
<img src="https://github.com/findingaadi/CS50/blob/main/Images/img1.png">

- This set of 8 bits = 1 byte is enough to represent characters upto 255, but if there are more than that, for example some languages have more than 255 characters or emojis, for this there is a solution where you add more than 1 byte to represent it.

- The solution is called "Unicode", which is used to map a language in digital form. If we use 32-bit to represent character on a keyboard, it can have 4 billion+ permutation & combination.

- Emojis for example are not an image but a character which is why ios, android represent it differently as they have different font for it.

- For complex emojis, for example a couple, instead of making new representation for it from scratch, it uses combined unicode of two people and put them together to make the new couple emoji. (one emoji)(another emoji)+(how to assemble them). An emoji is represented by emoji bits+ identifier of colour bits.

- For colours, each colour is represetned in pixels with 3 bytes(red, blue, green) and based on the composition of these 3 bytes a pixel gets its colour.

- similarly, when there is an image, a video is just a sequence of these images.

- To introduce an algorithms concept, its like searching for contacts; how we would search an actual phonebook. this is to determine how search algorithm works.

<img src="https://github.com/findingaadi/CS50/blob/main/Images/img2.png">

- The next part of the lecture was explaining the basic concepts such as loop, function, etc via a visually representing software called Scratch.
