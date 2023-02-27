# malaga-bus-graph
Analysis of bus public transport in Malaga using graphs. Project developed for the subject Learning from Networks, 2022-23 university of Padova.

## 1. Motivation
The motivation for this project was to analyze some of the main features of the bus public transport system of the city of Málaga, Spain using networks. Particularly, its frequency and speed. This analysis has taken place by creating a graph data structure with all the information about bus lines, stops, routes, and timetables… and extracting interesting characteristics from it using graph algorithms.

## 2. Current status
The initial objectives were seven, currently, we have completed four of them: (1) “Create a graph representing all the bus lines and stops…”, (2) “Compute some graph analytics at the node level…”, (6) “Do some experiments with random graphs…” and (7) “Create an analysis report with the conclusions”. This way, our work has been centered on computing graph analytics for nodes, especially closeness and betweenness centrality. After this, we studied some random graphs, following diverse models, to discover whether the centrality measures were relevant. Thus, the project title up to now could have changed to “Analysis of node centralities and its significance in the bus public transport of Málaga”.

## 3. Results
In a nutshell, we have discovered which are the more relevant bus stops in Málaga, in terms of closeness and betweenness centrality. For this, we have created a huge graph with multiple and directed edges. The information obtained has been contrasted with the characteristics of the city and its public transport. We have also proved that the centrality measures obtained are significant, by computing the same measures on random graphs and calculating some measures of significance.

In order to check that everything was working with the graph generated we displayed it graphically. This representation resembles fairly well the Málaga map, is the following:
![Line-based representation for our graph](drawings/line_based.png?raw=true "Line-based representation for our graph")

## 4. Localization
- ``/dataset/``: all the CSV files (taken from Datos Abiertos, Ayuntamiento de Málaga) used during the development of this project.
- ``/doc/``: all the documentation created about the project. It includes the project proposal (that was accepted by the professor) a midterm report explaining the status of the project before the Christmas vacation in 2022, and the final project report where all the work done is detailed.
- ``/drawings/``: some images and representations generated by the code.
- ``ProjectNotebook.ipynb``: all the code of the project in a Jupyter Notebook file.

## 5. Next steps
There is still a long way to go to elaborate a complete analysis. The next steps could be calculating some graphs level features and comparing them to other public transport systems in other cities or looking for the presence of some network patterns and motifs. Anyway, we consider that this project has been a very interesting and complete application of the theory studied in class.


