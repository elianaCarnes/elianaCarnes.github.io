---
layout: essay
type: essay
title: "First Impressions of Typescript"
# All dates must be YYYY-MM-DD format!
date: 2025-06-06
published: true
labels:
  - Typescript
  - C++
---

<img src="https://wallpapers.com/images/hd/cool-code-aesthetic-cqzxsy3jp8y5w6xx.jpg" style="width: 100%; height: 200px; object-fit: cover; border-radius: 8px;"> 
---

## Initial Observations
As someone with experience with C++, I can confidently say Typescript is my preference. C++ can often be demanding from a user perspective as it forces the programmer to think about how memory is being managed. I felt that with Typescript I'm able to focus more on problem-solving and worry less about syntax. 

One thing I immediately noticed was how user friendly Typescript is. Although I have only begun to scratch the surface, there are quality-of-life changes that make programming with Typescript feel less restrictive and easier from a user perspective. It is also a very readable langauge and writing logic has been very straightforward so far. For example, I created a function that returns true when a function only contains unique characters, and false when there are duplicates:

```
function isUnique (checkString: string[]): boolean {
    const lengthString = checkString.length;
    for (let i = 0; i < lengthString; i++ ) {
        for (let j = i + 1; j < lengthString; j++) {
        if (checkString[i] === checkString[j]) {
            return false;
            }
        }
    }
    return true;
}
const inputOne = (["a","b","c","d","e","a"]);
console.log(isUnique(inputOne));

const inputTwo = (["a","b","c","d","e"]);
console.log(isUnique(inputTwo));
```
In my experience with C++ there is always an additional step in order to perform tasks you might expect of a programming language. For example, if you were creating a function like isUnique you would have to include headers like <string> just to work with strings in any way. But in Typescript I can just write a function that has a string array parameter, and that's it. There are other small things I appreciate like ASI and type inference that make Typescript a more straightforward experience. 

## My Learning Experience
I really enjoy the readability and flexibility of Typescript. Not only does the syntax itself feel easy to understand but Typescript is very dynamic with what it allows the user to do. This design choice gives the programmer freedom to explore how the different features interact, and ultimately gives Typescript a creative component. With C++ I sometimes felt restricted, and while there are always multiple ways to a solution, there are a lot of limitations and specifics to consider when coding in C++. 

In Typescript I primarily notice this lack of restriction when it comes to objects. With Typescript, objects can be modified and changed with ease. You can even make an object without having a class for the object, which is limited in c++. I feel pushed to experiment and learn the boundaries of Typescript. From a software engineering perspective, I would say Typescript is designed with the programmer in mind. It's been enjoyable to learn about and I would recommend it to others. 
