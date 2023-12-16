I tackle the problem of finding the best minimally connected structure and parameters of an Ising like Hamiltonian:

$$H(s)=-\sum_{ij}J_{ij} s_is_j - \sum_i h_i s_i$$

First classes for a Graph, a variable and a factor are defined. Then we define the class needed to do Belief propagation: 'messages'. 
The Kruskal algorithm to find the best tree as from Chow Liu theorem is defined.
Finally we use a recursive algorithm to sample from the tree.

We test the code with the 2 spin model for which easy computations can be done by hand.
The algorithm was first created as part of a project to try to describe protein sequences from chorismate mutase enzymes, taking inspiration from: Russ, W.P., Figliuzzi, M., Stocker, C., Barrat-Charlaix, P., Socolich, M., Kast, P., Hilvert, D., Monasson, R.,
Cocco, S., Weigt, M. and Ranganathan, R., 2020. An evolution-based model for designing chorismate mutase enzymes. Science, 369(6502), pp.440-445

![alt text]([http://url/to/img.png](https://github.com/Wraithmat/Belief_propagation_Ising/blob/5c104d055b933e642332eb39cbd931dab0f9608f/Large_river.png)https://github.com/Wraithmat/Belief_propagation_Ising/blob/5c104d055b933e642332eb39cbd931dab0f9608f/Large_river.png)
