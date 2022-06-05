# Impacts on Society

I teach AP Computer Science Principles (APCSP) to 9th through 12th graders. It is an introductory level course meant to be a broad introduction to computer science. The impact of computing on society is a major theme of the course. In this document, I will describe how I teach and assess these ideas in my course.

## Plan



### Learning Objectives

APCSP is organized around 5 big ideas. Big Idea #5 is the Impact of Computing. The College Board describes this Big Idea as follows in the course description:
"You’ll examine the effects computing has had on societies, economies, and cultures and consider the legal and ethical responsibilities of programmers."
The three recommended/assessed concepts that fall under the umbrella of this big idea are:
<ol>
<li>The digital divide</li>
<li>Computing bias</li>
<li>Safe computing</li>
</ol>
The learning objectives for this unit require students to:
-Recognize/Discuss/Describe both the beneficial and harmful impacts of technological innovations 
-Interpret articles and videos about computing innovations that have been shown to represent algorithmic bias
-Compare and contrast access to and use of technology across generational, socioeconomic, and geographic boundaries
-Judge the impact and effectiveness of computing innovations that use big data and identity-based technologies
-Create a program that generates random passwords

### Learning Activities

To study the digital divide, we first have an informal conversation about student use of and access to technological devices and the internet at home. After the class baseline is established, students are tasked with choosing one article from the following website:
https://www.pewresearch.org/topic/internet-technology/technology-policy-issues/digital-divide/?_time_since=past-12-months
We jigsaw these articles with each group presenting a summary of the article they read and discussed in small groups to the entire class as we aim to describe what the digital divide is and what factors play a role in its persistence.

In order to teach computing bias, we watch & discuss two videos -- 
https://www.media.mit.edu/posts/how-i-m-fighting-bias-in-algorithms/ Joy Buolamwini's work on algorithmic bias in facial recognition software revealed it does a poorer job of identifying female, dark-skinned faces
https://www.youtube.com/watch?v=Ok5sKLXqynQ An episode of "Glad You Asked" that investigates Twitter's auto-cropping algorithm which consistently preferenced white faces over non-white faces
Next, on code.org, students train an AI machine to identify fish vs trash, then fish with certain "objective" attributes (color, shape, size), then finally fish with more subjective attribues ("scary", "weird", "funny" fish). Through these simulations, students confront two fundamental truths:
1) The bigger the dataset used to train a machine, the better it gets at identifying things accurately
2) Bias is part of human decision-making, so it easily becomes part of the way we train machines
While the implication of this bias in algorithms seems trivial with the fish exercise, it takes on a more serious tone when I ask the students to participate in the MIT Moral Machine simulations https://www.moralmachine.net/
This activity asks students to train a self-driving car to decide which outcome to choose when an accident involving fatalities is unavoidable. 
Finally students have to write to respond to a number of prompts about ethics and bias in algorithms, and what their ideas are for navigating this in the future as machine-learning algorithms become more and more prolific.

To study safe computing, we learn a bit about hacking, cybersecurity, encryption, two-factor authentication, and the importance of a good password. Students learn about these concepts through a series of videos and activities on code.org. THey get to tinker with a ceasar-cipher widget and a random-assignment cipher and attempt to decode an encrypted message by looking for patterns in the use of certain characters. The culminating project for this part of the unit is to code a password generator that uses at least three rules (numbers, capital letters, special characters, or short words to be included/required) and generates a random password.


### Assessment

To asssess student understanding of the digital divide, I ask them to write a paragraph about how they can reduce the digital divide through their own action and advocacy. The goal is to get them thinking about their privleged role as citizens who are computer-literate and fortunate enough to have conistent access to broadband internet and fast, reliable devices. Asking them to reflect on how they can make a difference in narrowing the digital divide allows them to relize they can play a role in solving this problem, not just learning about it.

I assess the algorithmic bias standards by asking students to write and eflect once again on the pitfals of training machines to make decisions when we as humans are inherently biased, and how they might combat those biases just getting repeated or amplified in the form of wide-ranging algorithms.

The assessment of safe-computing happens primarily throught the password-generator programming project, however there are brief reflection questions at the end of each lesson in the code.org unit I use as my curriculum that students must answer. 

### Outcomes

One of the things I do in my course to help faciltate diversity and inclusion in CS is to show many of the code.org videos which highlight women in tech and people of color in technology introducing topics through mini-lesson videos. I also try to introduce students to videos and thought leaders in the field who are female and women of color or who are bringing to light issues of equity, inclusion, and diversity. 
More broadly, my hope is that teaching AP CSP with a strong emphasis on the imapcts computing has on society will encourage students from different backgrounds and races realize that the field of CS needs them in order to develop, vet, research and revise technology tools that reflect their best interests and do more good than harm. 
Some of my students this year who were new to CS said they found our dicsussions on these topics more interesting and compelling than actually learning how to code. I think as tech companies evolve, more and more of them will need to create roles specifically for people to help ensure the tools they are creating are not just scaling up the biases and errors of the past, but are actively working to counter societal biases that may lead to unintended harms. As more and more students take this course and delve into these ideas, I believe there will be more awareness of an interest in holding the developers of tech tools accountable for assessing the ethical and societal impacts their tools can have
