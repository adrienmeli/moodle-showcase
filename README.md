# moodle-showcase

This repo showcases the sort of Moodle activities an R-based pipeline can create.



Using [R-exam](http://www.r-exams.org/), I created a series of scripts and templates that enable me to create all sorts of Moodle quizzes very easily.



The data/ folder contains the files a teacher needs to include.

Exercises are created from simple .csv files using semi-colons as field separators. 

The xml file is the final file to import in the Question Bank of your Moodle course.



# Dropdown exercises


The student must find the correct solution from a dropdown menu.
By default, the dropdown menu is formed from the second column of the original .csv file, and 3 random solutions (excluding the correct answer) are offered. The number of possible solutions is easily adjustable.



# Dictation



An exercise is created where the student must listen to a word and type what he listens.

To create it, a simple list of words suffices.

The .csv file must include "dictation" in its name.



# IPA / LPD



Same principe as dropdown exercises, except that it is the IPA transcription (from the Longman Pronunciation Dictionary) of a word that must be found in a list



# Stress Patterns



Same principe as dropdown exercises.

The stress pattern of the word must be found.



# Insertions



The student must conjugate a verb appropriately.

In the 'Hard' version, the list of possible verbs is jumbled.

The name of the .csv file must include "insertions".



# Flashcards



Just add pictures in the folder.

The dropdown menu will include the names of the pictures. Dashes in picture names will be replaced by white spaces in the dropdown menu.



# And so much more!



This is only a showcase. 

There is more (like automatically including texts or videos as iframes).







