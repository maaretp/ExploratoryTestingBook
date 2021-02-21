# Exploratory Testing Foundations

With so much to say and share on Exploratory Testing, what would you need to know to get started? This question lead us to summarizing basic theory on exploratory testing around one test target, and to creation of Exploratory Testing Foundations course material. The course and slides: Exploratory Testing Foundations by Maaret Pyhäjärvi is licensed under CC BY 4.0. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/. 

To create the course, Maaret Pyhäjärvi paired to test the application under test with the brilliant Irja Straus (Croatia), Parveen Khan (United Kingdom), Julia Durán Muñoz (Spain) and Mirja Pyhäjärvi (Finland). The application and lessons were tried with many ensemble testing groups to finally come to be summarized as part of this course. We particularly want to appreciate two open space communities in creation of this content: Socrates UK and TestCraftCamp. Both served as places to try out hands-on testing of the application to see the dynamics under various constraints. Pair testing and ensemble testing are social software testing approaches. In a pair, we have two people testing. In an ensemble, we have a group of at least three people. Both forms of social software testing enable us to test and learn together, and give us a better feel of the results testing of the application can produce. With tens of sessions with this little application, no two sessions have produced exactly the same results but each session has produced useful results that can be used to build on, should we seek good coverage over our target of testing. 

The course and this section sets out to teach foundational concepts of contemporary exploratory testing:

   * It is an approach to testing in which we optimize value of our testing. 
   * It is about systematically combining information from available sources to do the best work possible for the context at hand, not merely guessing errors.
   * It is multidisciplinary and allows us to take perspectives (using 'constraints') one after the other or simultaneously on the discretion of the person doing testing.
   * It includes use of test automation both for documenting and as a means to do things otherwise out of our reach. 
   * It leads us to thoughtful test coverage, where most meaningful sense of coverage is on missing less important information (e.g. bugs).
   * It reveals that a simple application that appears to 'work' has meaningful layers to isolate information on. 

We know there is more to teach on exploratory testing than this one course includes. We will create separate similar yet different sets on different types of applications and contraints that make sense with each of those examples. We will also address Exploratory testing the Noun - organizational frame of testing - on later courses. This one focuses on Exploratory testing the Verb - doing really good work optimizing value of testing through learning while testing. We give half of this course to the contraint of test automation as documentation, as we believe that this is a core aspect of contemporary exploratory testing. You can't automate well without exploring. You can't explore well without automating. 

## Introduction to Exploratory Testing Foundations

![Course Notes to Exploratory Testing Foundations](images/ETF/slide1.png)

Welcome to Exploratory Testing Foundations –course. This course intertwines a simple application to test with basic theory of how to do exploratory testing to give you a foundation to build on. 

Exploratory testing is an approach to testing that centers learning. Test design and test execution form an inseparable pair where the application and feature we are testing is our external imagination. It takes domain knowledge, requirements and specifications, and testing knowledge as input and produces information and a better tester as an output. It also encourages us to at least consider documentation and test automation as a form of documentation. 

We think of this course as an antidote to the idea that test cases tell you how to test a feature and that is where a new tester would start. That type of test cases are only a small subset. You are expected to find defects, where the system does not work as we specified but not stop there. Finding change requests, things that would make things better for users is included. And instead of using most of your work time on documentation, we're inviting you to consider lighter and executable formats of documenting. 

This is what we fit into two days with one application. Theory and application go hand in hand. When taught in classroom, we will also reflect course experiences to work experiences and share war stories of testing in projects where applicable. 

In it's current format, the course takes two days in a classroom to deliver with many different passes. We are working to build a video course on the scope of the course, to enable people to learn this in scale as we are unable to make space for classroom guidance for everyone - we prioritize working as testers in projects over being teachers of testing. Thus the course material is openly available to use as is, or to freely adapt to scope of your choosing. We have delivered it in 99 minute segments combining various constraints learning it takes a minimum of three sessions to go through the ensemble testing to cover the application without theory slides. 

Exploratory Testing Foundations by Maaret Pyhäjärvi is licensed under CC BY 4.0. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/

![Course Notes to Exploratory Testing Foundations](images/ETF/slide2.png)

