# pinocchio
Assume that both of the following statements are true:
1. Pinocchio always lies;
2. Pinocchio says, "All my Hats are Green".
We can conclude from these two statements that:
(A) Pinocchio has at least one hat..
(B) Pinocchio has only one green hat.
(C) Pinocchio has no hats.
(D) Pinocchio has at least one green hat.
(E) Pinocchio has no green hats.

I found this question in a YouTube video by MindYourDecisions (https://www.youtube.com/watch?v=YQykZU8mcZY). This question is what got me interested in sentential logic and mathematical proofs. After watching this video, I purchased How to Prove it by Daniel Velleman and worked through the book. This video is likely the reason (or one of many) that I am studying mathematics at the Universty of Waterloo.

Analysis and solution of the problem (Proof by contradiction).
Since ‘all my hats are green’ is a false statement.
Immediately, we can rule out options (B), (D), and (E).

We need to determine from (A) and (C) which option is correct. Let’s consider the possibility where pinocchio has no hats and the parity of the statement. Recognizing the statement follows P implies Q, where the premise is pinocchio has hats, and the conclusion is the hats are green. Looking at the truth table of P implies Q, we recognize when P is false, P implies Q is always true. In other words, a false premise leads to a meaningless truth. This case is called a vacuous truth where the premise is false. Consider the example, ‘all the computers in the room are working’. If there are no computers in the room, then this statement is logically true (although unintuitive at first), but meaningless. Returning to our Pinocchio example, if Pinocchio has no hats, then the statement, ‘All my Hats are Green’ is true. This is a contradiction. Therefore statement (C) is false.

Thus we can conclude statement (A), Pinocchio has at least one hat. 
