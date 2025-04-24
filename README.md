# Mathematics-for-Machine-Learning-Linear-Algebra

### Reflecting Bear

* **Description:**
    * This notebook contains a Python function that produces a transformation matrix for reflecting vectors in an arbitrarily angled mirror.
    * It deals with a scenario where a bear has a non-orthonormal coordinate system and needs to perform reflections correctly.
    * Key concepts include:
        * Matrix transformations
        * Orthonormal basis
        * Gram-Schmidt process
        * Matrix inverse and transpose
* **Instructions:**
    * Edit the code in the notebook to complete the `build_reflection_matrix` function.
    * The notebook includes a test case that displays an image of a bear and its reflection.
* **Dependencies:**
    * numpy
    * numpy.linalg
    * readonly.bearNecessities (provided with the assignment)

### PageRank

* **Description:**
    * This notebook explores the PageRank algorithm, which uses eigenvectors and eigenvalues to rank web pages based on their connectivity.
    * It includes a worksheet that explains the algorithm and an assessment that requires implementing PageRank for a large network.
    * Key concepts include:
        * Eigenvalues and eigenvectors
        * Power iteration method
        * Markov chains
        * Damping parameter to handle rank sinks
* **Instructions:**
    * The notebook is divided into two parts:
        * Part 1 is a worksheet with explanatory text and code cells to understand PageRank.
        * Part 2 is an assessment where you need to implement the `pageRank` function.
* **Dependencies:**
    * numpy
    * numpy.linalg
    * matplotlib
    * readonly.PageRankFunctions (provided with the assignment)

## Usage

* These notebooks are designed to be run in a Jupyter environment.
* Follow the instructions within each notebook to execute the code and complete the exercises.

## Notes

* Some functions are provided in separate modules (`readonly.bearNecessities`, `readonly.PageRankFunctions`).  Do not modify these files.
* The notebooks may contain specific instructions related to online courses or assignments (e.g., submission guidelines).  Ignore these if you are using the code independently.
