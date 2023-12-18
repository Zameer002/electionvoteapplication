# electionvoteapplication

In the electionvoteapplication project, as per given requiremenets i have created the total of 5 api's, below is the detail explanation of api's

Note : I have used port no as 9080

1. http://localhost:9080/entercandidate --> This Api will be used to create a candidate,it checks whether the provided candidate name is unique or already exits,if exits, it doesnt allow to create the candidate.

2. http://localhost:9080/castvote -->  This Api will be used to caste vote to the already created candidate/user, if provided candidate name is not exits / not already created,then it indends to create a new candidate.

3. http://localhost:9080/countvote --> This Api will be used to get the vote count of a specific candidate.

4. http://localhost:9080/listvote --> This Api will be used to get all the candidates deytails.

5. http://localhost:9080/getwinner --> This Api will be used ti get the candidate with max number of and will announce the user and if the multiple users share the same votes then it gives the details of candidates with same votes.
