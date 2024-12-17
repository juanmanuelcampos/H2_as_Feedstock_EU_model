# EU energy model for on-site hydrogen supply and its use as feedstock in the industrial sector (Vensim)
GENERAL INFO

This repository contains the EU energy model for on-site hydrogen supply and its use as feedstock in the industrial sector. The model was developed for the submitted paper to Applied Energy: "From Grey to “Green”: Modelling the Non-Energy Uses of Hydrogen within the EU Energy Transition". The model is implemented in VENSIM (see "EU energy model for on-site hydrogen supply and its use as feedstock in the industrial sector.mdl" file in "VENSIM model" folder) and is an outcome of the LOCOMOTION project. Future developments will involve integrating this model into the WILIAM model within the HYDRA project.

MODEL CAPABILITIES

The model offers two primary functionalities:

Evaluation mode: forecasts future trends based on predefined inputs and assumptions
Hybrid optimization mode (i.e., combining predefined future trends for certain variables while optimizing others): aims to minimize emissions over time under specified constraints.
PREDEFINED SCENARIOS

The model includes six predefined scenarios, whose definitions are detailed in the main paper. Scenarios can be selecting by setting a value from 0 to 5 in the variable ‘SCENARIO_SELECTION’; 0: Baseline scenario (Baseline), 1: H2-expansion, 2: H2-high-expansion, 3: Degrowth, 4: H2-delayed-expansion, 5: EU-H2-roadmap. Once a scenario is selected, the model can be simulated in:

Evaluation mode: run a single simulation in VENSIM
Hybrid optimization mode (the one used for exctract the results of the paper): instructions for this mode are provided in the "optimisation guidelines" view within the VENSIM model or in the accompanying file in the repository "EU energy model for on-site hydrogen supply and its use as feedstock in the industrial sector0000.bmp". Note: to perform this mode, it is required to place the "policy.lst", "policy.vsc", "POLICY_H2_INDUSTRYY.voc", and "POLICY_H2_INDUSTRY.vpd" files in the same folder as the .mdl file.
FOR USERS WITHOUT A FULL VENSIM DSS LICENCE

A Packaged version of the model (see "EU energy model for on-site hydrogen supply and its use as feedstock in the industrial sector.vpmx") is included in this repository, which allows scenario simulations with a freeware (VENSIM Model Reader: https://vensim.com/vensim-model-reader/). For accessing model equations, users without a full VENSIM DSS licence can open the .mdl file with a text editor.

CONTACT

For any query or suggestion contact us at: juanmanuel.campos@uva.es, inigo.capellan@uva.es, gonzalo.parrado@uva.es, ffrechoso@uva.es
