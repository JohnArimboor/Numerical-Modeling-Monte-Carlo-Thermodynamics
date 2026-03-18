# Numerical-Modeling-Monte-Carlo-Thermodynamics

Project Overview:- 
The goal of this project is to simulate how real gases behave under high pressure by modeling the microscopic interactions between individual molecules. The project aims in taking raw, non-linear physical parameters and build an algorithmic solver for an unsolvable equation using Python and Monte Carlo algorithms and produce data (like molar volume).

Problem give to solve:- 
In standard physics classes, we are taught the Ideal Gas Law which is pV=nRT. It pretends that gas molecules are infinitely small dots that never interact with each other.
In the real world, especially under high pressure, this is completely false. Real gas molecules have a physical size and they constantly bump into, attract and repel one another. To accurately predict how a real gas behaves, we have to calculate a specific correction score (known as the second virial coefficient) that measures exactly how much these molecules push and pull on each other.

The Roadblock to solve:- he mathematical formula that describes this microscopic pushing and pulling is incredibly messy. It creates a curve so complex that standard calculus literally cannot calculate the area underneath it. We cannot solve this on paper; we need a numerical model.
