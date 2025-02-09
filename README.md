# Homework on "Fundamentals of Parallel Computing and the MapReduce Model"

Welcome! 🧠

In modern IT, processing large volumes of data requires efficient and fast methods. Your task is to write a **Python script** that applies the **MapReduce paradigm** to analyze word frequency in a text and visualize the results.

Completing this assignment will enhance your skills in **processing large files efficiently** and utilizing Python’s **parallel computing capabilities** to speed up execution.

💡 If you previously took the **"Computer Systems and Their Fundamentals"** course, you might recognize this as [Task 2](https://github.com/AM1007/goit-cs-hw-05) from Homework after Topic 10 (Introduction to Parallel Computing). In that case, feel free to submit your previous solution without rewriting it from scratch.

📌 Make sure to include all links and attached files; otherwise, your homework will not be accepted!

Let’s get started! 💪🏼

### Task

Write a Python script that:
- Loads text from a given URL,
- Analyzes word frequency using the MapReduce paradigm,
- Visualizes the most frequently used words.

### Step-by-Step Instructions

1. Import required modules (e.g., matplotlib and others).
2. Use the MapReduce implementation from lecture notes.
3. Create a function visualize_top_words to display the results.
4. In the main script, fetch the text from the URL, apply MapReduce, and visualize the results.

👉🏼 For example, a graph showing the top 10 most frequent words could look like this:

![example](./assets/task.png)

(Graph example placeholder – implement it in your script.)

Acceptance Criteria
📌 These criteria must be met for your assignment to be reviewed. If any are missing, the mentor will return it for revision without grading. If you need clarification or get stuck, ask your mentor in Slack.

The script successfully fetches text from the given URL.
The word frequency analysis using MapReduce is correct.
The visualization clearly displays the most frequent words.
The script efficiently uses multithreading/multiprocessing.
The code is readable and follows PEP 8 standards.