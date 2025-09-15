# FOSSEE-Python-Task-2
Python Task 2 for FOSSEE Semester Long Internship - Autumn 2025

AI Debugging prompt for students in Python - Python Task 2

- Please find the prompt in the file named `prompt.md` in this Repository.

# Reasoning

1. Tone and Style
The AI should use a supportive, patient, and encouraging tone—like a helpful tutor. Its style should be conversational and curious, using questions to spark the student’s own thinking rather than lecturing or giving away answers.


2. Balancing Identifying Bugs and Guiding
The AI should point out potential problem areas in the code (like variables, conditions, or loops) but stop short of saying exactly what to change. For each issue, it should follow up with a guiding question that pushes the student to reflect and test their own assumptions. This balance helps students know where to look without being spoon-fed fixes.


3. Adapting for Different Learners

	Beginners: Use simple language and break down hints into small, direct questions (e.g., “What value does this variable hold before the loop starts?”). Keep the focus on building confidence and core debugging habits.

	Advanced learners: Use more abstract and strategic questions, such as edge-case prompts (“How would this behave with an empty list?”) or process-oriented prompts (“Why do you think the function isn’t returning the expected value?”). This approach sharpens their debugging strategies and critical thinking rather than just their syntax.


# Design Choices

1. Why I worded it the way I did
   I used simple but precise instructions like “highlight areas that could be causing problems” and “use subtle hints and reverse questions.” This wording makes it clear that the AI’s role is to guide, not solve. The emphasis on student thinking and critical computational skills ensures the focus stays on learning, not quick fixes.

2. How I ensured it avoids giving the solution
	I explicitly told the AI to avoid direct fixes or complete solutions. By requiring subtle hints and guiding questions, the AI is steered toward coaching behavior instead of code correction. This forces the student to do the reasoning and prevents the AI from short-circuiting the learning process.

3. How it encourages helpful, student-friendly feedback
	The instruction to keep the tone supportive and student-friendly ensures responses feel approachable rather than critical. By asking reverse questions (like “What happens if this condition is false?”), the AI nudges students to reflect and debug independently, which builds confidence and strengthens problem-solving skills.

