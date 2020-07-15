## Methane pyrolysis
### Techno-economic modelling of methane pyrolysis based hydrogen direct reduction of iron ore
The first step is to download import the relevant libraries required for the model.This includes the pandas, numpy and matplotlib libraries. An easier way to get all these libraries in one place is to download and install the Anaconda distribution, which is widely used for scientific computations. The size of the figures and the dpi for the figures is pre-defined to get publication quality graphs. 


 

**Assumptions:** 
1. Actual amount of hydrogen entering the shaft furnace is higher than the stoichiometric value.The ration between the actual value and the stoichiometric value is defined as lambda_$h_2$ in these calculations.   
2. Hydrogen production of 200 kili tonne per annum has been considered.  
3. Plant is operational 95% of the time in an year operating_hours
4. Reactor temperature varies from 1000-1200 C.
5. Two different heat sources have been considered for heating the bubble column reactor (gas fired heater or electric heating).
6. Methane conversion varies from 0.65 to 0.90
8. Methane feed rate varies from 1837  mol/sec to 2544 mol/sec
7. Reaction geometries etc. were taken from : https://www.sciencedirect.com/science/article/pii/S0360319919343666
8. Bubble column reactor was operated with liquid tin. Properties of tin at high temperature were taken from : https://link.springer.com/content/pdf/10.1134/S0036029518020143.pdf
9. The density of liquid tin was estimated using " Reference data for the density and viscosity of liquid copper and liquid tin"
link : https://aip.scitation.org/doi/10.1063/1.3467496

