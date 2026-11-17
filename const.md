## State:
#### Imposed human workload through N-back test.
- 0 back = low workload
- 1 back = medium workload
- 2 back = high workload
#### Berth Conditions
- Berth is unblocked
- Berth is blocked
#### Situational Awareness of the human
- Determined through the correct/incorrect answers the user gives to the question of "what berth the Astro Bee should place the container", if the human chose a blocked berth, then it was incorrect. If the human chose the open berth, then it was correct.
    - If the correct berth is chosen, then the human's situational awareness is sufficient. On the other hand, choosing the incorrect berth will show situational awareness is being affected.
        - Consistently answering incorrect shows poor situational awareness.
        - Consistently correct shows good situational awareness.
- There will always be a blocked berth and an open berth, it is the human's choice to determine where to put the container the Astro Bee is holding.
## Action:
#### Physical action:
- Placing the container in the designated berth
#### Communication action:
- Telling the human what berth is blocked.
- Communicate this to this user by:
    - Staying silent and doing it yourself
    - Asking a Yes/No question
    - Asking a Wh type question
## Transition:
## Reward:
$$
\begin{bmatrix}
Action & Correct & Incorrect \\
Silence & 10 & -100 \\
Yes/No Question & 9 & -101 \\
Wh-Question & 8 & -102
\end{bmatrix}
$$
## Observation:
## Belief Update:
## Repeat

