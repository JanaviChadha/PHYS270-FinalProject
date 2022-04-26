# PHYS260-FinalProject

## Authors: Janavi Chadha, Zuzanna Matysiak

COVID-19 pandemic has affected lives of many individuals across the world in the past 2 years. Therefore, in our project we simulated spread of the COVID-19 disease using Brownian motion given various initial conditions to understand the potential infection rate better.

To understand this problem better, we decided to perform 5 different analysis that can be found in the following files as well as on our poster:
- COVID-19 Infection Spread With Varied Initial Position -> analysis of how the starting position of the infected person affects the rate at which others get infected
- Color_Simulation_VPython-> vPython animation and analysis of spread of coronavirus given people can be categorized into 3 groups: mask-wearers, non-mask wearers and immunocompromised. 
- Forming Groups.ipynb -> vPython animation on how infection differs when people only interact with individuals from their own group. We accomplished this by chaning the force that each person can exert on others
- COVID-19 spread of misinformation analysis.ipynb -> analysis of how the number of people who do not spread misinformation affects the rate at which misin	ation reaches everyone.
- Orig_Simulation_No_VPython.ipynb -> This file when run generates a graph that plots the number of people infected over time for the original simulation where where each person you be infected with 100% certaintity if they came into contact with an infected person. 
- 320 Molecules.ipynb - Increased the number of people in the simulation to 320 to be able to provide a better analysis

To find more details about each of the analysis, please check out the files and/or the poster.

Split of responsibilities:
We worked on the code together through live share most of the time but some of the running of the graphs and vPython animations, we performed separately.
Janavi worked on the groups file and Zuzanna worked on the spread of misinformation. The rest of the files and analyses were performed together.
The poster was also done in collaboration. 

Project Requirements : 

	Enhancements : We took the Molecular Dynamics exercise that we did in class and created multiple versions of the simulations slightly editing for 	diffrent setups in each of the runs. We added the ability to chance the mass of each of hte molecules to change how they interacted with each other. 	By doing this they created large clusters instead of the original dipoles that were created. We also added more graphs and removed the temperature 	bar since it did not add to our simulation. Finally added the ability to chance the number of molecules in the system but this simulation is only 	able to be run without the visual python aid since when we tried running with visual python my computer was not able to handle fully generating and 	moving the molcules when there were more than 80 

	Numberical Methods : To accomplish this project we utilized the Trapezoid rule to normalize the radial distrubted function and we utilized the 	lennard Jone interaction to tell us how the "people" moved and what happened if two people interacted


Questions our Poster Answered : 

	What scientific question did you attempt to answer? Include any relevant background information.
	What numerical methods did you employ and why? Provide details about any approximations made.
	What are the results of your calculations and what can you conclude from them?
	How accurate are your results?
	Are there theoretical predictions or experimental results relevant to your project? If so, how well does your calculation agree with them?