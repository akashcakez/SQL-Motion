# SQL Motion

Animated, row-by-row lessons for **SQL Server (T-SQL)**. Every clause runs one row at a time: rows get checked, move to where they belong, and arrows show where each value goes. You can pause, step one move forward or back, and slow it down.

**Live site:** https://YOUR-USERNAME.github.io/sql-motion/

| Level | Topics | Page |
|---|---|---|
| Beginner | 1–17: SELECT, WHERE, sorting, functions, CASE, aggregates, GROUP BY, DML | [beginner.html](beginner.html) |
| Intermediate | 18–39: joins, subqueries, CTEs, window functions, pivot, procedures, transactions, indexes | [intermediate.html](intermediate.html) |
| Advanced | 40–57: recursive CTEs, analytics, execution plans, tuning, isolation, dynamic SQL, security, recovery | [advanced.html](advanced.html) |

## What each lesson has
- **Animation**: the query runs clause by clause, row by row, with narration of the real values (for example `C3: 'DENIED' = 'PAID' → FALSE`).
- **Controls**: Play / Pause, one move back or forward, replay a step, and speed (1×, 0.75×, 0.5×, 1.25×).
- **Try it**: an interactive lab for the topic.
- **Use it at work**: a practical query.
- **Playground**: write your own query and watch it run, plus a drag-and-drop query builder.

## Run it
No install and no build step. Each page is one self-contained HTML file: open it in a browser, or use the live site above. Fonts load from Google Fonts; everything else is inside the file.

## About the data
All examples use a small, made-up health-plan dataset (members, claims, plans, claim lines and a few extras). No real people or real claims.

The in-page SQL engine is a teaching tool that follows SQL Server's rules for the features it covers. It is not a database, and results for features outside the lessons may differ from SQL Server.
