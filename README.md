# SQL Motion & Python Motion

Animated lessons that show code **running**, not just written.

- **SQL Motion:** SQL Server runs your query one clause and one row at a time. A *Run order* chart shows the real processing order (FROM → WHERE → GROUP BY → HAVING → SELECT → ORDER BY → TOP), and each row's condition is solved piece by piece (`amount >= 300` → `250.00 >= 300` → `FALSE`) before the row moves to *kept* or *removed*.
- **Python Motion:** Python runs your program one line at a time. A live flowchart shows the path taken, expressions are solved in place (`total + n * 2` → `0 + 3 * 2` → `6`), values fly into variables, and function calls build a call tree.

Every step follows the same order: **where** it goes (and why), then **what** it solves, then the **one thing** that changes. Explanations are typed at a readable pace, and you can pause or step one move at a time.

**Live site:** `https://YOUR-USERNAME.github.io/YOUR-REPO/` (replace both parts with your GitHub username and repository name)

| Track | Level | Topics | Page |
|---|---|---|---|
| SQL | Beginner | 1–17: SELECT, WHERE, sorting, functions, CASE, aggregates, GROUP BY, DML | [beginner.html](beginner.html) |
| SQL | Intermediate | 18–39: joins, subqueries, CTEs, window functions, pivot, procedures, transactions, indexes | [intermediate.html](intermediate.html) |
| SQL | Advanced | 40–57: recursive CTEs, analytics, execution plans, tuning, isolation, dynamic SQL, security, recovery | [advanced.html](advanced.html) |
| Python | Beginner | 1–14: variables, strings, conditions, loops, lists, dictionaries, functions, errors, patterns | [python-beginner.html](python-beginner.html) |
| Python | Intermediate | 15–28: tuples, sets, nested data, comprehensions, scope, files and CSV, sorting with keys, classes | [python-intermediate.html](python-intermediate.html) |
| Python | Advanced | 29–42: recursion, generators, closures, decorators, inheritance, Big-O, algorithms, hash maps, stacks | [python-advanced.html](python-advanced.html) |

## What each lesson has
- **Animation** with Play / Pause, one move back or forward, replay, and speed (1×, 0.75×, 0.5×, 1.25×).
- **Try it / Solve it:** interactive labs. Python lessons include *predict the output* and *put the lines in order* puzzles.
- **Use it at work:** a practical example on the same claims data.
- **Remember:** the key points (Python topics also link each idea to its SQL equivalent).
- **SQL Playground and query builder**, and **Python Practice** with random challenges.

## Run it
No install and no build step. Each page is one self-contained HTML file: open it in a browser, or use the live site. Fonts load from Google Fonts; everything else is inside the file.

## About the data and engines
All examples use a small, made-up health-plan dataset (members, claims, plans and a few extras). No real people or real claims.

The SQL pages include a teaching engine that follows SQL Server's rules for the features the lessons cover; it is not a database. The Python animations were recorded by running every program in real Python 3.12, so the values, output and errors shown are exactly what Python produced.
