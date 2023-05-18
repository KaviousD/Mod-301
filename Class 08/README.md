# Introduction to React and Components

## Why It's Important

This information is important because it breaks down the design of APIs while providing practices for it. This teaches us how we need to create APIs and the diffrence between codes depending on wheather we executed code coreectly or not.
## Reading Q&A

### **API Design Best Practices**

<https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design>

**What does REST stand for?**

- Representational State Transfer

---

**REST APIs are designed around a ____.**

- resource

- any kind of object, data, or service that can be accessed by the client

---

**What is an identifier of a resource? Give an example.**

- A resource has an identifier, which is a URI that uniquely identifies that resource.

---

**What are the most common HTTP verbs?**

- Get

- Post

- Put

- Patch

- Delete



**What should the URIs be based on?**

- URIs should be based on nouns (the resource) and not verbs (the operations on the resource)



**Give an example of a good URI.**


https://adventure-works.com/orders/1




**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

- A "Chatty" web API release large numbers of small resources. It is bad to have a chatty API for this reason



**What status code does a successful GET request return?**

- It'll return HTTP status code 200 (OK)



**What status code does an unsuccessful GET request return?**

- It'll return HTTP status code 404 (Not Found) or 204 (No Content).



**What status code does a successful POST request return?**

- It'll return HTTP status code 201 (Created)



**What status code does a successful DELETE request return?**

- It'll respond with HTTP status code 204 (No Content). This indicates that the process has been successfully executed.

### Bookmarks & Review

**RegExr*Cheatsheet**
<https://regexr.com/>

**Regex Tutorial**
<https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285>

**Regex 101**
<https://regex101.com/>


## Things I Want to Know More About

**What's the difference between URI and a URL???**
They both sound the same but have diffrent meanings
