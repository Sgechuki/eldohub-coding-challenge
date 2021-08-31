eldohub-coding-challenge
### Data Science/ Data Analytics challenge
Consider a dataset providing information on the functionality of infrastructure resources,
for each water point it includes the name of the village it is in and its functional state.<br>
Implement a data processing module in python which takes a dataset URL as input and
returns:<br>
● The number of water points that are functional,<br>
● The number of water points per community,<br>
● The rank for each community by the percentage of broken water points.<br>
There should be a top level object or function calculate(“http://...”), which returns a data
structure with the above information, something like:<br>
{<br>
number_functional: …,<br>
number_water_points: {<br>
communityA: …,<br>
},<br>
community_ranking: …<br>
}<br>
But that’s just a suggestion and we can think of alternative, maybe better, data structures
to use.<br>
We will use a water point dataset that contains many columns, the relevant ones are:<br>
communities_villages, water_functioning<br>
The data can be found on this <a href=https://raw.githubusercontent.com/onaio/ona-tech/master/data/water_points.json>URL</a><br>
When your solution is complete, upload it to github (if you do not have a github account
you may create a free one). Submit your solution by sending us a link to it on github.
