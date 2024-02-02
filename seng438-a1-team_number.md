>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: Group Number      |
|-----------------|
| Student 1 name    Ella Boulanger            |   
| Student 2 name    Kenzie Fjestad          |   
| Student 3 name    Raina Jugdev           |   
| Student 4 name    Dominico Mendes            |   


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

In this lab, we have developed our understanding of software testing by testing the given ATM system. Our goal is to test the system in 3 parts being exploratory testing, scripted testing, and regression testing. Prior to the lab, we knew from lecture that exploratory testing meant navigating the system without proper test cases to find bugs. This meant that We also knew that manual functional testing meant following a set of test cases to find bugs within the system.

# High-level description of the exploratory testing plan

Text…

# Comparison of exploratory and manual functional testing

Our team definitely had different experiences when completing exploratory testing and scripted testing. The process of exploratory testing took more time overall due to having to analyze all the requirements and attempt to come up with the best approach to test each requirement. Even with a testing plan in place the nature of exploratory testing often means more routes that tend to be longer as we attempted to create unique paths that may confuse the system and make a bug known. We found exploratory testing to be effective in finding more hidden bugs that may have come from developers not considering all the small details in the system design. The main frustration we had throughout exploratory testing was that the nature of the testing process made duplicate bugs a common occurrence due to multiple paths leading to the discovery of the same bug. The added step of parsing through all detected bugs to remove duplicates made this process even more inefficient. The process of scripted testing was a more straightforward and simple process. With the given test suite, each required functionality was named along with steps to guide you to the appropriate point in the system to test the targeted functionality. As a team we found this step in the testing process to be extremely efficient, pre-made test cases allowed us to easily split up the tasks to be done and complete them individually. We felt the effectiveness of this testing type was decently high due to the requirement targeted tests that were easily divisible within our team. High efficiency made us feel as though this approach must be the most effective, however there would still be bugs that weren’t caught using this testing approach alone due to its simplicity. So often bugs come up when non-traditional paths are taken within a system, perhaps developers never considered a user would do this and therefore did not plan to address those possible problems throughout development. This is a case where a more fluid and exploratory route would be more effective. Through this lab the use of both exploratory and scripted testing was proven to be important for different reasons, each testing process has its own benefits as well as its own drawbacks, as discussed above. While doing this reflection of direct comparison it became clear that these approaches when paired solve each other's main problems, exploratory testing can pick up bugs missed in scripted testing and vice versa. Now having experience with these different types of testing processes it is evident how multiple testing approaches are necessary when it comes to ensuring a well rounded test plan and execution. 

# Notes and discussion of the peer reviews of defect reports

After each pair of the group concluded with the exploratory plan, we observed that both pairs had come up with the same defects for the system. Each defect was also encountered using similiar steps. This was becuase of how our exploratory testing plan was set up. We were able to target all the general funcrions which allowed for finding a similiar and fair amount of bugs in the system. Although, each pair described the defects differently and grouped defects differently as well. Before reporting the bugs in Jira, we discussed on how we wanted to report them. Since there were two valid cards, we were stuck between creating similiar bugs for each card, or grouping the bug into one for both cards. When reporting the bugs, we decided on a mix of this. Some bugs such as withdraw, deposit, and transfer were consistent across cards in terms of what the bug did and how to replicate it. For these bugs we just made one bug report where we described the steps to replicate it for both cards. For other bugs such as balance inquiry, although each card had an error with the functionality of this feature, the actual difference was too drastic to say they were similiar to each other. Due to this, we decided on creating seperate bug reports for each card for this function.

# How the pair testing was managed and team work/effort was divided 

The pair testing was managed by splitting our team into two sub groups of two members each. One person would execute tests on the SUT, while the other observed and analyzed the outcome. Conducting tests using this strategy allowed us to evenly divide the work, and made testing itself more manageable. Within the pairs we switched roles so that each person had the chance to interact with the SUT as well as observe the process. We managed the scripted testing by dividing the test suite evenly amongst our team and completing each test individually. Doing this accounted for any possible overlap of our work. We recorded the bugs we found in our Jira board to track what tests were completed. Our regression testing was divided similarly, and any previous bugs we found individually, we retested. Our effort was divided evenly, and every member had the chance to become familiar with the system under test and the technique of pair testing.

# Difficulties encountered, challenges overcome, and lessons learned

Our team faced some difficulties when conducting tests on this system. When working on the exploratory testing, it took a lot of time to become familiar with the system and be thorough enough when looking for bugs. It was difficult to not get carried away when finding bugs, and to properly follow our testing plan when reporting them. We had to focus on the organization of our bug reports when testing the system. At times it was difficult to not lose track of the state of the system during a test. We all found that when doing the scripted testing, it was sometimes hard to differentiate between bugs and not accurately remembering the state of the accounts. This took time to adjust to, and filling out the bug report while executing the bug was the most effective way to avoid this. Another issue we ran into was keeping track of what bugs were the same between the two cards and which differed. This caused confusion when testing as we had to check both cards to be as thorough as possible. Another learning curve was becoming familiar with the Jira software as none of us had worked with a testing software before. After adjusting to the process of executing a test and filling out a bug report, this was more manageable and helped us stay on top of the bugs through the bug reports.

A lesson we learnt from testing the system is that organization is key when detecting bugs. It was necessary to keep the bug reports organized, and stay on track when performing the pair testing. Working as pairs taught us to communicate with each other and maintain a synchronized pace when testing. This was essential to the proper recording of bugs as both people had to be on the same page when a bug was found, otherwise it could be temporarily lost. The lessons learnt from this lab provided us with many new techniques to use when testing our code.


# Comments/feedback on the lab and lab document itself

This lab was a great introduction to the process of testing a system and using a testing suite for a SUT. The instructions were moderately simple to follow, with only a few things causing confusion. Some feedback on the structure of this lab would be to provide us with a more in depth introduction to the Jira software, as our team was not familiar with it prior to the lab. Without a complete understanding of how to report the bugs or how to organize our tables, we had some trouble setting up our board. A demo or a bit more information of the organization of our reports would have come in handy when we were just starting out. Some minor feedback on the document format would be that it is hard to follow the instructions in the layout of a long section of text. This is not at all a big issue, it is just often more readable in a PDF style document.
