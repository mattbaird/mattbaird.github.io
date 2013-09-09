---
layout: post
title: "Are credit cards the reason software development sucks?"
description: "Technical debt can hobble your team, try to avoid it as much as possible"
category: Product Development
comments: true
tags: [lean, product development, Software Development, technical debt]
---
{% include JB/setup %}

Humans have a serious flaw. It doesn’t matter if you are smart, stupid, educated, uneducated, tall, short, thin or fat – most humans have this flaw. A flaw that certain people and industries have learned to exploit.

The flaw is our emotional brain overvalues immediate gains at the cost of future expenses. The longer the feedback cycle, the harder it is for us as a species to tie the reward to the behavior that caused it. Credit card companies understand this intimately hence the reason they offer you teaser rates with really high lifetime rates. It seems we can’t understand the concept of debt.

If you disagree because you understand debt, let me give you a more tangible, visceral example: Subprime mortgages. Why would anyone buy a house they can’t afford at a low interest rate knowing the rate goes up dramatically after a few years? Why would any rational person choose a credit card with a lower one year rate, but a much higher lifetime rate knowing that lifetime > 1 year? Why wouldn’t people with a good income level invest in their 401k’s?

So, moving on to software, you’ve probably encountered the term [technical debt](http://www.martinfowler.com/bliki/TechnicalDebt.html). This is the accumulation of bad code, design, architecture, whatever that you have not paid for. The payment is in the form of iterating and doing it better. Unfortunately I’ve noticed that technical debt accumulates interest much like credit cards – slowly at first when the bad code is introduced, and more significantly as other bad code is built on top of it, or it is cut and pasted throughout the codebase.

What’s the end result of too much credit card debt? Sometimes it’s some sort of intervention or program that gets you on the path to financial health, but a lot of time it’s bankruptcy. In the software world this is often when your best engineers decide the product just sucks too much to work on, they aren’t having fun, and they want to move on to a green field opportunity to try to build something they are proud of somewhere else. Perversely you can be left with the worst abusers, the folks that haven’t been self-introspective enough to understand how their behavior affects the whole.

Now if you have a great team of engineers that understand how decisions and decision-making affect the outcome you can still end up with the same outcome. Debt can be forced on the team by a CEO/VP Sales/Product Manager focused exclusively on the parts of the system they can touch, feel, experience and hence sell which excludes about 80% of what goes into a product. So the team is “forced”, and I put that in air quotes, to spend 80% of their time on the 20% of the code that non-engineers can understand, and 20% of the time on the stuff that makes it work, scale and be maintainable. So when you passionately fight against taking on too much debt and get labelled as “emotional”, understand that the true emotions at play are the ones that favor the short-term gain (the feature) over the long-term benefit (increase speed, maintainability, and NOT going out of business). Neuroeconomists are already crafting programs to help people get around this [limbic](http://en.wikipedia.org/wiki/Limbic_system) trap in the real world – programs like Save More Tomorrow which take short-term gain out of the equation by asking folks to commit to a savings program that kicks in not immediately, but in a few months. Programs like this are measurably improving humans ability to make decisions about their finances.

Don’t feel bad if you recognize this failure as one you have. It’s not our fault – we are not yet equipped to deal with modern decision-making. Our emotions evolved over a long period of time to solve a different set of problems. The best thing we can do is become aware of our short comings and, through that self consciousness, control our actions.

Where the analogy breaks down is I can save money and use my credit card knowing that I can and will pay it off each month before financing kicks in. I can’t do that in software product development. But I can build up reusable software assets and a team built for speed that allows me to accumulate a small amount of debt and pay it down quickly. I wonder if there is a correlation between great software developers and financial debt.

What can we in software development do to make better decisions on debt? I don’t know right now. I currently believe developing software in [small batches](http://www.startuplessonslearned.com/2009/02/work-in-small-batches.html) in a lean manner covers up some of the symptoms, but I don’t know if it provides a real solution.

I carry a credit card for “just in case” emergency situations, and I recommend you should only incur technical debt in emergency situations because often times the longer term results are the same – you go out of business.