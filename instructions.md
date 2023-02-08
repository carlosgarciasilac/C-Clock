# Instructions
Implement a clock that handles times without dates.

## Part 1 - Let's format the output!
Make a class that can store the time of day and display it in 24 hours format, also known as "HH:mm". For example, if we start the clock with 2 hours and 10 minutes it should display "02:10".

## Part 2 - Add minutes
We want to be able to add minutes to the clock and have the time still make sense. Remember that the date doesn't matter, only the time of day.

## Part 3 - Substract minutes
Now that the clock can go forward, it should also be able to go backwards!

## Part 4 - Compare clocks
Once the clock can add and subtract minutes, we want to know that two clocks are equal if they end up having the same time of day.

## Part 5 - Immutability
Consider making the clock instances immutable

# Hints
- Try not to change the method signatures unless you think it's necessary
- You might want to override the ToString method for the class and format the time there
- Consider minutes and hours overflowing and underflowing
- There are test cases written but we encourage you to also write some if you need to

# Solving this problem with Replit
Replit lets us use a common environment that doesn't need local setup and can be shared! Because of some limitations with test projects in .Net core the run button doesn't do anything. 

To run you can open a console (on the left toolbar you will find a section called Tools and you can open a console there, if there's not one open already). Once in the console you can run the unit tests by using:
```bash
dotnet test
```

If you want the tests to run continually as you do edits to the problem you can use:
```bash
dotnet watch test
```