# Question 5- User Interface Specification Document
## User Management Screen
### Screen Initial view
- When the page is opened, the user will see a table containing all users in the system
- Users are sorted by their IDs

### Requirements
- The screen will show all current users (Their ID, Name, Email, and status)
- Allow the user to filter the table by any column
- Allow the user to add and save new users
- Allow the user to hide Disabled users

### UI Components
- A table containing 4 columns (ID, User Name, Email, Enabled)
- Sort drop-down for each column of the table to sort the data shown
- New User button. This button will open a side window for adding a new user to the system
- Save User button. Used to save new users after filling in the required data in the side window
- Hide the disabled Users checkbox. 

### User Actions
- Sorting. When the user clicks on the sort drop-down for the columns, the table should update to show the data after being sorted
- Adding users. When the user clicks the New user button, a side window containing a form will be opened. The form consists of: 
  Username, Display Name, Phone, Email, User Roles (Drop down menu containing: Guest, Admin, SuperAdmin options), a check box for the enabled status of the user.
- Saving new users. After the user has entered the required information in the form, the Save user button now can be pressed and the new user will be added to the table.
