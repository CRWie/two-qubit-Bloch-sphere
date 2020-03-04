# two-qubit-Bloch-sphere
This repository provides Python3 codes to plot Bloch spheres for two-qubit pure-states. 
If you give the complex amplitudes alpha, beta, gamma and delta, then the codes plot the three Bloch spheres.

A complete description of the Bloch spheres can be found in this article arXiv:2003.01699

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

"Three unit spheres can represent the two-qubit pure states. One such model previously reported [1] is refined and presented. The three spheres are named the base sphere, entanglement sphere and fiber sphere. The base sphere and the entanglement sphere represent both the reduced density matrix of one qubit (the base qubit) as well as the non-local entanglement measure, concurrence, while the fiber sphere represents the other qubit (the fiber qubit) geometrically under a local unitary operation. When the bipartite state becomes separable, the base sphere and the fiber sphere seamlessly become the single-qubit Bloch sphere of each qubit. Since either qubit may be chosen to be the base qubit, two sets of such spheres can fully represent the reduced density matrices of both qubits as well as the concurrence where the concurrence value is the same in the two sets. The concurrence in this Bloch sphere is correctly related to the reduced density matrices. In particular, the entanglement (concurrence) and the imaginary part of coherence (off-diagonal element of the reduced density matrix) are related via an angle parameter and are represented together in the entanglement sphere. We illustrate partially entangled two-qubit states on the Bloch spheres. The significance of each sphere is discussed."

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
