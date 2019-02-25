# Homework 

## Starting a homework

Follow these steps when you begin a homework.

* Fork repo.

![fork](https://i.imgur.com/N1TxHZF.png)

*  You'll know you're on the right page if it says "forked from" in the upper left corner.

* MAKE SURE YOU ARE WORKING ON YOUR OWN FORK BY CHECKING FOR **YOUR NAME** IN THE TOP LEFT CORNER. 

* Click the "clone button" in the top right to reveal the HTTPS key and copy it.  

* In the command line, navigate to the directory where you want your homework to live.  

* Once you are there, type the command `git clone [_paste https key_]`.  This will pull all of the information from your remote(browser) repo to a local version of it on your desktop.

![clone](https://i.imgur.com/7V68x1w.png)

*  Do your homework.

---
## Submitting a Homework

When you've finished your homework, all you have to do is get it online.  To do this, follow these steps:
 
- Stage your changed files.
    - `git add -A` 
- Commit your code.
    - `git commit -m "W01D03 Homework"`
- Push to your remote repository.
    - `git push origin master`

    **Tip:**
    > after `git add -A` you can use the command `git status` to make sure your changes have been staged before committing

- In your browser, go to your Github repo for the homework. You should now see all of your completed homework there.  Once you confirmed you're homework is up online, you can:

- Click on a new pull request. 
    
    >**Pull requests** let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary. We will be using pull requests to submit homework. 
    
    
    ![pull](https://i.imgur.com/D3vUnJm.png)
- Make sure you are comparing the correct repos. The **base** _(first repo)_ should reference the homework assignment. The **head** _(second repo)_ should reference the work you completed.
    ![comparin reops](https://i.imgur.com/Vn5PS2h.png)


- Fill out your submission. When submitting, include the following:
    - on a scale from 1 to 5, how comfortable were you with this assignment?
    - what was a win you had with this assignment?
    - what was a challenge you had with this assignment?
    - is there anything that you'd like some further information on?
    - other stuff on your mind? work with anyone?  tell us about it!

![submit](https://i.imgur.com/hsDhlMD.png)

- Click `Create Pull Request` to submit your work!