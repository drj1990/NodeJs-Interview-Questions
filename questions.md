# Interview Preparation Questions

## JavaScript Questions

- What is callback hell? How can you demonstrate it using
  `setTimeout`?
- What is the difference between Promises and `async/await`?
- How does error handling work in Node.js and JavaScript?
- Explain the JavaScript event loop.
- How does the event loop work internally in Node.js?
- What is the `this` keyword in JavaScript?
- How does `this` behave in the global scope?
- How does `this` behave inside a normal function?
- How does `this` behave inside an inner function?
- How does `this` behave inside an arrow function?
- Arrow function vs normal function: how does `this` differ?
- What are closures?
- What is hoisting?
- What is the scope chain?
- Explain `call()`, `apply()`, and `bind()`.
- What is the difference between `Promise.all()` and
  `Promise.allSettled()`?
- How do `module.exports` and `require()` work?
- How do you export functions without using classes?
- How do you export and import classes?
- Practice JavaScript output-based questions.
- Input: [ ['a', 1], ['b', 2] ] ➝ Output: { a: 1, b: 2 }
-

## Node.js Questions

- How is Node.js different from other backend technologies?
- How does error handling work in Node.js?
- Explain the internals of Node.js.
- What is the Node.js event loop?
- What is event-based or event-driven design in Node.js?
- What are buffers in Node.js?
- What are streams in Node.js?
- What is a child process in Node.js?
- How do you prevent memory leaks in Node.js?
- How do you identify a memory leak?
- What is middleware?
- How does JWT authentication work?
- What is the difference between `package.json` and
  `package-lock.json`?
- How would you design an event-driven Node.js application?

## SOLID Principles and Design Patterns

- What are SOLID principles?
- Explain each SOLID principle with an example.
- What is Dependency Injection?
- Why is Dependency Injection useful?
- Explain the Singleton design pattern.
- Explain the Factory design pattern.
- Explain the Observer design pattern.
- When would you use Singleton, Factory, and Observer?
- How is the Observer pattern related to event-driven systems?

## MySQL and Database Questions

- What are ACID properties?
- Explain Atomicity, Consistency, Isolation, and Durability.
- What is database normalization?
- Why do we normalize a database?
- What are database transactions?
- How do transactions work?
- What are the different types of keys in MySQL?
- What is a primary key?
- What is a foreign key?
- What is a candidate key?
- What is a composite key?
- What is indexing in MySQL?
- How does an index work internally?
- When should you create an index?
- What are the disadvantages of indexing?
- How do you identify slow queries in a production system?
- How do you analyze a slow MySQL query?
- How do you improve the performance of a slow query?

## MongoDB Questions

- What is indexing in MongoDB?
- How do MongoDB indexes work?
- MySQL indexing vs MongoDB indexing.
- What is aggregation in MongoDB?
- Explain the MongoDB aggregation pipeline.
- How do you identify slow MongoDB queries?
- How do you optimize MongoDB queries?

## Microservices and Distributed Systems

- How do you ensure security in microservices?
- How do you authenticate communication between microservices?
- How do you authorize requests between services?
- How do you ensure data consistency in a distributed system?
- What is eventual consistency?
- How do you handle distributed transactions?
- What happens if one microservice fails during a multi-service
  operation?
- How do you handle retries?
- How do you prevent duplicate processing?
- What is idempotency?
- What is a service registry?
- Why is service discovery required in microservices?
- How does one service communicate with another service?

## Serverless Questions

- What is serverless architecture?
- What are the principles of serverless architecture?
- Serverless vs traditional server architecture.
- What is a managed service?
- Serverless vs managed services.
- What are the advantages and disadvantages of serverless?
- When should you use serverless?
- When should you avoid serverless?

## AWS Lambda Questions

- What is AWS Lambda?
- How does AWS Lambda work?
- How do you write and deploy a Lambda function?
- How do you connect Lambda with API Gateway?
- How do you trigger Lambda using S3 events?
- How do you connect Lambda to MongoDB or another database?
- What is the maximum Lambda timeout?
- What happens when a Lambda function times out?
- What is an API Gateway timeout?
- What happens if Lambda execution takes longer than the API Gateway
  timeout?
- What are Lambda Layers?
- Why do we use Lambda Layers?
- What is a Lambda cold start?
- How can you reduce Lambda cold starts?

## AWS Questions

- What is Amazon S3?
- How does S3 work?
- How do S3 events trigger Lambda?
- Explain the S3 + Lambda architecture.
- What is DynamoDB?
- When should you use DynamoDB?
- DynamoDB vs MongoDB/MySQL.
- What are EC2 Security Groups?
- How do Security Groups work?
- What is a NACL in AWS?
- What is the difference between a Security Group and NACL?
- What is Amazon Aurora?
- Aurora vs MySQL.
- How do you deploy a service on EC2?
- How do you expose an EC2 application port publicly?
- How do you deploy multiple services on one EC2 instance?
- How do two services running on EC2 communicate?
- What is ECS?
- How do you deploy a service to ECS?
- How do two ECS services communicate?
- How do you expose an ECS service publicly?

## System Design Scenario: Image Upload → Lambda Adds Watermark

- Design a system where a user uploads an image and Lambda adds a
  watermark.
- Where should the original image be stored?
- How will Lambda be triggered?
- How will you prevent API Gateway timeout?
- What happens if image processing takes too long?
- How will you handle Lambda timeout?
- Where will the watermarked image be stored?
- How will you track image processing status?
- How will you retry failed image processing?
- How will you prevent the same image from being processed twice?
- How will you scale the system for millions of image uploads?
- Should image processing be synchronous or asynchronous?
- Would you use S3 events, SQS, or API Gateway? Why?

## DSA and Logical Coding Questions

- Flatten a nested object.
- Flatten a nested array.
- Convert an object to an array.
- Convert an array to an object.
- Solve the House Robber problem.
- Solve Sliding Window problems.
- Solve the Container With Most Water problem.
- Practice array-based logical questions.
- Practice string-based logical questions.
- Practice 2D array problems.

## Git Questions

- What is `git rebase`?
- What is the difference between `git rebase` and `git merge`?
- When should you use rebase?
- What are the risks of rebasing a shared branch?