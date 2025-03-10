### Tasks completed:
- created a temporary page to display the user answers table on the website to assist with debugging
- added the ability to empty the table from the page to remove experimental records
- allowed the user to go back and change there answers
- tested that the updating answers correctly changes the database
- tested that the updated answers are saved when the user resubmits and revisits the page

### Tasks to complete before next week:
- create new tables in the database for the nect sections of the quiz
- design the next section of the quiz, including coming up with the questions and answers for each department and designing the algorithm

### Issues:
encountered a bug which was interfering with updating the database, spent lots of time trying to figure out the issue. I had forgot to remove a foreach loop which meant that the users answers were being saved to the database three times, which was confusing the program when updating 
