# LebanesePoundForecast
A model to predict the black market rate of the Lebanese Pound as part of a Machine Learning course.

In this project, we use a Human Centered Design (HCD) approach to alleviate the impact of the economic crisis in Lebanon that violently struck the Lebanese market by shutting down businesses and diminishing the consumers’ purchasing power.

## How did we do it?

- We interviewed stakeholders and aggregated the relevant data to understand the users' needs
- We brainstormed solutions ranging from an online marketplace to an automatic need-based shopping curator

*We concluded that a Lebanese Lira forecaster would provide the highest sense of financial security to the users*

## What were our next steps?

- We created an initial wireframe with detailed features and user journeys
- We gathered feedback from stakeholders and iterated on our design
- We conducted a literature review to understand the solution landscape
- We collected, cleaned and visualized daily value of the black market Lebanese Lira over the course of 1 year
- We implemented several models ranging from ARIMA/SARIMA to LSTM, optimizing the parameters and evaluating model accuracy in an agile manner

The model was then tested in the real-world and feedback was conducted through interviews with stakeholders.

Forecast of the Lebanese Lira for October 2020

![https://anthonykahwaji.files.wordpress.com/2021/02/forecast.png?w=381](https://anthonykahwaji.files.wordpress.com/2021/02/forecast.png?w=381)

## What's next?

- Implementing a simple UI
- Improving the ML model to include more parameters:
    - Consumer Price Index
    - Market sentiment by analyzing news headline sentiment -NLP
- Developing a web-scraping tool to automate the collection of black market rates
    - Current Database can be found here but needs updating: https://drive.google.com/file/d/1QdvyOmDmC3m_muG2ZHd5XtCseBT9ch-5/view?usp=sharing
