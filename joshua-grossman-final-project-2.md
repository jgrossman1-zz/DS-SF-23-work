# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) SF-DAT-21 | Final Project, Part 2: Project Design Writeup and Approval Template

Follow this as a guide to completing the project design writeup. The questions for each section are merely there to suggest what the baseline should cover; be sure to use detail as it will make the project much easier to approach as the class moves on.

### Project Problem and Hypothesis

- What's the project about? What problem are you solving?

### *For my final project I have chosen a Kaggle dataset that contains data on every shot Kobe Bryant took over the course of his basketbal career with the Los Angeles Lakers. I will be trying to predict if a shot was made based or missed

- Where does this seem to reside as a machine learning problem? Are you predicting some continuous number, or predicting a binary value?

### *Kobe took over 30,697 shots over the course of his 20 year career. Every shot he took was recorded as a make or a miss. The make or miss will be the binary value to be predicted.  The dataset also contains an array of meta data about the context of the shot, including shot location, type of shot, opponent, etc. Given the volume of data and set of dimensions this seems like a great opportunity to use machine learning to make a prediction

- What kind of impact do you think it could have?

### *Little to no impact, but a great opportunity to learn fundamentals of data science

- What do you think will have the most impact in predicting the value you are interested in solving for?

### *At this point I’m not sure, however I would imagine distance of shot, and location would play significant factors - there could be others

### Datasets

- Description of data set available, at the field level.  (see table)
- If from an API, include a sample return.  (this is usually included in API documentation!) (if doing this in markdown, use the JavaScript code tag)

attribute | datatype |
--- | ---
action_type | object
combined_shot_type | category
game_event_id | category
game_id | category
lat | float64
loc_x | int64
loc_y | int64
lon | float64
minutes_remaining | int64
period | object
playoffs | category
season | category
seconds_remaining | int64
shot_distance | int64
shot_made_flag | category
shot_type | category
shot_zone_area | object
shot_zone_basic | object
shot_zone_range | object
team_id | category
team_name | object
game_date | object
matchup | object
opponent | object

### Domain knowledge

- What experience do you already have around this area?

### *I watch a fair amount of basketball and understand the basics of the game

- Does it relate or help inform the project in any way?

### *Having a general knowledge of the game could help to determine what features are important

- What other research efforts exist?
    - Use a quick Google search to see what approaches others have made, or talk with your colleagues if it is work related about previous attempts at similar problems.

### *Nate Silver from 538 make sports predictions on sports including basketball, but I’m not aware of a way to benchmark this type of prediction

    - This could even just be something like "the marketing team put together a forecast in excel that doesn't do well."
    - Include a benchmark, how other models have performed, even if you are unsure what the metric means.

### Project Concerns

- What questions do you have about your project?  What are you not sure you quite yet understand?  (The more honest you are about this, the easier your instructors can help)

### *Still learning the tools and how to interpret the results correctly

- What are the assumptions and caveats to the problem?
    - What data do you not have access to but wish you had?
    - What is already implied about the observations in your data set?  For example, if your primary data set is twitter data, it may not be representative of the whole sample.  (say, predicting who would win an election)

### *The dataset is pretty thorough, but we don’t have any data on the defensive player who was guarding Kobe, which could be interesting. We also don’t have any data on the defensive strength of the opponent team

- What are the risks to the project?
    - What's the cost of your model being wrong?  (What's the benefit of your model being right?)
    - Is any of the data incorrect? Could it be incorrect?

### *It’s possible that some of the data is incorrect because it was recorded by humans, however the cost of the model being wrong is minimal

### Outcomes

- What do you expect the output to look like?

### *I’m under the assumption the closer shots will be easier to predict. I’m hoping to predict the shot made better than random

- What does your target audience expect the output to look like?

### *I would think the target audience would expect the model to be better than random

- What gain do you expect from your most important feature on its own?

### *I’m guessing shot distance will play a large factor, but hoping to uncover others

- How complicated does your model have to be?

### *I’d like to start simple and add complexity if I can improve the model's accuracy

- How successful does your project have to be in order to be considered a "success"?

### *I’d like to learn and apply new concepts; to me that is success

- What will you do if the project is a bust (this happens! but it shouldn't here)?

### *Try another dataset, and apply the same concepts