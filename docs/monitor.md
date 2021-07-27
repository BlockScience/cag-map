# Monitor

![](https://i.imgur.com/iYqVRRM.png)

[Science](https://en.wikipedia.org/wiki/Science) wouldn't work if we ran experiments but didn't bother to record the results. Same goes for governance. There needs to be a [feedback loop](https://en.wikipedia.org/wiki/Feedback) between decisions and results. Monitoring allows you to verify the results of decisions to see if they had their intended effects.

If a proposal succeeds you'll want to see if it actually has the effect you intended. If so, then great. If not, then figure out why.

If a proposal doesn't succeed that's OK too. If you had a hypothesis of what will happen if your proposal does not pass then you can validate that. This can provide data to support your original proposal, potentially allowing you to resubmit a modified version with more evidence (*"I told you so!"*).

Monitoring complex systems is a lot of work, but there's tools that can help. You'll probably want to automate things like feeding raw data into recurring model runs and alerts based on key metrics - and you'll probably want to manually read community discussions to understand context and sentiment. Analysis of both objective data and subjective social activity are important to understand the global view of a system. One without the other is likely to lead to a [local optimum](https://en.wikipedia.org/wiki/Local_optimum).

## Concepts

### Success

If the proposal passes monitor the relevant metrics to ensure it behaves as expected. If not, suggest ways to adjust accordingly.

### Iteration

If the proposal does not pass still monitor the relevant metrics to see if your prediction holds (then you can say "I told you so" and/or give your proposal another go if it's still relevant).

## Tools

### Automated Alerts

If possible setup automated alerts for activity that matters in the context of a proposal. This way you can know if expected milestones/thresholds/etc were reached and/or what performance looks like.

### Recurring Runs

If you can get a raw data-feed from the system, you might be able to pipe that into your model and setup recurring runs. This would regularly pull new data into the model and run it to see if anything changed. This can provide more detailed insights than simple metrics. You'll also be able to modify the model to explore potential future scenarios based on new updates.

### Manual

Not all data is packaged in a convenient numerical format. Sometimes you need to also review human readable proposals and/or gauge sentiment on community forums and chats. This can sometimes provide insight related to the satisfaction and/or desires of stakeholders. This is important because governance proposals determine how resources are distributed between stakeholders so even if the results are technically what was expected, if stakeholders are unhappy then it's important to understand why and take that into consideration. 

## Notes

```
MOTIVATION
- feedback

CONCEPTS
- success
- failure

TOOLS
- automated alerts
- recurring runs
- manual review
```
