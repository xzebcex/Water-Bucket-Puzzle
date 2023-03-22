# **Water Bucket Puzzle**

## Description
This application mimics the famous game of "Water Bucket Puzzle," which requires players to measure a given amount of water using three buckets of varied capacities (8L, 5L, and 3L) (4L). The player has the ability to pour water from one bucket into another as well as fill and empty buckets. When the player successfully uses the available buckets to measure the desired amount of water, the game is over.

## How to Play
The state of the buckets and the amount of water within each one are displayed when the code is run. The next step is for the player to decide what to do with a bucket in the following way: 
1.	(F) --> fill the bucket
2.	(E) --> empty the bucket
3.	(P) --> pouring from one bucket into another
4.	(Q) --> quit
When the program is executed, the current condition of the buckets is displayed, along with the amount of water in each bucket. The player must then choose an action to carry out on a bucket: If the player chooses (F) or (E), they will be asked to choose a bucket (8, 5, or 3) on which to conduct the action. If the player chooses (P), they will be requested to choose a source bucket and a destination bucket into which to pour water.
Based on the player's activity, the application will then update the status of the buckets and show the new state. The game runs until the player measures 4L of water successfully or decides to stop.

## Code Explanation
The amount of water in each bucket is kept in the program's water in bucket dictionary. The program also utilizes a variable steps to record how many steps the player has made to complete the problem and a constant GOAL to indicate the desired amount of water to measure.
The code then enters a loop in which it shows the current status of the buckets and prompts the player to choose an action to execute on one of them. The cycle continues until the player either measures the desired amount of water or chooses to exit the game.
The program uses a sequence of if statements within the loop to identify which action the player has chosen and updates the state of the buckets appropriately. The software additionally used nested loops to evaluate the player's input for picking a bucket to conduct an action on and a destination bucket into which to pour water.
After the player correctly measures the desired amount of water, the software leaves the loop and shows a message showing the number of steps taken to complete the problem. If the player decides to abandon the game, the software exits the loop and displays a good-by message.
