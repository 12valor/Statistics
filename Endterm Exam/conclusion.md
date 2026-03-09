# Website Bounce Rate Analysis - Conclusion

Hey! For this exam, I wanted to figure out if our website's average Bounce Rate is actually different from the industry standard of 0.50.

To start things off, I cleaned up the data by kicking out some extreme outliers (using a z-score cutoff of 3). Since we had a ton of rows, I used the Central Limit Theorem (CLT) to grab 100 sample means and normalize everything before testing.

Here are the results from the **1-Sample T-Test**:

- **The Standard We Tested Against:** 0.50
- **Our Actual Sample Mean:** ~0.278
- **T-Statistic:** -85.5268
- **P-Value:** 0.0000

### What does this actually mean?

Because our p-value (0.0000) is way below our 0.05 limit, we **reject the null hypothesis**.

Basically, the website's average Bounce Rate is definitely _not_ 0.50. In fact, it's way lower (around 0.278), which is super good news for the site!

To double check if this difference actually matters, I looked at the effect size (**Cohen's d = 8.55**), which is absolutely massive. It proves the drop in bounce rate is huge, not just barely noticeable. Also, our **Power of the Test was 100%**, so we can be fully confident that we didn't just get a false positive.

**TL;DR:** The site is doing great, and its bounce rate is significantly lower than the 0.50 standard!
