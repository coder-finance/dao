CoderDAO solves finding "manpower" problem.

### Functions
1. Community organizer. Use governance to aquire tokens and vote decisions and implement them together. 
2. Funding organizer. Project management tool with focus on funding. Tracks and automates contributions to job done.

Scaling via becoming a platform for projects.

More just dispute resolution.

### Case 736
You a company that wants to use this library for your needs.
You decided to integrate it into your software.
You create a task on the platform for the project to contribute with a certain feature.
You get job well done without hiring consultants.


### Case 862
Indie dev groups want to grow up as fast as they can no matter cost, because they want to secure investment. 
You need a lot of manpower but you don't have funds.
You decided to run this as an open source project on the platform and invite contributer that are paid in IOU.
You get your manpower and once the project is released, IOU become real stuff.

![[aws startup loft ny ideation.pdf]]

## Summary of the above
Proposed Project Management models:
1. M1 – Many contribute, only one is awarded. Works when `money/time>threshold`, i.e. money offered are much more than cost of time to work on the contribution. Can be useful for newbies or promo contributions to get onboard. 
	```
	Open field, anybody can contribute, proposal is public (gold rush), expensive.
	```
1. M2 – Picking. Many EoI, one allowed to contribute.
2. M3 – Many contribute, one awarded with access to a list of tasks. Works when intro task is take home task or a pilot, etc.
   ```
   Task chunks, private vetting, open initial chunks, then upon contribution fulfillment, will have access to more tasks.
	```
3. M4 – Many EoI, several allowed to contribute to a list of tasks.
   ```
   Tasks chunk pools. Tasks get released in chunks to pools of contributors. Upon completion, each  pool gets further access (Private gold rush)
	```

Wireframes: https://drive.google.com/file/d/1a8fv_F6zEk-4wD4E9wNea__fLHPnYY1N/view?usp=sharing

## Flow Explanation
Here is an app description. 

We are building a project governance platform with automated feature and code tracking and organises payments to contributors through Ethereum, based on a combination of decentralised technologies (IPFS, Ethereum) and public centralised platforms (GitHub, Discord).

The belief is that it is more cost-efficient and of higher quality to invite the public to contribute to a project. New communities and monetisation opportunities can be built around these projects through consulting, bounties and workload delegation. Shared ownership of a project encourages different perspectives to help improve the project in ways infeasible or undesirable for a single entity.

A user will be able to open a web site and see a list of projects. After clicking on a specific project he will be able to see a list of tasks. Each task has a price tag assigned and governance model that will be used for this task. A user can choose a task and open a detailed view, where he can see detailed description, price, link to discord to discuss it with stakeholders. If the task uses M1 governance model then there will be a list of github pull requests from different users who submited their solution for this task expecting to be paid the price. The user can use an input box on the detailed page to submit a link to his github pull request to be added to the list of contributors for this task, by creating a transaction on the blockchain using Metamask, that will require a contributor to pay a small fee to prevent DoS attacks. After one of pull requests is chosen by the stakeholders, it will be highlighted and the relevant user will receive a blockchain transaction with the price amount of funds. That's it.

From the other side, stakeholders can also open the project and see the list of tasks. Each list item shows task name, governance model, if it was approved or not by stakeholders to be sent to contributors. Stakeholders can also add a new task with properties: task name, description, price, deadline, when task expires, governance model. A new task is created by sending a transaction on the blockchain. Also a file on ipfs is created. After a new task is created, stakeholders can vote to send this task to the contributors, or reject it. Voting period is constant and if quorum is failed, the task is rejected. Voting is done by sending a transaction on the blockchain. After a task is sent to contributors, stakeholders can see submitted pull requests and vote for one of them to be accepted. Voting is done by sending a transaction on the blockchain. After one of the pull requests is accepted,  it is merged by the github app automatically and an oracle will notify the blockchain that the contributors needs to be paid. This will create a blockchain transaction to reward the contributor. That's it.

Your goal is to make it more appealing to the stakeholders of open source projects. 

## Prompts
https://www.dropbox.com/scl/fi/mg2n995ry3vtc1ahpcvku/GPT-prompts.paper?dl=0&rlkey=6vu8gx6mpdx30jchzmuxyypt6
