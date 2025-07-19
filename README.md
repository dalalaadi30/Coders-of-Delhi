#Coders of Delhi

Welcome to the official GitHub repository for the **Coders of Delhi**. This project simulates a real-world data science project, a social media platform for coders.

You were tasked to clean, analyze, and build recommendation features using **pure Python (no external libraries like pandas or NumPy)**. The project consists of multiple tasks that demonstrate my Python skills and understanding of data structures.

---

#Project Overview

- **Domain:** Social Media Analytics
- **Language:** Python (no external libraries)
- **Goal:** Build core recommendation features by analyzing user data

---

#Tasks Completed
Task 1: Load and Display the Data
Read and parse the codebook_data.json file.

Display user profiles with their friends and liked pages.

Print the available pages with their names.

Task 2: Clean and Structure the Data
Remove users with missing names.

Deduplicate friend IDs.

Remove inactive users (no friends and no liked pages).

Remove duplicate page entries by ID.

Task 3: People You May Know
Suggest friends based on mutual connections.

Rank suggestions by the number of mutual friends.

Task 4: Pages You Might Like
Recommend pages that similar users have liked.

Use basic collaborative filtering based on common liked pages.

Features Implemented
Feature	Description
load_data()	Load JSON data from file.
display_users()	Display structured user data.
clean_data()	Remove inconsistencies and duplicate data.
find_people_you_may_know()	Recommend friends based on mutual connections.
find_pages_you_might_like()	Recommend pages using collaborative filtering.

#Conclusion
This project showcases:

How to process and clean JSON data using core Python.

How to build features like People You May Know and Pages You Might Like.

The foundation of a social media recommendation engine using zero external libraries.
