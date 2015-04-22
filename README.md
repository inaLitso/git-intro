git-intro
=========

# An introduction to Git's collaboration style.

## Assignment

### Initial action

Select a task from the list below and tackle it.
Feel free to add a task to the existing tasks.
To avoid conflicts between each other, once you clone
this repository:
* select a task,
* put your GitHub user name next to the task (as I have done)
  noting that it is work in progress,
* commit the change to this file, and
* push your commit to the upstream repo at GitHub so that
  your colleagues can see that the task is taken.

Note: if your commit is not accepted when you try to push
this means that one of your colleagues has updated the repo
in the interim (between the time you cloned and pushed).
Pull the changes to your local repository, merge any conflicts,
and try to push again.
Don't worry if it happens, you will get extra credit for that :-)

### Work guide

All tasks should be done in a new branch that
should be merged to the master branch after 
a task is successfully completed.
Don't delete your branch afterwards.

In your branch, explain briefly the Git commands you used to complete the task
in a new file named Changelog followed by an underscore followed by your GitHub
user name (for me it would be Changelog_mfragkoulis).
Place the Changelog file under version control.

Don't forget to put your GitHub user name next to the task
you undertook (see below).

### Tasks to do:

* Set up task list -> mfragkoulis
* Cleanup repository -> k-karakatsanis
 * Generated files (e.g. .class files) should not be under version
   control; remove them.
* Place the story in folder test_branch with the rest of the stories
   and remove folder test_branch -> p3110145
* Refactor code -> theosotr
 * Fix code alignment
 * Class names should follow unanimous style (e.g. AdventureStory, ScaryStory)
 * If they have (or should/could have) common characteristics create a superclass
   (e.g. Story) and have the existing ones inherit from that
 * Enhance code readability (e.g use the sentence() method everywhere)
* Document code
 * Place comments on top of methods
 * Place comments inline to the code if/when needed (use sparingly).
* Fix code errors -> kostastsili94
 * Option -y does not work properly
 * Option -z does not work properly
