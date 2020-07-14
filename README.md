# NN-potential-water-vapor

Input files for the neural-network potentials for RPBE-D3 water including 
interfacial configurations

- input.data : configurations and RPBE+D3 forces used for the training
- input.nn : input file for the n2p2 package
- scaling.data  : scaling factors, input for the n2p2 package
- weights.001.data : neural network weights for hydrogen
- weights.008.data : neural network weights for oxygen

For the network training and libraries to run MD simulations with NN potentials
using LAMMS, see https://github.com/CompPhysVienna/n2p2
