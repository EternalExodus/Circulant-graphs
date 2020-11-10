# Circulant-graphs
This work presents examples of algorithms for generating circular and Paley graphs using the python language.

When talking about graphs of this kind, we are talking about their signature of the form C(N, s1, s2, ..., sn), where 
        C is the notation of the circulator; 
        N is the number of graph vertices; 
        s1, s2, ..., sn are generators of the graph, that is, these numbers define an edge connecting the vertices x and x + s1, x + s2, ..., x + sn.
This is how we have defined the graph.

Script С_ (N, s1, s2) generates a graph with N vertices and two generators. As a result of the script's work, we have 2 csv files of the format required for further integration into Gephi software: a file with vertex designations and a file with designations and vertices that they connect.

Example:
In the Example folder you can see the files describing the graph C (9,2,3). The result of integrating this data into Gephi after the necessary reduction to the required visual form, namely the circulant, is shown in the figure below.
![alt text](Example/C(9,2,3)/C(9,2,3).png "Описание будет тут")
