# Fandom-Analysis
Analysis to understand Star Wars fans

While waiting for Star Wars: The Force Awakens, the team at FiveThirtyEight was interested in answering some questions about Star Wars fans. One question that particularly interested the team was: "Does the rest of America realize that “The Empire Strikes Back” is clearly the best of the bunch?"

To address this question [FiveThirtyEight](https://fivethirtyeight.com/) surveyed Star Wars fans using the online tool SurveyMonkey. They received 835 total responses, which you download from [here](https://github.com/fivethirtyeight/data/tree/master/star-wars-survey).

# Know your Dataset
The data has several columns, including:

* **RespondentID** - An anonymized ID for the respondent (person taking the survey)
* **Gender** - The respondent's gender
* **Age** - The respondent's age
* **Household Income** - The respondent's income
* **Education** - The respondent's education level
* **Location (Census Region)** - The respondent's location
* **Have you seen any of the 6 films in the Star Wars franchise?** - Has a Yes or No response
* **Do you consider yourself to be a fan of the Star Wars film franchise?** - Has a Yes or No response

There are several other columns containing answers to questions about the Star Wars movies. For some questions, the respondent had to check one or more boxes. This type of data is difficult to represent in columnar format. As a result, this data set needs a lot of cleaning.
