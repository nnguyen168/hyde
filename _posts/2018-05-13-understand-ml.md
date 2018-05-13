---
layout: post
title: Understand Machine Learning with zeros Maths required
date: 2018-05-13
---

Let me first be cleared: I am no expert in Machine Learning but a person just as many of you who is eager to learn about all 
those definitions, algorithms, and applications of ML. Fortunately, I have realized that the best way to learn is to teach. 
Tell me the last time you try to teach something to somebody and then only find out that it helps you to remember that 
particular thing more profoundly.

![Photo by Igor Ovsyannykov on Unsplash](https://source.unsplash.com/3gsOwvsy7dc)

I started with Machine Learning quite late when the thing has been already a hype and was buzzing all around the Internet. I took some statistical and probabilistic courses at the university, and then I did my graduate internship about the Speech Recognition technology. That was when it surprised me that there was always this Machine Learning here and there. Machine Learning will soon be a foundation principle for every other technology to be built on. Whether you are coming from Economy, Laws, Medical, Psychology, or that kind of things, you will sooner or later need Machine Learning in your own field. It all comes back to the moment when we first sat down in the elementary class and the teacher said there was one thing to learn before all: Maths.  

“But hey! Hold on for a second, you said that I can understand Machine Learning with zero maths required. How come I can continue to read if the rest of this article is all about some equations invented by books-on-the-hands-and-glasses-on-the-face guys?” Do not be worried that much, I said that you wouldn’t need any maths, but actually I lied, a little. You don’t need to calculate the last three number of pi to estimate the area of your house. All we need is basics algebra to understand how Machine Learning works, just like 2 plus 2 is 4 minus 1 is 3, quick maths, right?  

All right no more small talks, let’s attack today’s problem by the very first question: What is Machine Learning? Whether you have ever heard of it or not, sometimes you might be wondering if you understand it correctly. I am not here to teach you all the things you can easily learn on the Internet (type machine learning course on Google and you’ll have 133,000,000 results), I am here to discuss with you what I perceived about Machine Learning from my point of view. Let me split this Machine Learning thing into two parts syntactically by some “boring” definitions I found on Wikipedia:

* __[Machine](https://en.wikipedia.org/wiki/Machine)__: A machine uses power to apply forces and control movement to perform an intended action. They can also include computers and sensors that monitor performance and plan movement, often called mechanical systems.
* __[Learning](https://en.wikipedia.org/wiki/Learning)__: the process of acquiring new or modifying existing knowledge, behaviors, skills, values, or preferences.

And finally my favorite definition of Machine Learning from the book of Tom Mitchell
>A computer program is said to learn from experience E with respect to some class of tasks T and the performance measure P, if its performance at tasks T, as measured by P, improves with experience E.

“Wow, you are making me confused buddy, please don’t just give me tons of definitions and tell me to deal with it.” We are getting to the point, just a little patience. Long story short, __Machine Learning__ can be regarded as the process where __machines__, especially computers, actually __learn__ things. Now let me take an example: the coffee machine. It’s not exactly a computer, but for the sakes of simplicity, it would make a good deal.  

![Photo by Tyler Nix on Unsplash](https://source.unsplash.com/qIxkKKdLQvA)

My coffee machine has only two buttons: start and stop. When I press the start one, it makes coffee, while other button makes it stop, so simple. Now I think the coffee machine is doing a good job, __the machine will do exactly what it was told__. Personally, I think that this “stupidity” is what makes all the machines effective. We humans can barely perform what the machines are capable of. We have emotions, we might get fatigued, and so on. Back to the coffee machine, I am so greedy and not satisfied with just a normal machine, I want something smarter and __be able to learn__. I want whenever I wake up, there will be a coffee ready for me at the table. How can the coffee machine come up with that? Imagine that now I equip my machine with a new “brain” who is capable of learning things. I have a tight schedule so I tell this new brain when I will wake up for a relatively long period of time, says for 1 year. The brain will somehow remember all these information, and it will tell the machine make a perfect taste coffee ready for me every morning.  

“Still be vague about this example?” Let put it into the context of the above definition. What is this experience E the brain behind the coffee machine is learning from? That is my habit or my hours of awake. The task T here is making coffee, and we can measure the performance P of this task through the time from the moment I leave my bed to my first coffee. So the more I feed the brain with my schedule, the better it will perform in making my morning cup of coffee.  

My own definition of __Machine Learning__
>Machine Learning is the process where the machine gets to keep its accuracy and effectiveness while learn to perform differently on the same task based on what it has acquired from outside factors.

We all look the same phenomenon from different angles, hence the different definitions of __Machine Learning__ could be produced. I hope that you will have your own words to describe what you observed about this interesting trend of the technology. Until now you must understand why Machine Learning is so important in the new world where we can make machines doing things they have never been capable of doing. I think it is as important as the discovery of fire, or electricity because we can run our societies on a whole new thing.  

I will present you some kinds of different Machine Learning techniques just in case you want to look them up on the Internet or get confused from the class
* __Supervised Learning:__ this is where the machine is told what to learn, or in another word, it learns from a pair of values — the input and the output. When I teach my two-year-old cousin about vehicles, I expect him to say “truck”, not “motorcycle” or “bicycle” when there is a truck in a picture. The same thing happens in supervised learning. We teach the machine with a large amount of (input, output), and we expect the next time it will predict the correct output given the input. Some applications of this technique are image classification, object detection, speech recognition, etc. although the real-life problem is much more complicated than my example.

![Photo by pan xiaozhen on Unsplash](https://source.unsplash.com/cEf2lvyhNAI)

* __Unsupervised Learning:__ here we do not have any specific goal for the machine to learn. We just give it a bunch of things and hope that it will be able to output something interesting. One good example I can think of is when we have lots of articles from newspaper and do not know which one belongs to economy, politics, or sports. We then feed the machine with the content of the articles and it somehow can pick which belongs to which. This is called clustering where we want to output many classes of the data and it is also the most important application of this technique.  

* __Reinforcement Learning:__ to be honest I have touched this area of Machine Learning yet, but I’ve heard that it would be applied well in the field of robotics. This is the definition on the Wikipedia — “Reinforcement learning (RL) is an area of machine learning inspired by behaviorist psychology, concerned with how software agents ought to take actions in an environment so as to maximize some notion of cumulative reward.”

# Conclusion
We come to an end of my first post about Machine Learning. Congratulations! I have to confess that it is you that gives me the motivation to finish this article. I hope to share with you some of my knowledge about my favorite domain. For the next article, I will talk more about the state-of-the-art of Machine Learning and the current trend in ML which is __Deep Learning__.  

# Further reading
I would like to recommend you some books and courses that I found really useful in learning about Machine Learning which I’ve been personally going through  
## Books
* [_Pattern recognition and Machine Learning_](https://www.amazon.com/Pattern-Recognition-Learning-Information-Statistics/dp/0387310738/ref=sr_1_1?ie=UTF8&qid=1525515472&sr=8-1&keywords=pattern+recognition+and+machine+learning) - Christophe M. Bishop
* [_Statistical Machine Translation_](https://www.amazon.com/Statistical-Machine-Translation-Philipp-Koehn/dp/0521874157/ref=sr_1_1?ie=UTF8&qid=1525515548&sr=8-1&keywords=statistical+machine+translation) - Philipp Koehn
## Courses
* [_Machine Learning on Coursera_](https://www.coursera.org/learn/machine-learning) by Andrew Ng
* [_Deep Learning Specialization_](https://www.coursera.org/specializations/deep-learning) by deeplearning.ai  

I hope you enjoy __Machine Learning__ as much as I did. See you next time!