Exploratory Testing centers learning. The application we test is our external imagination. While we test, we learn about the application and about ourselves. We optimize the value of our work continuously. Instead of following a plan we created at a time we knew the least, we create plans, learn, adjust, even completely revise as we learn. Our ideas of the plan are best when we know the most, at the end of our testing. 

To emphasize learning, we emphasize agency – the responsibility of the person doing testing to do the work to their best ability, and to grow with the testing they do. 

We remember we learn 
   * by researching the domain – the business, the legal, the financial 
   * by passing on information from those who worked on the problem before us  - the stakeholders, the requirements and specifications
   * by using the application and thinking while using it
   * by critically evaluating the application as we use it
   * by focusing our attention to both how it could work and how it could fail
   * by reflecting new information against what we know from the past
   * by experimenting with approaches outside our usual repertoire
   * by centering value of information we produce

The work we do is done in slots of time: a minute at a time, an hour at a time, a day at a time. Every unit of time, as we learn, makes us better at optimizing our value. 

We go as fast as we need, or as slow as we need. Just like driving a car requires you to take yourself and your surroundings into account to choose the right speed for the situation at hand, same applies with exploratory testing. You drive, your speed and your route – with the destination in mind. 

Optimizing value of our testing and centering learning hint that we most likely want to avoid investing prematurely into documentation. We also want to avoid forgetting documentation, as delivering the right documentation is part of our goals. We also want to avoid separating test ideas and test execution, but enable those two to go hand in hand, within the brain of the very same tester. Pulling information from outside, but not executing on someone else's orders. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide3.png)

To set our minds for the road, let’s talk about the process of exploratory testing. 

We are given something new to test. It may be a new application like one on this course. It may be a change in the application you’ve worked years on already. It may be a new feature that is new, in an application you are already familiar with. Your task in testing it is to provide information on when it works and when it doesn’t, in the perspective of stakeholders. 

This is a process of information discovery. We already know something, and we use that. But we are asked to learn more and share our learning with the rest of the application team. The information you provide extends the existing information. 

In the process of exploratory testing, anything can happen. Quality of output is related with quality of input, and time used in the process to learn and improve. 

We usually think of the process in terms of time used on activities. Simply put, there are four main activities you will want to pay attention to:

   * **Test**: Using time on test, you go through new ideas of what to try and observe. Without time on test, coverage will not grow.
   * **Bug**: Using time on bug, you work on understanding information you are discovering and refining it to better serve others as you pass it on. 
   * **Setup**: Using time on setup, we work to make test possible. You may be setting up test data, operating the application to get to a starting point, researching while connecting information with the target of testing or solving issues on getting to test. 
   * **Document**: Using time on document, you leave notes and materials for your future self and anyone coming after you. This becomes increasingly important to track as own activity when we apply test automation as documentation. 

These activities can happen in any size chunks within the process. They can be consecutive or concurrent. Usually through practice an exploratory tester learns to intertwine things for an appearance of concurrency of some perspectives, and each tester combines things within what they are comfortable with. 

Thinking back to the process of driving a car - When you were new driving stick, you would accidentally stop your car on traffic lights, forgetting which gear you were on, or letting go of clutch a little too soon. Over time, the basic operation of the car became a routine leaving you time to pay attention to surroundings rather than operating the car. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide4.png)

The most important thing going into the process of exploratory testing is whoever is doing testing. It could be a career tester. It could be programmer. It could be an analyst. Job role aside, we call someone who performs testing a tester. 

No matter what the features the tester goes in with, going with the idea of learning while doing, we come out different. Since we optimize our value, we optimize our learning too: we want to be always both **learning** and **contributing**. 

What we can’t take in as we start, we can acquire as we do testing. We can ask around. We can research. We can read existing documentation and apply it to the application under test. We can constrain ourselves with a test technique. We can make notes and create versions of documentation we intend to leave behind. 

Exploratory testing – doing testing from whatever the input - emphasizes learning while contributing. And while it can be something you do solo, on your own, it is also something you can do with a pair or a group (ensemble). 

