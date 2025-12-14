# STATS 506 - FINAL PROJECT

Research Question: Has belief in astrology increased among Americans between 2006 and 2018, and has this trend been significantly prevalent for young adults and women?

Dataset:

-   Response variable: `astrosci` - opinion on the scientific nature of astrology

-   Explanatory variables:

    -   `year` : years that the question was surveyed on, centered at 2012
    -   `sex` : respondent's gender
    -   `age` : respondent's age, divided into three groups - 18-35, 36-49, and 50+
    -   `educ` : highest year of school completed
    -   `relig` : respondent's religious preference, sorting major religious groups - Christian, Catholic, Jewish, None, Other non-Christian, Other
    -   `polviews`: political view, extremely liberal - point 1 - to extremely conservative - point 7

Methods: Ordinal Logistic Regression

-   Base Model: all variables

-   Sex Model: include `year`\*`sex` interaction

-   Age Model: include `year`\*`age groups` interaction
