# time-mgmt
Single node version for personal time management &amp; Distributed version for team project management

<p align="center">
  <img src="http://leoncom.org/wp-content/uploads/TraceInfrastructure_12137/image.png" width="400px"/>
</p>

<p align="center">
  <em>Task Dependencies / Credit to Google Dapper Paper</em>
</p>

# Initial Plan (Single Node Version)

1. Think an individual as a CPU
2. How to organize tasks in terms of priority, deadline, and complexity
3. Consider every possible scenarios
4. Think about the requirement of the task itself (importance & urgency) and whether it's easy to be done (our efficiency & its complexity)

# ToDo

1. Security on rich-editor
2. Make it as a convenient daily tool first
   + Based on Time （Resource)
   + Based on Topic (Planning)
3. *Formulate Task Dependencies*, Graph Algo
4. __Topic Distribution__ for _a range of time_
5. __Cores__: Node, Edge, View
   + Node:
     + Automatic Classification/Clustering (with/without checked topices) for each new Task
     + Ranking
       + In terms of Node Importances
     + Node Feature/Metric
   + Edge:
     + [Graph Theory](https://en.wikipedia.org/wiki/Graph_theory)
   + View:
     + Reorganize the hierarchy like dealing with DOM
     + Emphasize different perspective
       + Left Dropdown (Topics, title dropdown) + Middle (optional, Titles) + Right Full text (Description)
       + Ranking
         + Different Views centered around different tasks or objects or topics
     + Allow duplication for easir manipulation and reorganization
     + Form a new module or component when it includes so many details (the way of forming hierarchy)
# Reading

1. [Redirecting](http://api.rubyonrails.org/classes/ActionController/Redirecting.html)
2. [Rails 5 improves redirect_to :back with new redirect_back method](http://blog.bigbinary.com/2016/02/29/rails-5-improves-redirect_to_back-with-redirect-back.html)
3. [Getting Started with Rails](http://guides.rubyonrails.org/getting_started.html)
