Public repository containing general access training materials and sandbox projects.

Training
========
Wiki:  
*https://github.com/dirty-mechanics-3932/training/wiki*

FRC Offers a RobotBuilder:
*http://wpilib.screenstepslive.com/s/3120/m/7882/l/80358-starting-robotbuilder*

Test Mode:  
*http://wpilib.screenstepslive.com/s/3120/m/8564/l/87776-using-test-mode*

PID:  
*http://www.virtualroadside.com/blog/index.php/2009/01/29/pid-parameter-calculation-spreadsheet/*
*http://en.wikipedia.org/wiki/PID_controller*


========
Helpful git command line commands:
========

Get a copy of a remote repository onto your local machine:  
*git clone https://github.com/dirty-mechanics-3932/training training*


Revert local changes to last commit:  
*git checkout .*

Push locally committed files to a remote repository:  
*git push https://<username>@github.com/dirty-mechanics-3932/training/*

Get an update from a remote repository (merge repository to local copy):  
*git pull https://<username>@github.com/dirty-mechanics-3932/training/* 

Reset changes in local copy that were not yet staged:  
*git reset*

Reset changes in local copy that were not yet committed:  
*git checkout -- .*

Force a switch from your working copy back to the head of another branch:  
*git pull --rebase https://adamzg@github.com/daniel-ruess/FRC-3932 robot-fire-control*

Clean up files that were added that you don't want to keep:  
*git clean -fd*

Find out what remote repositories are associated with a local checkout:  
*git remote -v*

Compare branch "testbot" with working copy in current directory:  
*git difftool testbot .*







