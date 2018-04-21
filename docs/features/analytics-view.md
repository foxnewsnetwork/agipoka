# Analytics View

This is where we show graphs and charts that attempt give details regarding the status of a team's coherence, fragility, and predictability.

We should show the following metrics:

- coherence: how close together the teams are on pointing. This is important because it's correlated with how well the team shares knowledge or how badly each member is specialized. The higher the coherence, the more the teams agree (up to a maximum of 100%). Management should try to increase this number by advocating education
- bounce: the ratio of unpointable tickets to pointable ones, the higher this number, the more business / product (e.g. the "stakeholders") have no idea what the technical engineering staff are doing, and the more brittle the entire company is.
- tag cloud landscape: this is a series of graphs displaying each tag clouds versus their scoville points, versus their hours-to-completion, etc., This shows to the team what segment of the business takes the most amount of effort
- scoville / implmentation-time versus time: the ratio of scoville to implementation-time *should* be a constant value across time. However, in a fragile code-base / company, this value goes down, in a robust one it stays constant, and in an antifragile volaphilic one, it actually goes down (somehow)
- difficulty: a measure of experience (how frequently someone engages in an area of code) over either scovilles or implementation time. The more difficult a codebase, the more experience it takes a developer to become useful