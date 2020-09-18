# Student Submission Process
---

This document explains the process of submitting assignments throughout the bootcamp.

# Part 1: Submitting Project Code

All project code will be pushed to a new repo and submitted through Google Forms.

1. Create a public repo for each project on Github.
2. Clone the repo onto your local computer.
3. Code up your project, going through the add -> commit -> push process as needed.
4. Submit the URL of the repo through the Student Submissions Google Form.


# Part 2: Submitting Challenges and Investigation Slides

All challenges and investigation submissions will be pushed to your forked onl20_ds4 repo and submitted through Google Forms.

## Let's practice with some fake homeworks
### 1. Do your homework

Create a homework file on your Desktop.

```
$ cd ~/Desktop

$ echo "This is my first homework assignment." > joan_homework.txt

$ cat joan_homework.txt
This is my first homework assignment.
```

---

### 2. Go through the Git workflow

Move the homework into the student_submissions folder on this new branch. You can do this with a `cp` or manually through Finder or the File Explorer. 
Afterwards, check to see if git recognizes the new file.

```
$ git status
```

Go through the git workflow.

Go to the student submissions directory where the homework assignment is located before going through the steps below OR you can do a `git add .` if you're confident you've only changed what you intended to.

```
$ git add student_submissions/joan_homework.txt

$ git status

$ git commit -m "added my homework assignment"

$ git status

$ git push origin master
```
---
### 3. Submit the URL through Google Forms

Go to your forked repo: https://github.com/user_name/onl20_ds4 and navigate to the desired file within the student submissions folder. Then, submit this url through your campuses Student Submissions Google Form:

[Lasso Submissions](https://docs.google.com/forms/d/e/1FAIpQLSdzIwmJpkeOeQd7HsAnSr3e6KAHlV28_chulHmZUFPSt10A-A/viewform?usp=sf_link)

[Ridge Submissions](https://docs.google.com/forms/d/e/1FAIpQLScEWF1KL6oHCcaU6_vm-jv8-8rRNsH_uzUeFBnCITEDTyMzGQ/viewform?usp=sf_link)

---

**Note:**  
GitHub commit every day, green dots show up on user home page and it looks good for potential employers.
