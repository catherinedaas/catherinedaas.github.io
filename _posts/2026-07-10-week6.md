---
layout: post
title: Week 6
---

Week 6, July 6 - July 10

Much of the initial code for this was experimental and heavily AI-generated, used to get a better sense of the shape of the data. Normally, I don't think it is a good idea to refactor code for the purpose of understanding or validating it, but I don't really have a good perspective on what a reliable approach looks like with AI. There are definitely a few math bugs, and I definitely want to rewrite the statistical methods to rely on library calls, as opposed to equation-based methods that the AI generated, so a refactor absolutely has to happen.

This is really turning out to be quite a frequentist statistics problem. This is interesting because the project is creating a deliverable for a mechanical engineer, but also for clinicians. Bayesian methods are more frequently used in some areas of computing and ML and might have been a good fit. However, we are trying to estimate what normal IMU data looks like for someone with good balance in a way that is useful to clinicians. My thought process is that using methods clinicians are familiar with from their training, and that are widely used in medical research, is the most important part of the output.

We had a follow-up meeting this week for the DREAM cohort for the summer of 2026, and it was very encouraging to hear a lot of the same experiences. There are many students encountering scientific coding and shared repos for the first time. The practical business of navigating Git, parsing an existing repo, and, in my case, working with participant data has been a really great learning experience.
