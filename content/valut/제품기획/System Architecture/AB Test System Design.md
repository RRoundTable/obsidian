https://medium.com/problem-solving-blog/a-b-testing-what-is-the-solution-for-your-web-and-mobile-apps-part-1-68faf132fceb

## Definition
 “A/B testing is a way to compare two versions of a single variable, typically by testing a subject’s response to variant A against variant B, and determining which of the two variants is more effective.”

![[Pasted image 20231026234740.png]]

![[Pasted image 20231026234829.png]]
## Data Engineering
refactoring the data source to determine the audience of interest, then divided it into the A-set and the B-set. The result of this process can be one of those two:

- Mark a selection for A/B and NOT(A/B), visible to the client-side.
- A list of A/B or NOT(A/B) users to be referred by a routing service.

## Software Engineering
develop new features for A-set and B-set. The previous version will become the feature NOT(A/B-set). The result of this process will be:

## System Engineering
network wiring the audience set of A/B or NOT(A/B) to the corresponding feature A/B or NOT(A/B). The result of this process will be:


## How to
![[Pasted image 20231026235603.png]]
![[Pasted image 20231026235611.png]]