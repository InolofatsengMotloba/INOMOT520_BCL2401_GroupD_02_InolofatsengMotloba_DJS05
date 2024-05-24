# DJS05: Building a Redux-Inspired Store for a Tally App

In this challenge, I ventured into the realm of state management by constructing a Redux-inspired store to manage the state of a simple Tally App. My primary goal was to manage the app's state changes efficiently, focusing on core functionalities like incrementing, decrementing, and resetting a counter. Instead of rendering changes on the UI, I subscribed to state updates and logged them to the console, highlighting the power of state management in applications.

## Achievements

### SCENARIO 1: Initial State Verification
`
When the 'getState' method is executed, and the result is logged to the console with the browser console open, the state displays a count of 0
`

### SCENARIO 2: Incrementing the Counter
`
By dispatching an 'ADD' action twice without any prior interactions & with the browser console open, the state displaying a count of 2, incrementing the count by 1 for each dispatch
`

### SCENARIO 3: Decrementing the Counter
`
Given the initial count in the state is 2, upon dispatching a 'SUBTRACT' action with the browser console open, the state reflects a count of 1
`

### SCENARIO 4: Resetting the Counter
`
Given the current count in the state is 1, the achievement occurs when dispatching a 'RESET' action with the browser console open. In this scenario, the state displays a count of 0
`

## Overview of approach

This JavaScript setup has a main storage place called a store that handles all the information about how the Tally App works. It uses a `reducer` function to decide what happens when you do something in this app.

There's a piece of data called `count` which starts at zero. When you do things like adding, subtracting, or resetting, these actions cause changes to the 'count'.

The store makes sure everything runs smoothly. When you do something in the app, the store uses the reducer to figure out what the new 'count' should be. It then notifies of any changes made in order to make updates. 

I stored everything in separate scripts to organize things makes it easier to manage the data in the app. It helps keep things clear, easy to understand, and able to grow as the app gets more complex.

## Challenges

Challenges include frustration when encountering bugs or unexpected behaviors when importing and exporting. I also experienced self-doubt and anxiety because of the unfamiliar concepts. Balancing the desire for perfection with the need to deliver results was also difficult.

