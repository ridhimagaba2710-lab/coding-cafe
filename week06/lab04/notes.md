Q1. What did --global mean here? What would happen if you left it out? Guess, then check with man git-config or ask.
Ans : --global means the username and email configuration will apply across my entire account for all current and future Git repositories.

Q2. What appeared in ls -a but not in ls? What is inside it?
Ans : The .git hidden directory appeared, like all the internal configuration files, .venv files etc. 

Q3. Roughly how many files and folders is Git offering to track? Does anything in that list look like something you did not write?
Ans : It is offering to track numerous no. of files because it is picking up everything inside the .venv directory. The contents of .venv are things I did not write.

Q4. Compare this git status with the one from Question 3. What disappeared?
Ans : The .venv/ file and all its untracked sub-files and directories disappeared. 

Q5. .gitignore itself shows up as untracked. Should it be committed, or ignored too? Why?
Ans : It should be committed. The .gitignore file needs to be tracked, ensuring everyone ignores the same temporary or private files.

Q6. README.md moved from one heading to another in the git status output. Which two? In the three-places model from the session, what just happened to it?
Ans : It moved from untracked files to "Changes to be committed". In the three-places model, the file moved from the Working Directory to the Staging Area.

Q7. What did Git print after the commit? How many files did it say changed?
Ans : It printed : 
"[main 9f87d51] Lab work so far
 7 files changed, 3604 insertions(+)
 create mode 100644 README.md
 create mode 100644 week02/lab01-log.txt
 create mode 100644 week02/notes.md
 create mode 100644 week02/notes.txt
 create mode 100644 week03/Copy_of_lab2_cc_2026 (1).ipynb
 create mode 100644 week03/Copy_of_lab2_cc_2026.ipynb
 create mode 100644 week05/Copy_of_lab3.ipynb"

 Q8. What are the first seven characters of your commit called, and what are they for?
 Ans : They are called the Short SHA-1 Hash (or short commit hash). They serve as a unique identifier for that specific commit snapshot so one can reference, inspect, or revert back to it later.
