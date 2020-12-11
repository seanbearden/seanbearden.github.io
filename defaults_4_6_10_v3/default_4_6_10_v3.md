
# Default Rates for Various Loan Durations V3
### Condensed Version

## Investigation of CFW Data Dumps

We see in Figure 1 that the likelihood a loan is past due decreases as loan duration increases. 
Perhaps, lower payments on a longer schedule are easier for borrowers to make. 
However, the 10-month borrowers in the chosen date interval are not even halfway through their payment schedule. 
In Figure 2, you will notice there are many more loans in the 4 and 6-month buckets.

In Figure 3, we have a visualization of how much money was received through payments as a percentage of what CFW 
expected to receive based on the payment schedule of the borrower. 
There is evidence that CFW collects more of what it expects to receive when loans have a longer duration. 
However, there is concern that borrowers who were offered 6-month or 10-month loans are more responsible with their 
debt payments, based on how the borrowers are selected by CFW.

{% include_relative _images/boxplot_funds_received_20201208.html %}

In Figure 4, we look at the number of payments received if a borrower is considered past due by 12/1/20, regardless 
of their loan duration. As one might expect, the number of loans past due decreases as payments received increases. 
In Figure 5, we take the same data, but break it up into loan duration buckets. Surprisingly, the 10-month loan 
bucket is most likely to have received one payment for a past-due loan.

In Figure 6, we look at the first missed payment for those borrowers who have missed a payment, though, not 
necessarily past due as of 12/1/20. We see borrowers are likely to miss a payment early in the payment schedule. 
However, we should not draw conclusions from this figure, because the loans considered have various payment 
schedule frequencies.
 
In Figure 7, we look at all missed payments for borrowers who have made at least one payment to their loan by 
12/1/20. 
I have excluded those borrowers who have never made a payment so we can focus on those borrowers who have shown 
some intent to payback their loan. There is a peak of missed payments at the 3rd payments. I am reluctant to draw 
any conclusions from this plot, because the payment schedule frequencies vary from weekly to monthly.






See Figure 1 [here](images/duration_weeks_calc_perc_recent_20201208.html)

See Figure 2 [here](images/duration_weeks_calc_freq_recent_20201208.html)

See Figure 3 [here](images/boxplot_funds_received_20201208.html)

