# Bill-of-Materials
This Python code implements a multi-level Bill of Materials (BOM) processor. 

**Functionality:**

* Calculates the total quantity of each raw material needed for given quantities of top-level assemblies (Assembly A and Assembly H).
* Calculates the total estimated cost based on raw material quantities and their unit costs.
* Generates a bulk processing template in Excel format for efficient calculation with varying quantities.
* Visualizes the BOM structure as a directed graph using NetworkX and Matplotlib.

**Usage:**

1. **Input:** Provide the quantities for Assembly A and Assembly H.
2. **Output:** 
    - A table displaying the total quantity of each raw material required.
    - The total estimated cost.
    - A visualization of the BOM structure.

**Data:**

* The BOM is defined as a dictionary where keys represent assemblies/sub-assemblies and values are lists of tuples containing child components and their quantities.
* Raw material costs are stored in a separate dictionary.

**Libraries Used:**

* pandas
* networkx
* matplotlib
* IPython


**Note:** The code can be easily adapted to different BOM structures and raw material data by modifying the input dictionaries.
