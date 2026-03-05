# RC-Circuit-Simulator
OVERVIEW:

I Built a interactive simulator that models an RC circuits charging and discharging over time. The program takes the inputs given like resistance, capaticance, and voltage, as well as weather or not the user wants the graph to discharging or charging. The program then takes these inputs and plots a Rc graph using standard Rc equations. I also used NumPy and Matplotlib to graph it. I built this program because I wanted to practice my python coding skills as well as getting a head start on learning and understanding fundemental Electrical Engineering concepts!

FEATURES:

- Interactive inputs for resistance, capacitance, voltage, and weather or not you want the graph to show charging and discharging 
- ajustable simulation length
- voltage v time Graph with lines, titles, and variables using Matplotlib

HOW IT WORKS  :

-For the simulator I used the standard RC time formula 
t = r*c

-for the charging aspect I used 
v(t) = V0(1-e^(-t/(r*c)))

-for discharging I used 
V(t) = V0(e^(-t/(r*c)))

-To gain the information I needed to make the graph I used Input code so that the user would be able to change what the capacitance, resistance, and  voltage was 

- after this 

- I then set the program to run up to 5T because thats about where the capciatator would be full.


HOW TO RUN 

- you must download matplotlib, and NumPy in python

- then input values and Voilia!

  PROJECT GOALS

  - The main goal for this project was to develope my ability to code in python. I knew as a developing engineer it was import to start working on the little skills that might help me later on. So combining the python I know and simple RC circuits I knew it would be a positive in the worthwhile.


    START/END DATE

    start: 2/28/2026
    end: 3/4/2026















