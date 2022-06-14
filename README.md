1. The project implements a table of employees using just HTML, SCSS and JS.
The table represents information about some employees.
But user can do something with this table, not just look at it.
You can see the list of available features below:
- table sorting by clicking on the title (in two directions).
- when user clicks on a row, it becomes selected.
- there is a form added by script. Form allows users to add new employees to the spreadsheet.
- if form data is invalid the corresponding notification appears.
- user can edit table cells after double-clicking on it. Only one cell can be edited at the time.
On blur or 'Enter' keypress changes are saved to table cell. If a new value is empty on submitting
initial value returns to the cell.

2. Technologies stack: HTML5, CSS3, BEM, SASS (I was provided with ready markup and SCSS), JS.

3. Preview link: https:/mykhailoivchenko.github.io/employees-table/

4. You can add new employee to the table using form on the right side of the screen.
But after after page reloading that employee disappears, because there is no any interaction
with server or local storage and table is created without any databases and even arrays with
employees data. The same situation with strings editing. This project just demonstrate the power
of JS for creating interactive elements which allow user to be an active participant of some process,
not just observer of web-site.
