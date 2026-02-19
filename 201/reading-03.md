# Learn HTML

## When should you use an unordered list in your HTML document?

When you need to make a list and you don't care about the order it's in.

## How do you change the bullet style of unordered list items?

List-style-type

## When should you use an ordered list vs an unorder list in your HTML document?

When you care about the order of your list

## Describe two ways you can change the numbers on list items provided by an ordered list?

By setting the numbering type using attributes such as: a, A, i, I or 1

# Learn CSS

## Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Margin, legendary knight of the south border and padding, legendary knight of the north border. Margin protects the outside of the border while padding protects the inside.

## List and describe the four parts of an HTML elements box as referred to by the box model.

margin, border, padding and content

# Learn JS

## What data types can you store inside of an Array?

Any type 

## Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

Yes, pull from the array using it's index, like:
people[0][0] = 'pete'

## List five shorthand operators for assignment in javascript and describe what they do.

+= add and assign
-= subtract and assign
*= multiply and assign
/= divide and assign
%= modulus and assign

## Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

The final result would be '10dog' because you can't add a number to a boolean so just the number is added  turning the problem into '10 + dog'

## Describe a real world example of when a conditional statement should be used in a JavaScript program.
let fuel = low

if {
    fuel is low
    then
    go to a gas station
}

## Give an example of when a Loop is useful in JavaScript.

When you have code you want to repeat like:

let answers = ['rpg', 'fps', 'horror', 'simulation'];
let attempts = 6;
let correct = false;

while (attempts > 0 && !correct) {
    let guess = prompt(
        'What type of game genre do I like the most? (' + attempts + ' attempts left)'
    ).toLowerCase();

    if (answers.includes(guess)) {
        alert('Correct!');
        correct = true;
    } else {
        attempts--;
        alert('Wrong!');
    }
}
