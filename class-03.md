# Read: Class 03 - HTML Lists, CSS Boxes, JS Control Flow

## HTML - OL and UL

1. You should use an *unordered list* when you want a list that does not have a particular order. These are usually bulleted lists.
2. To change the *bullet style* of unordered list items, you should use the *list-style-type* property in CSS.
3. You should use an *ordered list* when making a numbered list, such as step-by-step instructions. You should use an *unordered list* when you don't need to be ordered, such as a grocery list.
4. Two ways you can change the numbers on list items from an ordered list are by using Roman Numerals and by using nesting lists.

## CSS - The Box Model

1. The role of *margin* in the box model is to be the outermost layer of the box which wraps around element and provides whitespace between the box and other elements. The role of *padding* is to create space around element within the border.
2. The other two parts of an HTML element are *border* and *content*. Border is the area between the padding and margin. Content is the actual element itself.

## JS - Arrays, Operators and Expression, Conditionals, Loops

1. Data types that can be stored inside an Array are strings, numbers, objects, and other arrays.
2. Yes the people array in this example is a valid JavaScript array. The stored values can be accessed in the console log by typing console.log(people).
3. 5 shorthand operators for assignment in JavaScript are:

- Addition assignment ( x += f() ): adds the value of the right operand to a variable and assigns the result to the variable
- Division assignment ( x /= f() ): divides a variable by the value of the right operand
- Left shift assignment ( x <<= f() ): moves the specified amount of bits to the left and assigns the resule to the variable
- Bitwise OR assignment ( x |= f() ): uses the binary representation of both operands and assigns the result to the variable
- Logical AND assignment ( x &&= f() ): operator only assigns of x is truthy

4. The last expression (a + c) + b, or (10 + false) + dog would evaluate to 10dog, because the variable false has no value, so the expression in the parenthesis would evauluate to 10 and then value dog would be added to that.
5. A conditional statement can be used in a JavaScript program when a decision or situation with different outcomes is involved. A real world example would be if I had to choose between buying two cheap candles verses one nice candle.
6. Loop is useful in JavaScript when a user gives an invalid response to a prompt. The code block will loop back to the prompt until the user gives a valid response. Loops can also be used to display an array as a list.
