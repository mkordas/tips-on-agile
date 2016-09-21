# The Penny Game

Small activity illustrating pros and cons of working in iterations.

![](http://3.bp.blogspot.com/_nzj0JxErQqA/SRE2d1wQ-OI/AAAAAAAAALw/62B-OAbhJ4Q/s400/ScrumPennyBatchGame.png)

### Setup

- 20 pennies
- customer
- boss
- `N` departments of 2 people
- `N+2` stopwatches (one per department, one for customer and one for boss)

### Roles

1. Customer:
 - sends the batch of coins to the workers
 - accepts (by touching) received coins from the last worker
 - measures time between start and first coin accepted
2. Boss: 
 - measures the time elapsed time between between sending out the first coin
 and all coins accepted
3. Workers:
 - one per department
 - each worker receives a batch of coins, flips them using one hand
 and moves the bath to the next worker
4. Efficiency experts: 
 - one per department
 - measure the time "their" worker spends flipping coins
 
### Iteration

1. Each worker flips all pennies using one hand and when done passes to the
next worker
2. Exactly the same as first
3. Pass every 10 pennies
4. Pass every 5 pennies
5. Pass every one penny
6. Repeat previous
