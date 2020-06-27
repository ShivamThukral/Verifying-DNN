# Verifying-DNN

This project report contains short summaries of 11 state-of-the-art approaches to verify deep neural networks.
List of papers summarized:
1. John A Nelder and Roger Mead. **A simplex method for function minimization.** The computer journal, 7(4):308–313, 1965
2. Luca Pulina and Armando Tacchella. **An abstraction-refinement approach to verification of artificial neural networks.** In International Conference on Computer Aided Verification, pages 243–257. Springer, 2010.
3. Luca Pulina and Armando Tacchella. **Challenging smt solvers to verify neural networks.** Ai Communications, 25(2):117–135, 2012
4. Guy Katz, Clark Barrett, David L Dill, Kyle Julian, and Mykel J Kochenderfer. ** Reluplex: An efficient smt solver for verifying deep neural networks.** In International Conference on Computer Aided Verification, pages 97–117. Springer, 2017
5. Osbert Bastani, Yani Ioannou, Leonidas Lampropoulos, Dimitrios Vytiniotis, Aditya Nori, and Antonio Criminisi. **Measuring neural net robustness with constraints.** In Advances in neural information processing systems, pages 2613–2621, 2016
6. Ruediger Ehlers. **Formal verification of piece-wise linear feed-forward neural networks.** In International Symposium on Automated Technology for Verification and Analysis, pages 269–286. Springer, 2017
7. Timon Gehr, Matthew Mirman, Dana Drachsler-Cohen, Petar Tsankov, Swarat Chaudhuri, and Martin Vechev. **Ai2: Safety and robustness certification of neural networks with abstract interpretation.** n 2018 IEEE Symposium on Security and Privacy (SP), pages 3–18. IEEE, 2018.8.
9. Rudy R Bunel, Ilker Turkaslan, Philip Torr, Pushmeet Kohli, and Pawan K Mudigonda. **A unified view of piecewise linear neural network verification.** In Advances in Neural Information Processing Systems, pages 4790–4799, 2018
10. Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian Goodfellow, and Rob Fergus. **Intriguing properties of neural networks.** arXiv preprint arXiv:1312.6199, 2013
11. Lindsey Kuper, Guy Katz, Justin Gottschlich, Kyle Julian, Clark Barrett, and Mykel Kochenderfer. **Toward scalable verification for safety-critical deep networks.** arXiv preprint arXiv:1801.05950, 2018

Methods discussed above are still far from being scaled to large neural networks. In the next section, we discuss about ReLUplex and how it can be used to verify deep neural networks.

## ReLUplex: 
ReLUplex is a  novel, scalable, and efficient technique for verifying properties of deep neural networks (or providing counter-examples). The technique is based on the simplex method, extended to handle the non-convex Rectified Linear Unit (ReLU).

Ran ReLUplex on two systems:
1. Kyle D Julian, Jessica Lopez, Jeffrey S Brush, Michael P Owen, and Mykel J Kochenderfer. **Policy compression for aircraft collision avoidance systems.** In 2016 IEEE/AIAA 35th Digital Avionics Systems Conference (DASC), pages 1–10. IEEE, 2016
2. A Collision Avoidance System taken from 6.

Please refer supplmentary material for sample example runs on collision detection  system.

Lastly, I propose an approach to verify large scale deep neural networks. Please refer section *Research idea* and *Thesis Proposal* for futher details. 
