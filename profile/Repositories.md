The EMOD Repositories
=====================
- **EMOD** - This repository contains the source code for the disease model and is the place where the main science happens.  It is the place where infections, immunity, and transmission are modeled.
- **emmod-api** - The base-level of the python support packages is emod-api.  Its main responsibility is to provide tools for reading and writing EMOD input and output files.
- **emodpy** - The emodpy python package is the “base-class” of the workflow tools.  It works with an IDM package called IdmTools allow users to configure and commission experiments to different platforms.
- **emodpy-malaria** - Malaria resarchers should only need to interact with the emodpy-malaria package.  This package is customized for malaria researchers and the malaria features of EMOD.
- **emodpy-hiv** - HIV resarchers should only need to interact with the emodyp-hiv pacakge.  This package is customized for HIV researchers and the HIV features of EMOD.
- **emod-workflow** - The emod-workflow is a high-level workflow for EMOD that allows the user to focus on data, experiments, and results and less on the details of running and configuring the model.
