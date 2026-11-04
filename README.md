# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To design, execute and evaluate different prompting techniques by progressively improving prompts from basic instructions to structured prompts for analyzing and summarizing student attendance and academic performance using AI platforms.

## Scenario:
In educational institutions, teachers need to monitor students' attendance and academic performance regularly. Checking attendance records and test scores manually can take time, especially when handling a large number of students.
An AI-Based Student Attendance and Performance Analysis System helps teachers analyze student records and generate meaningful summaries. It processes attendance percentages, internal assessment marks and academic progress to identify students who may need additional academic support.
This experiment uses different prompting techniques to generate clear, concise and meaningful summaries of student academic records.

## Sample Student Academic Performance Report

A second-year Computer Science and Engineering student has an attendance percentage of 78%. As per the college attendance rules, students must maintain more than 80% attendance to be eligible for examinations.

His internal assessment marks in different subjects are given below:
Subject	Internal Marks
Python Programming	85/100
Computer Networks	72/100
Database Management Systems	90/100
Mathematics	65/100

The student performs well in Database Management Systems  but needs improvement in Mathematics and Computer Networks.

His attendance percentage is below the required college limit. Therefore, he is currently not eligible for examinations based on the stated attendance rule. Teachers are advised to monitor his attendance and provide additional academic support in subjects where improvement is needed.

# PROMPTING TECHNIQUES USED

# 1.Basic Prompt
**Prompt:**
Analyze the following student academic performance report and provide a short summary.

Report :
 Give the academic performance report

**Sample Output:**
A second-year Computer Science and Engineering student. His attendance is 78%, which is below the college requirement of above 80%. He performs well in Database Management Systems and Python Programming but needs improvement in Mathematics and Computer Networks.

# 2.Role Prompt
**Prompt:**
Act as an experienced college academic advisor. Analyze the student's attendance and internal marks. Identify the student's academic strengths, weak subjects and attendance eligibility. Provide suggestions for improvement.
**Sample Output:**
As an academic advisor, I observe that the student has performed well in Database Management Systems (90). He needs to improve Mathematics (65) and Computer Networks (72). His attendance is 78%, which is below the required level of above 80%. He should improve his attendance and focus more on the subjects where his marks are low.
# 3. Context Prompt
**Prompt:**
A second-year Computer Science and Engineering student named Arun has an attendance percentage of 78%. His college requires students to maintain attendance above 80% to be eligible for examinations. His internal marks are Python Programming – 85, Computer Networks – 72, Database Management Systems – 90, Mathematics – 65 and Operating Systems – 80.

Based on this information, analyze his academic performance and explain his attendance status.
**Sample Output:**
The student's academic performance is good in Python Programming and Database Management Systems. His performance in Mathematics and Computer Networks needs improvement. His attendance is 78%, which is below the college requirement of above 80%. Therefore, he does not currently meet the attendance requirement for examination eligibility.

# 4. Constraint Prompt
**Prompt:**
Analyze the student's academic performance using the given report. Follow these conditions:
- Use simple English.
- Write the summary in 100 words or less.
- Mention the attendance percentage and college requirement.
- Identify the highest-scoring and lowest-scoring subjects.
- Do not provide information that is not included in the report.

**Sample Output:**
The second-year CSE student has 78% attendance. His college requires attendance above 80%, so he currently does not meet the attendance requirement. His highest mark is 90 in Database Management Systems, followed by 85 in Python Programming. His lowest mark is 65 in Mathematics. He should focus on improving Mathematics and Computer Networks and work towards meeting the attendance requirement.

# 5. Output Format Prompt

**Prompt:**
Analyze the student's attendance and academic performance. Present the result using the following format:
1. Student Name
2. Department and Year
3. Attendance Status
4. Highest-Scoring Subject
5. Lowest-Scoring Subject
6. Academic Strengths
7. Areas for Improvement
8. Suggestions
Use bullet points wherever appropriate.
**Sample Output:**
Student Name: Arun
Department: Computer Science and Engineering
Year: Second Year
Attendance Status: 78% – Does not meet the required attendance level.
Academic Strengths: Good performance in DBMS and Python.
Weak Subjects: Mathematics and Computer Networks.
Suggestions: Improve attendance and practice weaker subjects regularly.

# Comparison of prompting techniques

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/804288f0-7194-4ee1-92df-a532d4811c57" />

# Evaluation Criteria

1. Accuracy: Checks whether the AI provides correct information about student attendance, marks and academic performance.

2. Coherence: Evaluates whether the summary is logically organized, clear and easy to understand.

3. Simplicity: Checks whether the summary uses simple language that college students can easily understand.

4. Speed: Measures how quickly the AI platform generates the summary.

5. User Experience: Evaluates how easy and convenient the platform is to use, including the clarity and presentation of its response.

# Overall findings

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/3e782e34-b77c-4499-9db9-fec37eace7a9" />

# Conclusion

The comparison shows that Context-Based, Constraint-Based, and Output Format Prompting techniques provide better results in terms of accuracy, clarity, relevance, and structured output. Combining these techniques produces more effective and reliable responses for the AI-Based Student Attendance and Performance Analysis System.

## Result

The experiment successfully demonstrates the design and progressive improvement of five prompting techniques for an AI-Based Student Attendance and Performance Analysis System.

The prompts were developed from basic instructions to more detailed and structured instructions. The results show that providing a clear role, relevant student information, specific college attendance rules, and a predefined output format can improve the accuracy, relevance, clarity, and usefulness of AI-generated student performance analysis.
