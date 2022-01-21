# Blockchain-CampusFeedbackFungibleToken-FT
Using ERC20 standard, implemented our own CFB Token smart contract on Blockchain. The project aims at improving the campus dining feedback service by integrating the deployed smart contract with the developed website and then calling the contract’s functions.

# Objectives: 
ERC-20 has emerged as the technical standard; it is used for all smart contracts on the Ethereum blockchain for token implementation and provides a list of rules that all Ethereum-based tokens must follow. The goal of our project is to implement a complete blockchain platform solution for the feedback system in Campus Dining Services at University at Bufallo, as an alternate to the existing trivial approach. This would add value to services provided by and benefit students.

# Description:
Feedback is important for any organization to improve their service. Currently CDS feedback system at UB is SMS based where students have to send an SMS to a specific number to submit feedback. After submitting feedback, students do not receive anything in return which does not motivate lot of students to submit their feedback. With limited feedback, any organization, CDS in this example, will not have sufficient inputs to make any changes and thus improve the system/service. Using ERC20 tokens as reward points for students, we can encourage more students to participate in providing feedback. This will provide more input to CDS and they can effectively make useful changes. Students get rewarded with ERC tokens which they can in turn use to order special services/food through our platform. Another problem that this contract can tackle in a better way is choosing which services to establish. Suppose CDS has multiple ideas/proposals to implement but they have resources to implement only one. For this, CDS would organise a poll with multiple proposals and the proposal with most votes can be picked. In this way the decision will be made by majority of users rather than just few people at CDS. ERC-20 tokens are issued on the Ethereum network. It defines a common list of rules that all Ethereum tokens must adhere to. Some of these rules include how the tokens can be transferred, how transactions are approved, how users can access data about a token, and the total supply of tokens. Using these standards, we have implemented a token system for CDS.

# Design features:
ERC20 symbol:
CFB – Campus FeedBack

Using Design Principles we can develop a use case diagram and contract diagram specific to our model. This highlights the structure and members of the token system.

Use case:

![use_case](https://user-images.githubusercontent.com/52970601/150601506-4481a3af-abc3-4411-997d-2bd600e40ac2.png)

Contract diagram:

<img width="300" height="500" alt="table" src="https://user-images.githubusercontent.com/52970601/150601579-16cca272-5705-4a90-884f-88db5c562fde.png">

# Sequence of operations:
Our system is fairly simple and straightforward. Initially CDS deploys the smart contract with a finite amount of tokens and thus CDS will own the smart contract. Students and faculty of the university can register through the UI and thus become participants of the decentralized network. Students have the option to provide feedback on the UI and this will be stored in the database. Once the feedback is confirmed, the participant is rewarded with a predefined amount of tokens. Participants can use these tokens to order special services/food. Based on the feedback, the admin/chairperson can come up with couple of new services. However if due to limited resources only one can be implemented then a poll is initiated. Students can register for voting and vote for their choice of proposal. The proposal with maximum votes will be the changes that will be implemented by the CDS. There is also option for the participant to unregister themselves or for the chairperson to unregister any participant.
Below sequence diagram represents the sequence of actions/processes that takes place in the system.

![sequence](https://user-images.githubusercontent.com/52970601/150601686-751be9a3-165e-4587-82ca-1674626d40e9.png)

# Architectural Diagram

<img width="400" alt="architectural" src="https://user-images.githubusercontent.com/52970601/150601848-9d74b22f-9989-4f50-a3a2-31b61508e6f4.png">

# User Interface
The project consists of two sections:
# 1. Feedback points
This is the more usual part of the platform where students are able to register and provide feedback on various services of CDS. For this, students will earn CFB points in return. Once sufficient CFBs are collected, a student can redeem those points for any rewards offered by CDS(like Fruit/Chips, Meal or Buffet).

<img width="946" alt="page" src="https://user-images.githubusercontent.com/52970601/150602169-b5a870db-8a0e-4dc5-ad23-9ad8e8f3805c.png">

<img width="946" alt="page2" src="https://user-images.githubusercontent.com/52970601/150602715-3223bb37-605e-4ec4-a926-a35b48e6e78a.png">

# 2. Voting for the services
This is an occasional part of the platform where CDS organizes a poll in order to make decisions. Lets say there is resource for setting up only one extra cuisine in the new One World. Instead of only the members of CDS making the decision, a poll is organized where registered students can vote. The Chairperson (CDS) will be controlling the various phases of voting. Highest votes means more customers for CDS and more students will get what they want, win-win.

<img width="946" alt="page3" src="https://user-images.githubusercontent.com/52970601/150603017-025def8e-f2ae-4800-90d8-e872235df58a.png">

<img width="946" alt="page4" src="https://user-images.githubusercontent.com/52970601/150603055-631e1b7a-9bbe-4a88-87a7-1bd5ac445389.png">


