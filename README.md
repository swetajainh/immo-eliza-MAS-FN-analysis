
# immo-eliza-MAS-FN-analysis

The Mission

Pick out the properties that are the most valuable to the real estate company Immo Eliza and their clients.

The real estate company Immo Eliza wants to establish itself as the biggest Belgian real estate services provider. To achieve that goal, they need to more accurately and faster than their competitors estimate the value of properties, to pick out those properties that are most valuable to them and their clients.

Enter creating a machine learning model to predict the prices of properties across Belgium. Having no in-house data scientists, they are looking for talented people to do it for them. Since your last encounter with them went great, they continue to rely on you to do the job. Everything is in your hands now!

By the end of this week, Immo Eliza's management wants to see a preliminary analysis based on the dataset you previously scraped. The management has no technical background. Broadly speaking, they have two main questions:

What are currently the most interesting insights about the Belgian real estate market?
What variables are the most important when determining the price of a property?


## Repo Structure

https://github.com/realpython/rptree
## Installation

### Step 1: Data Cleaning

You have collected your data, time to further clean it.

A cleaned dataset is a dataset that doesn't contain any duplicates, has no blank spaces, and has no other obvious errors. The rest of the analysis is worthless if you neglect this step; Garbage In, Garbage Out.

Take care of the following:

- No duplicates
- No blank spaces (e.g. " I love python " => "I love python")
- No empty values (set them to None or NaN)
- No wrongly encoded values (e.g. a text value in the price column)

### Step 2: Data Analysis
Now that the data has been both collected and cleaned, let's move on to the analysis.

You must be able to answer following questions (with a vizualization if appropriate):

- How many observations and features do you have?
- What is the proportion of missing values per column?
- Which variables would you delete and why?
- What variables are most subject to outliers?
- How many qualitative and quantitative variables are there? How would you transform the qualitative values into numerical values?
- What is the correlation between the variables and the price? Why do you think some variables are more correlated than others?
- How are the variables themselves correlated to each other? Can you find groups of variables that are correlated together?
- How are the number of properties distributed according to their surface?
- Which five variables do you consider the most important and why?
- What are the least/most expensive municipalities in Belgium/Wallonia/Flanders? (in terms of price per m², average price, and median price)

This is a non-exhaustive list of possible questions. Try to make a maximum number of interpretations from the dataset. Bonus points for creative and out-of-the-box insights.

Use tools such as matplotlib, seaborn, plotly, or [insert whatever visualization tool you find useful]...

Do your analysis in notebooks. No real need for scripting in this case, you'll want to have your hands free to experiment and explore the data in many directions. Writing functions for code you reuse is still a good idea, don't lose track of your good habits. Don't make it too messy though, your results should be reproducible and Immo Eliza's CEO might ask to rerun an analysis with a slight change :-)

### Step 3: Presentation
After analyzing your data, you're finally ready to present your results. You have to communicate your analysis using simple words and clear graphs, and ideally also deliver a few recommendations.

You can make your plots presentation-ready by accounting for the following points:

- A clear title
- A legend (if applicable)
- Add axis labels (in understandable language, no variable names)
- Add axis units
- Have comparable scales
- Have no overlapping text
- A main takeaway
- Remove all clutter that doesn't contribute to the message
- Smart use of colors

Don't mention data cleaning in your presentation as this is a technical background task. You should focus on the insights you found and the recommendations you can make.

```bash
  npm install my-project
  cd my-project
```
    
## Usage/Examples

```javascript
import Component from 'my-project'

function App() {
  return <Component />
}
```


## Visuals

Posting your code is good, but putting a little preview in the form of a screenshot (or even just your application logo) is a small touch that goes a long way.

Adding a link to an online demo is even more stylish!

Insert gif or link to demo
## Contributors

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.
## Timeline

When did you work on the project? Was it yesterday or three years ago? The GitHub repo will certainly mention the dates but it's still more pleasant to read when a human explains that the website showcasing the grey shrimp lovers was made during the summer of 2015 during a hackathon that took place in Miribel.