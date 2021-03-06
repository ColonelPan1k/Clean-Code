# Table of Contents

1.  [Three Steps to Clean Code](#orgeca80c9)
    1.  [Step 0: Have a roadmap](#org330f830)
    2.  [Step 1: Make it work](#orgcf15dd2)
    3.  [Step 2: Tests](#orgcfc3d28)
    4.  [Step 3: Make it clean](#org4375784)
    5.  [Step 4?: Make sure it works](#org4422bdc)
2.  [Tests](#orgb701bd7)


<a id="orgeca80c9"></a>

# Three Steps to Clean Code

This is adapted/heavily inspired by a series of talks given by Robert "Uncle Bob" Martin.
They can all be watched [here](https://www.youtube.com/watch?v=7EmboKQH8lM).  It's a long series that I highly recommend watching.
This document is a mix of notes I've complied throughout watching the lessons, along with


<a id="org330f830"></a>

## Step 0: Have a roadmap

-   Know what you want to make
-   Know what you need
-   Know, generally, how to get there


<a id="orgcf15dd2"></a>

## Step 1: Make it work

In this step, the goal is to just make the computer do what you want it to do.
Don't worry too much about how clean the code is at this stage, just lay down
the groundwork and get something down. i.e. Make the code computer readable

The first thing to do when starting out with code is to make it work. You can't
iterate over something that doesn't work or doesn't exist. Get the code to do
the bare minimum of what is required.


<a id="orgcfc3d28"></a>

## Step 2: Tests

In his talks, Uncle Bob stresses, above all, that the most important thing you
can do in the pursuit of clean code is to write tests for everything.

The only way to be confident in your system, and the only way to consistently
iterate over what you've done, is to write thorough tests for your code.


<a id="org4375784"></a>

## Step 3: Make it clean

In this step, the goal is to iterate over the original code and make it human readable. Simplify functions,
create new functions, and think of ways to make the core logic of the code more understandable.  In this step,
it becomes easier to see/understand the bigger picture.

-   Clean up the code
-   Make it human readable
-   Generalize the code
-   Find better ways to do things than what was in the original code
-   Look out for side effects


<a id="org4422bdc"></a>

## Step 4?: Make sure it works

-   Write lots of tests for each function
    -   This will ensure you understand exactly what's going on
-   Make sure the code does exactly what you want it to do and nothing more

-> Repeat Steps 2 and 3 until the code is as clean as possible, then sleep on it.
   We're shooting for zero WTFs/min

-   Something is not finshed if it's not clean, organized, and well-tested.
    And something is not finished if you don't understand it.

-   You can make a mess all you want, just make sure you clean up after yourself


<a id="orgb701bd7"></a>

# Tests

Code coverage should be all-or-nothing. Assume untested code is broken by
default.

Testing should be an integral part of the development process/iteration cycle,
not something that happens after the fact.

Tests can be a great starting point to scaffold out what you want to happen. You
can write tests before you start to make sure the end product does what you want
it to do. You can then add on to those tests during development to further test
other areas of the code

QA is not the group that finds bugs

-   Test automation
