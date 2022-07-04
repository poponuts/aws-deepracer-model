# AWS Deep racer model

This is the reward function for my AWS Deep racer model which completed 34 seconds on the simulation race and completed 11 seconds on the actual physical race using the _re:Invent 2018_ track. It finished 1st place on our company's event.

## Specs
| Hyperparameters | Values |
|---|---|
| Gradient descent batch size	| 64 |
| Entropy	| 0.01 |
| Discount factor	| 0.88 |
| Loss type	| Huber |
| Learning rate	| 0.0003 |
| Number of experience episodes between each policy-updating iteration	| 18 |
| Number of epochs	| 4 |

| Training Time |
|---|
| 100 minutes |

| Input Space |
|---|
| [1.1, 2] m/s |
| [-30, 30] degrees |

## How I did it?
https://dev.to/poponuts/how-my-aws-deep-racer-model-finished-best-in-11-seconds-5dg3