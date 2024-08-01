This code helps you find recently trending products or recently bad performing products.

The code is structured in such a way where it identifies Yesterday's sudden movemnt in comparison with Last x days avg.

Helpful for Fashion, Jewellery, large catalog business where such product movements doesn't show up in any analytics.

How to adjust the code based on your own need?
=============================================

Step 1 >> Fetch X number of days of orders and product sales. Suggested is not more than 60 days.

If your store is fast moving one (daily 500 order) then fetch 7 days order only.

For a slow mover take upto 60 days.

Step 2 >> Change Line 37 number of days based on your comparison need. Example code contains last 3 days data basis product movement.

Step 3 >> Line 37 and Line 56 needs to be changed based on need.

Line 37 is same as above.

Line 56 where I try to identify products where Last x days avg is greater or equals to 2. 

You need to change your numbers after looking at your Product Sales report manually once.