We want to spefically mention four categories of input:

   * **Domain knowlegde** is about what the tester knows and how well the existing knowledge enables connecting with new knowledge to understand what the application is about, why would anyone want to use it and what risks pose a relevant, meaningful threat to its value.Both knowing domain of this application or another domain enable you to compare and contrast the information you have to information you are acquiring as you are testing, and building patterns. ß 
   * **Requirements and specifications** is about knowing the agreements around the organization on what the application under test should do. While being aware of claims is good, sticking only to claims made by others limits testing in a way that it can block us from starting conversations on relevant features we are missing. 
   * **Testing knowledge** is about knowing how to think in terms of charters and constraints to provide new relevant information about the application under test. It's about understanding the difference of seeing something work and then seeing it fail in both ways it should (error messages) and should not (bugs). 
   * **Miscellaneous knowledge** is about everything else, including the tester's ability to program. Being fluent in programming enables writing documentation as code that can then stay around for later. Endless curiosity in wanting to understand how the world works helps ask relevant questions about the application instead of settling too low. Catalytic skills enable drawing other people's knowledge into the work you are doing and creating connections for shared success. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide5.png)

What comes out of the process is a better tester but also different kinds of deliverables we consider relevant when optimizing value of testing for *the specific testing at hand*. Sometimes we only report new information. We leave coverage as implicit, but our information is only as good as our ability to cover multiple perspectives. While we can come out with only information, we often want to put our learning into a good use for our own and our coworkers’ future and leave behind documentation, even executable documentation. 

Let’s now say this out loud: test automation belongs in exploratory testing. You can’t explore with great coverage without automation. You can’t automate without exploring in a relevant way. When automation fails, it calls you to explore. With that said, we are optimizing the value of our testing with exploratory testing: value today, value in the future.  Automation is a constraint that directs our attention. We make choices of when it is the right time for that constraint. 

If you don't know how to code and write automation, it cannot be part of exploratory testing you do personally. What you cannot do personally, you can compensate for through collaboration. Collecting ideas to pass to team members while exploratory testing to document as automation may be a constraint you live with. You can also learn to code and remove a knowledge-based constraint. Same applies for people who know programming but have hard time with good testing ideas. You can also learn to test and remove a knowledge-based constraint. 

On the knowledge-based constraints, we would like to remind people that software industry doubles in size every five years, meaning half of us have less than five years of experience. With less than five years of experience, we have knowledge-based contraints we later in our careers learn away from. Choosing a focus of skills to learn first is a natural way for us to divide the learning in a team, without letting it box us indefinitely into roles. Contributing to test automation efforts isn’t the most complex of our programming tasks and we believe everyone can learn it. We're less sure if everyone can learn to think in ways that ensure multidimensional coverage and we're hopeful with that too.  

Successful output is effective: we find problems our organization expects us to find. The path to the result of finding relevant issues is through understanding coverage. 

The four main categories of output we want to mention are: 

   * **Coverage** is about knowing how effective your testing is. Did you cover code (implemented), requirements (asked), risks (problems) and how can you tell?   
   * **Information** is about knowing your results. What conversations is testing starting? What changes are we making based on those conversations? Are we removing bugs that might bug a user? 
   * **Documentation: Strategy** is about knowing how we approach testing for this particular application under test. At first our ideas are vague, but in the end they should be at their clearest state. 
   * **Documentation: Tests** is about leaving behind a checklist of any sort that enables us to build on current learnings ourselves later or by others. How can we accelerate testing for next time around? 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide6.png)

This course is first in the series of Contemporary Exploratory Testing courses where teaching on the course is framed around a particular test target. For foundations, our application is very simple, and it was chosen based on the idea that is *not supposed to be full of bugs*. While finding lots of bugs is fun and does wonders to a tester’s self-esteem, it gives a false impression of what it is we do when we do exploratory testing.

The course is split into 17 chapters, where each chapter will have a supporting video, and the final chapters will describe the best testing we have done on the application. It isn’t a recipe for all applications, but an example for you to understand what coverage for this application may mean, and what parts of the work you could do make sense when you are truly optimizing value.  

From the outline, you can see that we will be using a test automation framework (Robot Framework) on this course. Choice of tool is irrelevant but using one to give you concrete examples helps teach this content. Robot Framework allows for natural language like programming in its own custom-made language and can be useful for new people to get into test automation programming. We believe it soon becomes a limiting factor you may want to learn away from and become a polyglot programmer.

