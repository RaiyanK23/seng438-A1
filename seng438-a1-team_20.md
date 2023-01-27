>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: 20      |
|-----------------|
| Mohammed Kabir               |   
| Jacob Adeyemo              |   
| Markosch Saure              |   
| Kundai Dziwa               |   


**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

Assignment 1 involves having group members go through a program which involves an Automated Teller Machine (ATM) and
receiving a list of instructions by which we run this program. Each group is instructed to run a series of exploratory,
manual and regression testing, and then compile a list of bug defects followed by a formal lab report. 

Exploratory testing is a form of test-case design. It is the testing process by which we (humans) design test values
based on domain knowledge as well as general human knowledge of testing. In our case, we use Appendix B to gain knowledge
about the specific requirements of the program and compile a list of tests based on that.

Manual functional testing is also a form of test-case design. It is the testing process by which test values are designed
to cover and satisfy coverage criteria or a specific engineering goal. In our case, Appendix C provides specific values
and criteria through which we should be testing our system.

Lastly, regression testing is a form of testing done to check that updates that were made in response to bug defects
do not reintroduce faults that were correct prior to the fix. This type of testing is most often done after all fixes
are made to bugs (when code is checked in to the repository).

# High-level description of the exploratory testing plan

Our exploratory testing plan involves looking at each of the major functional components
of the ATM and going through a case-by-case basis of testing. Examples of these functionalities:

1. Start/Off of the ATM
2. Inputting a card into the ATM + validation process
3. Entering the amount of $20 bills requested
4. Inserting the card, and trying out different pins.
5. Transactions (deposit, withdraw, transfer) 

The approach that we are adopting is to isolate a specific functionality of the program (i.e entering card + verification)
and then create test cases and extensively test. We are looking to put more weight/emphasis on areas and functionalities
of the program that we believe are more prone to bugs (such as functionalities that require more input vs others that require
less input) rather than going chronological. 

We are using Appendix B that we received as part of our lab documents as our oracle for exploratory testing, and the basis of our test cases. The oracle tells us expected outcomes that we know as truths, therefore we will try test cases of equivalent classes and boundary/edge conditions. Equivalent classes being inputs that fall in similar ranges and boundaries are conditions which are specifically targeted and fall on the "boundary" of our test inputs. 


# Comparison of exploratory and manual functional testing

Exploratory testing is beneficial when it comes to more "obvious" test cases, as in we can approach this as the user of the
system and more easily pin down functionality that has a greater or more meaningful impact on the overall system itself. To
contrast, manual testing is excellent at breaking down every part of the system into components and extensively testing based on the given test suites. Where in exploratory testing we may be able to better test the obvious functionality and target bigger impact areas, manual testing can take those bigger functionalities and break them down and see if there are any edge cases we missed.

Exploratory testing trades extensive testing for quicker and more domain-based knowlegde testing. It is relatively quicker but
may not catch boundary conditions as effectively. Manual testing on the other hand trades quick testing for a much rigorous testing process with a large test suite. While it is much more effective at finding bugs/defects, it takes significantly more resources (time) in order to perform the manual tests.

As an example, in our 30-minute exploratory testing phase, we targeted high-impact functionality such as the login, though we did not rigorously test the start-up/shut-down of the system itself since the ATM was behaving normally for equivalent classes but we did not search for boundary conditions. Whereas in manual testing, the test suite has 4 test cases that specifically target the start up and shut down processes.

From running both exploratory and manual functional testing, we conclude that exploratory testing is efficient time-wise but not nearly as effective at finding and or targeting a wide array of defects. Likewise manual testing is very effective at finding defects but is not as time efficient as exploratory testing and requires more resources.

# Notes and discussion of the peer reviews of defect reports

Peer reviews were an excellent way to see the results of our functional testing. Reviewing bug reports made by someone else offers more context into the specifics of the bug (what function, repro steps, etc.). Peer reviewing the defect reports is also a great way to make fixes to perhaps incorrect summaries and or procedures in the bug ticket. 

Our group acknowledges that having a peer review of bug reports that we create is essential for all members of the group to be on the same page but to also catch any small mistakes that maybe were made when the bug ticket was created.

Pair reviews also allowed each of the pairs to compare and contrast our results and point out any inconsistencies (if there were any) and then proceed to compile/combine both of them into one cummulative review.

# How the pair testing was managed and team work/effort was divided 

Text…

# Difficulties encountered, challenges overcome, and lessons learned

Text…

# Comments/feedback on the lab and lab document itself

Text…