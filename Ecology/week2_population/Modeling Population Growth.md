# Modeling Population Growth
- A population of a species is a part of a very complex system. If one wants to study the future of a population, one might make model of such by establishing some
assumptions to simplify complexity and make an informed prediction based on current information. 
- Here we discuss a very simple but powerful "Exponential Logistic growth model" based on the population's birth rate, death rate, and the habitat's carrying capacity. 

## Assumptions of Expoential growth model
- Although, a species's ability to reproduce follow exponential growth. This rarely happens in nature. Because there are always some factors that stops a species 
from doing so. May the factors be: predators, resourses, etc. 

### Expoential growth model
- <img src="https://render.githubusercontent.com/render/math?math=N_{t} = N_{0} * e^{rt} ">
- r = birth rate - death rate
- <img src="https://render.githubusercontent.com/render/math?math=N_{0}"> is the starting population of a species
- <img src="https://render.githubusercontent.com/render/math?math=N_{t}"> is the population of a species after t period.
(period depends on the species's reproduce period)

- <img src="https://render.githubusercontent.com/render/math?math=\frac{\mathrm{d} N}{\mathrm{d} t} = rN">
- This equation says the change of a population is r multiply its current population size.

## Assumptions of Logistic Expoential growth model
- The assumption made previously still applys here. Keep in mind that the carrying capacity is an estimation and can change from time to time.

### Logistic Expoential growth model
- After acquiring the expoential growth model, we take consideration of the carrying capacity.  
- Every area has a threshold—referred to as its “carrying capacity” and often indicated by the symbol K — the maximum number of individuals that it can support.
- As the population size approaches the carrying capacity, its growth rate will decrease. 
- Once the population size exceeds the carrying capacity, its growth rate will be negative. Because the area is unable to support such number.
- <img src="https://render.githubusercontent.com/render/math?math=\frac{\mathrm{d} N}{\mathrm{d} t} = r(1-\frac{N}{K})N">
- All this equation is doing is making its rate of change dependent on the ratio of its current population size and carrying capacity. 

## Applications
- Such models are used often in fishing industry. As the fishermen and regulation organizations need to come to an agreement of how many fish can be harvested 
while avoiding overfishing. 
- If use the above Logistic Expoential growth model, the amount of fish would be rK/4 (substituting <img src="https://render.githubusercontent.com/render/math?math=N = \frac{K}{2} ">) into  <img src="https://render.githubusercontent.com/render/math?math=r(1-\frac{N}{K})N">).
- <img src="https://render.githubusercontent.com/render/math?math=N = \frac{K}{2} "> Because the population size growth fastest in this case.
- (solve the derivative of <img src="https://render.githubusercontent.com/render/math?math=\frac{\mathrm{d} N}{\mathrm{d} t} = r(1-\frac{N}{K})N"> wrt. N)

## Limitation
- Note that harvesting at the “sustainable maximum” does not guarantee that a population will be stable. 
- Example:
- The Peruvian anchovy (Engraulis ringens) fishery, the largest in the world, was annually harvested near the sustained maximum from 1964 to 1971. Then, in 1972, because of overfishing and an El Niño event that affected reproduction, the fishery collapsed. 
- It’s an example of how natural disturbances can have long-lasting effects on populations and should be taken into account in management decisions.



