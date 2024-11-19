# Maze DQN

A Deep-Q-Network implementation in a 15x15 maze to visualise path finding abilities of an agent for autonomous navigation.

## Directory Structure

running.ipynb : python notebook that needs to be run (suggested to use virtual python 3.11 for kernel)
non_idle_q_network_torch.pt : File that stores tensors of trained neural network

Testing_Vids : contains demo running of neural network agent on 4 randomly generated maps (in .mov format)

## Notes

For gpu usage-

On apple silicon mac: device=torch.device("mps" if torch.backends.mps.is_available() else "cpu")
On systems using CUDA: device=torch.device("cuda" if torch.backends.cuda.is_available() else "cpu")
