

  ______          ___             __   _______ __          _______ __                  
 |   _  \ .-----.'  _.-----.---.-|  |_|       |  |--.-----|   _   |  .-----.-----.----.
 |.  |   \|  -__|   _|  -__|  _  |   _|.|   | |     |  -__|.  1___|  |  _  |  _  |   _|
 |.  |    |_____|__| |_____|___._|____`-|.  |-|__|__|_____|.  __) |__|_____|_____|__|  
 |:  1    /                             |:  |             |:  |                        
 |::.. . /                              |::.|             |::.|                        
 `------'                               `---'             `---'                        
                                                                                       

What i have in mind is a game bot
How to play:
The user has 100eth(Balance) at the start of the session and he can invest on different nft projects buying pieces at floor price.This game will be weekly 
playable, so it must have a cooldown of 7 days.

##### FIRST WEEK #####

- The user starts searching in menu the different name of the collection he wants to buy, then he has to add the number of pieces of that NFT that he wants 
  to add in his list. (Max 5 per collection);
- When he will confirm the number of items the bot will do Balance - items * floorprice (at that moment);
- When the user will reach the 100eth balance the bot cannot accept more items in the list and will ask him to confirm his list of NFTs. # If the balance at 
  the end of the NFTs selection is less than 100eth , for example 98eth the 2eth difference will be stored in the player bank (he will be able to use the that 
  amount ot eth in the next week).


##### SECOND WEEK #####

After the 7 days cooldown the user will ask the bot to do again the math of the value of his NFTs that he selected the week before this time the bot will use 
the current floor price of the NFTs. After the calculation the bot will subtract the current value of the NFTs with the old value of the NFTs, so for example
if the price of the NFTs in the second week will be lower than before (ex 60eth) the bot will give the user the loss result (40eth). 
Now we will start again with the game as we did in week one by selecting the NFTs that we want to put in our list, but this time the budget will be 60eth , 
because is the amount of eth that we have left after the calculation we did before.

The game will continue like that for one month , after that the bot will give the final result and the player will see how much he lost or gain with the NFT 
trading in the last month. 

The bot must be usable in a big discord server so he must be able to accept multiple requests at the same time. 

Bonus features: 
-weekly leaderboard of the all the players in the server. Final leaderboard of the month with best trader of the month.  
