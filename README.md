# Best_time_to_sell_stock
You are given an array prices where prices[i] is the price of a given stock on the ith day.  You want to maximize your profit by choosing a single day to buy one stock and choosing a different day in the future to sell that stock.  Return the maximum profit you can achieve from this transaction. If you cannot achieve any profit, return 0

1.  We can not find the Maximum and Minimum value and then subtract to get profit.
2.  Because we can only sell stock after one day of buying it.
3. Maximum value can be the first element, so that way is not possible.

4. We need to iterate through the different elements to get the max profit
