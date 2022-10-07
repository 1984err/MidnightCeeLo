# MidnightCeeLo 
A famous dice game recreated in python.
Author: Valentin Cain
Version: V1.0
Creation Date: 2018


 In this version of Cee-lo, each round involves 3 players. A bet of $100 is automatically put into the pot from 
each player at the beginning of the round. Each player then will roll all three dice at once and must continue until a 
recognized combination is rolled or they have rolled 3 times. If the player has not rolled a recognized combination after 3 rolls, they will receive a 0 for the round. Whichever player rolls the best combination wins the entire pot, and a
new round begins. In cases where two or more players tie for the best combination, the pot will be split
accordingly. The combinations are and can be ranked from best to worst as: 4-5-6:
The highest possible roll. If you roll 4-5-6, you win the pot and receive a bonus $100 from each player.
Trips: Rolling three of the same number is known as rolling "trips". Higher trips\n beat lower trips, so 4-4-4 
is better than 3-3-3. Any trips beats any established point.Point: Rolling a pair, and another number, establishes the singleton as a "point". A higher point beats a lower point, so 2-2-6 (6) is better than 5-5-2 (2). 1-2-3: The lowest possible roll. If you roll 1-2-3, you must pay both players $100 at the end of the round. Any other roll is a meaningless combination and the player can re-roll until one of the above combinations occurs or 3 attempts have been made.
