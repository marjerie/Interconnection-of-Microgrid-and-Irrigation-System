# Interconnection of Microgrid and Irrigation System

This work has been presented at 2019 Annual IEEE Global Humanitarian Technology Conference (GHTC), Seattle,
Washington and published [here](https://ieeexplore.ieee.org/abstract/document/9033013).

# Load Modelling

The irrigation load for agricultural purposes is designed using the code given below. It takes the weather data of the village into consideration
to provide an accurate representaion of the load demand. 

[Irrigation-load-modelling.ipynb](https://github.com/marjerie/Interconnection-of-Microgrid-and-Irrigation-System/blob/master/Irrigation-load-modelling.ipynb) <br>
[monsoon.txt](https://github.com/marjerie/Interconnection-of-Microgrid-and-Irrigation-System/blob/master/monsoon.txt) (Weather data)

The domestic load of the village is modelled taking into consideration of the number of houses, type of house, number of appliances and heat index of the 
village. The code to simulate the load demand for 20 years is given below.

[Domestic-load-modelling.ipynb](https://github.com/marjerie/Interconnection-of-Microgrid-and-Irrigation-System/blob/master/Domestic-load-modelling.ipynb) <br>
[HI.txt](https://github.com/marjerie/Interconnection-of-Microgrid-and-Irrigation-System/blob/master/HI.txt) (Heat Index)

# Base Design

The Irrigation system and the Microgrid system operate independently and is simuated in the code given below.

[Base-Design.ipynb](https://github.com/marjerie/Interconnection-of-Microgrid-and-Irrigation-System/blob/master/Base-Design.ipynb)

# Proposed Design

The two systems are interconnected and the energy transfer is enabled using the Smart Energy Transfer Algorithm which is given in the following code:

[Smart-Energy-Transfer-Algorithm.ipynb](https://github.com/marjerie/Interconnection-of-Microgrid-and-Irrigation-System/blob/master/Smart-Energy-Transfer-Algorithm.ipynb)