![Course Notes to Exploratory Testing Foundations](images/ETF/slide7.png)

The same course delivered in a one-day classroom format uses this four part structure. We start with options for exploring (and do exercise on documenting our ideas without use of application), continue with addressing personal choices on constraints allowing people to explore without automating, adding automation as constraint teaching people who to automate with Robot Framework Browser library, and conclude with addressing use of time over results, thinking through coverage. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide8.png)

In this first chapter, we don’t yet get to use the application, but we get to see the application. Sometimes a good way to learn about how learning changes things is to try to think what you would do before you had more information. 

With exploratory testing, you need to appreciate learning. Learning shows up by your ideas changing, and ideas changing change your actions. You should notice when your ideas change. It is expected, welcomed, and makes you better. You can’t have the best answers available at the time you know the least. 

With an application you have never seen before, it is clear you *now* know the least. It is harder to appreciate how that is true on your day-to-day job, with the same application with new changes coming in. Yet it is the same: at start you may know a lot, but you still know the least about that specific change and its impacts on the application compared to what you can know given proper time to explore it. 

Working in pairs or ensemble on generating ideas, we find people do better with versatile ideas than on their own. Then again, having a lot of ideas before you know anything that would help you prioritize or target your testing isn't going to be the best use of your time. Recognize what you think is most pressing on your list of ideas. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide9.png)

The application we test on this Exploratory Testing Foundations course is called E-Primer. It’s a little application for people who want to check their English writing to master e-prime – a way of writing English avoiding the “be” –verb in all its formats. 

We chose this application because we were under impression it is not target-rich application for testers. That is, it is not so full of bugs that you should consider it ridiculous. 
Having tested it, I know it has its share of issues. And to begin with, the version we styled for this course has one major issue that the original did not have and we haven't yet fixed it. 

We can figure out what the application is and what it does by using it. Also, name of the application gives us a hint and allows us to research e-prime further should we want to. 

At this point, let's not yet go and use the application. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide10.png)

By the time we get to chapter 3: The Moment of First Impression, your first impression on just seeing the application is already gone. But the first impression of using it is still ahead of you. 

Before you move forward, stop to think. What would you do first, and what soon after you get started? If you make an inventory of ideas you have, what do you list? Try doing that. 

People testing applications come to the targets of testing with our biases. Our internal dialogue of being awesome just as much as our internal dialogue of being bad has an impact on our ability to look at what we can do objectively, which is why I encourage writing things down to support your own learning about yourself. Learning is about changing your mind, replacing something you thought you knew with something more accurate, and adding new knowledge on top of what you already knew. Pay attention to what your first instincts say about testing this one. 

This careful listing of your starting point supports your learning, and we would not ask you to do this with every application you ever test. But it is an option you can start with, an option we enforce here for learning purposes even if it didn’t help with optimizing value of testing the application at hand. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide11.png)

Now that you have created an outline of what you would do without doing anything but digging into your past lessons, it’s time to discuss your options for getting started with a new application. 

Time you spend away from application to learn about it is time when you don’t know about what the application does. 

Time you spend wandering without a purpose with an application could be a way of learning about the purpose, but there may also be more effective ways to learn about it. 

Balancing your options and creating new options as you go is at the heart of exploratory testing. 

If you can research the domain in a way where you continuously test and learn, you are simultaneously learning and contributing. 

If you start using the application, take control over what you do. Think of what is included, and particularly what isn't included.

Some people will start with automation first. With many sessions over testing this application, we have come to understand it both enables and limits us. We see some types of problems, while becoming more blind to others. Same works when we start with use of the application first. No matter what constraint we choose to start with, it is our right as exploratory testers to make that choice for ourselves. 

## Self-Management in Exploratory Testing

![Course Notes to Exploratory Testing Foundations](images/ETF/slide12.png)

You have options for exploring, and your task in exploratory testing is adjust your intent, charter and constraints on a cycle that enables *you* to keep up and do the best possible testing you can. Exploratory testing centers the tester, so you don’t have someone from the outside telling you what detail to verify, the control is with you. 

Some people tell us that the freedom frustrates them and makes it hard for them to start. They don’t have to have this freedom; they are free to set themselves into a box that enables them. They are also free to let themselves out of the box they created, when they discover that to be useful. 

In this chapter, we introduce three concepts:
   * Charters 
   * Constraints
   * Multi-dimensional thinking for intent and learning

![Course Notes to Exploratory Testing Foundations](images/ETF/slide13.png)

Charters are a key concept in how the community talks about framing your exploratory testing. You can think of a charter as a box that helps you focus and generate ideas, but also assess when you think you are done with a particular idea. 

We like to think of charters as free form test cases. 

A charter could be a chapter from your design specification you want to understand empirically with the application. 

A charter could be reminding you of a non-functional perspective, like accessibility – can people with disabilities, permanent, temporary or situational, use the application, being an important group of stakeholders. 

A charter could be a very traditional step-by-step test case with your promise of stretching every single step to both it’s intended path but paths it inspires. 

Charter is a structure for *thinking like this*, not *passing work along like this*. Some people use charters to share work in team and our advice is to not do that *unless* you co-created the charters in the first place. As soon as you remove tester designing, executing, and learning intertwined, and replace it with a tester designing and another executing, you will lose a core feature of what makes testing exploratory testing and shorten the leash a tester learns in. 

Elizabeth Hendrickson introduced a charter template in her book Explore It, and Elizabeth Zagroba introduced an adaptation of it in one of her presentations. We like the concise template a lot but encourage you to think in terms of charters being anything that can box your testing and help you maintain focus, rather than follow a format. 

We advise against using charters for passing work along unless the work distribution is a shared endeavor between people. When we pass them along, the process starts to resemble traditional test cases where someone is following another's lead. This might be a temporary structure you try when you have new testers but our advise on teaching new testers is to pair with them rather than passing information through documentation they don't yet understand how to stretch. 

Growing a new tester in exploratory testing, we often see a pattern of first looking at an application as something that has little to test. Pairing and sharing dimensions in an actionable way transforms the tester, and with the tester, the results the tester is able to deliver. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide14.png)

We prefer framing exploratory testing with constraints, which is one of the options to use in resources part of the charter template. The way we look at it, we have limited bandwidth to doing many things at once, and for us to frame the work we do in an effective way, we need to deliberately exclude perspectives to a level where we can cope with the perspectives we have decided to focus on. 

Like, you could say you are deliberately not writing notes at all to get through as much of different scenarios of using the application you can think of. Or, you could say you will go through a document describing correct behavior in detail, ensuring not to miss important claims. You could say you will get through 100 scenarios around the application quickly, or five in a lot of detail in the same timeframe - a day of testing. You most likely cannot do it all at once but need multiple passes with the application, with seemingly same tests but different ideas in what to do and pay attention to. 

If you try to do everything at once, you can’t get any of it done. So, we get to choose our constraint with my primary heuristic to never be bored.  

Testing is a lot of fun. Finding out information that others don’t know is investigative work, and servicing many stakeholders is an intellectual challenge. No matter what changed, there is something new we now need to figure out, in a way that optimizes the value of our work. Doing the exact same things isn’t optimizing value of our work, so you start with the idea of always varying things to not be bored. If you find yourself bored, you need a new constraint that challenges you. 

Some folks take automation as the challenge that keeps them from being bored. Others find the multidimensional work all the ways we could use the application to see new problems motivating. Some people say that automating helps them have time for exploring, and they mean that seeing simple problems isn't good use of anyone's time. Covering ground with the application under test in a repeatable way is the gruntwork of automation.  However, automating on level of unit tests might be our best bet towards catching unintended simple bugs and we like framing freeform exploratory testing and unit tests together in keeping things interesting! 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide15.png)

Exploring is wandering with a purpose – without purpose, we are lost. A high-level purpose of spending time with the application or finding information is a little too generic. Specific purpose, intent, looks at what is the next step, next timebox and next theme, balancing serendipity (lucky accident) and coverage (making accidents likely). 

When we practice being intentional, learning to structure our thinking that is multi-dimensional can be helpful. When you imagine and fill the next slot of testing in your schedule be it next hour or next day, I find this matrix has helped me keep track of my intent and learning. 

Think of this as an empty A4 paper for the next piece of testing you are about to perform. **Mission** includes a statement of why you exist in the organization, what is expected of you – there might be a role-based constraint applied to you such as being a test automation specialist, but that does not stop you from doing other things, merely reminds you that if there is a priority call, yours might go this direction.  Like a sandbox you are responsible for, but with sides so low you can easily cross them when you are excited, this corner reminds you of where you anchor your purpose in larger scale. **Charter** would talk about something on shorter term, like a personal promise: “today I will test with 100 different inputs on one browser”, implicitly saying you will do that rather than test for example 10 inputs on 3 different browsers. It’s your intent you are framing, so it is your right to change the framing any time. **Details** makes space for things you note while you test on level of details.  Typically, we note things that are bugs, things that are questions, and things that are ideas for documenting for future in whatever test material I leave behind. **Other charters** is your placeholder for things you’d like to do but won’t do now even they popped up in your head under influence of the application as your external imagination. 

When you find a bug, you can choose to write it down quickly and continue. Or you can choose to isolate it properly and log it. Your choice. 
When you find a question, you can choose to ask it right away. Or you can choose to collect them for later, seeing if other things you learn while testing will provide you an answer. 
When you find something to document, you can write it down in the best possible format immediately. Or you can write a note appreciating it as something worth documenting and take time later. 
You can also completely skip a bug, a question or the documentation. The more thoroughly you process them, the more time they take from what your intent for this testing was.  

![Course Notes to Exploratory Testing Foundations](images/ETF/slide16.png)

You are approaching the moment of first impression. You usually want to see it work before you see it fail, or you don’t understand and appreciate the way it fails to communicate the fail properly. What is the first thing you will do? Would you frame your start as a charter, a constraint or as an intent? Or maybe you have your own style of framing your testing that we did not talk about here? 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide17.png)

We already saw the application, even if we did not yet use it. One more thing to note before heading in for the test. You are only new with an application once. Even if it is time when you know the least, let yourself listen to how you feel about the application. Your joy could be user’s joy. Your confusion could be user’s confusion. Your mistakes are most likely some user’s mistakes. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide18.png)

With making choices of what we do first and what we do after, it is good to be aware that while we have an endless selection of options, some options expire. 

You can only have a 1st experience without having read documentation or given a personal demo before those have happened for you. Even if you can’t have the first impression personally working closely with the feature, you can always work to borrow someone else’s experience through pairing or watching them use the application. 

While many of our options don’t expire and we can do them in which ever order, it takes exceeding amount of energy to remain curious about the new information when you have already tried many things. I find that we often give up and stop testing too soon! In the words of the famous Albert Einstein: “It’s not that I’m so smart, I just stay with the problems longer.” Given time of use, software has the habit of revealing issues it has always had but we either could not see or appreciate earlier. 

When working close to a deadline, options expire also on what feedback is welcome. Days into a major release, issues considered major months before can be prioritized down. Timing of feedback matters. 

You usually stop testing before you have exhausted all your options. Knowing your options helps you be intentional about it. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide19.png)

With all this said, it is our time to test. The application is available at https://www.exploratorytestingacademy.com/app/ and eviltester’s original at https://eviltester.github.io/TestingApp/apps/eprimer/eprimer.html. 

Pay attention to where you start from, how you learn, and how you decide on your next steps. Each of the following chapters gives you one constraint that is applicable to this application at hand and explains where the constraint leads you. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide20.png)

Your first impression and learning of the application is most likely not taking you this far. This mindmap is from an hour of pair testing with a tester who found none of these problems alone but needed training on how to look at an application to identify what might go wrong with it. The mindmap is by no means exhaustive list of things that are off with the application. We’ll talk about bugs  in more detail when we get to the part about coverage – because most relevant coverage is bug coverage except that we can only assess in hindsight.  


![Course Notes to Exploratory Testing Foundations](images/ETF/slide21.png)

We would hope first impressions are not about bugs, defects and change requests for users of our applications. Tester’s sometimes get to bugs on the very first thing they do with an application, drawing from past experiences to select a way of using the application that reveals a bug. Tester’s fast forward a user’s year into the hours they use testing – or better yet, multiple users’ years. 

