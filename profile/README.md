EMOD-Hub
============
EMOD-Hub is a GitHub Organization focused on the agent-based disease model called EMOD.
It is the home to the source code and many of the things that one needs to know about EMOD.

What is EMOD?
--------------
Epidemiological MODeling software (EMOD), is an agent-based model (ABM) that simulates 
the simultaneous interactions of agents in an effort to recreate complex phenomena. 
Each agent (such as a human or vector) can be assigned a variety of "properties" 
(for example, age, gender, etc.), and their behavior and interactions with one another 
are determined by using decision rules. These models have strong predictive power and 
are able to leverage spatial and temporal dynamics.

EMOD is also stochastic, meaning that there is randomness built into the model. 
Infection and recovery processes are represented as probabilistic Bernoulli random 
draws. In other words, when a susceptible person comes into contact with a pathogen, 
they are not guaranteed to become infected. Instead, you can imagine flipping a coin 
that has a λ chance of coming up tails S(t) times, and for every person who gets a 
"head" you say they are infected. This randomness better approximates what happens 
in reality. It also means that you must run many simulations to determine the 
probability of particular outcomes.

More Information
-----------------
- [History & Publication Samples](HistoryAndPublications.md)
- [Getting Started](GettingStarted.md)
- [The Repositories](Repositories.md)
- [Be Part of the Community](Community.md)
- [How to Contribute](Contributing.md)
- [Main Documentation](https://docs.idmod.org/models.html#emod)
- [Presentations](Presentations.md)

Disclaimer
----------
The code in this repository was developed by IDM and other collaborators to support 
our joint research on flexible agent-based modeling. We've made it publicly available 
under the MIT License to provide others with a better understanding of our research 
and an opportunity to build upon it for their own work. We make no representations 
that the code works as intended or that we will provide support, address issues that 
are found, or accept pull requests.  You are welcome to create your own fork and 
modify the code to suit your own modeling needs as permitted under the MIT License.
