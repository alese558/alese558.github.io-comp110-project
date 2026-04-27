---
# Do not edit the text between these lines!
layout: default
---

# Analysis: Why we Should Implement a Uniform Note Document
**By Alex Sevilla**

## 1. Project Overview
In this analysis, I explore the relationship between student study habits—specifically the frequency of taking personal notes—and the perceived difficulty of the course. The goal is to determine if providing a "uniform notes document" would create value for students.

## 2. The Idea
The course should provide a uniform notes document for every lecture because it will reduce the workload for students who are currently struggling with complex material on their own. This change would primarily benefit students who find the material challenging and would come at the cost of the instructors who have to implement the document.

---

## 3. Data Analysis
To analyze this, I used a custom function named "classify" and also utilized other functions to simplify the data and place it into a single table.

* **Data Presentation:** I utilized the selection and head functions in order to choose the specific data columns I needed and preview only the first set of rows.
* **Categorization:** I used a custom `classify` function to group raw 1-7 scores into three buckets: `Never` (1-2), `Sometimes` (3-5), and `Always` (6-7).
* **Selection:** I isolated the `own_notes` and `course_difficulty` columns to focus specifically on the correlation between student note taking and course difficulty.

---

## 4. Visual Analysis

### Distribution of Note-Taking Habits
The first visual I created was a simple bar graph to visualize the frequency of each students note taking in the class. This allows me to get a general idea of how many students are taking notes in the class.

<img width="581" height="463" alt="image" src="https://github.com/user-attachments/assets/46019c87-4b95-46f5-8e9b-ca523df10d67" />)

This image shows that a large portion of the students are in the "Always" bucket of the data. This means that most students are either taking notes sometimes or most of the time, proving that this notes document would impact a large portion of the population.

### Course Difficulty vs. Note-Taking Correlation
Next I used a point plot and a boxplot. These graphs shows the average reported difficulty at each level of note taking. This allows us to see the distribution of how students feel about the course based of if they take notes or not. Now I can visualize if students find taking their own notes helpful which allows me to conclude whether or not a uniform notes document is needed. 

<img width="562" height="463" alt="image" src="https://github.com/user-attachments/assets/1ff2fad0-ae8f-4424-86d5-e84b2507f9ed" />

<img width="577" height="463" alt="image" src="https://github.com/user-attachments/assets/5f619149-4988-4ede-8c2e-4775a6247e85" />

The data shows that students who take notes 'Always' actually report higher course difficulty than those who 'Never' do. This suggests that the current self-note-taking process is contributing to the difficulty of the course. 

---

## 5. Conclusion & Recommendations

### Summary of Findings

The data analysis does not support my idea of implementing a uniform note document for students. The point ploy shows a clear positive correlation where as students take more notes, the average reported course difficulty increases. This does not support the initial assumption that note-taking leads to lower reported course difficulty. If more notetaking results in students feeling that the course is harder, then we can assume that a uniform notes document would not be benefitial. 

Despite the analysis not supporting my idea, I still think that a uniform notes document would be a benefitial change to the course. While it is true that the data suggests self note taking is not benefitial in reducing course difficulty, this could simply be due to students who are struggling with content being more likely to take notes than ones that are confident. Additionally, if students who find themselves taking more notes are reporting a higher class difficulty, providing them with a more uniform notes document might lead to allowing them more time to digest the material. 

Potential costs of implementing this document is that it burdens the instructor with more work. Another cost is that there is percieved benefits in students writing their own notes which are discourged if there is already a notes document. Students may also become over-reliant on the document which takes away from their personalized learning. While these are valid concerns, I believe that this uniform document is still valuable to the course as it provides students with an outline of material they are responsible for and it allows students to focus on understanding the content instead of merely writing down what is being said. 
