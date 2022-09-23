 _________________________________ 
|                                 |
|           README.TXT            |
|        GIT SCRIPT - A11         |
|_________________________________|
 _________________________________ 
|     __    __    __    __        |
|    /  \  /  \  /  \  /  \       |
| __/  __\/  __\/  __\/  __\__    |
| _/  /__/  /__/  /__/  /_____|   |
|  \_/ \   / \   / \   / \  \___  |
|       \_/   \_/   \_/   \___o_> |
|                                 |
| .. ALGONQUIN COLLEGE - 2022F .. |
|_________________________________|

STEP-BY-STEP:

-- 1. LOCAL REPOSITORY ---

1.1. Create your folder with individual/team identification.
* Suggestion: First name + Last 3 Id numbers
* Ex: > mkdir Paulo081

1.2. Create the Git folder:
* Command: > git init

1.3. Create the A11 folder:
* Command: > mkdir A11

1.4. Add this folder to your local repository:
* Command: > git add A11

1.5. In this folder, download the "CST8152_Compilers_A11_AnswerTemplate.docx" from A11 assignment activity.

1.6. Rename this file to a language name.
* Requirement: Give a snake name (in the case of GPL) or a context name (in the case of DSL).
* Ex: I will update "Boa" to "Jiboia" (brazilian name to "Boa"): CST8152_Compilers_A11_Jiboia.docx

1.7. Then, I can add this file and folder in git:
* Command: > git add .

1.8. Include this file in your stage:
* Command: > git commit -m "Initial A11"

1.9. Now, you can start changing this file. Periodically update it in the repository, repeating the commit command (with the proper message).

1.10. To be sure that your local repository is ok, check the status:
* Command: > git status

-- 2. MOVING TO REMOTE REPOSITORY ---

2.1. In GitHub, create a new repository (ex: ACF22Com)

2.2. Once created, check the messages in your "Quick setup" in the session for pushing the repository:
* Commands:
> git remote add origin https://github.com/acstudent0/ACF22Com
> git branch -M main
> git push -u origin main

2.3. If you have problems with the credential (ex: remote: Permission to acstudent0/ACF22Com.git denied), include your credentials:
* Commands:
> git config user.name "studentName"
> git config credential.username "studentName"

2.4. If errors about "Updates were rejected because the tip of your current branch is behind" appear:
* Commands:
> git pull origin main --allow-unrelated-histories
> git push -u origin main

--- 3. CLONING A REMOTE REPOSITORY ---

3.1. The professor also created a Git repository that you can use to clone (basic instructions and the same template to be used. Just clone it, if you want:

* Command:
> git clone https://github.com/acstudent0/ACF22Com

3.2. Or you can select in GitHub to clone a repository by Web. So, in the end you can see something like:
https://github.com/acstudent0/ACF22Com/import

<<<<<<< HEAD
--- 4. UPDATING FROM A REMOTE REPOSITORY ---
> git fetch https://github.com/acstudent0/ACF22Com

=======
>>>>>>> faa701123e7a06ea39a6ee31cf11d975a706aab4
---
(Update: 23/09/2022)
