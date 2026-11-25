# CS50 Plurality
A command-line election program written in the C programming language that simulates a plurality voting system, where the candidate receiving the most votes wins.

## Features:
- Candidate Management: Stores candidate names and vote counts using a custom `candidate` structure.
- Candidate Limit: Supports up to nine candidates using the predefined `MAX` constant.
- Vote Collection: Prompts voters to cast their votes for a candidate.
- Vote Validation: Uses the `vote()` function and `strcmp()` to check whether a submitted vote matches a registered candidate.
- Vote Counting: Automatically increments the corresponding candidate's vote count.
- Winner Detection: Identifies the highest vote count using iteration and comparison.
- Tie Handling: Supports multiple winners when candidates receive equal numbers of votes.

#

Developed as apart of the curriculum for [Harvard University's CS50X: Introduction to Computer Science](https://cs50.harvard.edu/x/2025/psets/3/plurality/)
