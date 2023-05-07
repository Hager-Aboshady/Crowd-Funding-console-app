# Crowd-Funding-console-appliction

This console application is designed to allow users to create and manage crowdfunding projects. Users can register for an account, create projects, and manage their own projects.

## Features

## Authentication System
    • Users can register for an account with the following information:
        ◦ First name
        ◦ Last name
        ◦ Email
        ◦ Password
        ◦ Confirm password
        ◦ Mobile phone number (validated against Egyptian phone numbers)
    • Users can log in after activation using their email and password.
    
## Projects
    • Users can create a project fundraising campaign, which includes the following information:
        ◦ Title
        ◦ Details
        ◦ Total target 
        ◦ Start and end dates for the campaign (validated against date formula)
    • Users can view all projects.
    • Users can edit their own projects.
    • Users can delete their own projects.
    • Users can search for a project using the date (bonus feature).

## Technologies
    This console application was developed using Python and the following modules:
    • uuid
    • prettytable
    • time
    • re
    • getpass
    • termcolor
    • datetime
    
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
git clone https://github.com/Hager-Aboshady/Crowd-Funding-console-app

``` 
## Usage
    1.Register for an account by entering 0 then enter your details.
    2. Log in using your email and password.
    3. Create a project by entering 1 to "Create Project" and filling in the required fields.
    3. Edit or delete your project by entering the corresponding numbers then entering the project's ID you want.
    4. View all projects by entering 2.
    5. Search for a project using the date by entering 5 and entering the desired date.
    
    

