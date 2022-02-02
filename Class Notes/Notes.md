# Day1

Dataset is important - need to use standard size dataset.

2 things to consider :

if we use n no of characteristics then:

1. how much time is used for each file
2. after how much time are all the files in the dataset affected

There may be deviations in the total time from the expected time due to problems from the OS and other problems.

## Types

1. Supervised -> Previous information is present and their conclusion is also present and we are doing new stuff on the basis of that data
2. Unsupervised -> No previous information is present and it is asked to do a task. Output changes on how system decides to handle the task.
3. Reinforcement -> Initially unsupervised & then it becomes supervised.



Centroid v/s Meroid 

Centroid -> no physical existence

Meroid -> Physical existence

### Example (Unsupervised & Supervised)

We have a group of points & have to put them in 3 baskets depending upon centroid.

We keep on reshuffling until we get a proper centroid. This is a classification problem(unsupervised).

Now we can label the points like point1 belongs to category 1, pt2 -> ct3, etc.....

If we want to add a new point there, we can use these labels to get the pos where to put it. Like we can check how far deviation is there from category1, category2 and so on.....The one with the least deviation is where we put the data.



### Example 2 (Reinforcement)

Suppose there is robot in front of fire, water, etc.. The robot does not know which is good and which is bad.

The robot initially moves towards fire and sees that all its sensors are beeping and gets a negative reward and will not move towards fire.

Next time, the robot will not move towards fire as it slowly learns that fire is not good.



## Voting

We use 3 classifiers to check where to put the data. This will almost never give us 100% match, as 3 classifiers use 3 diff results



## Predictions not answers

ML is widely used to give us predictions especially in the medical industry, where ml does calcs and advises the dr to do certain stuff which the dr can consult to give proper treatment

Similarly automated cars, the functions turn left & right are implemented as classes and the car makes an informed choice about the decision taking in surrounding factors.

What we are doing becomes a class and then we have to take a decision



### Page 16: Predictions

We create a model and then use that to classify.



## Classification v/s Forecasting

Classification -> we can say which category it lies in. like put it in categories -> higher or lower, good or bad, etc.

Forecasting -> We put a value on the prediction -> Time Dependent data has to be used like temperature -> Like use past 7 days data for forecasting tomorow's weather



# Day2

Before solving a research-based question, we have to do certain things:

## First Step - Requirement Analysis

We have to check the requirements

## Background Check - Literature Survey

If the problem to be solved is already solved or not

Search what has been done regarding the problem that I am solving - journals, research, etc.

### Look back - but how much back in time do we have to look?

Looking too back might give us results that might be redundant, use old software or have better methods of solving

A good rule of thumb is to check for the last 5 years (sometime less or more).

Another good rule of thumb look back until we get atleast 10 research papers.

Decency : We must not haphazardly refer to all the sources. We mention the research papers in chronological order(oldest to newest or vice versa). Generally, we should refer the newest papers at the first and then slowly move on to the oldest papers.

## Analyze solutions and look for ways to improve the solution - Theoretical Foundation

We have to analyze the solutions we get and then look for the scope in the improvement by looking for the drawbacks in the past solutions.

The past papers produced better solutions and not perfect solutions.

Look for ways to enhance. If this step fails, we cannot move forward with solving the problem

If we find a way to enhance, then this becomes the scope of the problem.

## Implementation

Design <-  <<Interchangeable>>  -> Code

Many a times when we try coding, the design might not be practically non-implementable, then we have to look back to design and gradually improve the solution.

Very time-consuming process

## Testing

We do the implementation based upon some known data. Here we have to check the solution for some other valid data.

If we get a better result, we have completed the work 

## Conclusion

Conclude the results

































