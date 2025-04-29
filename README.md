# comp341-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [COMP341 Assignment 3 Solved](https://www.ankitcodinghub.com/product/comp341-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113652&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP341 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Introduction to Artificial Intelligence

Assignment 3

Submission Through: Blackboard

Make sure you read and understand every part of this document

Important: Download your submission to make sure it is not corrupted and it has your latest report/code. You are only going to be graded by your blackboard submission.

Grading

You are given two options about submitting your homework: (1) both code and report, and (2) only report. The second option is given to you in case you are not able to implement the programming part. These options will be graded differently:

Code and Report: The code part and the report will have 2:1 weight ratio in your submission (programming 2/3, report 1/3).

Only Report: The report part will be treated as 1/2 of the total grade. You must credit the code you used and must not submit a code part.

Part 1: Programming

Hints

The first 8 programming questions are fairly straightforward especially if you paid attention in class. Furthermore, both the website and the code comments include a lot of hints so make sure you read them!

Website and the Comments

I cannot stress this enough so I am just going to repeat. This homework has a lot of guidance, both in its webpage and in the code comments. I suggest you read them carefully.

Getting an error related to cgi.message If you get this exception, go to the corresponding file and add import html. Then change cgi.message to html.message. This would happen if you upgraded your Python version.

The DiscreteDistribution Class Be careful during normalization when the total is 0! Otherwise, you might get a divide-by-zero exception later on. Also, the doctest for sampling assumes you normalize within the sample function. This is not necessary if you always normalize before. If you do not want to normalize within the sample function you can add a dist.normalize() to the doctest comments. However, make sure you normalize before any sampling steps later on in the code! Also, do not forget to normalize any distributions you calculate as a final step.

Exact Inference

Uniform Initialization of Particles

As stated in the comments, do not initialize randomly (even with a uniform distribution!) but do it uniformly. Imagine I give you 10 slots and 100 balls. How would you fill those slots uniformly? Find the number of particles per ghost position you need to have and take it from there. There are cases analogous to having 104 balls for 10 slots. I leave it up to you to deal with the remainder (i.e 4) as you like, random is fine. A piece of information; the number of particles is typically much bigger than the legal ghost positions.

Particle Weight Representation and Particle Resampling

Note that you need to resample after updating the particle weights in the observeUpdate() method of the ParticleFilter class. The advantage of using the DiscreteDistribution() data structure is that the existence of the DiscreteDistribution.sample() function. Be careful about normalization.

You can always use another list or keep a combined list for the weights, in which case you will need to implement another sampling function.

Dynamic Bayes Nets

When you are done with the first 8 (Q0-Q7) questions, I suggest you take a break and answer the relevant questions in your report before working on these last 3 questions. I do not want to spoil all the fun for when you get back. So I will only briefly mention a few things.

For this part, a particle will include positions of two ghosts. The emission models are for individual ghosts. To get a particle weight, you need to multiply the emission probabilities together. Each ghost will also have its own jail cell. If a ghost is in a jail cell, then its emission probability becomes 1 for the jail location.

In the previous cases, a ghost had legal positions which you used to pick uniformly distributed particles. In the DBN case, this gets slightly tricky. Think carefully about what you need to pick from. We will give a small example without explaining it:

Let {(1,3),(2,2),(2,3)} be a list of legal positions. Assuming that two ghosts cannot be in the same position, you need to pick from {[(1,3)(2,2)],[(1,3)(2,3)],[(2,2)(1,3)],[(2,2)(2,3)],[(2,3)(1,3)],[(2,3)(2,2)]}.

Note that the observations for the DBN part is multi-dimensional, based on the number of ghosts.

Getting the unhashable type error If you get an unhashable type error, go and look at the way you represent your particles. In Python, lists are not hashable (since they are mutable) but tuples are (since they are immutable).

Part 2: Report

This part includes answering the following questions based on your program’s output on the given pacman tests. You are expected to answer the questions concisely. Five sentences is more than enough for most of them. Limit yourself to 300 words. It is okay if you over-generalize, as long as your direction is clear and correct.

Create a PDF file named report.pdf containing your answers for submission. Write your name and your number on the report as well!

Written Q1:

Run the autograder on Q3 and watch the probabilities. Why do they settle even though the ghost is moving? Can you tell the two ghosts apart and if so how? (Hint: Run these test cases q3/1-ExactPredict, q3/2-ExactPredict, if you need to observe them individually)

Written Q2:

Try the following lines of code and watch the probabilities settle:

python autograder.py -t test cases/q2/2-ExactUpdate python autograder.py -t test cases/q2/3-ExactUpdate

Why is it the case that in one of them we can find the ghost but not in the other one?

Written Q3:

Run the autograder on q6 for the 5th and the 6th test case and watch the probabilities. Can you tell when the particles get re-initialized? Comment on the reason(s) on why pacman gets in that situation?

Would increasing the number of particles be a solution?

Written Q4:

Compare how the probabilities evolve between the exact inference and the approximate inference cases (Q2, Q32 vs Q5, Q6). Also comment on if 5000 particles make sense for the problems you have seen.

Written Q5:

In the DBN questions (Q8-Q10), you had to work on a particle that had multiple ghost positions. Their transitions were dependent on each other but their emissions were not. How did you create a new particle with elapsed time and how did you calculate its weight? You can use mathematical equations to help you explain this.

Submission

You are going to submit a compressed archive through the blackboard site. This file should only contain report.pdf, bustersAgents.py and inference.py. Make sure you put your name and ID inside the report as well. Other files will be deleted and/or overwritten. Do not submit any code if you only want us to grade your report.

Submission Instructions

You are fine as long as the compressed archive has the required files within 4 folder levels.

Once you are sure about your assignment and the compressed file, submit it through Blackboard. Do not submit code that does not terminate or that blows up the memory.

Important: Download your submission to make sure it is not corrupted and it has your latest report/code. You are only going to be graded by your blackboard submission.

Best of luck and happy coding!
