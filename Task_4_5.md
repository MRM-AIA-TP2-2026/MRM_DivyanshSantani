# Task 4 and 5: Branching, Merging, and READMEs

## Task 4 Description

Task 4 involved creating a new branch named `Temp`, adding a README file named `Task_3.md` (which described Task 3), and pushing the `Temp` branch to the remote GitHub repository.

## Task 5 Description

Task 5 involved merging the `Temp` branch into the `master` branch and creating this `Task_4_5.md` file to document both Task 4 and Task 5.

## Git Commands Used

The following Git commands were used for Tasks 4 and 5:

1.  **`cd /c/Users/HP/Documents/GitHub_task`:** (Linux command) Navigates to the project directory.
    ```bash
    cd /c/Users/HP/Documents/GitHub_task
    ```

2.  **`git branch Temp`:** Creates a new branch named `Temp`.
    ```bash
    git branch Temp
    ```

3.  **`git checkout Temp`:** Switches to the `Temp` branch.
    ```bash
    git checkout Temp
    ```

4.  **`nano Task_3.md`:** (Linux command) Opens the `Task_3.md` file in the `nano` text editor (or creates it if it doesn't exist).
    ```bash
    nano Task_3.md
    ```

5.  **`git add Task_3.md`:** Stages the `Task_3.md` file for commit.
    ```bash
    git add Task_3.md
    ```

6.  **`git commit -m "Add Task_3.md describing Task 3"`:** Creates a commit with the staged changes.
    ```bash
    git commit -m "Add Task_3.md describing Task 3"
    ```

7.  **`git push -u origin Temp`:** Pushes the `Temp` branch (including `Task_3.md`) to the remote repository and sets up tracking.
    ```bash
    git push -u origin Temp
    ```

8.  **`git checkout master`:** Switches back to the `master` branch.
    ```bash
    git checkout master
    ```

9. **`git merge Temp`:** Merges the changes from the `Temp` branch into the `master` branch.
    ```bash
    git merge Temp
    ```
10. **`nano Task_4_5.md`:** (Linux Command) Creates/opens the `Task_4_5.md` file in the `nano` text editor.
    ```bash
      nano Task_4_5.md
    ```

11. **`git add Task_4_5.md`:** Stages the `Task_4_5.md` file for commit.
    ```bash
    git add Task_4_5.md
    ```

12. **`git commit -m "Add Task_4_5.md describing Tasks 4 and 5"`:** Creates a commit.
    ```bash
    git commit -m "Add Task_4_5.md describing Tasks 4 and 5"
    ```

13. **`git push origin master`:** Pushes the changes (including the merge commit and `Task_4_5.md`) to the remote repository.
    ```bash
    git push origin master
    ```
     14. **`git status`**: (Optional, but highly recommended) This command shows the status of your working directory and staging area.
        ```bash
        git status
        ```
    15. **`git branch`**: (Optional) I did not use this command in this task, but it helps listing all branches in your local repository. If you add -r you can see remote branches.
       ```bash
       git branch
       git branch -r
       ```
    16. **`git checkout`**: (Optional) I did not use this command in this task. You can use it for switching branches or restoring working tree files.
        ```bash
        git checkout <branch-name>
        ```
