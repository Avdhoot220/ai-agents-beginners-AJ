# Learning Notes

## Lesson 1:
- Explains the setup

- Primarily, 
We have to connect to Foundry service, using MS Agent Framework.. (Which is like a library),
then we have a function, which works as a **tool**; which our agent can interact with or use.,
then set the envi variables, which are mentioned in the imported agent.

We give context (through a description) to the agent, telling what it is supposed to do.
Then the function gives domain related details, that the agent can refer to.

And, then we run the agent, and it gives response, and does some actions.


## Lesson 5: Agentic RAG.
Where (LLMs) autonomously plan their next steps while pulling information from external sources.
Iterative calls to the LLM, makes corrections, tries better methods.
System's ability to own its reasoning process, making decisions on how to approach problems without relying on pre-defined paths.
All of these steps—refining queries, choosing sources, iterating until “happy” with the answer—are decided by the model, not pre-scripted by a human

To do: Additioanl resources from lesson 5 readme file.


## Lesson 6: Building Trustworthy agents
Possible threats:
a. Attachkers can change the role / instructions of the Agents.
b. Access to critical systems: If the Agent has access to crucial / sensitive data, attackers can use multiple prompts to get that info. 
We can limit the number of requests per user, to avoid this.
c. Attackers can poison the knowledge base. So, the Agent will mal-function.
d. have a 'human-in-the-loop'
For giving feedback regularly.


## Leson 7: About planning the design, sub-agent design etc.
As such, it gives a nice project to implement; though the code might be incomplete.

** Lesson 8: Multi-agent (Good theory)
Why multi-agents required:
a) Large workloads --> for scalability, you will divide the load.
b) Complextiy --> to simplyfy the activity, to avoid complications / failures
c) Specialization / expertise: Making each agent focused on one type of thing
d) Successive tasks: better to divide the tasks periodically
e) Fault tolerance: If one agent fails, other should continue, ensuring system reliability.

Imp thing here, is to ensure all agents are communicating with each other.
Agents need to coordinate their actions.
Need to have Visibility into Multi-Agent Interaction. This means that you need to have tools and techniques for tracking agent activities and interactions. This could be in the form of logging and monitoring tools, visualization tools, and performance metrics.

aa
