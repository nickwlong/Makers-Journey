## Day One:
Introduction meetings with two from the team
Met with Alister regarding 
Met with Annebeth and was given my first backend ticket - to update some logic in the smart thermostat API repo. Included writing some unit tests for existing code, writing some new logic and then updating the tests for this logic. 
![my first ticket](https://i.imgur.com/GAYGhEx.png)

For the first part I had to write tests that covered the existing code. To do this, I spent a good amount of time looking over the other test files that already existed in the repository, checking for particular formatting and methods that the team commonly use. I then started to produce my own tests using the same style, including mocking a number of functions and database queries. It was a good challenge, as I had done a little bit of this in the Bootcamp but nothing significant.

## Day Two:

Having mapped out the stages that the end point works through, I was able to create a test for each part. Having completed this, I moved on to updating the logic in the status handler function and changed the existing tests to include my new functionality. 

I realised then that a function that is used within this endpoint also did not have any tests. I enquired as to whether I should write some for this file, and I was given the all-clear! This was a little more complicated as it handled an external API which I had to mock, but again with research and using others code as an example, I was able to produce some tests for this code. 

![](https://i.imgur.com/4bqaVeA.png)

## Day Three:

Following my work on the above ticket, I was then asked to check how this would impact the frontend customer view of their thermostat connection. I had to explore the large repository for this frontend application, finding where our connection status was being used. 

After finding out how our endpoint is accessed and how the returned data is used, I was able to adjust the response from the end point to include what was required to allow a user to reconnect their thermostat if it had expired.

I then worked on writing up a lot of notes on what I have done so far. Admin for the apprenticeship and some further research. I was set an extension to the ticket that I had and had to finish this off.

## Day Four and Five: OOO!

Reflections:
- Research more around 'promises'
- Find more examples of where middleware is used
- Continue to book one-to-one meetings with others in the team
- Don't be afraid to ask questions!