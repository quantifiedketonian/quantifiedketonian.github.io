---
author: justin_mitchell
title: "How to: Run your Own Quantified Self Experiment"
posted_date: 2019-06-03 06:00:00 +0000
layout: post

---
Whenever I talk about quantified self and my personal health experiments, somebody will inevitably ask how I know if something I'm doing is actually having an effect on my health. 

I've found that answering this question is not as easy as I would have expected. For any great personal experiment, there are four  steps:

1. **"Seeing a need"**
2. **Planning the experiment**
3. **Doing the experiment**
4. **Assessing the effect**

Let's start at the beginning: 

# 1. "Seeing a need"

If you've ever watched the movie "Robots"[^1], you might know the movie reference. If you haven't, here's a quick summary. A famous businessman robot, Bigweld, encourages children to come up with their own solutions for the problems in the world. He promotes the phrase, "See a need, fill a need" because he says that's how you find something great to invent.

I think this phrase "see a need" is critical for doing any quantified self-experiment, and for me, it's the hardest part.

As a slightly OCD person, I would like to improve everything simultaneously. But if I did that, then it would be impossible to know what changes are having an effect and, eventually, nothing would improve.

So how do you decide where to start and what to focus on?

## Finding a "need"

Sometimes, finding a problem to focus on for the experiment is easy. You feel like something is a bit off and you want to fix it. But you don't just depend on your feelings to identify if something's off. Because I'm tracking so many different metrics on a regular basis, I can also just look at one of my dashboard tools and see if there's something that's not in my ideal range. I started keto originally because I saw my weight creeping up (a lot) over time. 

![Withings weight over time]({{site.url}}/assets/images/withings-weight.png)

Other times you find something to focus on because you learn that others are trying to optimize it. With so many quantified self-resources on the internet, it's easy to find an area of your life that might need optimization. 

Now, it might sound extremely negative to always be looking for problems, but I'm a firm believer that there's always room for improvement. 

## "Filling a need"

Finding the problem isn't enough; you have to think through how you will "fill the need" or come up with a hypothesis. Since you're not a scientist in a lab, you can usually get away with a much simpler description of your hypothesis (if that's what you're willing to do). I've found that simple cause-and-effect hypotheses are easiest for self-experiments because it helps to define inputs and outputs, even if it's somewhat difficult to always control for confounding variables.

The hypothesis for your experiment can be as simple as mine was at the beginning of my keto journey. I hypothesized that if I ate fewer carbs, then my weight (and hopefully at the same time, my body fat percentage) would return to a healthy range again. 

# 2. Planning the experiment

Proper planning is crucial for quantified self-experiments. Just like any science experiment, you want to make sure that you can reliably redo the experiment and get similar results. To have a reproducible personal experiment, you have to define reliable measurement methods and a solid protocol for the experiment. 

## Measuring reliably

For any experiment, you have to know how you plan to reliably measure the inputs and outputs. For subjective measures, like sleep quality, reliable measurements can be very difficult. With these types of data points, I will often take the time to determine if there's a way to increase redundancy (i.e. two sleep scores from two different devices) or reduce my variability between measurements. 

For objective measures, like fasting glucose, it can be easier to know how to measure and what to shoot for. Confirming reliability of objective measures also involves a little bit of trust in the accuracy and precision of any device that's measuring it (something that's a bit hard for me).

As I started researching the keto lifestyle, I learned pretty quickly that there were a few input metrics that you can track to ensure that you're in ketosis: net carbs, glucose levels, ketone levels, and glucose-ketone index. I knew it would be easy to track net carbs inside of Cronometer. But tracking the glucose and ketone levels were a bit harder. That required buying a device, the KetoMojo meter. The output that I wanted was a body composition improvement (not necessarily a lower weight, mostly a lower body fat percentage). My basic knowledge could be laid out with this simple chart. 

![Net carbs to body fat percentage]({{site.url}}/assets/images/net-carbs-to-bfp.png)

## Defining the protocol 

The protocol for any experiment is directly dependent on three main elements of your hypothesis.

1. How long do you expect it to take for a change to occur in your output?
2. How frequently can you measure your inputs and outputs?
3. How do you plan to control for any other factors that might affect your output (including time)?

One of the key concerns with the third question is do you need to have a runout period between transitions to ensure that that there's no confounding between the two (or more) interventions. The best way to illustrate how you answer these questions for your experiment is to show you how I did it for my experiment. I'll go through each question.

1. When I started the keto diet, I knew that it takes two to six weeks to become "fat-adapted" and that I probably wouldn't be able to measure the effect of keto on my body fat percentage until at least that long. 
2. For each of the inputs and outputs, I was not very diligent at measuring regularly, but I knew that it wouldn't be difficult. 
	1. **Net carbs**: I set a goal to document all of my meals in Cronometer. It's hard when you are at social gatherings, but otherwise pretty simple to do a couple times every day. 
	2. **Glucose and ketone levels**: Now that I have a KetoMojo meter, I could track both after poking my finger once so I placed it in my bathroom and have made it part of my morning routine. 
	3. **Body fat percentage and weight**: Thanks to having my Withings scale in the bathroom, this has been a part of my routine as well (as long as I keep it charged).
3. I knew that the biggest confounding factor would be exercise so I made a plan to be as consistent as possible with my exercise. I also planned to get at least 2 months of data so I could actually update my beliefs about the ketogenic diet's effect on my body composition and control for weekend variables and travel.

# 3. Doing the experiment

Once you've got your need defined and your experiment planned, you've got to run the experiment. This is probably the easiest part if you've planned well. At this point, it's just a matter of following the experiment design that you've created.

For my ketogenic lifestyle experiment, I followed my protocol of getting daily measurements of glucose, ketones, body fat, and weight every morning. I was also reasonably good at getting my meal intake added to Cronometer.  

# 4. Assessing the effect

After you've finished the experiment, you can easily assess if there was an effect on your outcome and its size (if there was one). For it to be a truly scientific experiment, you need controls (data without the intervention or with a placebo intervention) and randomization, but in n-of-1 experiments, this is difficult. 

Another key thing about assessing the effect for self-experiments is the importance of not doing too many statistical tests on one set of data. I'm not a statistical expert, but it's fairly intuitive that if you do 20 statistical tests on one set of data while shooting for a 1/20 chance of refuting the no-intervention approach, you're pretty likely to have one test that appears to show significance. Statistical experts will say you should use the Bonferroni correction or something like that. I don't want to spend the time to learn that so I just use a Bayesian approach to my analyses and update my beliefs about if one intervention or another is having an effect. 

As a general rule, I like to make sure that my experiment results are reproducible. I have found that the simplest way to do this is to use a [Jupyter notebook](https://jupyter.org/). 

Once you understand the effect, then it's up to you what to do with that knowledge.

[^1]: My personal opinion is that you aren't missing anything if you never watched it. This quote is basically the only quality part of the movie. You can get a decent synopsis of the movie on [IMDB](https://www.imdb.com/title/tt0358082/).
