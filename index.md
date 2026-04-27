---
# Do not edit the text between these lines!
layout: default
---

# EX09 Analysis Presentation Website!


## Analysis on Idea #1 - Requiring Office Hours for COMP110

This website is the final presentation site for the EX09 Continuous Analysis Assignment for COMP 110. 
This site includes the final analysis of our first idea, regarding whether or not students will benefit
from requiring that COMP 110 students attend one office hour appointment per semester. This could help
students prepare for quizzes, assignments, and the final. We will measure this through oh_effective and qz_effective.
You can find our analysis and visualizations down below!

## Summary of Our Analysis on Current Office Hour Effectiveness

To evaluate the effectiveness of office hours in COMP110, we analyzed survey data collected from students in the Spring 2026 semester, and focused on responses related to office hours attendance (oh_visits), perceived effectiveness of office hours (oh_effective), and overall understanding of course material (understanding). The data was first read from a CSV file and transformed into a column-based format using utility functions.

Both descriptive statistics and data visualization techniques were used to explore the relationships between these variables. We used the count function to understand how frequently students attend office hours, while Seaborn visualizations, which included count plots, scatterplots, and boxplots, were used to examine patterns between office hours attendance, student understanding, and perceived effectiveness.

Overall, our analysis aimed to identify whether increased attendance at office hours is associated with improved learning outcomes and greater perceived value, providing insight into how office hours currently support student success.

## Visualizations Through Seaborn

<img width="623" height="473" alt="Screenshot 2026-04-26 at 11 44 29 PM" src="https://github.com/user-attachments/assets/7b2059d7-f9d7-4ada-85c5-211a78e84da8" />

<img width="611" height="476" alt="Screenshot 2026-04-26 at 11 44 42 PM" src="https://github.com/user-attachments/assets/384e5b5e-e2d0-469a-a044-f6c5595da06a" />

<img width="624" height="474" alt="Screenshot 2026-04-26 at 11 44 52 PM" src="https://github.com/user-attachments/assets/b2163a53-1dcc-451f-898b-40f7ea406ca0" />

<img width="627" height="488" alt="Screenshot 2026-04-26 at 11 45 00 PM" src="https://github.com/user-attachments/assets/183f66cf-18e6-4da8-88d4-835a8788d00c" />

## Final Conclusion of Analysis

Through our analysis and visualizations, we found that our results did not fully support our idea that requiring one office hour visit will increase quiz performance and overall content understand because our results were inconclusive. Without further research, we cannot conclude that going to office hours more frequently increases student understanding of the COMP 110 content. With our visualizations, 7 meant an extremely high level of understanding, and 1 meant a very low level of understanding. From our visualizations, they actually showed that student understanding decreased as office hour visits increased from the survey data. With the students' perceived levels of their understanding, the mean understanding level was very similar throughout the amount of office hours attended, staying at approximately an understanding level of 4-5. Our analysis also showed that over 100 students only attended office hours once, and less then 20 students attended more than three times. This shows how skewed the distribution was throughout the dataset, which shows that we did not capture an even sample or distribution of office hour attendance.

Additional data collection would definitely help build our confidence in assessing our idea. It would be helpful to survey a more even sample population of COMP 110 students, getting a similar number of students who attend office hours frequently and students who do not attend frequently. It would also be helpful to survey students who have already finished a full semester of COMP 110 so we can get accurate numbers based on their understanding and office hour attendance from an entire semester. This survey was taken by students currently enrolled in COMP 110 when the semester was not over, which means their attendance records and understanding could have changed. It would also be helpful to go more in depth about what understanding means to students, as the perceived student understanding data point would be very helpful in determining how students respond to office hours. We could separate understanding into different topics, such as magic methods, memory diagrams, class writing, recursive functions, etc. It would also be helpful to do observational research, such as watching students complete exercises and quizzes, as students can lie on surveys.

The stakeholders that could be negatively impacted by this data collection are students who do not enjoy going to office hours, students who are not free during office hours times, and the TAs and professors who help students during office hours. If office hours were found to be benifical for student understanding through further research, every COMP 110 student would be required to attend one office hour. If more students were incentivized to attend office hours with grade motivation, the COMP TAs and professors would get way busier. This would cause additional stress and dread for them, as they are already handling their own academic responsibilities and commitments. In turn, this could negatively affect the students because they would get less time with the TAs, and the TAs would most likely be stressed, overwhelmed, or upset while they were attempting to help students. Students who do not find office hours beneficial would also struggle with this because they would have to spend their time going to something that does not benefit them, or their grade would be negatively affected. Students who are not available during office hour times would also be hurt by this as their grade would go down if they could not find a way to attend office hours. To avoid these situations, professors should offer alternative assignments for those who do not benefit from office hours, or those who cannot go.

## Thank you for learning about our research!
