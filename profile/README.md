EMOD-Hub
============
EMOD-Hub is a GitHub Organization focused on the agent-based disease model called EMOD.  It is the home to the source code and many of the things that one needs to know about EMOD.

EMOD
-----
Epidemiological MODeling software (EMOD), is an agent-based model (ABM) that simulates the simultaneous interactions of agents in an effort to recreate complex phenomena. Each agent (such as a human or vector) can be assigned a variety of “properties” (for example, age, gender, etc.), and their behavior and interactions with one another are determined by using decision rules. These models have strong predictive power and are able to leverage spatial and temporal dynamics.

EMOD is also stochastic, meaning that there is randomness built into the model. Infection and recovery processes are represented as probabilistic Bernoulli random draws. In other words, when a susceptible person comes into contact with a pathogen, they are not guaranteed to become infected. Instead, you can imagine flipping a coin that has a λ chance of coming up tails S(t) times, and for every person who gets a “head” you say they are infected. This randomness better approximates what happens in reality. It also means that you must run many simulations to determine the probability of particular outcomes.

[History & Publication Samples](HistoryAndPublications.md)


Getting Started
------------
Since EMOD is a stochastic model, you must run numerous realizations of each scenario in order to collect proper statistics.  You will likely need a high performance computing (HPC) platform to run these simulations.  As of July 2024, we only support a SLURM-based HPC.

To make running EMOD easier, we have created some python packages that simplify configuring, running, and plotting the results.  As of July 2024, we are working to make these packages more user friendly and will have updates coming in Q4 of 2024.


The Repositories
-------------------
- **EMOD** - This repository contains the source code for the disease model and is the place where the main science happens.  It is the place where infections, immunity, and transmission are modeled.
- **emmod-api** - The base-level of the python support packages is emod-api.  Its main responsibility is to provide tools for reading and writing EMOD input and output files.
- **emodpy** - The emodpy python package is the “base-class” of the workflow tools.  It works with an IDM package called IdmTools allow users to configure and commission experiments to different platforms.
- **emodpy-malaria** - Malaria resarchers should only need to interact with the emodpy-malaria package.  This package is customized for malaria researchers and the malaria features of EMOD.
- **emodpy-hiv** - HIV resarchers should only need to interact with the emodyp-hiv pacakge.  This package is customized for HIV researchers and the HIV features of EMOD.
- **emod-workflow** - The emod-workflow is a high-level workflow for EMOD that allows the user to focus on data, experiments, and results and less on the details of running and configuring the model.


Community
------------
The EMOD Community is made up of researchers and software developers, primarily focused on malaria and HIV research.
We value mutual respect, openness, and a collaborative spirit. If these values resonate with you, 
we invite you to join our EMOD Slack Community by completing this form:

https://forms.office.com/r/sjncGvBjvZ


Contributing
------------
Questions or comments can be directed to [idmsupport@gatesfoundation.org](<mailto:idmsupport@gatesfoundation.org>).

Full information about EMOD is provided in the [documentation](<https://docs.idmod.org/models.html#emod>).


Disclaimer
----------
The code in this repository was developed by IDM and other collaborators to support our joint research on flexible agent-based modeling.
 We've made it publicly available under the MIT License to provide others with a better understanding of our research and an opportunity to build upon it for 
 their own work. We make no representations that the code works as intended or that we will provide support, address issues that are found, or accept pull requests.
 You are welcome to create your own fork and modify the code to suit your own modeling needs as permitted under the MIT License.
