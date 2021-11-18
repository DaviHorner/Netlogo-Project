# Netlogo-Project

## WHAT IS IT?

This model explores the stability of predator-prey-water ecosystems. Such a system is called unstable if it tends to result in extinction for one or more species involved.  In contrast, a system is stable if it tends to maintain itself over time, despite fluctuations in population sizes.

## HOW IT WORKS

There are two main variations to this model.

In the first variation, the "sheep-wolves-grass" version models grass (green) and wolves and sheep. The sheep must eat grass in order to maintain their energy - when they run out of energy they die. Once grass is eaten it will only regrow after a fixed amount of time nad if is close to water that in this model doesn't exist. Because of this the simulation is doomed to fail.

The second variation,  the "sheep-wolves-grass-water" version add the patch of water(blue) to the simulation, and create "rain" where after 360 ticks the simulation generate a certain amount of blue patches where before where brown patches. This simulation is able stable on the default settings.    

The construction of this model utilized the predation model from Netlogo 6.2
