# Lottery

**Specifics:**

* Lottery Ticket Fee for 1 ticket: 1 VISION
* Single User Lottery Entry Limit: No overall limit, but only 50 can be bought at one time through the UI
* Paying for one ticket will give users a random 4 digit combination with each digit being between 1-9, for e.g. “1-3-6-9”

\*\*\*\*

**How to win:**

To win the lottery jackpot \(75% of the entire lottery pool\), users need to match all 4 numbers on their tickets in the same position as the 4 winning numbers.

If you don’t match all 4, no need to worry. As long as you match 2 or more numbers in the correct position, you are guaranteed to win a reward.

**Winning Ratio:**

* Match all 4 numbers in the exact order = win 75% of the pot \(or split the pot if more than 1 winner\). 
* Match 3 numbers in the exact order = win or split 19% of the pot.
* Match 2 numbers in the exact order = win or split 4% of the pot.
* Burn the remaining 2% of the pot.

Please note - in the event that no participants were able to match 3 numbers on any draw, the 19% allocated to winners will then be burned accordingly.

For example, if the final 4 winning numbers are “1-9-3-2”:

* “2-3-9-1” = match 0
* **“1-9-3-2” = match all 4**
* “1-9-2-2” = match 3
* “2-3-3-2” = match 2

**Lottery phases:**

Each full lottery session is completed every 12 hours \(2 per day\), with the timings for each as below:

4 AM - 4 PM \(UTC\)

4 PM - 4 AM \(UTC\)

An example of a lottery session starting at 4 AM is below:

**Phase 1 - Buy Tickets \(4 AM to 3 PM\)**

* You have 11 hours to buy tickets. 
* The lottery jackpot will accumulate at the top of the page with each ticket bought.
* Users will receive a ticket \(comprised of 4 digits\) for each 1 VISION paid.

**Phase 2 - Lottery Draw! \(3 PM\)**

* The 4 winning lottery numbers are drawn and will appear on the page. 
* Each participant’s winnings will be automatically calculated based on their ticket numbers and shown on the page.
* Users can claim winnings if they have any.
* Users will also be able to see the lottery results: How many users matched all 4 numbers, 3 numbers and 2 numbers. 

**Phase 3 - Celebration and Sharing \(3 PM - 4 PM\)**

If you won, congrats! Share with your friends or in our community groups.

The next lottery starts in 1 hour!

**How are ticket numbers drawn?**

The lottery aims to be completely random. Even though the ticket numbers given out are determined by a front-end logic, there is an extremely low chance that anyone is able to determine the 4 winning numbers ahead of time.

* The 1st lottery number will be determined based on the %10 remainder of a hash encoded by the blockhash and the number of participating users at the entry deadline.
* The 2nd lottery number will be determined based on the %10 remainder of a hash encoded by the blockhash and the total pooled cake balance at the entry deadline.
* The 3rd lottery number will be determined based on the %10 remainder of a hash encoded by the blockhash and the timestamp of the last lottery participant at the entry deadline.
* The 4th lottery number will be determined based on the %10 remainder of a hash encoded by the blockhash and the block difficulty at the entry deadline.

