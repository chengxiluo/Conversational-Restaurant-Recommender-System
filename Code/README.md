## Dependencies

- python3.7
- torch1.2
- numpy
- tqdm
- sklearn
- pickle


## Command to Run

python example.py 0 0 --num 3

First parameter is user type. 0: simulated users, 1:real users.

Second parameter is agent type. 0: rule-based method, 1: RL-based method.

Third parameter (optional) is the number of conversation round, default is 1. 

SampleConversations.pdf is the log of sample conversations. 

## Current Process: 
When user type is real users,
- All the conversations are through terminal commands, and users have to restrictly type the correct answer.
- target restaurant is randomly chosen by the system and revealed to users; 
- target restaurant information is provided; 
- users have to answer questions from the system based on these information.

## Ideal Process:
- All the conversations will be through a platform, so no constraints on chatting in natural language.
- Target restaurant is radomly chosen by the system and not reveal to users;
- Users learn the preference of simulated user based on past visiting restaurants information;
- Users answer the question based on these information; 
- The system gives recommendations.



