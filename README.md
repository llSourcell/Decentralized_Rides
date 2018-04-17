# Stride-Tokens
What if ride sharing was done via Smart Contracts?

In this project, the goal is to create a web application that will allow users to buy rides without the middle man. A person looking for a ride would put out their request along with a price they are willing to pay. This can be based on the average tokens spent per distance or it can be arbitrary. Drivers would see a list of available ride requests and would initiate the contract to verify that the ride is completed.

Tokens are rewarded proportional to the length of the rides drivers fullfill. The tokens can be sold and bought on the same web application. 

Tokens can be used to pay for rides or they can be bought and sold to others for ethereum.

## In The Future

1. Code up the Node.js server to maintain information pertinent to verifying rides and to append the verification function to the blockchain using the contract owner's address.
1. Flesh out the React.js front end to show people their tokens, offer trading, and display rides.
1. Embed Google Maps to show the routes and to generate the distance data.

One of the biggest challenges: designing and writing the token smart contract, is basically done. The contract will be adapted to do a bit less as the node.js server is built up. In its current state, the 'gas' cost of some of the functionality could be reduced. 
