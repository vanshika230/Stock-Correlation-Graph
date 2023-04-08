# Stock-Correlation-Graph

This code creates a correlation matrix from a dataset of asset prices, and then uses the networkx library to create a graph based on the correlation matrix.
 
     --> The first part of the code calculates the correlation matrix and creates a snapshot of the first 5 rows. 
     --> The second part of the code creates a graph by converting the correlation matrix to a numpy matrix and then using networkx to create the graph. 
     --> The third part of the code defines a function to create and display a network from the correlation matrix, which can be used to visualize the relationships between assets based on their correlations. 
     --> The fourth part of the code defines a function to separate between negative and positive correlations.
     --> Next we filter edges with a minimum correlation
     

## Implications :- 

Improved Visualization: The project provides an improved method for visualizing stock price correlations. The NetworkX library provides a powerful tool for creating interactive graphs, which can help users identify patterns and relationships in the data more easily.

Better Investment Decisions: By analyzing the correlation between stock prices, investors can make better-informed investment decisions. The project can help investors identify stocks that are likely to move in the same direction or stocks that are negatively correlated.

Enhanced Portfolio Management: Portfolio managers can use the project to optimize their portfolios by identifying stocks that have a high degree of correlation with other stocks in the portfolio. This can help to reduce risk and improve overall portfolio performance.

Research Opportunities: The project provides opportunities for researchers to study the correlation between stock prices in greater detail. Researchers can use the project to investigate how different sectors or industries are correlated or how correlations change over time.

Overall, the project has the potential to improve our understanding of stock price correlations and help investors make better-informed decisions.
