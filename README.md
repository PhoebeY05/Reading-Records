# Description
Web app made in Flask that acts as a book list for avid bookworms who read unpublished books
## Features:
1. Login functionality allows user's book list and tastes to remain privacy 
2. Status with standard options like Finishing, Finishing Soon, Left Extras, Uncompleted & customisable option to type anything user prefers
3. Three categories of "Completed", "Unfinished"(i.e. DNF) & "To Be Read" with their respective pages
4. Randomly choose a book in one of those categories
5. Automatically calculates days taken to read the book (days between addition of previous book to current addition)
6. Filters to check for existence of genres, notes, or series
7. Timeline views of books added
   - Specific year: books added to 1 of the above categories in specified year
   - Recents: books added today, this week or this month
8. Search function that returns books (even if complete name is not entered)
9. Convenient switching function from "Unfinished" & "To Be Read" to "Completed" and each other
10. Easily add 1 to number of times reread
## Possible Improvements:
- Filter by language
- Input to set number of rereads
- Link to book website (e.g. Wattpad, 晋江文学城）
  - Automatically retrieve status of book
- Prompt for reviews when switched to "Completed"
- Estimated time of completion for book (data analytics)
- Show periods of times where some genres are preferred (clustering)

# How to visit?
1. Clone repository/Download zip file <img width="1331" alt="image" src="https://github.com/PhoebeY05/Reading-Records/assets/115935747/a178ac76-cd85-4656-8136-4f8789c741f4">
2. Open folder in VS Code
3. Run the below commands in VS Code's terminal

```bash
export FLASK_APP=app.py
export FLASK_DEBUG=1
flask run
```



