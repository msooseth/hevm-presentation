## Intros (remember you can do a quick demo [< 3 mins])
* hevm is a concrete and symbolic execution engine for EVM bytecode
* it can be used both like geth, executing transactions, but it can
  also be used to declare one of the inputs as a variable, and
  compute all possible execution paths.
* This can help verify correctness of smart contracts, automatically generate
  test cases, use the system as a fuzzer (as in Echidna), and many more

## How did your project come about?
* Came about as a way to verify the UniSwapv1 and v2 contract. At the time,
  there were very few tools available that could do this kind of work.
* So it started around 7-8 years ago -- a long history with many contributors

## What part of the Ethereum stack is your project building?
* It is the trust layer that permeates the entire Ethereum ecosystem.
* Used to verify the correctness of contracts
* Can also be used to improve gas performance of contracts
* Can be used to verify correctness of compiler improvements (such as new
    simplification rules)

## What’s the future you envision for Ethereum, related to your project?
* I hope that more systems can migrate to Ethereum. To do that, we must solve
  the trust issue. Currently, many systems are not migrating because they
  see it too risky relative to to (large) advantages.
* Basically, I want to help grow the pie, and to do that, we need
  tools that make the Ethereum space more trustworthy

## What’s the most exciting breakthrough you’ve built with your project?
* The most exiting development has been that our downstream project,
  Echidna, started using our symbolic execution engine. This means that
  important other projects are now taking advantage of our work.
* We have made a lot of improvements to the tool such that its' a lot more
  user-friendly and contracts that we could not imagine verifying before
  can now be verified

## What makes you excited about the (near) future of the project? Any particular features you’d like to share?
* We are about to release a new version that should be significantly
  easier to use and much more powerful. So I'm curious what the
  community will say.
* I am also very excited for the future of Echidna, which is
  a fuzzer that uses hevm as its backend. I hope people will
  see the benefit of symbolic execution as part of their fuzzing
  runs and will be more curious about hevm.


