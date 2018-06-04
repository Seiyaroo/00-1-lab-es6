# 1-ES6-practice

## Feature Tasks

Follow these instructions carefully and in order.

1. Open the HTML file in the browser to ensure that it works.
2. Turn all `var` variable declarations into `let`.
3. After you do, there will be one error. Find that line in the code, delete that line and respond to the adjacent TODO item.
4. Return to the browser to ensure that the code works again.
5. **Save the code, and do a Git "add" and "commit".**
6. Now, in the code, convert all `let` variable declarations into `const`.
7. Bugs will erupt everywhere. Debug by using the error messages in the browser console, turning `const` declarations back into `let` where necessary. Expect there to be some back-and-forth between your code editor and your browser.
8. When you think you have things working, clear local storage and reload the page to ensure that the code still works when starting from a totally clean state.
9. **Save the code, and do a Git "add" and "commit".**
10. Now find all concatenations in the code and convert them into template literal notation.
11. Reload the browser to ensure that the code works as expected.
12. **Save the code, and do a Git "add" and "commit".**
13. Answer the following questions:

---

##### Investigate how `let` and `const` are now used in the code. Where did you need to convert `const` into `let` to make the code work? Can you identify any patterns/similarities?

So let is smaller scope than Var, and allows for better management of errors. Because its so narrow you can add stuff and keep it easier to understand where your errors are. Const allows you to keep things very straight forward. Things that wont change can have constant as long as they aren't incrementing, or decrementing, or changing. So I had to change let and const for my counters, so (const to let) to let them work in the whole of the program. I was able to do const on most other stuff labeled var, because those things were never changing. They were simply constant variables, thus const.

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

I definitely like template literals more. Its gonna take some getting used to but it was a lot of fun to see the difference. Also template is much easier to read compared to object literals.
