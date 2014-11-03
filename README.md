# Name

Michael Aaron

# How many points have you earned?

100/100

(Make your own calculation and replace the number 0 with the points you think you've earned.)

# How many hours have you spent on this?

3.5 hours

# When did you first start working on this week's learning challenges?

fill-in-your-answer

# What is the most difficult part about this week's challenge?

fill-in-your-answer

# Show and tell (6 points)

## Link (2 points)

[Circle Packing](http://bl.ocks.org/mbostock/4063530)

## Write down TWO D3 features you’d like to learn next . (4 points)
- JSON integration to tool tips/ other datum
- Angular transformations

fill-in-your-answer

# MongoDB III

## Checkpoints (4 points x 1 = 4 points)

# 1. (4 points)

![image](https://www.dropbox.com/s/9hc76g1jwwvfd9w/Screenshot%202014-11-02%2021.39.40.png?dl=1)

## Challenges (5 points x 5 = 25 points)

# 1. (5 points)

> db.aiddate.find({donor: "Belgium", disbursement_amount:{$ne:""}}, {_id: 1, recipient:1, disbursement_amount: 1})

![screenshot](https://www.dropbox.com/s/4bdrvvrgmyot2py/Screenshot%202014-11-02%2022.08.21.png?dl=1)

# 2. (5 points)

> db.aiddate.find({biodiversity:{$ne:""}}, {_id_:1, recipient:1, title:1, biodiversity:1})

![screenshot](https://www.dropbox.com/s/5z7hw2256smr4hz/Screenshot%202014-11-02%2023.20.33.png?dl=1)

# 3. (5 points)

> db.runCommand({distinct: "aiddate", key:"flow_type"})

![screenshot](https://www.dropbox.com/s/hvotvritaep0nap/Screenshot%202014-11-02%2023.54.37.png?dl=1)

# 4. (5 points)

> db.runCommand({distinct: "aiddate", key:"flow_type", query:{disbursement_amount:{$gt:100000}}})

![screenshot](https://www.dropbox.com/s/r4um0fs8tr7elsd/Screenshot%202014-11-03%2000.01.21.png?dl=1)

# 5. (5 points)

> > db.aiddate.aggregate( [ { $match:{donor: "Belgium"} }, {$group: {_id: "$year",total :{$sum: "$disbursement_amount"}}}])

![screenshot](https://www.dropbox.com/s/3ig00bpyjjo1y0m/Screenshot%202014-11-03%2000.21.04.png?dl=1)

# Machine Learning (II)

## Challenge 1 (3 points x 4 = 12 points)

### a. (3 points)

![screenshot](https://www.dropbox.com/s/psm56uzo2pmrh1d/Screenshot%202014-11-03%2009.08.26.png?dl=1)

### b. (3 points)

![screenshot](https://www.dropbox.com/s/sulgnojl8k907db/Screenshot%202014-11-03%2009.09.32.png?dl=1)

### c. (3 points) 

![screenshot](https://www.dropbox.com/s/rmnhnspgtqtm7a0/Screenshot%202014-11-03%2009.13.43.png?dl=1)

### d. (3 points) 

![screenshot](https://www.dropbox.com/s/rmnhnspgtqtm7a0/Screenshot%202014-11-03%2009.13.43.png?dl=1)

## Challenge 2 (8 points)

Doing analysis on a data set is very difficult when you don't nessesaily know what the fields mean. For example, Flag Touch After Event
seems like it is probably a relevant field, but I am not entirely sure what it corralates with. The analysis I decided upon was viewing
the times where Gravity Z was highest, corrlated with when the error occures. As I don't have a description for the fields, I am not really
sure if this is correct. But it seems that often later in the study the z acceleration of the phones for most users went up. I wouldn't
be entirely suprised if this correlated with an error (setting the phone down, pulling it away from you in frusturation); but I don't 
have a ton of evidence to back that up. 
![screenshot](https://www.dropbox.com/s/o4ly5hnjsliae2y/Screenshot%202014-11-03%2009.41.11.png?dl=1)


# D3 (V)

## Checkpoints (5 points x 4 = 20 points)

# 1. (5 points)

![image](https://www.dropbox.com/s/nlkro172vka02n3/Screenshot%202014-11-03%2013.08.25.png?dl=1)

[checkpoint](d321.html)

# 2. (5 points)

![image](https://www.dropbox.com/s/e7d2jmn6pujomkr/Screenshot%202014-11-03%2014.01.24.png?dl=1)

[checkpoint](d3_checkpoint2.html)

# 3. (5 points)

![image](https://www.dropbox.com/s/xjspk7eignafyrp/Screenshot%202014-11-03%2014.06.24.png?dl=1)

[checkpoint](d3_checkpoint3.html)

# 4. (5 points)

![image](https://www.dropbox.com/s/jfwu4d1lbnahd3f/Screenshot%202014-11-03%2014.09.31.png?dl=1)

[checkpoint](d3_checkpoint4.html)

## Challenges 	(5 points x 3 + 10 points = 25 points)

### 1. (5 points)

![screenshot](https://www.dropbox.com/s/amxciquh0utlr1o/Screenshot%202014-11-03%2014.23.39.png?dl=1)

### 2. (5 points)

![screenshot](https://www.dropbox.com/s/o8yo27hnpihnqrt/Screenshot%202014-11-03%2014.26.38.png?dl=1)

### 3. (5 points)

![screenshot](https://www.dropbox.com/s/ny2p76b2t7e7vuc/Screenshot%202014-11-03%2014.27.39.png?dl=1)

### 4. (10 points)

-What is the layout of 4 and 5 star resturants in Las Vegas? [based on lat and long]

![screenshot](https://www.dropbox.com/s/gres0s78ovt1zrr/Screenshot%202014-11-03%2014.47.07.png?dl=1)

