# Assignment 1 - Designing Models and Analyzing Data (Template)


> * Participant name: (Vanessa Thompson)
> * Project Title: (Moving Escalator: Can We Get there Faster?)

# General Introduction

The first part of this assignment explores designing models (and basic Python/Git features). 

We will look at **subway model in a city** system. A **subway system** is an underground, tube, or metro, underground railway system used to transport large numbers of passengers within urban and suburban areas - modern subways use different types of electronic data collection sensors to supply information which is used to manage assets and resources efficiently. 

The second part of the assignment explores data analysis. Data analysis and visualization is key to both the input and output of simulations. This assignment explores different random number generators, distributions, visualizations, and statistics. Additionally, it will look at getting you accustomed to specifying input and output variables to a system. We will also practice working with real data.


# Part 1: Designing a Model - Subway System


The yearly influx of individuals visiting and/or commuting underground transportations has vastly increased for major cities around the world. For instances, the city of London, England has experienced for the past few years record-breaking numbers of both visitors and new residents, in addition to existing residents to it’s already overcrowded transportation systems (Erianger, 2016). That is the case for London’s Underground subway stations, which currently not only experiencing more frequent over-crowdedness but also an increase in annual ridership (2016). Thus analyzing the usages and over-reliance on transporting systems such as escalators are essential to understand areas in which these types of public facilities can reduce problematic issues such as over-crowdedness. One aspect concerning the usage of escalators within London’s Underground stations is observing and understanding behavior patterns of passengers and their traffic flow. This study will analyzes these passengers’ behavior patterns and their relationship with the system performance of the escalators. It is to the benefit of all passengers and the Underground subway operators and workers to study ways of enhancing the traveling experiences/usages of subway escalators that could establish organization in the subway traffic flow, augment safety measures and improve the timing flow of passengers moving hypothetically from point A to point B. 

Erianger, S. (2016). A London subway experiment: Please don’t walk up the escalator. Retrieved from http://www.nytimes.com/2016/06/13/world/europe/a-london-subway-experiment-please-dont-walk-up-the-escalator.html


![Image of Subway City System](images/subway_model.png)

## (Part 1.1): Requirements (Experimental Design) **(10%)**

When using escalators, many passengers may form a pattern of stepping onto every step or every other step. They may also hesitate upon boarding the first step or approach the escalator in an urgent manner than other passengers and may want to bypass those ahead of them. Such behavior however may attribute to the increasing rate of bottlenecking at the entrance opening of the escalators. To help the need of passenger users in their traffic flow movements, this study aims to observer the effect of constructing order to passengers’ behavior patterns. A set of requirements pertaining to this system shall specify that:

For passenger: 
•	Users need to move from one destination to the next in a timely manner
•	Users need to move in an orderly fashion
•	Every other step shall have two occupants traveling on it

For Escalator system:
•	Have the capacity to operate/perform to its maximum conditions
•	Have the capacity to perform to its optimal running speed towards its intended direction (going up)
•	Be able to quietly and smoothly operate constantly and efficiently during the hours of operations
•	Shall have moving speed of conveyor stairs equaling to moving speed of handrails.


## (Part 1.2) Subway (My Problem) Model **(10%)**

(remove: add a high-level overview of your model, the part below should link to the model directory markdown files)
(remove: Look at the [**Object Diagram**](model/object_diagram.md) for how to structure this part of Part 2 for each diagram. Only the Object diagram has the template, the rest are blank. )

* [**Object Diagram**](model/objectdiagram.jpg) - provides the high level overview of components
* [**Class Diagram**](model/classdiagram.jpg) - provides details of (what are you providing details of)
* [**Behavior Diagram**](model/sequencediagram.jpg) - provides details of (what are you providing details of)
* [**Agent / User case** (if appropriate)](model/usediagram.jpg) - provides details of (what are you providing details of)

## (Part 1.3) Subway (My Problem) Simulation **(10%)**

Observing and analyzing the passenger behavior patterns and the system performance of the escalator can incorporate the usage of all three types of simulations (continuous-based, discrete-event, and agent-based) due to both the static and dynamic natures of the escalator systems. With the use of AnyLogic, we can first establish agent-based aspects to emphasis behavior patterns of passengers. However, we can add the agent-based aspect to a discrete-event approach. This approach would be most optimal to simulate the pattern from studying how by having two passengers board every other escalator step, we may (1) increase the moving amount of passengers between the entrance and exit per minute, (2) reduce the size of congestion at the boarding entrance, and thus (3) reduce the waiting time for passengers moving from one point to the next.


## (Part 1.4) Subway City (My Problem) Model **(10%)**
[**Escalator model**](code/POTS_system/escalator_object.py) - Starting coding framework for the escalator model.
You are expected to create the python files - the code should run without errors, create and object(s) for your system, but not provide function detail.



## (Part 1.5) Specifying the Inputs to a System **(10%)**


