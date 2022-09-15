# Week 8 - Learning a new language

## Weekly Goals

1. Describe a process for learning a new language
2. Follow an effective process for learning a new language
3. Compare and contrast Javascript and Ruby
4. Test drive a simple front-end web app with Javascript

#### Plans to achieve:

I started the week by asking the question: What would my plan be if I were to start learning another new language tomorrow? 

The main aim will be able to follow specifications to build simple programs in Javascript using TDD and OOD. I will then look to create front-end web apps using Javascript. Test-driven development needs to be at the core of all of this.

1. Use the Makers resources to develop my understanding of the Ruby language
2. Apply what I have learned to drills and small projects
3. To work with others via pair programming to refactor my code

#### Evidence:
1. **Basics of JS** I started by reviewing what I already knew about JavaScript, having worked with it a little before. I found I was confident in using its arrays, functions, and objects but needed a little practice applying its syntax. So I had a go at coding some simple programmes using Jasmine to test the code [for-example](https://github.com/nickwlong/Learning-Javascript/tree/main/1.%20Test-driving%20JS/JasmineWhat/src)
2. **Testing JS development**I then moved on to coding a [thermostat](https://github.com/nickwlong/Learning-Javascript/tree/main/1.%20Test-driving%20JS/Thermostat) using Jest instead to test my code during development. I was missing the brilliant html interface that Jasmine provided, so found out that I can use `jest --coverage` to provide coverage checks and an html interface for showing the code.
3. **Interacting with APIs..** What the Geoff is JSON.parse, and what is GOT and what is the response? How do these callbacks work!?
  This step threw up some big blockers. I had to learn what callbacks were, to ensure that APIs were accessed and handled in order. I also had to get to grips with what JSON was providing (parses text into a data object). I managed to set up access to APIs of [GitHub](https://github.com/nickwlong/Learning-Javascript/blob/main/1.%20Test-driving%20JS/GitClient/githubApi.js) repositories, and for accessing [weather](https://github.com/nickwlong/Learning-Javascript/blob/main/1.%20Test-driving%20JS/WeatherApp/index.js) in certain locations. 

  **This led into exploring Express for handling routes in JavaScript -> the next logical step from handling APIs, in the hope that I can attempt the Chitter API challenge. I used a combination of the Makers express resources, and Codecademy's 'Learn Express Routes' course.**

4. **Build Javascript Web Apps**
  To start building Javascript Web Apps I needed to learn how to create dynamic JavaScript that can update web pages, and how to test drive this. To do so, I learned how to use Jest-environment-JSDOM.

  Wednesday - explored how to make clickable buttons that lead to changes on the page, using functions such as createElement to create new elements if necessary on a page. Spent some time pairing on APIs too.

5. **Mid-week challenge**
 ["Ten Minute Walk"](https://www.youtube.com/watch?v=ilXMqA8RsNE) was our mid-week challenge, where we were tasked with writing a function to check if some directions would allow us to finish where we started and that the walk would take exactly 10 minutes. I wanted to practice OOD so I decided to make a class with methods to complete the task.

6. **APIs in Web Apps**
  I have now come far enough through the web applications module to come against API calls again, it makes a lot more sense now that I have worked through APIs as a pair. Looking forward to using them to make interactive pages.

7. **JS is asynchronous, the horror!**
  Working with servers and accessing/storing data makes working with JS' asynchronous nature quite the challenge! I managed to get my head around the use of callbacks and created a functioning notes page which:
  - Adds notes to the server
  - Reads notes from the server and lists them on the page
  The issue was testing! Running Jest with 'expect' statements wouldn't work after using the database, as they would run asynchronously. So I have explored async functions and the use of await. VERRY interesting. Tests are now working and I'm looking forward to the next challenge.
## Daily Goals
  
  
## Reflection


### Question 1

*Did you meet all of your goals to the standard you set at the start of the week?*



### Question 2

*What would you change/improve moving forward?*


**Technical:**


**Personal:**