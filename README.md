# red-pencil-sale-kata
Red Pencil Sale Kata without TDD

Adapted From: https://github.com/ardalis/kata-catalog/blob/master/katas/Red%20Pencil%20Sale.md
Original Version by Stefan Roock: https://stefanroock.wordpress.com/2011/03/04/red-pencil-code-kata/

Instructions
The scope of this kata is the implementation of the rules for activating and deactivating red pencil promotions. Write your code to ensure the following:

A red pencil promotion starts due to a price reduction. However, the red pencil promotion is only applied if the price was reduced by at least 5% and at most 30%. Also, the previous price must have been stable (unchanged) for at least 30 days.
A red pencil promotion lasts at most 30 days.
If the price of an item is further reduced during the red pencil promotion, the promotion will not be prolonged by that reduction.
If the price of an item is increased during the red pencil promotion, the promotion ends immediately.
If the price is reduced during the red pencil promotion so that the overall reduction is more than 30% with regard to the original price, the promotion ends immediately.
After a red pencil promotion has ended, additional red pencil promotions may follow. However, the start condition remains: the price must have been stable for 30 days (and these 30 days cannot intersect with a previous red pencil promotion).
