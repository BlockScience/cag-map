# Monitor

![](img/cag-map-0.0.3-monitor.png)

> Picture of the Monitor section (with pictures and colors) goes here. This can prime the reader for the next section and might also help to break up an otherwise monotonous wall of text.

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

## Overview

[Science](https://en.wikipedia.org/wiki/Science) wouldn't work if we ran experiments but didn't bother to record the results. Same goes for governance. There needs to be a [feedback loop](https://en.wikipedia.org/wiki/Feedback) between decisions and results. Monitoring allows you to verify the results of decisions to see if they had their intended effects.

If a proposal succeeds you'll want to see if it actually has the effect you intended. If so, then great. If not, then you're back to the ask stage to understand why it's not having the effect you intended. If a proposal doesn't succeed that's OK too. If you have a hypothesis of what will happen if the problem is not solved then you can validate that as well. This can provide more data to support your original proposal, potentially allowing you to resubmit a modified version with more evidence to back it up.

There are a few tools that can help with this process. You'll want to automate some things like alters and recurring model runs, but others will be more manual like engaging with the community to understand sentiment. Both are important to provide context for your next questions and proposals.

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

