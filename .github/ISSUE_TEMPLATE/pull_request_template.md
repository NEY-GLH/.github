## Title

- Add a title for your PR


## Aim and background

- State background in a sentence or two
    - 'Users reported that API calls were failing under high load'
    - 'Users were asking for an easier way to obtain data as files'.
- Link any relevant bugs or enhancements
    - E.g. The original API call issue repor
    - E.g. The enhancement request for data export.
- State the aim of your PR
    - E.g. 'Reduce number of API complaints from users'
    - E.g. 'Add a data export function in the web interface'.


## Changes made

- Briefly describe the changes you've made:
    - E.g. 'a longer wait was added between API calls'
    - E.g. 'I built an export function, which queries the database for entries made by a user in a date range, and outputs a CSV'.


## Code style

- Have you run the 'black' PEP8 formatter? This is available as a VS Code add-on.


## Unit testing

- If you've written unit tests - have you run them? 
    - Provide the summary output.
    - Explain where you left gaps and why.
- If there are unit tests failing which you didn't write - show that you've checked this isn't caused by your code.
    - If this is a known bug: Link known issues for this repository.
    - If the unit test failure was already occurring on the main repo: Make a bug report, and link to it.


## New behaviour of code

- Carry out sense checking - prove that you've achieved your aim.
- MAKING SURE TO OMIT SENSITIVE DATA - Show screenshots or pasted code for the following, where relevant:
    - The GUI
    - Database outputs (e.g. if you're working on a Django app, run 'shell plus' commands to demonstrate changes)
    - Migration success messages (e.g. if you've changed the db for a Django/Flask app)
    - Files
    - And anything else that might be relevant


## Documentation and validation

- List documentation that will need changing or writing
- Indicate the level of validation required - if the output used for downstream analysis could be affected by the changes, then a higher level of validation will be required.


## Are acceptance criteria met?

- Would the requester be happy with what you've done?


## Tickets closed by this PR

- Use the 'Closes' keyword to make this auto-close on merge. See formatting here: https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue