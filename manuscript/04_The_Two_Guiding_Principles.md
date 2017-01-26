# The Two Guiding Principles

Whenever I need to define exploratory testing, I bow to people who have come before me.

Cem Kaner introduced me to the idea of exploratory testing with the first testing book I ever read: Testing Computer Software. He defines exploratory testing as:

    **Exploratory software testing is a style of software testing that emphasizes the personal freedom and responsibility of the individual tester to continually optimize the value of her work by treating test-related learning, test design, test execution, and test result interpretation as mutually supportive activities that run in parallel throughout the project.**

Elisabeth Hendrickson et al. created an invaluable resource, a Cheat Sheet, to summarize some ideas common to starting with exploratory testing. She defines exploratory testing as:

    **Exploratory testing is a systematic approach for discovering risks using rigorous analysis techniques coupled with testing heuristics.**

A lot of writing on the topic and techniques are part of Rapid Software Testing Methodology that James Bach and Michael Bolton have created. They define exploratory testing as:

    **<add the definition here>**

I talk of exploratory testing to emphasize the difference that Julian Harty very clearly makes: "Most of the testing I see is worthless. It should be automated, and the automation deleted."

I find myself talking about two guiding principles around exploratory testing again and again. These two guiding principles are **learning** and **opportunity cost**.

# Learning

If we run a test but don't stop to learn and let the results of the test we just run influence our choices on the next test, we are not exploring. Learning is a core to exploring. Exploring enables discovery of information that is surprising, and the surprise should lead into learning.

The learning attitude shows in the testing we do so that there is testing against the risk of regression, but a lot of times the risk isn't best addressed by running exact same tests again and again. Understanding the change, seeking out various perspectives in which it might have impact and introduce problems that were not there before is the primary way an exploratory tester thinks. Whatever I test, I approach it with the idea of actively avoiding repeating the same test. There's so much I can vary, and learning about what I could vary is part of the charm of exploratory testing.

When we optimize for learning and providing as much relevant information as we can with whatever we have learned by that time, we can be useful in different ways at different phases of our learning with the system.

# Opportunity Cost

Whatever we choose to do is a choice away from something else. Opportunity cost is the idea of becoming aware of your choices that have always more dimensions than the obvious.

There are some choices that remove others completely. Here's a thought experiment to clarify what I mean: Imagine you're married and having hard time with your spouse. You're not exactly happy. You come up with ideas of what could be changed. Two main ideas are on the table. One is to go to counceling and the other is to try an open relationship. If you choose the latter and your spouse feels strongly against this, the latter option may no longer be available. The system has changed.

There are some choices that you can do in different order and they still are both relevant options. If you choose to test first with a specification, you will never again be the person who has never read the specification. If you choose to test first without the specification, you will never have the experience of what you would notice if your first experience was with a specification.

There are some choices that leave others outside scope. If you choose to use all your time in creating automation and avoiding following the exploration ideas you generate while automating as basic cases already require effort, you leave the information exploring could provide out of scope. If you choose to explore and not automate, you leave repetitive work of future to be done manually or undone.

The idea of being aware of opportunity cost emphasizes a variety of choices where there is no one obviously correct choice in the stream of small decisions. We seek to provide information, and we can do so with various orders of tasks.

It's good to remember that rarely we have an endless schedule and budget. So being aware of opportunity cost keeps us focused on doing the best testing possible with the time we have available.
