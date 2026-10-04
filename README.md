# becoming-a-programmer
Teaching Sofia programming &amp; computer science.

## 

| Week | Subject &amp; Concepts                                              | Project                                                               |
|------|---------------------------------------------------------------------|-----------------------------------------------------------------------|
| 1    | Completed: Printing, primitive types                                | Setup environment, basic CLI script                                   |
| 2    | Variables, user input, type casting, arithmetic                     | split_bill.py: Tip and shared-expense calculator with formatting      |
| 3    | Conditionals (if/elif/else), boolean algebra, logical operators     | password_check.py: Password strength & criteria evaluator             |
| 4    | Control flow: while loops, for loops, break/continue                | budget_tracker.py: Interactive CLI expense logger                     |
| 5    | Data structures I: Lists, tuples, list slicing, and comprehensions  | task_manager.py: Prioritized CLI to-do manager                        |
| 6    | Data structures II: Dictionaries, sets, nested JSON-like data       | flashcards.py: Terminal flashcard study tool with score tracking      |
| 7    | Functions: parameters, default values, *args, return values, scope  | Refactor Week 6 into clean, modular functional code                   |
| 8    | File I/O: Reading/writing .txt and .csv files, with context manager | csv_analyzer.py: Parse a CSV log and output a summary report          |
| 9    | Error handling (try/except), debugging, writing basic assertions    | Add defensive input validation and edge-case testing to past scripts  |
| 10   | External packages & HTTP APIs: pip, venv, and the requests library  | weather_cli.py: Fetch and display real-time weather from a public API |
| 11   | Basic Data Visualization: Introduction to matplotlib or plotly      | plot_expenses.py: Generate an interactive chart from a CSV dataset    |
| 12   | Capstone: End-to-end mini-app & GitHub Pull Request review          | Web scraper, API bot, or an interactive data dashboard                |

TODO
------------------------------------------------------------
## git approach
clone/sync the repo 

```
cd <your working directory>
git clone git@github.com:SolanoPinedo/becoming-a-programmer.git
cd becoming-a-programmer
```

*Why?*: This is how programmers work. You should see the benefit.

## change keyboard language fast
Edit .xinit, add:
```
setxkbmap -layout us,latam
setxkbmap -option 'grp:alt_space_toggle'
```

*Why?*: You need a fast way to write in (at least) spanish &amp; english.

## Day's lesson
### Warm-up
- print a sentence
- print a number
- confirm the type of both

### Variables
### User Input
### Type Casting
### Arithmetic Operators & Precedence
### Daily project - "split bill"
Create a command-line tool `split_bill.py` that calculates how much each person owes when splitting a bill, including a custom tip percentage.

#### 📋 Requirements
- [ ] Prompt the user for the total bill amount (decimal/float).
- [ ] Prompt for the tip percentage they want to leave (e.g., 10, 15, 20).
- [ ] Prompt for the number of people splitting the bill (integer).
- [ ] Calculate the total tip, grand total, and amount owed per person.
- [ ] Round the per-person amount to 2 decimal places.
- [ ] Print out a clean summary of what each person owes.
