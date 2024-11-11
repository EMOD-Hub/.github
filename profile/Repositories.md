The EMOD Repositories
=====================
- **[EMOD](https://github.com/EMOD-Hub/EMOD)** - This repository contains the source code for the disease model and is the place where the main science happens.  It is the place where infections, immunity, and transmission are modeled.
- **[emmod-api](https://github.com/EMOD-Hub/emod-api)** - The base-level of the python support packages is emod-api.  Its main responsibility is to provide tools for reading and writing EMOD input and output files.
- **[emodpy](https://github.com/EMOD-Hub/emodpy)** - The emodpy python package is the "base-class" of the workflow tools.  It works with an IDM package called IdmTools allow users to configure and commission experiments to different platforms.
- **[emodpy-malaria](https://github.com/EMOD-Hub/emodpy-malaria)** - Malaria researchers should only need to interact with the emodpy-malaria package.  This package is customized for malaria researchers and the malaria features of EMOD.
- **[emodpy-hiv](https://github.com/EMOD-Hub/emodpy-hiv)** - HIV researchers should only need to interact with the emodyp-hiv pacakge.  This package is customized for HIV researchers and the HIV features of EMOD.
- **emod-workflow** - (Coming Soon) The emod-workflow is a high-level workflow for EMOD that allows the user to focus on data, experiments, and results and less on the details of running and configuring the model.
- **[EMOD-InputData](https://github.com/EMOD-Hub/EMOD-InputData)** - This is a set of example EMOD input files used in the regression testing of the code in the EMOD repository.  You will only need this repo if you are making changes to the C++ code.
