# Verifying-DNN

This project report contains short summaries of 10 state-of-the-art approaches to verify deep neural networks.

#### List of papers summarized:
* Nelder, John A., and Roger Mead. **A simplex method for function minimization.** The computer journal 7.4 (1965): 308-313.

* Pulina, Luca, and Armando Tacchella. **An abstraction-refinement approach to verification of artificial neural networks.** International Conference on Computer Aided Verification. Springer, Berlin, Heidelberg, 2010.

* Pulina, Luca, and Armando Tacchella. **Challenging SMT solvers to verify neural networks.** Ai Communications 25.2 (2012): 117-135.

* Katz, Guy, et al. **Reluplex: An efficient SMT solver for verifying deep neural networks.** International Conference on Computer Aided Verification. Springer, Cham, 2017.

* Bastani, Osbert, et al. **Measuring neural net robustness with constraints.** Advances in neural information processing systems. 2016.

* Ehlers, Ruediger. **Formal verification of piece-wise linear feed-forward neural networks.** International Symposium on Automated Technology for Verification and Analysis. Springer, Cham, 2017.

* Gehr, Timon, et al. **Ai2: Safety and robustness certification of neural networks with abstract interpretation.** 2018 IEEE Symposium on Security and Privacy (SP). IEEE, 2018.

* Bunel, Rudy R., et al. **A unified view of piecewise linear neural network verification.** Advances in Neural Information Processing Systems. 2018.

* Szegedy, Christian, et al. **Intriguing properties of neural networks.** arXiv preprint arXiv:1312.6199 (2013).

* Kuper, Lindsey, et al. **Toward scalable verification for safety-critical deep networks.** arXiv preprint arXiv:1801.05950 (2018).

Methods discussed above are still far from being scaled to large neural networks. In the next section, we discuss about ReLUplex and how it can be used to verify deep neural networks.

## ReLUplex: 
ReLUplex is a  novel, scalable, and efficient technique for verifying properties of deep neural networks (or providing counter-examples). The technique is based on the simplex method, extended to handle the non-convex Rectified Linear Unit (ReLU).

Ran ReLUplex on two systems:
1. Julian, Kyle D., et al. **Policy compression for aircraft collision avoidance systems.** 2016 IEEE/AIAA 35th Digital Avionics Systems Conference (DASC). IEEE, 2016.
2. A handwritten digit recognition network take form Ehlers, Ruediger. **Formal verification of piece-wise linear feed-forward neural networks.** International Symposium on Automated Technology for Verification and Analysis. Springer, Cham, 2017.

Please refer supplmentary material for sample example runs on collision detection  system.

Lastly, I propose an approach to verify large scale deep neural networks. Please refer section *Research idea* and *Thesis Proposal* for futher details. 
