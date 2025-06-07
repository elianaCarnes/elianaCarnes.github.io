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
With most of my experience being in C++, learning TypeScript has been an enjoyable experience. C++ is a solid language that allows for a deeper understanding of how memory is managed on a computer, but TypeScript is more forgiving and clearly designed with the programmer as a priority. With TypeScript, I feel I'm able to spend more time on the logic of my code and worry less about strict type declarations and issues like memory leaks. 

One of the first things I came to appreciate was how user-friendly TypeScript is. Even though I am new to using TypeScript I have noticed how it feels less restrictive. The syntax is straightforward and allows me to write freely without encountering as many hurdles. For example, I created a function that returns true when an array pf strings only contains unique characters, and false when there are duplicates:

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
In C++, a function like isUnique would have required a few extra steps. I would need to include the string header, and make sure that all data types are properly declared. While these are small changes, you notice these differences when writing code. Not having to deal with these details allows for TypeScript to feel less restrictive overall. With TypeScript, I do not have to worry that I forgot to include a header or forgot to specify a datatype. If I want to use a string array as a parameter, I can just define it and allow the language to infer the type. The experience of programming with TypeScript feels more focused on creating logic. 

## My Learning Experience
TypeScript has been enjoyable to learn because of its simplicity and how easy it is to read. It is easy to look at a function and follow the logic, even without comments. The syntax has been very straightforward, and with features like type infrence and automatic semicolon insertion it's clear that the language was designed with the programmer in mind. I get to write less code and spend less time fixing small errors. With TypeScript, I feel more creative and focused on solving problems, and I'm able to focus more on my logic and trying different things. 

Another difference I have noted between TypeScript and C++ is how objects work. In C++, creating and using an object is strict and requires that a struct or class be defined independently. But with TypeScript, objects are much more flexible. You can define objects without defining a class and you're able to change properties and alter data freely without requiring a fully created class or struct. Without spending as much time setting up objects, they feel more simple to use and can be applied with less constraints. In my opinion, TypeScript is designed with the user in mind and is overall less restrictive than C++. So far, I have enjoyed learning about it and I would reccomend TypeScript to others. 
