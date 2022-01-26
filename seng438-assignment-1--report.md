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

1. [Introduction](#introduction)

2. [High-level description of the exploratory testing plan](#high-level-description-of-the-exploratory-testing-plan)

3. [Comparison of exploratory and manual functional testing](#comparison-of-exploratory-and-manual-functional-testing)

4. [Notes and discussion of the peer reviews of defect reports](#notes-and-discussion-of-the-peer-reviews-of-defect-reports)

5. [How the pair testing was managed and team work/effort was divided](#how-the-pair-testing-was-managed-and-team-workeffort-was-divided)

6. [Difficulties encountered, challenges overcome, and lessons learned](#difficulties-encountered-challenges-overcome-and-lessons-learned)

7. [Comments/feedback on the lab and lab document itself](#commentsfeedback-on-the-lab-and-lab-document-itself)

# Introduction

We have done unit testing previously in a previous class. We also have done some "exploratory testing" (although we didn't know that this is what we were doing) while building personal projects. Other than that, we had some understanding of manual testing from the course lectures but no real experience.


# High-level description of the exploratory testing plan

We want to test the system as if we were a user, we will test all features generally to make sure that the system functions well as a whole.  Therefore, we want to test the most common paths. We will focus on functionalities such as depositing and withdrawing to specific accounts. We want our system to work for the greatest number of users. While also ensuring no large bugs exist when working with depositing/withdrawing money as that may be very stressful for a user.

# Comparison of exploratory and manual functional testing

Manual testing is useful for testing key functionalities, ensuring the proper due diligence has been taken to make sure everything works as intended. Exploratory testing is an ad hoc form of testing which may highlight issues that aren't initially apparent. For example, two separate functions may work as intended, and work independently, but may break when used consecutively. This issue would be far more likely to be found when doing exploratory testing. Exploratory testing is more creative, we were trying to think of ways to break the system and because of this we were able to test use cases that would be less used. Both methods play different roles and are best when used in conjunction.

# Notes and discussion of the peer reviews of defect reports

Working in pairs was beneficial as during the exploratory testing many of the bugs both groups found were different from those of the other groups. We were able to find more bugs in this way than we would have working as a group of four. Peer reviewing of bug reports was also helpful in the sense that some potential bugs found may have been features. For example, all three of the account types were shown on the pages even if the user didn't have an account of some type. One team thought this might be a bug as it allowed the user to select it and select a withdrawal amount before being notified that the account type was invalid. However, the other team thought this was an intended feature. So, peer reviewing of bug reports brought up the discussion and helped up resolve issues such as this.

# How the pair testing was managed and team work/effort was divided 

We split into two pairs, and then took turns with one person operating the system and the other reporting defects. Switching roles once we went from the exploratory section to the manual one.

# Difficulties encountered, challenges overcome, and lessons learned

We had some initial difficulties understanding the backlog system. It would appear that the project version feature has been removed, so we just included the version in the title.

# Comments/feedback on the lab and lab document itself

This was an interesting lab as using a website like backlog would be something that we will probably encounter when working in the real world. It was fun to work in pairs finding bugs in this system, though there seemed to be a lot. Additionally, there seemed to be some ambiguity on if the group worked in pairs for certain testing phases.
