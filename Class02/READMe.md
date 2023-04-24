# reading notes for mod 3 class 02

## Reading


**React lifecycle**

+ Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
based off the diagram render came first

+ What is the very first thing to happen in the lifecycle of React?
the constructor came first in the mounting collum. 

+ Put the following things in the order that they happen: *componentDidMount*, *render*, *constructor*, *componentWillUnmount*, *React Updates*
Constructor, render, react updated componetdidmount, componetDid update, componetwillupdate

+ What does componentDidMount do?
After the componet is mounted this method can be invoked to load any material using network request or dom. setState() can be called here, however not much because it can lead to performance issues.



## Videos

**React State Vs Props**

+ What types of things can you pass in the props?

We can store compnets in the props

+ What is the big difference between props and state?
props we pass into the componet, state is handeled inside the componets

+ When do we re-render our application?

if we want to change somthing in our browser we use state to rerender this.

+ What are some examples of things that we could store in state?
we can store updated values or constant changing values

## Things i want to know more about

when to use state and props accordingly