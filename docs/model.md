# Model

![](img/cag-map-0.0.3-model.png)

> Picture of the Model section (with pictures and colors) goes here. This can prime the reader for the next section and might also help to break up an otherwise monotonous wall of text.

## Overview

[Models](https://en.wikipedia.org/wiki/Model) allow you to define your ideas and test them in hypothetical environments. They're like thought experiments, but with code. Something in between a white paper and a working implementation. This is great if you want to test an idea before building it, or want to test variations on an idea to see which might be the best.

## Concepts

### Legibility

A model is a living document. It conveys information, but you can also modify and interact with it to learn new information. As such, the results of your model are only a small part of it's value. More important is people's ability to go through your model to understand how it works, and to also modify it to explore other parameters and assumptions. For this to be possible it's important that your model is legible. This means that code is organized neatly and commented where appropriate. Check out the [insert python/cadCAD code syntax and best practices guide here] to see some examples.

> Is your model structured so that it's easy to interact with?
> Could people easily modify it to test your assumptions and their own?

### Assumptions

Most models depend on external factors to be true. At the same time modeling every detail would be exhausting. The model is a representation of a thing, not the thing itself. Just like with a map, it's important to specify what you included, what you left out, and why. It's also important to specify what you're assuming to be true and/or external states/environments that you assume the model is operating within.

> Make assumptions explicit.
> What does your model assume or require to be true?

### Specificity

What is the focus/purpose of the model?

The opposite of assumptions: what did you choose to be specific about?

Is your model specific enough that it defines the problem and the potential solution?

### A/B Testing

[A/B testing](https://en.wikipedia.org/wiki/A/B_testing) allows you to test multiple variations of a thing.

A then B != A/B 
- statefulness and ordering is important
- A then B is different than A/B testing

### Data generation

Generating new data (which you might not have IRL) allows you to test alternate scenarios and explore the state space more than what would be possible with historical data. 

If your assumptions are made explicit then you can also test your model in different contexts. That way you can have a better idea of under what macro conditions your assumptions might hold.

### Reflexivity

Explain dangers of reflexivity

Are there any portions of your model that are self referential?

## Tools

### cadCAD

[cadCAD](https://cadcad.org/) is an open-source Python package that assists in the processes of designing, testing and validating complex systems through simulation. Download it, check out demos, and fork snippets into your own models from the [cadCAD repos](https://github.com/cadCAD-org).

### Labs

> Is there public data/tooling available for BlockScience Labs yet?

### tokenSPICE

[Token](https://en.wikipedia.org/wiki/Token) - A thing that represents a thing.

[SPICE](https://en.wikipedia.org/wiki/SPICE) - "Simulation Program with Integrated Circuit Emphasis"

Ocean Protocol has created tokenSpice to model their token system dynamics. It's agent based and V2 even has EVM integration with Ganache. Check out the code and fork it for your experiments here:

- [tokenSPICE V1](https://github.com/oceanprotocol/tokenspice)
- [tokenSPICE V2](https://github.com/oceanprotocol/tokenspice2)

