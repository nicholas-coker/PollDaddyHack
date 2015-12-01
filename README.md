#PollDaddy Hack

This is pretty easy to use.  Just download the Python script, and customize the variables for what form/answer/number of votes.  

It needs Python 2.7.6.

### Example
You want to rig this poll: https://polldaddy.com/poll/9206448/ for the answer "It's a great way to keep kids in line during a crazy time of year.", and you want to vote 1000 times.  The poll_id comes from the url: https://polldaddy.com/poll/*9206448*/.  The answer_id comes from the looking at the source code for the associated checkbox: <input type="radio" name="PDI_answer" id="PDI_answer41930288" value="*41930288*">.


Thus, you would want the variables to be set to:
```
poll_id = 9206448
answer_id = 41930288
number_of_votes = 1000
```