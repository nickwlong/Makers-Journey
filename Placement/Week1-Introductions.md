## Day One:
What an interesting day! I started by meeting with my line-manager as an introduction, and we quickly joined the rest of the team for a retro and sprint-planning meeting. Acronyms and words were thrown everywhere - things that I don't yet understand, this will be a bit of a journey!

I did, however, finish setting up my OVO Macbook and was tasked with submitting my first PR. This was just simply adding my email address to two json files, but it was a significant first step. 

Why does it take so long to download command-line tools?!

I then took some time to explore the various GitHub repositories for my team, and explored a bit of TypeScript via Codecademy.

## Day Two:

I started up the day by completing a couple of OVO-Learn courses (welcome videos and quizzes regarding 'Plan Zero' - the company's climate pledge), and had an introduction to the workflow of the team. My mentor demonstrated how CircleCI works with regard to continuous integration and continuous development. The code is uploaded to a test base on AWS first, having already been tested by Snyk and various other processes. After checking that the code is running as intended on the UAT, it can be manually passed to production.

In the afternoon we met with one of the HoD for Software Engineering who introduced us officially to the company, it is a fantastic place to work! 

## Day Three:

My team's documentation is stored on Confluence (Atlassian) and today I was given access to this useful store of notes. With this, I was able to read up a lot on what my team do, the various roadmaps/guides that they have written. This took a big chunk of the day. 

## Day Four:

With my mentor we explored AWS a little, particularly how it can be used to create 'Lambdas', functions that are *serverless* and run as and when they are needed. With this introduction I then went away and followed some tutorials to make basic functions, initially just a 'Hello world' that was return upon sending a get request to the API. And then later I set up an energy cost calculator that would return a total cost to a client upon a *post* request to the API.

Following this, I explored Strava's API as this is well documented, and it also has a webhook that you can access. I then set up access to the API and the webhook to explore a little more.

## Day Five:

I started by continuing more work on the Strava API and joined the team for an estimation meeting. They use a fibonacci numbering system to grade the complexity of tasks:
1
2
3
5
8
13

With my mentor, we explored data pathways e.g. through Kafka and BigQuery. This gave me some further ideas to explore such as middleware

Estimation meeting

Set up Strava webhook and basic strava api interaction. Fixed token authentication and refreshing.