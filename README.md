# GraphSAGE_MultiGPU
Libaries needed:<br />
Pytorch https://pytorch.org/ <br />
dgl https://docs.dgl.ai/<br />
tqdm https://tqdm.github.io/<br />

Command to run:<br />

> python3 graphsage_multi_gpu.py --num-epochs 30 --gpu 0,1,2,3 


30 -- number of epochs<br />
0,1,2,3 -- gpus<br />

To generate plots for accuracy and losses, plot the output arrays from running above commands since it might cause trouble for some systems.
Data_Plots.ipynb is an example with output data and plotting code.
