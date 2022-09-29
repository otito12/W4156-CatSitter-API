# W4156-CatSitter-API

THE GOAL IS TO MAKE THIS APPLICATION AS LUDICROUSLY COMPLEX. SACRIFICING LATENCY, BEST PRACTICES, AND NATURALLY COMMON SENSE TO USE AS MANY TECHNOLOGIES AS POSSIBLE

Advanced Software Project Proposal

Part 1
Team name: Oddbeans
Team membership: Otitodirichukwu Darl-Uzu
Programming language: Java 
GitRepo Link: https://github.com/otito12/W4156-CatSitter-API

Part 2
The server will provide an API to simulate an autonomous cat sitter IoT Device. It will be modeled with two clients in mind. 
The autonomous cat sitter which we will model as a series of sensors that send API calls in response to stimuli.
The human pet owner which can issue commands to the autonomous cat sitter forwarded through the API and receive real time updates from the IoT events
The data stored would be a log of commands issues and a persistent state of the autonomous cat sitter along with regular Auth information for both the human user and the autonomous cat sitter. 

Part 3
For testing, the server will be built using the spring boot framework. A testing server will be deployed along with a jenkins instance to manage the CI/CD pipeline. On commit the JUnit tests will be run on the latest build. The team will use a TDD approach writing the tests for the endpoints before the server code is written. 


