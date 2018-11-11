# Double Shutter Simulation

![](https://images-na.ssl-images-amazon.com/images/I/71bAiqICt3L._SY450_.jpg) 

## Rules of the Game

Double Shutter is one of those games that has a simple mechanism and complicated strategy. There are two rows of tiles, both 1-9, and two six-sided die. The rules are simple: roll the dice, shut tiles that add up to the dice total, and repeat until you get a dice roll you can't match with tiles (You Lose) or you shut all of the tiles (You Win!). Shutting the front row reveals the back row, but you can't use the back row tiles until its respective front row tile has been shut.

A player's score is the sum of all remaining tiles (even one in the back row that are obscured), with any remaining front row tiles being doubled. 

## The Simulation
This seemed like the perfect game to simulate - it's simple and self-contained enough to replicate with code, yet difficult to determine the best strategy without many, many rounds of play. So that's what I did! 

I started with two strategies: Most Tiles and Largest Tile. I know Most Tiles was doomed, but I wanted to see how much worse it would be that the other strategies. I thought Largest Tile might be the winning algorithm, and it performs pretty well.  