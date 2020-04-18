# Inspiration

Until a few weeks ago there were hardly any useful infographics, modelling of the spread or curated datasets about Covid-19 available. This made it hard to communicate the gravity of the situation to friends and decision makers. Also this made it difficult for researchers to just start, analyse data, develop machine learning models. Thus, Richard started to takle this as a project. His inspiration was to build unified and curated datasets of various countries, which contain Covid-19 cases with population details and political actions to forecast future spread in order to enable both decision makers and individuals to make personal adjustments.

# What it does so far

The project has three parts.
We have been working on all three parts to provide an end-to-end prototype to showcase how such projects can be done and motivate to continue working on the project:

1. Data Layer: Software that downloads publicly available datasets and harmonizes them such that they can be merged together easily. For some countries the data preparation is finished (Germany, USA, UK, China), others are close to finishing.
2. Modelling: Different models where theoretically discussed. We implemented an extended SIR model that is able to forecast the spread of the virus.
3. Presentation: We visualized our results and present them at a webpage, showing both the historical course and the future course using the predicitve models.

# How we built it

We used the data science stack of python: python, scipy, numpy, pandas. The webpage is running on the github.

# Challenges we ran into

Finding data for the countries was not that simple, cleaning it, defining standards - all that takes quite a bit of time.

# What we are proud of and what we learned