We like to think of bugs as conversation starters. Sometimes we need to avoid the word defect and reserve that only for use where it is clear that the behavior of the application is against something we explicitly agreed. Defects come with the burden of guarantee, whereas change requests have a different tone to them. In many teams, we have called bugs “undone work” to remove the judgement from the conversation – it is simply undone work we propose we still might want to do. 

Bugs are things that might annoy a user, and unless someone starts a conversation on them, they conversation starts only at a time a user starts it. These conversations turn things we didn’t know into something we can be aware of. And for many, it enables us to design changes that remove the bugs. 

You can also start conversations on the good things you see, the absence of bugs that surprises you or just the things you find that make our users with our application more awesome. Having that empirical touch on what we have built gives you a perspective of use that serves as a conversation starter. Identify something good, find ways of getting more of that kind of good. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide22.png)

Let’s move to discussing domain, requirements and specifications. The information about what the application is and does comes to us in many forms. 

Domain is the problem-solution space of the application. The application exists for a purpose, and that purpose is the domain. 

Sometimes we know the domain by just our life experience – like most editors. We know what a text editor does. While there are specific functions to a text editor, we can figure those out since we too have edited text before.

Sometimes we know very little of the domain and need to learn it as we test it. Learning a domain effectively and becoming a domain expert over time is what we would expect from someone testing applications in a particular domain for a longer period. Knowing the domain or learning about it until we know is what separates us from assuming something could be right to understanding if it is right. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide23.png)

To learn a domain is to acquire information about the problem-solution space of the application, and usual expectations of it. 

You have three main routes to it:
   * **Conference** is about asking around. Talk to anyone you need to. 
   * **Reference** is about getting an authoritative document. It may be given to you directly, or you may use general search to find it. 
   * **Inference** is about applying other knowledge you have access to with this domain, expecting similarities or differences. 

You may have a requirements specification. You may have a functional specification. You may have a user interface specification. You may have an architecture specification. No matter what you have, it is not all you will need. And if you have none or some of these, or some others, we advice to think that documentation is useful but also it reflects the things we already think we know. Exploratory testing begins with what we know and seeks to learn what we don’t know yet. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide24.png)

With E-Primer, we don’t have a specification. We have a Wikipedia description of the domain that gives us a decent perspective into what the application is designed for, without knowing any of its intentional limitations. 

We can search online for any information about e-prime we consider useful and educate ourselves on it. 

With specification, we can find phrases to test with that showcase the application’s functionality. This good demo phrase is a result of testing, not the first idea to use the application even based on its specification. We can best get good demo examples by asking the developers on how they discover the functionality. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide25.png)

With this specific application, we can find the source code to view it in the browser.

Or we can find it in GitHub where it is hosted. https://github.com/exploratory-testing-academy/ETF/blob/master/app/eprime.js 

Looking at the code gives us a direct chance of comparing what it can do to what we would expect it to do with regards to the Wikipedia page.  We could, just by reviewing the list of words that get marked discouraged identify that the words “you're, we're, they’re” that should be marked won’t be, as they are missing from the list. 

Programs do what they are told. You don’t have to know how to read all of code to read enough code to make sense on existing logic. 

We recommend all testers read pull requests / commits to understand scope of changes they are testing. 


![Course Notes to Exploratory Testing Foundations](images/ETF/slide26.png)

It is time to test. Try out what how testing flows when focusing on the domain knowledge. What do you think of coverage of what you have tested so far? Eventually, we care about you not missing relevant information others don’t yet have and thus can’t specifically ask of you! 


![Course Notes to Exploratory Testing Foundations](images/ETF/slide27.png)

The combination of reading and using the application means a significant portion of your time went into making sense on the Wikipedia text and finding other relevant references. You most likely learned something.

We expect you are now more comfortable with the application and have an idea of what it does. 

You may still find the “Possible Violations” something you can’t understand or figure out. The written references on it are not particularly helpful. 

Most commonly people come to understand “Possible Violations” as a side effect. We commonly see three routes to finding it. 
Using the demo phrase this course has – given the demo phrase, people miss out how hard it is to figure out when it should not be
Reading the code – figuring out from the code that “’s” is the search criteria for counting things as possible violations, and then understanding that it looks like possessive and “be”-verb appear so often in hard to distinguish formats that this appears a likely design choice signaling need of user intervention over programmatic algorithm doing all the work
Using large data samples – browsing through large data samples, like copy-pasting the whole Wikipedia page text at once in the application and browsing for blue

