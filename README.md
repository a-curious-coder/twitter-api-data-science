# Data Science Twitter

## Scenario 1

Twitter Data Analysis 

> You have been asked to analyse information of the social media Twitter, such as the network of certain accounts, hashtags and some other data that can be extracted from it. You are required to implement a full Data Science Workflow going from the data gathering, cleaning, pre-processing, implementation of a model (network), and analysis of different statistics (e.g. Degree Distribution, Cluster coefficient, etc.); you are also required to provide justification of the process, analysis of the findings, reasoning behind the design and implementation, decisions, and assumptions.

> Your overall task is to implement the data science process on data collected from Twitter of at least three accounts and three hundred tweets (most recent tweets) of each account. 

## Scenario 2

Google Maps API

> An internal department in the university is looking to create a full and comprehensive list of travel time form some English postcodesto the university Whiteknights campus. They are expecting the output to be an Excel file or similar. The postcode areas for which they are asking to have this information are the following:

> RG, OX, SN, SP, GU, PO, SO, DH, DT, all London, SL, HP, MK, LU, AL, SG, GL, CV, B, GL, WR, HR, NP, DY, BA, BS, NN, LE and RH.

> The client knows that there are several providers from where to obtain the data, but they prefer Google Maps. An additional constraint is that they would like to be cost effective. Given that every API request has a cost involved and following the constraints of the project we need to make the requests effective. There are cases where the postcodes are close to each other or even are in the same building, considering this, one strategy is to select the most representative points in the data and just execute the API request on this representative sample; then the data can be replicated to the rest of data points.

Example output table (but not limited to):
| Postcode | Car travel time | Transit Travel time | Walking time |
|----------|-----------------|---------------------|--------------|
| RG1 1AB  |                 |                     |              |

## Setup

Open terminal and change your directory to the project's working directory.

Download and install virtualenv:

```
pip install virtualenv
```

Create your virtual environment

```
virtualenv .venv
```

Run your virtual environment

```
# Windows
.\.venv\Scripts\activate
# Mac
source .venv/bin/activate
```

Uncomment the first line of the notebook(s) to run

```
!pip install requirements.txt
```

which downloads and install all required libraries for this project to your virtual environment.

Run notebook using virtual environment
