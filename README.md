# Description
   These codes reproduces results/figures in the report, which 
   expeted to be published as Kajiwara et al. (2021).
  
--------------
# Requirments
    
  Matlab, Statistical and Signal Processing Toolbox and Statistics and Machine Learning Toolbox are necessary to run these code.
 
----------------
# How to run fig*.m ?
  - (1) Save all files at one directory of your computer.
  - (2) Type the following code in Matlab: 
  
            addpath(genpath('./'));  % addpath all relating branch folders.
            fig*
  
----------------
# Description of fig5b.m
  This program products a figure showing degree histgrams, histgrams of number of connections.
  
----------------
# Description of fig5ce.m
This program products two figures showing the histgram of firing rate for excitatory and inhibitory neurons, and the histgram of connectivity strenghs for excitatory and inhibitory neurons.

----------------
# Description of fig5d.m
This program products tje figure showing the total number of identified excitatory and inhibitory neurons within cortex, and their ralative ratios.

----------------
# Description of fig6ab.m
This program products two figures showing the difference of averaged k-core values for all cortical excitatory and inhibitory neurons, and showing  the difference of averaged k-core values for excitatory and inhibitory neurons within individual cortical layers.

----------------
# Description of fig7ab.m
This program products two figures showing the difference of ratios of FVS  (Feedback Vertex Set) for all cortical excitatory or inhibitory neurons, and showing the difference of ratios of FVS for excitatory or inhibitory neurons within individual cortical layers.

----------------
# Description of fig7c.m
   This program products data set for comparing between high K-Core nodes and FVS (Feedback Vertex Set) of nodes. The data was utilized to drowing the Venn diagram.

-----------------
# Reference
   If you use this code, cite this following article: 
   
   Kajiwara, M., Nomura, R., Goetze, F., Kawabata, M., Isomura, Y., Akutsu, T., & Shimono, M. (2021). Inhibitory neurons exhibit high controlling ability in the cortical microconnectome. PLOS Computational Biology, 17(4), e1008846.