You learn domain by asking questions and paying attention to answers. Not all your questions have an answer, but they start conversations you get to consider how far you take them. What helps you optimize the value of your work when testing? 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide28.png)

Now that we have an idea of the domain, let’s look at the functionality. 

Different applications are built on a different technology. As someone testing an application, knowing about the technology is something we would expect. Not expert level knowing, but at least a basic level curiosity turning into expert level knowing over time, question after question. 

A lot of testers given a picture of the application start suggesting SQL into the text box, which makes little sense now that we know the application under test is a javascript application that runs in your browser after you have downloaded it. The application keeps working even if you disconnect from network as long as you don’t try to refresh from the download location. 

Let’s discuss functionality as constraint a little more. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide29.png)

For functionality – features – we find a good approach to be seeing function in different scale and naming it. 

The code has functions the programmer has given names to. It is structured as functions the programmer calls to get their intended results overall.  We could use a unit testing framework to explore the functions of the code, and for the scale we can, we probably should. 

The application has functions we would probably name ourselves. Some of those functions come from what the programmer explicitly introduces, some come from the fact that it runs in a browser. 

We can name what we see. We can name what we expect to see. And we can compare those. 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide30.png)

Given the constraint of function, what would you test? 

![Course Notes to Exploratory Testing Foundations](images/ETF/slide31.png)

Usually when we use the constraint of function after using the constraints of domain, we find there is either an overlap or challenges in naming things we did not already see. Many times, we find we need to point at a function directly and name it to make it visible. 

With this application, there are a few functions that are not obvious.

Text area for output text has a size limit with the grey background
Text box is resizable, and so is the page and browser window
Anything running in browser has a connection to browser settings
The eprime recognition algorithm is core to the problem and feels to be on a weaker side
Between our version of the application and eviltester’s version of the application, we have lost scroll bars – a function really relevant when dealing with larger chunks of text

![Course Notes to Exploratory Testing Foundations](images/ETF/slide32.png)



![Course Notes to Exploratory Testing Foundations](images/ETF/slide33.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide34.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide35.png)

Given the constraint of data, now it is time to find the things that could be different. You find data you can vary on the easy places like input values to a text field, but equally data is there on getting to output values of the application. What can you vary to discover problems the application holds? 


![Course Notes to Exploratory Testing Foundations](images/ETF/slide36.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide37.png)

In this chapter, we will see a bug I accidentally introduced in copying the test target and restyling it. We will also FIX it. 


![Course Notes to Exploratory Testing Foundations](images/ETF/slide38.png)

No matter what level of detail we look at when we test – code structures, application programming interfaces, user interfaces be it individual parts of multiple parts end-to-end – we should remember that with testing, we are not only evaluating our own code, but we are also evaluating our own code in the bigger ecosystem. 

Quality experience of our users depends on things that are outside our direct control, and we may need to choose things in our direct control respectively to uphold promises we make for our users. 

Signal – the messaging app – is a great example, and Naomi Wu makes the point for one aspect of quality (security) very clearly. You are only as secure as the weakest link in the system, and you can’t have a secure application if it runs on a platform that isn’t secure. 

We evaluate applications as systems for multiple stakeholders. 


![Course Notes to Exploratory Testing Foundations](images/ETF/slide39.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide40.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide41.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide42.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide43.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide44.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide45.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide46.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide47.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide48.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide49.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide50.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide51.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide52.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide53.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide54.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide55.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide56.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide57.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide58.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide59.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide60.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide61.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide62.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide63.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide64.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide65.png)

Testers cope with tedium, developers automate it away. Best of both worlds! 


![Course Notes to Exploratory Testing Foundations](images/ETF/slide66.png)

Improving testability

![Course Notes to Exploratory Testing Foundations](images/ETF/slide67.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide68.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide69.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide70.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide71.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide72.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide73.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide74.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide75.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide76.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide77.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide78.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide79.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide80.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide81.png)

![Course Notes to Exploratory Testing Foundations](images/ETF/slide82.png)