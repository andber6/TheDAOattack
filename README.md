# TheDAOattack
Exploiting the DAO attack on the ethereum blockchain

The error lays in the payout function being called in the withdrawCoins function where I loop over it over and over through recursion before it setting my balance to 0.
This results in me withdrawing (in this case) 20 times the amount I was supposed to.
