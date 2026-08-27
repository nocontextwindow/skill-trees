# Reinforcement Learning

[← Machine Learning / AI](../index.md) · `ML_RL`

Learning to act from interaction and reward rather than from labeled
examples. The formal problems — credit assignment over time, the
exploration/exploitation tradeoff, sample efficiency — are well posed and
much studied. The problem that actually sinks projects is upstream of
all of them: specifying a reward that means what you intended. Most
famous RL results depend on a simulator cheap enough to burn millions of
samples in, which is exactly what the real settings people want to apply
this to do not have.

## Open questions

- Reward specification causes most real failures — is there any
  principled method for writing one, or is it always iterative patching?
- How much of RL's success is the algorithm and how much is having a
  simulator good enough to waste samples in?
- Is offline RL a genuine answer to sample cost, or does distribution
  shift simply reappear in another form?
- What does exploration mean in a setting where an unsafe action can't be
  tried even once?
- Where does the MDP framing misdescribe a problem — non-stationarity,
  partial observability, other agents adapting to you?
- When reward is learned from human feedback, what exactly is being
  optimized — the preference, or the rater's ability to notice?

## Notes

## Resources
