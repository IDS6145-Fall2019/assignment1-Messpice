# Assignment 1 - Designing Models and Analyzing Data (Template)


> * Participant name: (Vanessa Thompson)
> * Project Title: (Moving Escalator: Can We Get there Faster?)

# General Introduction

The first part of this assignment explores designing models (and basic Python/Git features). 

We will look at **subway model in a city** system. A **subway system** is an underground, tube, or metro, underground railway system used to transport large numbers of passengers within urban and suburban areas - modern subways use different types of electronic data collection sensors to supply information which is used to manage assets and resources efficiently. 

The second part of the assignment explores data analysis. Data analysis and visualization is key to both the input and output of simulations. This assignment explores different random number generators, distributions, visualizations, and statistics. Additionally, it will look at getting you accustomed to specifying input and output variables to a system. We will also practice working with real data.


# Part 1: Designing a Model - Subway System


The yearly influx of individuals visiting and/or commuting underground transportations has vastly increased for major cities around the world. For instances, the city of London, England has experienced for the past few years record-breaking numbers of both visitors and new residents, in addition to existing residents to it’s already overcrowded transportation systems (Erianger, 2016). That is the case for London’s Underground subway stations, which currently not only experiencing more frequent over-crowdedness but also an increase in annual ridership (2016). Thus analyzing the usages and over-reliance on transporting systems such as escalators are essential to understand areas in which these types of public facilities can reduce problematic issues such as over-crowdedness. One aspect concerning the usage of escalators within London’s Underground stations is observing and understanding behavior patterns of pedestrians and their traffic flow. This study will analyzes these pedestrians’ behavior patterns and their relationship with the system performance of the escalators. It is to the benefit of all pedestrians and the Underground subway operators and workers to study ways of enhancing the traveling experiences/usages of subway escalators that could establish organization in the subway traffic flow, augment safety measures and improve the timing flow of pedestrians moving hypothetically from point A to point B. 

Erianger, S. (2016). A London subway experiment: Please don’t walk up the escalator. Retrieved from http://www.nytimes.com/2016/06/13/world/europe/a-london-subway-experiment-please-dont-walk-up-the-escalator.html


![Image of Subway City System](images/subway_model.png)

## (Part 1.1): Requirements (Experimental Design) **(10%)**

When using escalators, many pedestrians may form a pattern of stepping onto every step or every other step. They may also hesitate upon boarding the first step or approach the escalator in an urgent manner than other pedestrians and may want to bypass those ahead of them. Such behavior however may attribute to the increasing rate of bottlenecking at the entrance opening of the escalators. To help the need of pedestrian users in their traffic flow movements, this study aims to observer the effect of constructing order to pedestrians’ behavior patterns. A set of requirements pertaining to this system shall specify that:

For pedestrian: 
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

* [**Object Diagram**](model/object_diagram.md) - provides the high level overview of components
* [**Class Diagram**](model/class_diagram.md) - provides details of (what are you providing details of)
* [**Behavior Diagram**](model/behavior_diagram.md) - provides details of (what are you providing details of)
* [**Agent / User case** (if appropriate)](model/agent_usecase_diagram.md) - provides details of (what are you providing details of)

## (Part 1.3) Subway (My Problem) Simulation **(10%)**

Observing and analyzing the pedestrian behavior patterns and the system performance of the escalator can incorporate the usage of all three types of simulations (continuous-based, discrete-event, and agent-based) due to both the static and dynamic natures of the escalator systems. With the use of AnyLogic, we can first establish agent-based aspects to emphasis behavior patterns of pedestrian. However, we can add the agent-based aspect to a discrete-event approach. This approach would be most optimal to simulate the pattern from studying how by having two pedestrian board every other escalator step, we may (1) increase the moving amount of pedestrian between the entrance and exit per minute, (2) reduce the size of congestion at the boarding entrance, and thus (3) reduce the waiting time for pedestrians moving from one point to the next.


## (Part 1.4) Subway City (My Problem) Model **(10%)**
[**Code template**](code/README.md) - Starting coding framework for the (insert your exact problem here.)
You are expected to create the python files - the code should run without errors, create and object(s) for your system, but not provide function detail.



