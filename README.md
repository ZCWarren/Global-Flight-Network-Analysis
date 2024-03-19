# PC5253 Final Project
# Flight Network 

The goal is to study the global flight network properties and investigate if they are related to or predictive of passenger numbers at different airports. 

## 1. Research Questions and Objectives
- Main research questions:
   - What are the key properties of the global flight network?
   - How do these network properties relate to passenger numbers at different airports?
- Specific network properties to investigate(etc.):
   - Degree distribution
   - Average path length
   - Clustering coefficient
   - Centrality measures
- Objectives:
   - Identify the most significant network properties that predict passenger numbers
   - Develop predictive models to estimate passenger numbers based on network properties

## 2. Data Collection
- Data sources:
  - a. [OpenFlights](https://openflights.org)
  - b. [SNAP: Stanford Network Analysis Project - Reachability](https://snap.stanford.edu/data/reachability.html)
  - c. [Air Transportation Networks](http://seeslab.info/downloads/air-transportation-networks/)
  - d. [List of busiest airports by passenger traffic (2010-2015)](https://en.wikipedia.org/wiki/List_of_busiest_airports_by_passenger_traffic_(2010%E2%80%932015))
  - e. [Top 20 busiest airports in the world](https://aci.aero/wp-content/uploads/2021/09/Top_20-busiest_airports_in-the_world_2.pdf)

- Data preprocessing:
   - Handle missing or inconsistent information
   - Organize data in a suitable format for analysis (e.g., adjacency matrix, edge list)

## 3. Network Analysis
- Calculate basic network metrics:
   - Degree distribution
   - Average path length
   - Clustering coefficient
- Identify key airports (nodes) based on centrality measures:
   - Degree centrality
   - Betweenness centrality
   - PageRank
- Analyze network connectivity and resilience:
   - Giant component size
   - Percolation threshold
- Investigate community structure(etc.):
   - Louvain algorithm
   - Infomap algorithm

## 4. Relationship with Passenger Numbers
- Collect passenger number data for airports
- Explore correlations between network metrics and passenger numbers:
   - Pearson correlation
   - Spearman rank correlation
- Apply regression analysis to identify significant predictors of passenger numbers
- Investigate temporal patterns or trends

## 5. Model Development and Validation
- Develop predictive models:
   - Regression models
   - Machine learning algorithms
- Split data into training and testing sets
- Evaluate model performance:
   - Mean squared error
   - R-squared
- Perform cross-validation

## 6. Results Interpretation and Discussion
- Analyze results and interpret implications
- Discuss limitations and potential sources of bias or uncertainty
- Compare findings with previous research
- Highlight novel insights or contributions

## 7. Documentation and Presentation
- Document methodology, data sources, and results
- Create visualizations:
   - Network graphs
   - Scatter plots
- Prepare report or research paper:
   - Introduction
   - Methods
   - Results
   - Discussion
   - Conclusion
- Present work at conferences or workshops
