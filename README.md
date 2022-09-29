# AspenPythonInterface
Aspen Plus to Python interface for the automation of the process synthesis. This API can be used for most equipment inside of the Aspen Plus system. The library consists of around 5000 lines of code which are made up of many smaller functions which each are able to set or get some value in the aspen plus user interface. It is based on the automation server which aspen plus has implemented together with the variable manager. Please read the documentation report if you plan to work with it.



Capabilities:
- Editing flowsheets
- Creating new flowsheet parts
- Setting values in equipment
- running simulations
- exporting results from simulations
- using optimization algorithms to optimize flowsheet


Applications:
- Case 1: Varying stagenumber in Destillation column to optimize energy usage
- Case 2: applying genetic algorithm to optimize TAC for destillation column sequence
- Almost all automated optimizations for the design of Aspen Plus programs can be done here since most variables are included in this library.



Equipment included:    (input&output function for each page)
- Heater
- Mixer
- RPLUG
- RCSTR


 
