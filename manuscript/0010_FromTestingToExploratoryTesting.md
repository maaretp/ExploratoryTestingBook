# From Testing to Exploratory Testing

You loaned some money from a friend for an immediate need. Bank transfer would take a few days, so you decide to rely on an app that does the transaction immediately. As your friend is moving you the agreed sum, something unexpected happens and they get an error message. They tell you the money is gone from their account. You see the money has not arrived in your account. And the sum was relevant enough you don't have the chance of trying again before the money re-emerges, one side or the other.

Does this sound familiar? Maybe this exact thing that happened to me did not happen to you, but in some way or form, software and systems have let you down. 

Problems, or rather, avoidance of problems by knowing about them is what motivates testing. Testing doesn't guarantee absence of problems, but shows presence of some of them and allows us to consider fixing them over troubling our users with them. 

Testing gives the solutions we provide our users a chance of failing in conditions that protect the users experience. We use many different techniques within testing to collect empirical information so that our users can do with the software what they should be able to do. 

Someone does some testing on all the different parts going into our solutions. Some parts have many parties doing some testing on them. Over designing, creating and maintaining the solutions users have, we test parts and the whole. We refresh our results because test results are like milk, going sour over time, with increasing speed on conditions of change. 

> Testing: Actively looking for empirical information of aspects that threatens the experience users of software have to know about it to support intent of making available solutions living up to their expectations.

Testing is breaking illusions. We think things work, but unless we go back and see, we may be fooling ourselves. 

Testing starts conversations about possible fixes. Fixing as a result of those conversations improves the users experience with the solution. 

We started with the example of a problem with a personal impact - lost transaction. The money re-emerged 5 days later, and we did not even bother reporting the problem to the app. Problems are that common, and we cannot expect our users to do the work of reporting them for us. 

## Exploratory Testing

With all testing, we face a dilemma. Everyone tests. Yet many of the problems we want to find, those require us to be intentional with a versatile approach to testing. With the assignment in testing being **Go find some of what may have been missed**, the field of work is endless and there are no right answers on what exactly to do. To be successful with the assignment, continuous learning is required.

To frame this work of testing, we see two very different approaches starting from different ideas: 

   * **Scripted Testing** starts with the idea that the great plans and designs we create in the software development deserve to be the center of our attention in testing. We take artifacts (requirements, designs, user stories, user journeys) and think through how we can test those, creating tests that we plan on running. 

   * **Exploratory Testing** starts with the idea that centering results and learning, we can use the great plans and designs but not be limited by them, to target finding information that matters. Tests emerge in the process of doing testing, and documentation is an output rather than input to testing. 

With scripted testing, we focus on the things we think we know, and learn that some of those things were not working. Illustrated, scripted testing stays within the boundaries of known.

![Illustration: Scripted Testing](/img/ScriptedTesting.png)

With exploratory testing, we cover things within the boundaries of known, but seek to actively expand the boundaries. 

![Illustration: Scripted Testing](/img/ScriptedTesting.png)

In scripted testing, we make detailed plans to know what tests we will complete before we are done. 

In exploratory testing, we draft areas we cover to recognize the progress, but replan based on learning regularly. 

Experiences are, as per research in Finland, that results of the two can be the same - both find problems. Scripted testing costs significantly more in preparation of the scripts, and creates more noise with incorrect results giving false alarms. My personal experience on real-sized projects is that the results in scripted testing are more often than not lacking, and projects structuring testing around creating tests from requirements often miss relevant results. 

## Contemporary Exploratory Testing

Since 1984 coining of the term *Exploratory Testing* by Cem Kaner, the approach being the second mainstream framing to testing has seen many forms. From a lense of centering scripted testing -approach, exploratory testing is seen as a technique on top of all things already scripted. From a lense of centering exploratory testing -approach, some people think we should drop the word exploratory as all testing is exploratory. 

In this book, we learn a specific style of exploratory testing that is a result of the author's 25 years of experience in doing and facili exploratory testing. We call this style **contemporary exploratory testing** to emphasize a key difference to a lot of the material out there. Contemporary exploratory testing centers around inclusive approach to test automation.

In scale of testing we believe that **You cannot explore without automation. You cannot automate without exploring.** Exploratory testing is a mix of attended and unattended testing and essential to driving modern test automation success. 



