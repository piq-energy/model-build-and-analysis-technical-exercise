# Power Systems Engineering Technical Exercise

Welcome to the Power Systems Engineering technical exercise. This assignment is designed to assess your expertise in power systems analysis and your proficiency with coding, particularly using Python.

## Objective

Analyze the impact of integrating a significant new load into an existing high voltage power grid and evaluate the system's performance under various contingency scenarios.

## Tasks

**Step 1: Build the Power Flow Model**

- Use the provided `csv` files to synthesize a power flow case of the power grid.
- Ensure that the base case converges.

**Step 2: Perform Contingency Analysis**

- Develop an N-1 contingency analysis tool using Python or any open-source software of your choice.
- Run the tool on your power flow case to simulate various outage scenarios.
- Report all thermal overloads and voltage violations identified during the contingencies.

**Step 3: Integrate the New Data Center Load**

- Incorporate a 300 MW data center load at bus **242** into your power flow model.
- Re-run the contingency analysis with the new load included.
- Identify and report any constraints or violations introduced due to the additional load.

**Step 4: Solutioning**

- Identify possible technical solutions for resolving any identified violations.
- Integrate the identified solutions in the case and validate their effectiveness 

**Step 5: Data Visualization**

- Develop visualizations to aid in analyzing the results.

## Guidelines

- **Tools and Technologies**
  - You may use any open-source power system analysis software, such as pandapower; Python is highly recommended.
  - Same applies to other libraries needed for analysis and vizualization.

- **Assumptions**
  - Document any assumptions made during modeling and analysis.
  - This includes default values for missing data, simplifications, or methodological choices.

- **Submission Instructions**
  - Fork this repository and create a new branch for your work.
  - Include your code, results, and any supporting documentation or visualizations.
  - Provide a concise report summarizing your approach and findings.

## Evaluation Criteria

Your submission will be evaluated based on the following:

- **Technical Proficiency**: Demonstrated ability to perform accurate power system modeling and analysis.
- **Coding Skills**: Effective and efficient use of Python and relevant libraries.
- **Problem-Solving**: Ability to identify, analyze, and address potential issues within the power system.
- **Reproducibility**: Ensure all steps are documented and easy to replicate, including code, data, and dependencies.
- **Communication**: Clarity and thoroughness in documentation and reporting of methods and results.
- **Professionalism**: Adherence to best practices in engineering and coding standards.

