# Q Simulations

Repository for the Q experiments of the Master's degree studies.

Developed in [Python 3](https://www.python.org/downloads/) and using [virtualenvs](https://virtualenv.pypa.io/en/latest/) and [Jupyter Notebooks](https://jupyter.org/install).

For the implementation of the Quantum algorithms, IBM's **Qiskit** is being used. It is an open-source framework for working with noisy quantum computers at the level of pulses, circuits, and algorithms.

Qiskit is made up elements that work together to enable quantum computing. This element is **Aqua**.

A couple of links bellow about the libraries being used:
* [qiskit-tutorials](https://github.com/Qiskit/qiskit-tutorials) and
* [qiskit-tutorials-community](https://github.com/Qiskit/qiskit-tutorials-sommunity) GitHub Repositories.

## API KEY:
API_TOKEN
You'll need to have an API key for the [IBM Quantum Experience](https://quantum-computing.ibm.com/), and then export it as a environment variable.
```bash
$ export API_TOKEN=<your-api-token>
```
#
## Dependencies:

###### Obs: If you already have this dependence, you can jump to *Running locally*

* The dependencies can be installed once you have set up the Python environment. Highly recomended the usage of virtualenvs for it. 
* To activate the virtualenv just run:
```bash
$ source <name_of_the_virtualenv>/bin/activate
```
* Then, install all the dependencies by running:
```bash
$ pip install -r requirements.txt
```
This notebook can also be downloaded as PDF for report purposes, to install the dependencies needed for that, run:
```bash
$ chmod +x install.sh
$ source install.sh
``` 
#

## Running locally

To be able to run and edit the code, go to the root folder project and run:
```
$ jupyter notebook
```
Then the notebooks will be available on: `http://localhost:8888/tree`.
