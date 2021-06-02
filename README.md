# User Management Screen / UI Specification Document

## User Management Screen - Header

- Create a new user button appears. There is a plus icon at the beginning to symbolize the create. The color has been changed to show the button itself. The text color is set as the title color in the background.
- Next to create user button, there is check box to remove disabled users from the list
- At the end of the title, there is a save button. It is lighter in color compared to the create new user button. The reason here is that since there is a list of users in the body on the left, the button there needed to be a little darker to show itself.

## User Management Screen - Body
The body part is divided into two. On the left is the list of users and on the right is the user creation form. The user list header on the left also serves as sorting and filtering. There are ID, User Name, Email and finally Enabled columns.

- The ID column shows the user registration order. It has the feature of filtering by number. It also offers the possibility to sort the list from smallest to largest or largest to smallest.
- The User Name column shows user names of registered users. It also has a filtering feature. It is also possible to sort alphabetically.
- Email addresses of registered users appear in the Email column. It is possible to filter email addresses. It is also possible to sort alphabetically.
- Enabled column highlights the enable users in the list. The list shows true for enable users. False value also appears for disabled users. Only enabled users are listed in the list, as the "Hide Disabled User" check was clicked above.

The right side of the body is the new user create area. It is prepared in form. It contains username, display name, phone, email, user roles and finally the enabled information are requested. 

- Username, Display Name, Phone and Email sections are prepared as text boxes.
- There are 3 roles in the User Roles section. These are divided into three as guest, admin and superadmin on the combo box.
- When the Enabled check box is clicked, the newly created user is transferred to the list as like Enabled. If not clicked, the user falls into the disabled user list.
