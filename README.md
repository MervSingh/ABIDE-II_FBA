# ABIDE-II_FBA_analysis

Scripts to run Single-shell 3-tissue Constrained spherical deconvolution (SS3TCSD) and Fixel-based analysis (FBA) of diffusion MRI data.

Code contained in this repository forms part of a project investigating the neuropathophysiology of ASD using data obtained from the open-source Autism Brain imaging Data Exchange Initiative II (ABIDE-II) http://fcon_1000.projects.nitrc.org/indi/abide/abide_II.html:

Project Status: [Active]

Research team and Institutions: 

1. Melissa Kirkovski -- Deakin University, Cognitive Neuroscience Unit, Geelong, Australia
2. Mervyn Singh -- Deakin University, Cognitive Neuroscience Unit, Geelong, Australia
3. Thijs Dhollander -- Murdoch Children’s Research Institute, Developmental Imaging; Melbourne, Australia
4. Natalia Albein-Urios -- Deakin University, Cognitive Neuroscience Unit, Geelong, Australia
5. Peter Donaldson -- Deakin University, Cognitive Neuroscience Unit, Geelong, Australia
6. Peter Enticott -- Deakin University, Cognitive Neuroscience Unit, Geelong, Australia

Users attemtping to run the scripts contained in this repository should note that the code is optimised for use on the Monash M3 High Performance Computing Cluster (https://docs.massive.org.au/), but can be adapted to work on a local system. Of note, we relied heavily on the MRTrix3Tissue (https://3tissue.github.io/) and TractSeg (https://github.com/MIC-DKFZ/TractSeg), FSL (https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/) and FreeSurfer (https://surfer.nmr.mgh.harvard.edu/) Software packages and their dependencies

All software required to run the analyses are contained in the "Modules" file. These are loaded directly into the M3 HPC terminal environment. Those attemtping to run the analyses locally must install the software separately on their system.

For more information on the use and dissemination of the resources in this repository, please email Mervyn Singh: mervynsingh87@gmail.com.au
