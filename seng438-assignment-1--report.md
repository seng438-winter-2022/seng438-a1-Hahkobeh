>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#:       | 5                |
|-----------------|------------------|
| Student Names:  | Jacob Artuso     |
|                 | Brian Kramer     |
|                 | Colin Christophe |
|                 | Nicholas Knapton |

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

We have done unit testing previously in a previous class. We also have done some "exploratory testing" (although we didn't know that this is what we were doing) while building personal projects. Other than that we had some understanding of manual testing from the course lectures but no real experience.


# High-level description of the exploratory testing plan

We want to test the system as if we were a user, we will test all features generally in order to 
make sure that the system functions well as a whole.  Therefore, we want to test the most common paths. 
We will focus on functionalities such as depositing and withdrawing to specific accounts. We want our 
system to work for the most amount of users. While also ensuring no large bugs exist when working 
with depositing/withdrawing money as that may be very stressful for a user.

# Comparison of exploratory and manual functional testing

Manual testing is useful for testing key functionalities, ensuring the proper due diligence has been taken to make sure everything works as intended.
Exploratory testing is an ad hoc form of testing which may highlight issues that aren't initially apparent. For example, two separate functions may work as intended, and work independently, but may break 
when used consecutively. This issue would be far more likely to be found when doing exploratory testing. Both methods play different roles and are best when used in conjunction.

# Notes and discussion of the peer reviews of defect reports
Some of the bug reports created by one pair were bugs that the other pair missed, and vice versa. So pairs doing separate testing, and test reviews was definitely useful for finding issues. Peer reviewing of bug reports was also helpful in the sense that some of the "bugs" found may be up for debate if they were actually bugs or not. For example all the account types were shown on the withdrawal and transfer pages even if the user did not have for say a money market account. One team thought this might be a bug as it allowed the user to select it and select a withdrawal amount before telling them it was an invalid account type. However, the other pair thought this wasn't a bug and just part of the design of the system. So peer reviewing of bug reports brought up the discussion and helped resolve issues such as this.


# How the pair testing was managed and team work/effort was divided 

We split into two pairs, and then took turns with one person operating the system and the other reporting defects. Switching roles once we went from the exploratory section to the manual one.

# Difficulties encountered, challenges overcome, and lessons learned

We had some initial difficulties understanding the backlog system. It would appear that the project version feature has been removed, so we just included the version in the title.

# Comments/feedback on the lab and lab document itself

This was an interesting lab as using a website like backlog would be something that we will probably encounter when actually working in the real world. It was fun to work in pairs finding bugs in this system, though there seemed to be a lot. Additionally there seemed to be some abiguity on if the group worked in pairs for certain testing phases. 
