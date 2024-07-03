# branches-and-things-
for practicing github flow, and testing conflicts


self tutorial for if i forget how branches work :) 

This diagram shows:

    The main branch
    A new branch called feature
    The journey that feature takes before it's merged into main

![image](https://github.com/JonathanCamberos/branches-and-things-/assets/73202309/22c319f2-463e-4724-931a-becdca6ba9ac)


**To create a branch**
Got to code tab
![image](https://github.com/JonathanCamberos/branches-and-things-/assets/73202309/9b166811-c4a0-4abc-8948-080e7e4bafa3)

Type a branch name, readme-edits, into the text box

Click 'Create branch'
![image](https://github.com/JonathanCamberos/branches-and-things-/assets/73202309/8533d38c-2a1f-496a-9d0a-407719f8c514)


**Make an commit changes**
Now that we have created a new branch, we are not at the new readme-edits branch, (a copy of main)

We can still make and save changes to the files in your repository. On GitHub, saved cahgnes are called commits. 

Each commit has a associated commit message

Lets edit the readme file.

Then Click **commit changes**

Then write a commit message and click commit changes.

**Note** - these chagnes will be made only to the README file on the **readme-edits** branch, so now this branch contains content thats different from main

Click on the Pull Requests tab
![image](https://github.com/JonathanCamberos/branches-and-things-/assets/73202309/42ee0a9f-445a-4f4f-9764-4aaf62dc2fc7)

2. Click New Pull Request

3. In the example comparisons box, select the branch you made, readme-edits, and compare itto the original

4. Look over the changes in diffs on the compare page

5. Click create pull request, give it a title and brief description, click create pull request

**Opening a pull request**
Now that we have the changes in a branch off of main, we can open the pull request.

Pull request shows differences, of the content from both branches.
These changes, additions and subtractions, are shown in different colors.

As soon as you make a commit, you can open a pull request.

![image](https://github.com/JonathanCamberos/branches-and-things-/assets/73202309/d5626f5a-b5aa-4c99-9e91-67e3df9f2ffb)

**Reviewing a pull request**
Now when collaborating with others, this is where you can ask for their review.

![image](https://github.com/JonathanCamberos/branches-and-things-/assets/73202309/2aec3aec-c949-4a8d-a12b-989bc62c2b6f)

**Merging your pull request**
Now lets merge the readme-edits branch into the main branch via merging the pull request, merging the branch and incorporating it into main.

**conflicts**
wa pull request may introduce changes to code that conflict with the existing code on main. If there are any conflicts, github will alert you about conflicting code and prevent merging until the conflicts are resolved.


**pushing to main, updating branches**
lets say you push something directly to main, and now one of your branches 'editreadme' is now out of date

will this be an issue? lets see, we added this last section (from main)
lets try to add another section (without pulling from the branch first)
