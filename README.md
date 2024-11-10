# Lennar-Risk-Score-Predictor

## Inspiration

Our inspiration was to challenge ourselves and push our limits by using ML to create a model that uses various attributes to generate a risk index for investing in the area. We understand the importance of knowing the potential risks based before investing a huge capital in a particular project so we have developed a tool that can help inform the investors about these potential risks.

## What it does

Our project is a web-based application that allows users to input the location of a particular piece of land and receive a risk assessment. The system analyzes various factors such as the crime rate, average population density, connectivity to the city  to generate a risk score for investing in a property.

## How we built it  ## Challenges we ran into
We spent more than 70% of the time gathering and cleaning data. Getting geospatial data pinpointing to a particular location was really hard. We tried to find all crime data, the number of disasters that occurred in the area, race, average age, percentage of lower status population, median incomes, radial distance from highways, number of corporate offices around, quality of soil and many such parameters.

We use latitude-longitude coordinates and classify the it into the county our location falls into, and maps all the data parameters to run a random forest ML model and output risk scores. We also added an inactive feature to make API calls to extract all the available local data for each location to provide risk scores more accurately. We also used variational auto encoders for data augmentation to fill the gaps,


The main challenge we faced during the development of our project was data acquisition. Finding accurate data that could reliably relate locations to their respective risk factors was one of the biggest problems. We had to spend 80% time compiling data from various sources, and feature engineering the data.

## Accomplishments that we're proud of
We are extremely proud of the fact that the model is able to produce accurate risk scores by specifically identifying flag zones and giving higher weight age to key parameters. 

## What we learned
The fact that data is crucial was already known but we learnt to be really creative with our data and how we drew insights from sparsely available data was a key learning lesson.