While using every other step may seem to be wasting extra space, we are also optimizing as much private space for passengers. By having passenger side-by-side as oppose to directly behind one another, we not only provide upper body- face forward space per passenger but also allow extra (however little) time at the boarding entrance for any passenger hesitating to make the first step and limit time wasting. The idea is to answer the research question: Is it possible to organize passengers to ride the escalator two-per-step as they board every other step in the pursuit of reducing their waiting time, the size of any congestion upon boarding, and increase the number ratio of passengers using the escalator per minute? 

Compare to one passenger on each step, it is hypothesized that passengers will have a shorter waiting time and travel faster when two per every other step is utilized. Two experiments will be conducted: (1) pedestrians travel escalator one per step; (2) pedestrians travel side-by-side every other step. The independent variables are the number of passenger per step, and the usage of every and every other step. Dependent variables will be the amount of waiting time boarding the escalator and the amount of passengers exiting the escalator per minute. Moreover, the experimental group is individuals using the subway station. 

It is important to capture the average mean of the passenger waiting time and the amount of passenger exiting the escalator for each experiment. Analyzing these data will help draw inferences concerning the output of the simulation. A multi-bar chart can be used to visualize the timing flow of passengers waiting at the entrance and the amount exiting after riding the escalator, in respect to their independent group. This chart graph can be part of a bigger infographic display depicting two images representing the two different travel patterns of escalators (i.e. one person each step or two per every other step). In addition to the multi-bar, pie charts will be use to highlight the relationship between results in each independent group and also between them.



# Part 2: Creating a Model from Code

## (Part 2.1) **P**ortable **O**rganic **T**rouble-free **S**elf-watering System (**POTS**) Model **(10%)**
Here [**we provide an overview**](code/POTS_system/README.md) of the **P**ortable **O**rganic **T**rouble-free **S**elf-watering System (**POTS**) Model and provide a source code template for the code found in  [**the following folder**](code/POTS_system/). Please create a **class** diagram of this model (replace the placeholder diagram). (you can use paper and pencil or a digital tool).
[POTS](model/POTS.jpg)



# Part 3: Data Analysis

## (Part 3.1) - Real Data **(10%)**

In November of 2015, the Transport of London conducted an experiment at a London tube station named Holborn to examine the effects of having station passengers use both the left and right sides of two escalators at the stations. The research experiment observed that during rush hours in the morning and evening more than 110 passengers per minute traveled through the escalator. This is in comparison to earlier data of approximately 80 passengers per minute traveling the escalator with one-side stand only, leaving the other side open for potential walkers. Moreover, there’s a 30% overall increased of passengers per hour traveling on both sides of escalator during these peak times at the station. These data are beneficial for the system of this current study because any new data in comparison will emphasize the effects of the extra space on waiting time and passenger per minute when passengers are organized to ride on both sides, every other step of the escalator.  There are standard data on the capacity of the escalator that should be considered. Pertaining to the London Underground, escalators are set to travel at a 0.75m per second. Each step is 1m wide and 0.4m in length. At this rate, a new step will appear at the bottom entrance almost every 0.5 seconds (0.4m ÷ 0.75m per second). Using the method of having a passenger on every step, we calculate that the maximum capacity of an escalator carries approximately 7000 passengers per hour (3600 second/hr ÷ 0.5 seconds/step = 7000). Thus, if there is 30% increased of passengers if they utilized both sides of each step, then this method may increase the rate of passengers to over 9000 per hour. This study will observe whether the amount of  ≈ 9000 passengers will increase, decrease, or have no significant effect when passengers ride the escalator two people per every other step. 
[**Pie Chart**](images/ExamplePieData.docx)

Data retrieved from:
Erianger, S. (2016). A London subway experiment: Please don’t walk up the escalator. Retrieved from http://www.nytimes.com/2016/06/13/world/europe/a-london-subway-experiment-please-dont-walk-up-the-escalator.html



## (Part 3.2) -  Plotting 2D Random Number Generators **(15%)**

This portion of the assignment looks at generating random numbers in Python and understanding how to properly plot them. Plot two different random numbers, pseudo random and quasi random, for five different N values. There should be 10 subplots, all properly formatted 2D plots. Note, each of the N points will have two coordinates, an x and a y, therefore you will need to generate two random numbers for each point. You should replace the image with your results in a simalar format. Discuss how the patterns differ. Feel free to change the N values from the suggested N values in the image to state your case.

![Image of 2d template City](images/2Dtemplate.png)(images/pseudo N100.png)(images/pseudo N500.png)(images/pseudo N1000.png)(images/pseudo N2500.png)(images/pseudo N5000.png)


## (Part 3.3) -  Plotting 1D Random Distributions **(15%)**

Now, choose three different distributions to plot in 1D, or as a histogram. Choose a pseudo-random generator and generate three different distributions. Example distributions are Uniform (part 8), Normal, Exponential, Poisson, and Chi-Squared, but feel free to use any three distributions of your choice. Again, plot each distribution for five different Ns. This will result in 15 different subplots, formatted similar to the image in Part 8. Include your properly formmated 1D plots below and breifly describe what we are looking at and how things change as N is changed.

Repeat the above using a quasi-random generator. Discuss the similarities and differences.
