#Overview
This is a demo showing how to integrate drizzle with react.js

#Introduction to Drizzle
"Drizzle is the newest member of the Truffle Suite and our first front-end development tool. At its core, Drizzle takes care of synchronizing your contract data, transaction data and more from the blockchain to a Redux store. There are also higher-level abstractions on top of the base drizzle library; tools for React compatibility (drizzle-react) and a set of ready-to-use React components (drizzle-react-components).
 
 We're going to focus on the lower levels today, taking you through setting up a Truffle project with React and Drizzle from scratch. This way we can gain the best understanding of how Drizzle works under the hood. With this knowledge, you can leverage the full power of Drizzle with any front-end framework of your choosing, or use the higher-level React abstractions with confidence.
 
 This will be a very minimal tutorial focused on setting and getting a simple string stored in a contract. It's meant for those with a basic knowledge of Truffle, who have some knowledge of JavaScript and React.js, but who are new to using Drizzle." -- cited from Truffle Suite's Tutorial at: https://truffleframework.com/tutorials/getting-started-with-drizzle-and-react 

#'drizzle' instance and 'drizzleState'
For the most part, drizzleState is there for you to read information from (i.e. contract state variables, return values, transaction status, account data, etc.), where as the drizzle instance is what you will use to actually get stuff done (i.e. call contract methods, the Web3 instance, etc.).