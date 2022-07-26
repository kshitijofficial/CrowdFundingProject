# CrowdFundingProject

This is one of the many projects available on [Codedamn](https://codedamn.com/projects) to reinforce your learning by building. If you want to become a Blockchain Developer and learn by practicing, feel free to attempt this challenge. Feel free to check out the codedamn [Web3 Learning Path](https://codedamn.com/learning-paths/web3) to learn more about how to become an awesome Blockchain Developer.

Crowd Funding - The practice of funding a project or venture by raising money from a large number of people who each contribute a relatively small amount, typically via the internet.

**In this contract we will have three entities -**

1. Manager - This will deploy the smart contract.

2. Contributors - These will contribute to the crowdfunding.

3. Receipient - This will receive the money.

## Description

The manager will set the following when deploying the smart contract -

1. Target - The money that has to be raised for crowdfunding.

2. Deadline - The time at which the crowdfunding will end.

3. Minimum Contribution - This will be the minimum contribution that a contributor must pay for.

So for example manager wants to raise a fund for child education. For that, he needs 1 ether in 2 days so here the target is 1 ether and deadline is 2 days.And the minimum contribution the contributor has to contribute is let say 100 Wei.

The manager can create multiple crowdfunding requests. So for example the manager can make a request for child education, environment protection, food donation, etc. And which request will be taken into consideration will depend on the voting done by the contributors.

The contributors will send their ether to the smart contract only when the deadline has not ended and when they contribute the minimum contribution asked by the manager.

After the contribution, the contributors can vote for the requests raised by the manager. A contributor can only vote once for a specific crowdfunding request. So for example contributor A has voted for child education so now he cannot again vote for child education. Contributor A can vote for environmental protection or any other cause.So one vote = one cause.

And the request which will have the maximum votes that request will receive the money. The money will directly go the receipient address.

Contributors can also ask for a refund of their money if the desired target and deadline are not met.

**Some functions that you should have in your smart contract -**

1. sendEther() - To transfer ether to contract balance.
2. refund() - So the contributors can have a refund.
3. createRequests() - The manager can create request for a crowdFunding project.
4. voteRequest() - The contributors can vote for a request.
5. makePayment() - To transfer the money to the receipient address.

## Project checklist

- [ ] Functionality to set the target and deadline of the Crowdfunding.
- [ ] Functionality to become a contributor in the funding.
- [ ] Functionality to get the refund of the contribution.
- [ ] Functionality to create the request for the funding.
- [ ] Functoinality to vote for a request.
- [ ] Functionality to make payment to the recipietn.

Apart from the above functions you are free to add your own functionality which can help in making this smart contract more secure and better.

We love receiving feedback! We're always looking to improve our challenges and our platform. So if you have anything you'd like to mention, please visit [codedamn feedback page](https://codedamn.com/contact)
