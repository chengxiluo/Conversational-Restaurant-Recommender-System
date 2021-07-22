# Conversational-Restaurant-Recommender-System

Code to combine conversational agent and recommender system together as defined in [this paper](./design_and_evaluate_conversational_restaurant_recommender_system.pdf). 

## Abstract
Conversational agents are used widely in e-commerce websites to interact with customers and help them solve questions
and find products. Recommendation is also an essential feature of e-commerce websites, which help customers discover
more interesting products. In this paper, we implement a Conversational Restaurant Recommender System(CRRS), which
combines the conversational agent and recommender system
together. We also evaluate the performance of CRRS by a laboratory experiment. Our result shows that CRRS is an efficient
tool, which always recommends suitable restaurants based on
our users’ needs.

## Prerequisites

- python3.7
- torch1.2
- numpy
- tqdm
- sklearn
- pickle


## Usage

```
python example.py 0 0 --num 3
```

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

