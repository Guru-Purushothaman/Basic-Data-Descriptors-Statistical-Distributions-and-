
Correct
1 / 1
point
1. Question 1
A new airline company has a commuter airplane that can hold up to 64 passengers. The plane flies a single route and charges passengers $300 for a one-way fare. All fares are 100% refundable if the passenger does not show up for the flight. The fixed cost (the cost that does not change with the number of passengers, such as crew salaries, airport fees, etc) for every flight is $1,000. The variable cost (the additional cost per passenger) for every flight is $150 per passenger.

Create a spreadsheet that calculates the total profit per flight based on the number of passengers on the plane. What is the total profit if they fly with 56 passengers?

HINT:

1. Create a column of "Total number of passengers", put in values 1 through 64

2. The next column would be "Variable Cost". Put in values in this column, for example if you fly with 1 passenger the variable cost is $150, if with 2 passengers then it is 2*$150, with 15 passengers it is 15*$150 and so on.

3. The third column would be "Total Cost" which is the "Variable Cost" plus "Fixed Cost", i.e. the number in the Variable Cost column plus $1000

4. The fourth column would be "Revenue" column which is "Total number of passengers"*$300. That is if the plane only carries 1 passenger then the revenue is 1*$300, if it carries 43 passengers then revenue is 43*$300 and so on.

5. The fifth column would be "Profit" column which simply is "Revenue" column minus the "Total Cost" column.

6. Once you have created this "Profit" column then read off the value of profit when the plane flies with 56 passengers. That is your answer.

7400
Correct Response 

Correct
1 / 1
point
2. Question 2
Because they have a full refund policy, it is common for customers not to show up. Airline company management is wondering if it would make financial sense to overbook the flight and risk having not enough seats for all passengers that show up. In that case, the airline would find volunteers to give up their seats in exchange for a free ticket to the same destination on the next available flight. This would cost $100 for each overbooked passenger.

Update your spreadsheet to account for overbooked passengers. What is the total profit if they fly with 64 passengers after having sold 72 tickets, assuming all 72 passengers show up?

7800
Correct Response 

Correct
1 / 1
point
3. Question 3
If 80 tickets are sold, the number of passengers expected to show up can be approximated by a normal distribution with a mean of 68 and standard deviation of 5. Therefore, if the airline sells 80 tickets for the flight, what is the probability that the number of passengers who show up will result in an overbooked flight? Enter your answer as a decimal probability (not a percent) rounded to 4 decimal places.

0.7799
Correct Response 
=NORM.DIST(80,68,5,TRUE)-NORM.DIST(64,68,5,TRUE)


Incorrect
0 / 1
point
4. Question 4
Fill in the blank:

Using the same distribution as the previous question, there is a 0.10 probability that more than _________ passengers show up. Please round your answer to the lowest integer.

74.4078
Incorrect Response 
See Lesson 5 - The NORM.INV Function


Correct
1 / 1
point
5. Question 5
Continuing with the same distribution, what is the probability that less than or equal to 60 passengers show up? Enter your answer as a decimal probability (not a percent) rounded to 4 decimal places.

0.05480
Correct Response 

Correct
1 / 1
point
6. Question 6
XYZ Company produces copper pipes to be supplied to a local utility company. The requirement of the utility company is that the pipes need to be 200 cm of length. Longer pipes are acceptable to the utility company but any pipe less than 200 cm is summarily rejected and has to be scrapped. The XYZ Company loses all its production cost on pipes that are rejected.

The production process is such that it has some variability in the lengths of pipes produced, and this variability can be well approximated by a Normal distribution. The company can adopt one of the following three production processes:

Process A: Produces pipes with an average length of 200 cm and a standard deviation of 0.5 cm
Process B: Produces pipes with an average length of 201 cm and a standard deviation of 1 cm
Process C: Produces pipes with an average length of 202 cm and a standard deviation of 1.5 cm
If the company adopts the third Process (Process “C”), what is the probability it will have its pipe rejected by the utility company? Enter your answer as a decimal probability (not a percent) rounded to 4 decimal places.

0.0912
Correct Response 

Question 7
Correct
1 / 1
point
7. Question 7
The utility company temporarily changes its requirements and has a new requirement that it will accept any pipe of length from 199 cm till 202 cm. That is, pipes ranging in length from 199 cm to 202 cm will be accepted, others will be rejected.

With this changed requirement which Production process (out of the three) will result in the least % of rejections?


Process A

Correct 

Process B


Process C

Question 8
Correct
1 / 1
point
8. Question 8
XYZ Company earns a revenue of $200 for every pipe that gets accepted and loses all money for any pipe that is rejected. The cost of producing the pipes is $140 per pipe if production process “A” is used, $160 per pipe if production process “B” is used, and $177 per pipe if production process “C” is used.

Given this information, which production process would you recommend to maximize profits (revenue minus cost) if the requirement of the utility company is that pipes need to be of 200 cm (or more) and any pipe less than 200 cm is rejected?


Process A


Process B

Correct 

Process C
