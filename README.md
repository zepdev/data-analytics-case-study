# Case Study - Data Analytics - Zeppelin GmbH

### Intro
Team Data Analytics provides data science and machine learning solutions to Zeppelin colleagues and customers. In order to give you an impression of our work and to see if you are a good match, we have prepared the following task based on one of our actual use cases. Please complete the task and be prepared to present your results in a short presentation (max. 15 min). Happy hacking!

### Expectations
Solve the following task and use the Guiding Questions to help structure your presentation. Do not invest too much time, we would expect a maximum of 3-5 hours. This is not a competition and we are not searching for the best machine learning model, instead we are interested in getting to know your personal style and how you approach this task. You can present your results in any kind of format that you are most comfortable with and best shows-off your skills.

### Task
Taking oil samples on a regular basis is a common part of construction machine maintenance. Oil samples are examined in Zeppelin's Oil Laboratory and are tested for things like lead, magnesium, water content, and contamination by fuel. These values can tell us a lot about the condition of a machine - similar to a blood count in humans. In the final step, a technician evaluates all of the values from the oil samples using their expert experience and they decide a final result that is then sent to the customer. Results can be; (GREEN) everything is okay, (ORANGE) the machine should be observed, or (RED) there is damage. Our technicians currently evaluate an average of 500-600 oil samples per day and over the last few years, approximately 1 million data records have been generated.

For more background on the oil lab check out this video (not necessary for the completion of the task and only available in German, sorry): https://www.youtube.com/watch?v=knl4sMAd-yA&ab_channel=ZeppelinBaumaschinen

### Guiding Questions
1. How could this situation be improved with the help of data science / machine learning? Please formulate the challenge as a data science / machine learning task.
2. What kind of Minimum Viable Product (MVP) could you offer to the technicians in Zeppelin's Oil Laboratory? Please think about how to reduce the scope of the project to only the most important aspects.
3. What kind of data would you ask for?
4. The database owner sent you the attached data (`data.csv`), together with a description of the data (`description.csv`). Please prepare and analyze the data to build a machine learning model. Use the tool of your choice (ie a Python Jupyter Notebook or R).
5. Build a machine learning model that is able to classify the three classes (1=GREEN(good), 2=ORANGE(warning), 3=RED(critical), target column: "class"). 
6. Choose an appropriate metric to evaluate the model. How could you explain the results to the technicians in the Oil Laboratory as simple as possible?
7. If the Oil Laboratory likes your results, what steps would have to be done to make the model available in day-to-day operations?