## (Part 1.5) Specifying the Inputs to a System **(10%)**


While using every other step may seem to be wasting extra space, we are also optimizing as much private space for pedestrian. By having pedestrian side-by-side as oppose to directly behind one another, we not only provide upper body- face forward space per pedestrian but also allow extra (however little) time at the boarding entrance for any pedestrian hesitating to make the first step and limit time wasting. The idea is to answer the research question: Is it possible to organize pedestrians to ride the escalator two-per-step as they board every other step in the pursuit of reducing their waiting time, the size of any congestion upon boarding, and increase the number ratio of pedestrian using the escalator per minute? 

Compare to one pedestrian on each step, it is hypothesized that pedestrian will have a shorter waiting time and travel faster when two per every other step is utilized. Two experiments will be conducted: (1) pedestrians travel escalator one per step; (2) pedestrians travel side-by-side every other step. The independent variables are the number of pedestrian per step, and the usage of every and every other step. Dependent variables will be the amount of waiting time boarding the escalator and the amount of pedestrian exiting the escalator per minute. Moreover, the experimental group is individuals using the subway station. 

It is important to capture the average mean of the pedestrian waiting time and the amount of pedestrian exiting the escalator for each experiment. Analyzing these data will help draw inferences concerning the output of the simulation. A multi-bar chart can be used to visualize the timing flow of pedestrian waiting at the entrance and the amount exiting after riding the escalator, in respect to their independent group. This chart graph can be part of a bigger infographic display depicting two images representing the two different travel patterns of escalators (i.e. one person each step or two per every other step). In addition to the multi-bar, pie charts will be use to highlight the relationship between results in each independent group and also between them.



# Part 2: Creating a Model from Code

## (Part 2.1) **P**ortable **O**rganic **T**rouble-free **S**elf-watering System (**POTS**) Model **(10%)**
Here [**we provide an overview**](code/POTS_system/README.md) of the **P**ortable **O**rganic **T**rouble-free **S**elf-watering System (**POTS**) Model and provide a source code template for the code found in  [**the following folder**](code/POTS_system/). Please create a **class** diagram of this model (replace the placeholder diagram). (you can use paper and pencil or a digital tool).
POTS.jpg



# Part 3: Data Analysis

## (Part 3.1) - Real Data **(10%)**

Find a datasource that looks at part of this model - subway stations locations / escalator number, heights, widths / volume of passangers - ridership numbers   (*fits* - we are pretty loose here, it can be anything.)

* Write up a paragraph that describes the data and how it fits into your system.
* Load the data into Python
* Calculate a few useful statistic on the data - keep it simple- STD, means, etc..., this is just designed * to get used to working with real data. Explain the insights you derive from these statistics.
* Visualize the raw data - visualize a few critical aspects of the data to better describe what it is, what it is showing, and why its useful to your system.
* Calculate and plot some summary statistics that better describe the data.

(Add your plots and visualization here)
(Put your data into the data directory)


## (Part 3.2) -  Plotting 2D Random Number Generators **(15%)**

This portion of the assignment looks at generating random numbers in Python and understanding how to properly plot them. Plot two different random numbers, pseudo random and quasi random, for five different N values. There should be 10 subplots, all properly formatted 2D plots. Note, each of the N points will have two coordinates, an x and a y, therefore you will need to generate two random numbers for each point. You should replace the image with your results in a simalar format. Discuss how the patterns differ. Feel free to change the N values from the suggested N values in the image to state your case.

![Image of 2d template City](images/2Dtemplate.png)


## (Part 3.3) -  Plotting 1D Random Distributions **(15%)**

Now, choose three different distributions to plot in 1D, or as a histogram. Choose a pseudo-random generator and generate three different distributions. Example distributions are Uniform (part 8), Normal, Exponential, Poisson, and Chi-Squared, but feel free to use any three distributions of your choice. Again, plot each distribution for five different Ns. This will result in 15 different subplots, formatted similar to the image in Part 8. Include your properly formmated 1D plots below and breifly describe what we are looking at and how things change as N is changed.

Repeat the above using a quasi-random generator. Discuss the similarities and differences.
