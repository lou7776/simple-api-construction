# Trades Salary Finder

A simple front-end app that shows the median annual salary for a trade in any U.S. state. Built for the Simple API 1 challenge.

- HTML<img width="714" height="373" alt="Screenshot 2026-10-26 at 2 54 18 AM" src="https://github.com/user-attachments/assets/ae4d9832-06b4-41ee-86bf-b441ac6b4156" />

## What it does

Pick a trade and a state, click **Get salary**, and the median annual wage shows up on the page.

Trades included: Electrician, Plumber, Carpenter, Sheet Metal Worker, Roofer, Painter, Brickmason, and Welder.

## Built with

- CSS
- JavaScript (fetch)
- [SalaryWiki API](https://salarywiki.com)

## How to run it

1. Clone the repo
2. Open `index.html` in your browser
3. Choose a trade and a state
4. Click **Get salary**

## What I learned

- Using fetch to pull data from an API
- Building a request URL from dropdown values
- Updating the page with the response

## Future improvements

- Show a loading message while the data comes back
- Add error handling for states with no data
- Format the salary as dollars (like $65,000)
- Show hourly wage too
