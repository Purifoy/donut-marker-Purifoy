# Army Donut Maker App

![Screenshot (192)](https://github.com/Purifoy/donut-marker-Purifoy/assets/24870574/754ef656-05ae-408d-9875-afc8bb5087be)



## The Application Requirements
You must create a website that uses button clicks to create donuts. The donuts can be used as currency to buy Auto Clickers and Donut Multipliers, which will be used to make even more donuts!
Project Describtion 
Terminology
Donut Count
The number of Donuts you have created by clicking, either manually or with an Auto Clicker.

Auto Clicker
Auto Clickers will automatically click for us every second, so we don't have to click manually.

Auto Clicker Count
The number of Auto Clickers purchased. Auto Clickers apply one click per second for every Auto Clicker purchased.

Number of Auto Clickers Purchased

Clicks applied per second

1

1

2

2

3

3



...you get the picture

Auto Clicker Cost
The number of donuts required to purchase an Auto Clicker. Starting cost is 100 donuts. For each Auto Clicker purchased, the cost of the next Auto Clicker increases by 10%.

Next Auto Clicker Purchase

Cost

1

100 donuts

2

110 donuts

3

121 donuts

4

133 donuts

Donut Multiplier
Donut Multipliers increase the number of Donuts made for each click.

Donut Multiplier Count
The amount of Donut Multipliers purchased. Donut Multipliers increase the value of a click by 20% for each Donut Multiplier purchased. Donut Multipliers increase the value of both manual and Auto Clicks.

Donut Multipliers Purchased

Donuts Earned per Click

1

1.2

2

1.44

3

1.728

4

2.0736



NOTE: The number of Donuts earned per click can be calculated with the following equation:

1.2 to the xth power, where x is the number of Donut Multipliers
or written in JS syntax as Math.pow(1.2, DonutMultiplierCount)
Donut Multiplier Cost
The number of donuts required to purchase a Donut Multiplier. Starting value is 10 donuts. For each Donut Multiplier purchased, the cost of the next Donut Multiplier increases by 10%.

Next Donut Multiplier Purchase

Cost

1

10 donuts

2

11 donuts

3

12.1 donuts

4

13.31 donuts


## **Technologies used** 

Javascript
HTML
CSS


