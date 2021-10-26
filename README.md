# Assignment 1: Protests
The past few years in the United States, there has been a surge in protests in support of Black Lives Matter, gender equity, and other social issues. In this assignment, you'll work with data from [CountLove](https://countlove.org/) -- the same data often [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the New York Times -- to learn more about demonstrations over the past few years.

By completing the assignment, you will demonstrate the following skills:

- Use of **version control** for managing your code
- Declaring document rendering using **markdown** syntax
- Foundational programming skills in R.


## Background Research
Before diving into this (or any) dataset, it's important to have _domain familiarity_ (i.e., to know something about the topic). As preparation, I'm asking that you read **three articles** about protests in the U.S., and provide a brief 1 - 2 sentence summary or takeaway from each one.

In the section below, create an **unordered list** of the three articles you found. Make sure to provide an appropriate markdown link (_not_ just the URL) to the article in addition to your 1 - 2 sentence summary.

[Black Lives Matter May Be the Largest Movement in U.S. History](https://www.nytimes.com/interactive/2020/07/03/us/george-floyd-protests-crowd-size.html) -- The protests that started during the summer of 2020 was the result of building pressure in society concerning racism and it finally reached its tipping point with the death of George Floyd.

[The U.S Capitol Riots and the Double Standard of Protest Policing](https://www.usnews.com/news/national-news/articles/2021-01-12/the-us-capitol-riots-and-the-double-standard-of-protest-policing) -- There is a blatant double standard regarding the racist classification of a protest and a riot which is heavily dependent on the group of people gathering.

[Pandemics and protests: America has experienced racism like this before](https://www.brookings.edu/blog/how-we-rise/2021/06/09/pandemics-and-protests-america-has-experienced-racism-like-this-before/) -- These protests rooted in combating racism in society is not a new concept and history has been consistently repeating itself.


## Accompanying Image
In this section, please **display one image** to accompany your text, and describe _why_ you included it (~2 - 3 sentences). This will require that you download an image into your project folder. In your description, use **bold** and _italics_ (at least once, for practice) to emphasize some of your points.

![Protest](https://github.com/nlc02/a1-protests-nlc02/blob/main/!%5BProtest%5D(Protest_Image.jpeg).jpeg)

This image has placed two photos side by side that are almost **60 years** apart. I chose this image because the right photo is from the march in D.C. where **Martin Luther King** gave his incredibly famous "I Have a Dream" speech and the left is from the summer of 2020. Notably, they are shockingly similar demonstrating the _longevity of the BLM movement's fight for equality_.

## Analysis
At this point, you should open up your `analysis.R` script to begin working with the data. The script will guide you through an initial analysis of the data. Throughout the script, there are prompts labeled **Reflection**. Please write 1 - 2 sentences for each of these reflections below:

- What does the difference between the mean and the median tell you about the *distribution* of the data?
  - The _distribution_ is **skewed** since the mean and median are different. The median doesn't depend on the values of the dataset like the mean does therefore the **median** has a better representation of the data.
- Does the number of protests in Washington surprise you? Why or why not?
  - **Not entirely**, I have always considered Washington to be a mostly democratic state. Although I have a bias since I attend the University of Washington which I understand to be a _liberal_ univeristy.
- Looking at the `state_table` variable, what data quality issues do you notice, and how would you use that to change your analysis (no need to actually change your analysis)?
  - There are some case issues with the state since some are in **_lowercase_ instead of uppercase**. I would add them into their corresponding uppercase state in order to have a number of states that is _less than or equal to 50_.
- Does the change in the number of protests from 2019 to 2020 surprise you? Why or why not?
  - **No**, being on social media during both years I am able to recognize context to the great disproportion between 2019 and 2020.
- Do a bit of research. Find at least *two specific policies* that have been changed as a result of protests in 2020. These may be at the city, state, or University level. Please provide a basic summary, as well as a link to each article.
  -
- Take a look (`View()`) your `high_level_table` variable. What picture does this paint of the U.S.?
  - The U.S. has a **huge problem of racial injustice** above anything else right now.

## Final Thoughts
When you are finished, with your analysis, please answer the following questions in 1-2 sentences each.

- What about the analysis surprised you?
- What parts of this analysis did you find challenging?
- What types of analysis do you wish you were able to do with the dataset, but currently don't have the technical skills to do?
