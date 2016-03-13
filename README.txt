/*LFPsim - Simulation scripts to compute Local Field Potentials (LFP) of cable compartmental models of neuron and network implemented in NEURON simulation environment.

LFPsim works reliably on biophysically detailed multi-compartmental neurons with some or all active channels. 

Last updated 12-March-2016
Developed by : Harilal Parasuram & Shyam Diwakar
Computational Neuroscience & Neurophysiology Lab, School of Biotechnology, Amrita University, India.
Email: harilalp@am.amrita.edu; shyam@amrita.edu
www.amrita.edu/compneuro 
*/


README for LFPsim
=================

1. Copy all LFPsim files and the directory into your NEURON model directory downloaded from ModelDb. Copy lfp.mod and mea.mod from LFPsim to the mechanism directory of the NEURON model.

2. Compile the model; if you had already compiled the model without LFPsim, include the LFPsim mod files and re-compile using "nrnivmodl" or "mknrndll".

3. Load your neuron or network model in NEURON.  

4. On the terminal type: xopen("extracellular_electrode.hoc") to initiate LFPsim GUI interface.

5. Set the electrode properties in the GUI. 

6. Run the simulation to reconstruct LFP.
