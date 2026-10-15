Q1. What did pwd print?
Ans : pwd (print working directory) printed where i currently was in the terminal.

Q2. What did ls -a show that plain ls did not?
Ans : ls -a showed all the files and folders in the current directory (even the hidden ones) whereas ls shows normal visible files and folders only. 

Q3. Pick one line from ls -l. What do you think the first column means?
Ans : It tells us the permissions of that particular file, i.e. who can read/write/execute it. 

Q4. Why does that work from where you are standing? Which kind of path is coding-cafe/week02? Absolute or Relative?
Ans : It works because I'm currently in the same directory as the one I ran this ls command in. It is a relative path (not the complete location).

Q5. mv did two different jobs above. What were they?
Ans : One was moving the file to a different location and the other was renaming the file. 

Q6. How many folders are on your PATH? 
Ans : 12

Q7. Write down exactly where your python3 lives. 
Ans : "anaconda3/bin"

Q8. Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
Ans : No, our answers were not the same because Python might be installed in different locations on our computers, hence the path didn't give us the same output for python location. 

Q9. What exactly did the shell say? Explain the error in your own words, using the word PATH.
Ans : The shell said, "zsh: command not found: pyton3". 
In the PATH I'm currently at, there is no command called pyton3. The shell searched the folders listed in the PATH for pyton3, but it couldn't find it. 

Q10. .venv did not appear with plain ls. Why not? 
.venv must be a hidden folder by default, which is why it didn't appear with plain ls. 

Q11. What changed about your prompt?
Ans : (.venv) appeared at the beginning of my prompt, which must mean that the virtual environment was activated.

Q12. Compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell you about what activate actually did to your PATH?
Ans : No, the path is different now. Since .venv is activated, it enabled the shell to look into this environment first rather than the system and hence what the path was previously (anaconda) now changed to .venv.

Q13. What is in the second list that was not in the first?
Ans : In the first list, only the pip package and its version was there. In the second list, there were certifi, requests, and other packages as well. 

Q14. Where does python3 point now?
Ans : python3 now shows the initial path that it showed before we installed .venv. 

Q15. Find what ls -h does. Write it in your own words.
Ans : ls -h showed me the folder created under coding-cafe i.e. week01 and week02.

Q16. What is the difference between what Ctrl + C and Ctrl + D did?
Ans : Ctrl + C stops the command that is running, while Ctrl + D exits the Python interpreter. 