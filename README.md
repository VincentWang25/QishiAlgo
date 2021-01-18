# QiShiAlgo

## Week1_Recursion

1. https://leetcode.com/problems/merge-two-sorted-lists/
2. https://leetcode.com/problems/validate-binary-search-tree/
3. https://leetcode.com/problems/partition-to-k-equal-sum-subsets/
4. https://leetcode.com/problems/k-th-symbol-in-grammar/

## Week2_DP

1. https://leetcode.com/problems/maximum-product-subarray/
2. https://leetcode.com/problems/longest-increasing-subsequence/
3. https://leetcode.com/problems/partition-equal-subset-sum/
4. K-Eggs Problem
    - We want to use k eggs to find out the highest floor from which an egg will not break when dropped from that floor. If an egg is dropped and does not break, it can be dropped again. An interesting thing to consider is a minimax problem: The best (mini) number of drops in the worst case (max) scenario to determine the "breakeven" floor. Find that number.
    - Hint: What's the minimax value if we only have 1 egg? For the other extreme, infinite number of eggs? How about 2 (=1+1) eggs? 3 (=2+1) eggs?
5. Dynamic Card Game
    -  A casino offers a card game with 26 red and 26 black cards. The cards are shuffled and the dealer draws cards one by one (without putting back). You can ask the dealer to stop at any time you like. Upon stopping, you win $1 for each red card drawn, and lose \$1 for each black card. What is the optimal stopping policy to maximize expected payoff and how much you are willing to pay for this game?
    - Hint: Let the system state be (b,r): the number of black and red cards still left in the deck. The (conditional) action space is really just {continue, stop} (at b, r).
    - What's the expected payoff E[f(b,r)]?