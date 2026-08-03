# Questions Only

*Help a friend debug a problem by only asking questions.*

**Target Skills: Constructive Inquiry, Verbal Precision, Accessible Communication**

## Task

> The next time anyone asks for help debugging, resolve the issue using only questions. No direct answers. No keyboard-grabbing. No "have you tried..." suggestions in disguise.

Tia, a Python study group member, is learning about first-class functions. She's trying to create a list of five small functions, each of which prints a different number 0 through 4. She said that "they all print the same thing and I don't understand." 

## Process

I wrote open diagnostic questions that would help Tia debug her code by prompting her to articulate her own reasoning and guide her towards surfacing the bug. The difference between open versus closed diagnostic questions is that closed questions ask for yes/no responses or point out the fix right away, while open questions teach more and enable the author to find the bug themselves. Although more time consuming and sometimes frustrating for the author experiencing the bug, open diagnostic questions lead them to better understanding and identifying bugs next time around.

## Deliverable

### My Questions

1. What is the value of `i` when the second loop starts?
2. Walk me through the second `for` loop that appends the functions to the list `funcs`.
3. What do you think is happening inside the `append` call with `lambda`?
4. How did you decide to structure your function with `lambda`? 
5. What do you think `print(i)` is doing by the time the functions are called in the second loop? 
6. Where do you define `i` in your function using `lambda` that is added to the list `funcs`?

## Reflection

_**What do you think the most likely response or outcome would have been?**_

I think Tia would have noticed and responded with "The value of i is 4 when the second loop starts" after I asked my first question. Then, she likely would have responded with verbally tracing through the second loop, and my third question would have prompted the "aha" moment, forcing her to break down the parts of her `lambda` function itself. If necessary, questions 4-6 further hone in on the bug and guide her towards the underlying issue, especially question 6 where I asked if `i` is defined in the functions she's creating and appending.

_**Which question moved the person furthest? Where did you feel the pull to just hand over the answer? What would you do differently next time?**_

I think question 3 would move Tia the furthest because it asks Tia what she thinks is happening when she calls `append` with her `lambda` function, which guides her towards questioning whether what she thinks is happening corresponds to the code she wrote. I felt the most pull to just hand over the answer while thinking about and structuring questions 4-6 because from my perspective, it already felt obvious what the bug was after questions 1-3. However, that might not be the case for Tia, and any programmers I collaborate with in the future. Next time, I would write my questions with a bit more precision and make them more concise and digestible. 