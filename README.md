# Bottlenecks

This program finds edges in a network such that if the capacity of these edges increases so does the maximum flow. 

## Libraries used:

The script uses the networkx and matplotlib libray. Hence will need these to be installed. Run: 
- \pip instal networkx
- \pip instal matplotlib

## How to use:

- Main function input:
Solve(Network,Source,Sink), where network is a digraph in a networkx object examples of these are at the bottem of the script, source and sink are nodes in the network.
- Main function output :
A list with 2 objects: 1st being the max flow of the origonal networks, 2nd being a list of sets containing edges (bottlenecks) and an intergral value (to what value the capacities can improve the max flow)

- Max_flow:
Input is Max_flow(Network,Source,Sink) returning 3 objects:

 [v max flow value , set of nodes (Network partition) , dictionary of the flow network]
