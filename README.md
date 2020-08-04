# two-qubit-Bloch-sphere
This repository provides Python3 codes to plot Bloch spheres for two-qubit pure-states. 
If you give the complex amplitudes alpha, beta, gamma and delta, then the codes plot the three Bloch spheres.

A complete description of the Bloch spheres can be found in this article:   https://arxiv.org/abs/2003.01699
The previous article on the detailed parameterization process is given here: https://arxiv.org/abs/1403.8069

In order to plot the Bloch spheres, the *_Calculation files take the Input of the Complex Amplitudes and calculates the Bloch sphere coordinates using a simple quaternion algebra. After the calculation, the three spheres are plotted:  BASE, ENTANGLEMENT, and FIBER.

For a given bipartite state, we can plot two equivalent sets of three spheres depending on which qubit is in the base.
You can copy/paste the Python3 codes into four Jupyter Notebook input boxes and run them in order.

I.  Qubit-A is in the base: 

This is for qubit-A as the base qubit and qubit-B as the fiber qubit.

BASE(A)_Calculation => BASE(A)_PLOT => ENTANGLEMENT(A)_PLOT => FIBER(B)_PLOT


II. Qubit-B is in the base: 

This is for qubit-B as the base qubit and qubit-A as the fiber qubit.

BASE(B)_Calculation => BASE(B)_PLOT => ENTANGLEMENT(B)_PLOT => FIBER(A)_PLOT

The python3 codes are being disseminated according to the "MIT License and Copyright" as below.  Any input about or improvement of the codes are welcome.

ABSTRACT of the article:   arXiv:2003.01699

"Three unit spheres were used to represent the two-qubit pure states. The three spheres are named the base sphere, entanglement sphere, and fiber sphere. The base sphere and entanglement sphere represent the reduced density matrix of the base qubit and the non-local entanglement measure, concurrence, while the fiber sphere represents the fiber qubit via a simple rotation under a local single-qubit unitary operation; however, in an entangled bipartite state, the fiber sphere has no information on the reduced density matrix of the fiber qubit. When the bipartite state becomes separable, the base and fiber spheres seamlessly become the single-qubit Bloch spheres of each qubit. Since either qubit can be chosen as the base qubit, two alternative sets of these three spheres are available, where each set fully represents the bipartite pure state, and each set has information of the reduced density matrix of its base qubit. Comparing this model to the two Bloch balls representing the reduced density matrices of the two qubits, each Bloch ball corresponds to two unit spheres in our model, namely, the base and entanglement spheres. The concurrence-coherence complementarity is explicitly shown on the entanglement sphere via a single angle."

MIT License

Copyright (c) 2020, C.R.Wie

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
