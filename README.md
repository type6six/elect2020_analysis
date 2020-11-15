# elect2020_analysis

The data is obtained from thedonald.win website: https://thedonald.win/p/11Q8O2wesk/happening-calling-every-pede-to-/

The `json` files are election data feeds obtained from the NYT. Each time entry provides:

1. Total Vote Count
2. percent share of each candiate (only 3 digits of precision)

To compute each candidate's vote count, you multiply the total vote count with the percentage share.

Since the percentage share has only 3 digit, (i.e., 0.001) for one million votes counted, you can only determine the candidate's vote count to the 1000's, no more precise than that.

Claims of Trump votes switched to Biden can be determined by looking at each update:

For example, when a new update occurs, we can calculate the number of ADDITIONAL votes casted. Then we can see if the percentage share makes sense. For example, if an update shows 1000 votes added to 1 million, then assuming all 1000 votes goes to Biden (which is really impossible) then the worst trump's vote percentage share should goes down by 0.1% but no more. But you will see that there are plenty of cases where trump's vote share percentage goes down far more than the new votes added (assuming again they all go to Biden)

We captured the time stamps of updates where: (a) trumps loses more votes and should and (b) biden's seems to get more than 95% of all ADDITIONAL votes. see the (.txt) files.

We visualize it in a movie also for the four most important states: wisconsin, pennsylvania, georgia, and michigan.
