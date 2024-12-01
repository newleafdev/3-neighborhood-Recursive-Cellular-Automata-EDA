# Recursive Cellular Automata Research & Exploration

![basinfield](https://github.com/user-attachments/assets/6c455295-f0b1-41c2-b5c0-55b02388211d)

Status: ongoing


## Summary
This is an implementation of research I initally conducted at Queen Mary, University of London under the supervision and care of Professor David Berman.
The research sits on the interface of computer science, automata theory, information theory, dynamical systems theory and theoretical physics.
The original idea was proposed by Professor David Berman, initally implementing the novel cellular automata on a 1980s home computer with limited memory and compute.

![circulartopology](https://github.com/user-attachments/assets/483fd8b4-b08d-4b7f-8869-b2f0d322bac5)

## Most interesting discovery
Rule 90, which in Wolfram style elementary cellular automata is famous for it's ability to generate intricate patterns, though it is not chaotic like rule 30.
Our RCA Rule 90 has a number of interesting statistics including longest transition length before meeting an attractor state. Likely a coincidence but the symmetry exhibited in the local pattern of rule 90 is something to think about.

![255](https://github.com/user-attachments/assets/37e79411-06f4-47dc-8693-46f792b6bb76)


## Next Steps: Research
There are endless possibilites and I frequently return to this project to test new skills.
The biggest issue is that a similar exhaustive survey of the state space of a 5 neighbourhood RCA is impossible without vast amounts of compute, memory and time.
Therefore, I am planning to implement neural networks as classifiers to determine whether a state is an attractor, garden of eden, or a transient.
It is worth exploring whether an RNN can trained to predict the next state, finding a pattern invisible to the human intellect.

### Next steps: Code
- code is currently scrappy, plan to rewrite with OOP principles for managability and to write short tutorial projects
- implement ML or NN models to classify the states of the 3n system
- find a smaple of attractors in the 5n RCA to use as training data for the 5n classifier

![attractortypes](https://github.com/user-attachments/assets/79237ffb-38a9-44e1-bb9f-012c937c7abf)
