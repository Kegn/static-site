---
title: "Finding Expensive Assumptions"
author: Kegan
date: 2026-08-12
---

# Finding Expensive Assumptions

Your organization has thousands of security assumptions, and most of them are not worth your time.

## One Sentence of Impact

What is the one sentence you can say that would causes a change in the organization's direction? Time is scarce. Consider how your operation is shaping the security of the organization. What assumption are you breaking?

- "Compromising a standard employee laptop cannot lead to a compromise of our production database."

If disproven, this can begin conversations that result in significant architecural changes, identity controls, and segmentation.

- "Our aquistions do not result in meaningful changes to the parent company's attack surface."

If disproven, this can change the aquistion and onboarding pipeline


## Expensive Assumptions are Expensive Risks

How many valuable items are at risk due to an assumption?

Consider the recent [Coldcard Attack](https://decrypt.co/374817/coldcard-bitcoin-exploit-88-million-attackers-draining-wallets). 1367 bitcoin gone. With bitcoin currently valued at $63,000 this is a loss of over $80M. The assumption was that the device had suffient randomness when generating seed phrases. This assumption led to a catatrophic failure. Users never exposed their keys; they were not phished. The attacker was able to regenerate seed phrases based on timings and a device ID due to a weakness in how the phrases were generated. 

## Conclusion

Not all assumptions carry significant risk, but some do. **How many dominoes fall based on a single assumption?**
