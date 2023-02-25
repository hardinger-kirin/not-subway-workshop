# Welcome to "Not Subway"!

## Project Goals
1. Solidify our knowledge about looping
2. Review selection
3. Make tasty sandwiches! :blush::sandwich:

## Important Notes
* Do __not__ skip straight to the solution! You should work through this README document and try it on your own. If you get stuck, come to my workshop hours or ask a follow-up question on __Piazza__ to the original discussion where I posted this problem.
* Follow best practices for programming. Your code should be neat and organized (that means using indentation to section your code!) and have plenty of comments throughout. Confused? Come to my workshop hours to discuss! :blush:
* This is __not__ an actual assignment! ***You will not clone this repository and push to it.***

## Program
__Welcome to _“Not Subway”_!__ :sandwich: We’re going to make a program that simulates a build-your-own sandwich shop. 
The program asks the user to add toppings for as long as they want by using loops. To review selection, we will also display a unique message back to the user based on the number of toppings they added.

## Requirements
First, the user should be greeted. :wave:

Then, we allow the user to enter as many toppings as they want to their sandwich. This input is a single `char`, for example a user might input `T` for tomatoes. ***IMPORTANT HINT:*** __we do not need to save every single topping the user inputs into a new variable!__

To exit the topping selection process, the user can type in `0` to finish the sandwich. ***IMPORTANT HINT:*** __the character `'0'` is different from the integer `0`!__

Finally, the user is displayed a unique message based on the number of toppings they added to their sandwich. 

If the number is 0 :yawning_face: :
`"So... just bread?"`

If the number is anywhere between 1 and 3 :raised_eyebrow: :
`"Wow! Are you sure you don't want more...?"`
    
If the number is anywhere between 4 and 7 :star_struck: :
`"What a balanced sandwich! Yum!"`
    
If the number is anywhere over 8 :scream: :
`"Ummm... I don't think this can fit in the wrapper..."`

## Example Program Execution
***IMPORTANT NOTE:*** __These three outputs are only examples showing the 4 outcomes of the number of toppings. Try running the executable in this repository, `not-subway`, and putting in your own inputs to see what happens!__

0 toppings:

<img width="669" alt="image" src="https://user-images.githubusercontent.com/89322661/221372039-6d88307d-a061-4767-b17f-32a9a0715dac.png">

---

1-3 toppings:

<img width="666" alt="image" src="https://user-images.githubusercontent.com/89322661/221372091-35d14c3f-62b8-408a-b9c0-033abf1fa491.png">

---

4-7 toppings:

<img width="664" alt="image" src="https://user-images.githubusercontent.com/89322661/221372129-83ad8620-57c0-4da0-8db6-38d8b6383d0f.png">

---

8+ toppings

<img width="662" alt="image" src="https://user-images.githubusercontent.com/89322661/221372162-68ae17a6-d3ed-4b47-a5af-4454a38152b9.png">

# Now it's time to give it a try!
## Need help? Post a follow-up question to the original Piazza discussion post __or__ ***come to my workshop hours!***

---

## Bonus!
### The first part of the assignment covers while loops and if/else if/else statements. Want to do more? __Let's add a for loop component!__

The base price of a sandwich at Not Subway :sandwich: is `$5`.
For every topping added to the sandwich, it costs the user `$0.20`.
Using a for loop, tally up the user's total and display the final total to them!

### Example Output

0 toppings:

<img width="658" alt="image" src="https://user-images.githubusercontent.com/89322661/221373652-58a0b14c-76e2-4872-9959-d4fcad3fd6ad.png">

---

1-3 toppings:

<img width="667" alt="image" src="https://user-images.githubusercontent.com/89322661/221373671-67f58406-a392-4d61-90c8-d771d3c8f226.png">

---

4-7 toppings:

<img width="661" alt="image" src="https://user-images.githubusercontent.com/89322661/221373678-ed5c7757-c949-4e29-9302-afe4a7f27b50.png">

---

8+ toppings

<img width="661" alt="image" src="https://user-images.githubusercontent.com/89322661/221373693-58a88b4f-b684-4f4d-be6f-12bbaa56f9ad.png">
