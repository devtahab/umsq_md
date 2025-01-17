# User Management Screen UI Specifications

## Requirements

  - Add a new user with username, display name, phone, email, user role and enable status.
  - Save user.
  - Display a users table with their id, username, email and enable status.
  - Hide or show disabled users from the table
  - Show a create user form when clicked on "New User" button.

## UI Component Details

  ### Table

  - **Columns**: id, username, email, enable status.
  - **Features**:
    - "Hide Disabled User" checkbox: Filters out disabled users when checked.
  
  ### "New User" Button

  - **Functionality**: Shows a form on the screen for creating a new user and saving it.
   
  ### "New User" Form

  - **Fields**:
    - Username (text)
    - Display Name (text)
    - Phone (text)
    - Email (text)
    - User Roles (dropdown: Guest, Admin, SuperAdmin)
    - Enabled (checkbox)
  - **Buttons**:
    - "Save User": Saves the user with provided details.
   
## Behavior Of The Page

  - When the page is first loaded, there is just table, "New User" button and "Hide Disabled User" checkbox.
  - If user checks the "Hide Disabled User" checkbox, then table will be updated and only show enabled users.
  - After clicking the "New User" button, a form and also a "Save User" button appears.
  - After successful save of the user, the page goes back to original structure where form and "Save User" button disappears.

## What To Show User At The Beginning

  - Table shows all the users without filtering them.
  - "New User" button.
  - "Hide Disabled User" checkbox.
