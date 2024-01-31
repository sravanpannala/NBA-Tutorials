# NBA Analytics Tutorials by Sravan

This repo will contain tutorials related to NBA data scraping, processing, analysis and visualization.
Most of the tutorials here will be refined versions of code in my [NBA Projects repo](https://github.com/sravanpannala/NBA). The setup required for that repo is hard and can prevent many people from coding and running the code, thus leading to the creation of this repo. The setup required should be easy, and the tutorials will be easy to follow along and run, while having detailed explanations.

These tutorials take inspiration from:
- [Owen Phillips:](https://twitter.com/owenlhjphillips) [The F5 Substack](https://thef5.substack.com/)
- [Ryan Davis: NBA Tutorials](https://github.com/rd11490/NBA_Tutorials)
- [Andrew Patton: Basic NBA Tutorials](https://github.com/anpatton/basic-nba-tutorials)

The tutorials will also have a companion piece on my blog [https://blog.sradjoker.cc](https://blog.sradjoker.cc), which will go through methodology/analysis.  
Contact me on Twitter at [@SravanNBA](https://twitter.com/SravanNBA) if you have any questions/comments/concerns.  

# Setup
- The code in this repo is written in Python or iPython (jupyter) notebooks. You need python to run the code.
- You can install the packages required by this repo using [poetry](https://python-poetry.org/). 
- After installing poetry, just run in this folder
```
poetry install
```
- This command will install all the packages used to run the different codes in this repo in a new virtual environment.
- You can use the newly generated virtual environment as the kernel for the notebooks in this repo.

# Tutorials

### [1. How To: Adjust NBA Team Rating for Strength of Schedule (SoS) Using an RAPM styled approach](./sos_adjusted_ratings/how_to_adjust_nba_team_ratings_for_sos.ipynb)  
[Companion blog article](https://blog.sradjoker.cc/posts/nba-sosadj/)

### [2. How To: Analyze and Plot Three Point Shooting Trends](./three_pt_shooting_trends/plotting_three_pt_shooting_trends.ipynb)  
[Companion blog article](https://blog.sradjoker.cc/posts/nba-3pt-winning/)

