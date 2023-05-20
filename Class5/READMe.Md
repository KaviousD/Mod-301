# Introduction to React and Components

## Why It's Important

This information is important because it explains the best way to determine if something is a state.


## Reading Q&A

### **Putting it all together**

<https://react.dev/learn/thinking-in-react>

**What is the single responsibility principle and how does it apply to components?**

-  **Single Responsibility Pricinple:** a computer programming principle that mentions "A module should be responsible to one and only one actor."

It applies to components because they have one fuction. If it does multiple things, it should be broken down into smaller additional components to minamize the stress of coding alot into one. 



**What does it mean to build a ‘static’ version of your application?**

- A static verison of your applications means that it lacks interactivity.



**Once you have a static application, what do you need to add?**

- You can add elements that make the application interactive.

**What are the three questions you can ask to determine if something is state?**

1. Does it change over time? 
2. Are props passed in from a parent? 
3. does the code have errors thourgh missing componets not passed from props.

**How can you identify where state needs to live?**

1. You can put the state directly into their related parent. 


2. You can tag state into some component mentioning their related parent.



### **Higher-Order Functions**

<https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK>

**What is a “higher-order function”?**

- functions that operate on other functions by taking them as argument or by returning 



**Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**

Code from the Reading:


function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true

- the function is comparing the variables and anything that is greater than m will be true and less than m will be false line two of the function is returning m as it being greater than n 

**Explain how either map or reduce operates, with regards to higher-order functions.**

- it operates on collections (such as arrays or lists) and applies a given function to each element, returning a new collection with the updated elements

## Things I Want to Know More About