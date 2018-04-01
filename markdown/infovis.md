# InfoVis

Information visualization is a key part of the notebooks. We want to bring visual thinking, interactivity, and resources so vast they require visualizatins, to the K-12 students and teachers. 

### Background

##### Why do we visualize data?
+ External cognition
    + Use visualizations as external memory
    + Increase our problem solving capacity, beyond internal/mental processes
    + Connect to external data sources, extend our senses
+ Knowledge crystallization
    + Gather information
    + Make sense of it with a representational framework
    + Package results for communication or action
+ Discovery
    + Complex loops of interactions between data, visualization, and cognition
    + Can use imagination and exploration to leverage visualization and discover new ideas (use external world to increase our ability to think)


##### 6 Ways that Visualizations Amplify Cognition
1. Increasing the memory and processing resources available to users
2. Reducing the search for information
3. Using visual representations to enhance the detection of patterns
4. Enabling perceptual inference operations
5. Using perceptual attention mechanisms for monitoring
6. Encoding information in a manipulable medium

##### Limitations
+ Computational
    + Primarily the notebooks use remote resources from the hub to run their code but sometimes use the user's local resources. 
[//]: # (More on this [here](****) and [here](*****))
+ Perceptual/Cognitive
+ Display
    + If you are creating visualizations with small details the display limits will be a factor. Many schools use old low resolution screens, don't assume it will look the same way it does on your expensive work computer. Avoid fine grained details.
    + Not all displays are callibrated corectly, if you use many colours which have to be discriminated from each other, be sure to use [color brewer](http://colorbrewer2.org) to select your colour scheme.

##### Types of Data
1. Quantitative
2. Ordered 
3. Categorical

Special note: relational data represented by graphs, networks, trees

##### Visual Encoding Principles

### Practical Tips
Disclaimer: these are generalizations, use your own discretion. There are many situations where you should ignore these guidelines.

+ Avoid 3D if a 2D solution exists.

+ Design Mantra for Interactivity
"Overview first, zoom and filter, then details on demand" - Schneiderman (1996)

+ Text labels should be useful (can be crucial), not cluttering the design.

+ [Don't use pie charts](https://blog.funnel.io/why-we-dont-use-pie-charts-and-some-tips-on-better-data-visualizations), although this is [controversial](https://eagereyes.org/pie-charts)

+ [Avoid](https://python-graph-gallery.com/125-small-multiples-for-line-chart/) using spaghetti plots where many lines are layered on top of each other.

+ **Uphold accessibility standards!** 

##### Questions to ask yourself, is your visualization:
+ Informative. What are you trying to communicate with your datavis and is this the best way to communicate it? What information do you want to convey, how can you make it clearest to the user? Do any aspects of your datavis distract from the information you are trying to convey?
+ Representative. Is your data qualitative or quantitative? Discrete or continuous? Does your visualization match the data type?
+ Intuitive. If someone looked at my datavis, would they immediately understand it?

### Useful Links
Use [Color brewer](http://colorbrewer2.org) to select your color schemes.

[Basics](https://eagereyes.org/section/basics) you should know.

[Further reading](https://eagereyes.org/section/techniques) on infovis techniques.

[Perceptual edge](http://www.perceptualedge.com/) is a treasure trove of infovis.

[A gallery](http://conceptviz.github.io/#/e30=) of concept visualizations.

p.s. if you would like to learn more about information visualization reach out to india (india@pims.math.ca), she works in an infovis lab. Special thanks to Madison Elliott for providing many of these infovis outlines.