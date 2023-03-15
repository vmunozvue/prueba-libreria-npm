# NPM Library
Creation and publication of a typescript library in npmjs

## Getting Started
Some interesting links to understand the project

- [🖥️  How to publish a typescript library in npmjs](https://itnext.io/step-by-step-building-and-publishing-an-npm-typescript-package-44fe7164964c)
- [⏳  Classes in typescript:](https://www.typescriptlang.org/docs/handbook/2/classes.html)




## ✅ Tutorial of how I created the typescript library and published it to npmjs 

⚠️ It's crucial to follow the process step by step to not carry any error during the developing

First of all we init our package with the following command:


```bash
npm init -y
```


Now we can start and create the content of the library in my case I created a class Calculator with 4 different functions(add, substract, multiply and divide).

There are more steps following but there are git and typescript basics son we will move on and focus on the publication of the library in npmjs

In order to publish the library is so simple as running the publish npm command:


```bash
npm publish
```
Some errors could triger on this part involving test or also some errors from typescript directly(e.g. using console.log)


If everything works well we will have our library published on npm and can be accesible by the following URL: https://npmjs.com/package/<your-package-name> ⭐️