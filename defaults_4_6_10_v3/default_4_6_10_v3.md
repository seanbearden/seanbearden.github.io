
# Default Rates for Various Loan Durations V3
### Condensed Version

## Investigation of CFW Data Dumps

We see in Figure 1 that the likelihood a loan is past due decreases as loan duration increases. 
Perhaps, lower payments on a longer schedule are easier for borrowers to make. 
However, the 10-month borrowers in the chosen date interval are not even halfway through their payment schedule. 
In Figure 2, you will notice there are many more loans in the 4 and 6-month buckets.

See Full Page Figure 1 [here](images/duration_weeks_calc_perc_recent_20201208.html)

{% include_relative _images/duration_weeks_calc_perc_recent_20201208.html %}

**Figure 1: We see the likelihood that a loan is past due decreases as scheduled loan duration increases. Loans in the 
0-19 weeks bucket are the only ones to be refinanced at this time. Note, I determined the number of weeks based on the 
payment plan to which the borrower agreed.**

See Full Page Figure 2 [here](images/duration_weeks_calc_freq_recent_20201208.html)

{% include_relative _images/duration_weeks_calc_freq_recent_20201208.html %}

**Figure 2: Looking at the frequency at which loans occur for the three buckets, we see there are significantly less 
loans in the 29-43 week bucket.**

In Figure 3, we have a visualization of how much money was received through payments as a percentage of what CFW 
expected to receive based on the payment schedule of the borrower. 
There is evidence that CFW collects more of what it expects to receive when loans have a longer duration. 
However, there is concern that borrowers who were offered 6-month or 10-month loans are more responsible with their 
debt payments, based on how the borrowers are selected by CFW.

See Full Page Figure 3 [here](images/boxplot_funds_received_20201208.html)

{% include_relative _images/boxplot_funds_received_20201208.html %}

**Figure 3: Box plots for the percentage of payment CFW expected to receive from borrowers by 12/1/20. The boxes 
represent the 25th (bottom line), 50th (internal line), and 75th (top line) percentiles. We observe the 50th 
percentile rises as loan duration increases. The data points are individual borrowers, and more information can be 
accessed in the interactive figure. You may wonder why some borrowers have paid more than 100% of the expected 
amount. There can be various reasons, but most commonly this occurs because the loan has been paid off. (Note, 6 
loans do not appear in this figure due to no payment attempt on file.)**


In Figure 4, we look at the number of payments received if a borrower is considered past due by 12/1/20, regardless 
of their loan duration. As one might expect, the number of loans past due decreases as payments received increases. 
In Figure 5, we take the same data, but break it up into loan duration buckets. Surprisingly, the 10-month loan 
bucket is most likely to have received one payment for a past-due loan.

See Full Page Figure 4 [here](images/total_payments_for_past_due_20201208.html)

{% include_relative _images/total_payments_for_past_due_20201208.html %}

**Figure 4: Past due borrowers are more likely to make less payments, though, we should account for the varying 
payment frequency, ranging from weekly to monthly, before drawing conclusions.**

See Full Page Figure 5 [here](images/total_payments_for_past_due_buckets_20201208.html)

{% include_relative _images/total_payments_for_past_due_buckets_20201208.html %}

**Figure 5: Distribution of payments received per loan duration for past due loans. There is a decrease in past due 
loans as payments increase for 4-month and 6-month loans, similar to Figure 4, but 
the trend is not observed for 10-month loans.**

In Figure 6, we look at the first missed payment for those borrowers who have missed a payment, though, not 
necessarily past due as of 12/1/20. We see borrowers are likely to miss a payment early in the payment schedule. 
However, we should not draw conclusions from this figure, because the loans considered have various payment 
schedule frequencies.
 
See Full Page Figure 6 [here](images/first_missed_payments_20201208.html)

{% include_relative _images/first_missed_payments_20201208.html %}

**Figure 6: We observe the first missed payment of a loan is most likely to occur early in the payment schedule.**


In Figure 7, we look at all missed payments for borrowers who have made at least one payment to their loan by 
12/1/20. 
I have excluded those borrowers who have never made a payment so we can focus on those borrowers who have shown 
some intent to payback their loan. There is a peak of missed payments at the 3rd payments. I am reluctant to draw 
any conclusions from this plot, because the payment schedule frequencies vary from weekly to monthly.

See Full Page Figure 7 [here](images/all_missed_payments_20201208.html)

{% include_relative _images/all_missed_payments_20201208.html %}

**Figure 7: We observe that a borrow is most likely to miss their third payment, assuming the make a payment at all. 
Again, we should account for varying payment schedule frequency before drawing conclusions from this figure.**

