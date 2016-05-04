Michael Llanes 
CSCI2270 
Project

SUMMARY: 
For this project I will be using hash tables to develop a movie recommendation program.
I will prompt the user to choose which 'filter' they'd like; options will include date of release, genre, movies
alike other movies within the list, the movie's director, and the possible IMDb Top 250 Movies of all time ranking.
I will also allow the user to delete movies from the list that they have seen or simply do not like/do not want to
see pop up again. My program is influenced by one of our assignments, but I plan to implement the functionality of 
a recommendation system rather than an inventory system. I use a basic menu in the terminal, prompt the user for what 
they would like to do(get a recommendation, insert a movie, delete one, find one, or print the whole list).
In the first option(the recommendation portion), I will further prompt the user for what categorization they would
prefer, then I run my appropriate functions which find the titles to recommend, building a vector of every one found
then I randomly choose five elements of that vector to recommend as movies. The randomization comes from prompting the
user to enter any five non-consecutive characters and getting a sort of hash sum based on the length of the vector.


HOW TO RUN:
Download the .zip file, and extract.
Then run the project file using CodeBlocks. Build, compile, and run it once in CodeBlocks.
Then, simply follow the menu displayed by the program, entering appropriate values to access certain funtions.

When asked to enter five random characters, it is to be done exactly as said (alike characters will give same hash
values for random function), as such ("sdhte").

I used IMDb to catelog all these movies into my text file, so when finding a movie, or getting a recommendation
alike another movie, enter the title exactly as written on IMDb for appropriate results.
If you google the movie, the IMDb page for it is usually in the first three results. 
For example, the second part of Lord of the Rings would be ("The Lord of the Rings: The Two Towers") not ("LOTR 2")
or ("Lord of the Rings: Two Towers"). 



DEPENDENCIES:
There are no serious dependencies for my project. Just make sure to have the text file ("Titles") in the project
folder in order to be able to build the list.


SYSTEM REQUIREMENTS:
This project was constructed using CodeBlocks, so it should run on varying Operating systems. 
Any system requirements would be any of those for CodeBlocks.


GROUP MEMBERS:
I worked by myself for this project.


CONTRIBUTORS:
Until now, there have been no contributors to this project besides myself.


OPEN ISSUES/BUGS:
The randomization some times gives back repeated titles when one chooses the director sorting option.