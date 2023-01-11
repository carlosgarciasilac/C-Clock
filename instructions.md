# Instructions

Implement a clock that handles times without dates.

Printing the clock should format the time as "HH:mm"

You should be able to add and subtract minutes to it.

Two clocks that represent the same time should be equal to each other.

# Running (Not the green button)
On the left toolbar you will find a section called Tools and you can open a console there. Once in the console you can run the unit tests by using this command

```bash
dotnet test
```

If you want the tests to run continually as you do edits to the problem you can use

```bash
dotnet watch test
```

# Hints
You might want to override the ToString method for the class and format the time there.