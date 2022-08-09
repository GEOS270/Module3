---
layout: default
title: Assessment Key
parent: Potatoes
nav_order: 5
---

# Assessment

You can use the submit your answers to the Assessment via the Module 2 Quiz on Canvas.  Questions are listed here with hyperlinks to the relevant section of the module if you need help finding answers.  If you would like a .pdf version of the instructions, you can it download it [here](https://raw.githubusercontent.com/June-Skeeter/Module2_GEOS270/main/docs/Assessment.pdf).


## Written Answers & File Uploads

Written answers should be brief but they should adequately answer the question.  Bullet point format is sufficient unless otherwise specified.  All written answers & charts will be evaluated following this general rubrics below.

* Scores & categories are general guides, you TA may assign scores between these levels
* Your TA will provide brief comments where applicable, if you need more feedback you can follow up with your TA.

**Written Answer Rubric**

|Score|      Category      |                             Details                              |
|-----|--------------------|------------------------------------------------------------------|
|0%   |Missing             |N/A                                                               |
|40%  |Insufficient        |Minimal effort, missing major key points, or serious logical flaws|
|60%  |Below Expectations  |Missing a few key points or minor logical flaws                   |
|80%  |Met Expectations    |Hits key points and mostly well constructed                       |
|100% |Exceeds Expectations|Clearly thought out, concise, and astute                          |

**Charts Rubric**

|Score|      Category      |                             Details                               |
|-----|--------------------|-------------------------------------------------------------------|
|0%   |Missing             |N/A                                                                |
|40%  |Insufficient        |Serious errors in analysis, missing data, or major stylistic issues|
|60%  |Below Expectations  |Minor errors in analysis or multiple stylistic issues              |
|80%  |Met Expectations    |Error free analysis, minor stylistic issue                         |
|100% |Exceeds Expectations|Error free analysis and clean, aesthetically pleasing map/chart    |


---

# Module Quiz (30pts)

All quiz answers are multiple choice, numeric input, fill in the blank, etc. type questions.  They can be submitted via the Module 1 Quiz that can be found on the Canvas page.  You will have unlimited attempts to take the quiz.

## Content

### [QC1](Content_Part1.md#qc1)
It is important to avoid using sequential color pallets or graduated symbols for _____ data because they can imply a ranking/direction, even though this type of data has no rank/direction.

Correct:  **Nominal**
Half Pts:  Qualitative, Categorical

### [QC2](Content_Part1.md#qc2)
Diverging color maps are great for showing deviations from a mean value. [T/F]

Correct:  **True**

### [QC3](Content_Part1.md#qc3)
Sequential color maps use gradations of different shades (light/dark) of the same color. [T/F]

Correct:  **True**

### [QC4](Content_Part1.md#qc4)
The best maps can be interpreted quickly and easily [T/F]

Correct:  **True**

### [QC5](Content_Part1.md#qc5)
You always want to put as much information on a map as possible, even if it will overwhelm the map reader! [T/F]

Correct:  **False**

### [QC6](Content_Part1.md#qc6)
Every map should always have a north arrow. [T/F]

Correct:  **False**

### [QC7](Content_Part1.md#qc7)
This type of colorblindness impacts ~ 4.5% of the human population.

- Red-Green
- Blue-Green
- Red-Blue
- Full Spectrum

Correct:  **Red-Green**

### [QC8](Content_Part2.md#qc8)
Supervised classification methods area always better than unsupervised because humans are smarter than computers. [T/F]

Correct:  **False**

### [QC9](Content_Part2.md#qc9)
The natural breaks algorithm is a(n) _______ classification method that seeks to _______ similarity within classes and _______ dissimilarity between classes.

**0**
Correct:  **unsupervised**
Half Pts:  Jenks

**1**
Correct:  **maximize**
Half Pts:  maximize group

**2**
Correct:  **maximize**
Half Pts:  maximize group


### [QC10](Content_Part2.md#qc10)
Classification and regression trees (CART) are a _______ classification method that requires a user to provide _______ data.

**0**
Correct:  **supervised, user defined**
Half Pts:  

**1**
Correct:  **training, defined category, a set of classes as training**
Half Pts:  



### [QC11](Content_Part2.md#qc11)
Unsupervised classification methods require no input from the user, the computer does all the work!! [T/F]

Correct:  **False**

---

## Application 

### [QA1](Application_Part1.md#qa1)
Simply Analytics allows you to download data about businesses locations. [T/F]

Correct:  **True**

### [QA2](Application_Part1.md#qa2)
We used the clip tool to ensure we don't  ____ population density in the coastal Subdivisions.

Correct:  **underestimate, miscalculate, wrongly calculate, underrepresent, underrepresented, misrepresent**
Half Pts:  decrease, distort


### [QA3](Application_Part2.md#qa3)
The Select by Attribute tool lets us use SQL (Structured Query Language) to define expressions for querying vector data. [T/F]

Correct:  **True**

### [QA4](Application_Part3.md#qa4)
Box plots are most useful for looking at counts [T/F]

Correct:  **False**

### [QA5](Application_Part3.md#qa5)
In which Population Centre and Rural Area class does the the largest proportion of BC's population live?

- Large Urban Population Centre
- Rural
- Small Population Centre
- Medium Population Centre

Correct:  **Large Urban Population Centre**

### [QA6](Application_Part3.md#qa6)
What proportion of BC's overall population lives in Rural Areas?   (Round to the nearest tenth)  *Hint* Sum the four classes to get the total population.

29.0
Correct:  **28.9 - 29.1**
Half Pts:  **28.8 - 29.2**


### [QA7](Application_Part3.md#qa7)
What is the median percentage of their income people in Rural areas spend on food?  (Round to the nearest tenth)

17.2
Correct:  **17.1 - 17.3**
Half Pts:  **17.0 - 17.4**


---

# Module Assignment (70 pts)

All written answers should be numbered and record in one document, saved as a .pdf, and uploaded to canvas.  The file submissions should also be saved as .pdf and uploaded as a separate document.  **Written answers can be as brief as you want as long as they answer the question.**


## Content

### [WC1](Content_Part2.md#qc1) - 10 pts
Briefly, explain the differences between Supervised and Unsupervised classification methods.

- With supervised classification, the user either explicitly defines the class boundaries, or provides a training dataset with defined classes and has the system learn the boundaries.  When we define the classes, sometimes were at risk for inducing our own bias.

- With unsupervised classification, the user *generally* picks the number of classes (some advanced methods can do this this part too, but I don't expect them to mention that) and then the system defines the classes from there. - Not truly "unsupervised" because its not like the computer just spontaneously classifies things, we have to initiate and guide the process.

---

## Application

### [WA1](Application_Part1.md#wa1) - 10pts
Do you think this kind of information (locations of restaurants, groceries, etc.) might be helpful when studying the cost of food in a region?

- I'm looking for them to say something involving critical thought - ie. proximity to groceries (>travel distance = >cost$), >#groceries = >choice, etc.

### [WA2](Application_Part1.md#wa2) - 10pts
Which projection did are choose for the feature dataset?  Why did I choose this projection?

-BC Albers Equal Area - Equal Area because we're calculating **Population Dentistry**, BC Albers because its specific to BC


### [WA3](Application_Part2.md#wa3) - 10pts
Skim the Introduction of the [Documentation](https://www.statcan.gc.ca/eng/subjects/standard/pcrac/2016/introduction) explaining the classification scheme.  What was the reasoning behind updating from the old Rural/Urban method?

- The old urban class treated a small town of 1000 the same as a city of 1,000,000 - they needed a finer resolution classification because 2 groups was insufficient to distinguish given the scale of difference.

### [WA4](Application_Part3.md#wa4) - 10pts
Create Scatter Plot with Population Density on the X-Axis and Income_on_Food on the Y axis.  Does the r2 score indicate a relationship?  How does classifying the data help us reveal patterns in the data we cant easily see in the scatter plot?

- The scatterplot does not show a strong relationshp.  Classifiying the highlights the relationship better, by specifically grouping census subdivisions using two factors: total population **and** population density.  It allows us to see that cities have a close spread in the same range.  It also shows that while not all rurlal area are impacted by food affordability issues, all of the worst affected areas **are** rural.


---

## File Submissions

### [FA1](Application_Part3.md#fa1) - 10pts each (20pts total)
Submit your Bar Chart and Box Plot to Canvas.

- Must use colorscheme that is red-green colorblind friendly [see this video for reference on what I've told them](https://youtu.be/3Kf0Ng3ZVBs?t=687) **&** suitable for qualitative data (not a sequential colormap)

- Should have meaningful concise labels (edit out underscores, etc.) & generally be aesthetically pleasing.


# Rubric 

All written answers and file submissions will be scored using this generic rubric.  Your TA will provide brief comments where applicable.  For more feedback you can follow up with your TA.

|Score|Comments            |
|-----|--------------------|
| 0%  |Missing             |
| 25% |Insufficient        |
| 50% |Below Expectations  |
| 75% |Met Expectations    |
| 100%|Exceeds Expectations|

