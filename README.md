# PlannerDatabase

1. Requirements Addressed
1.1
- The first requirement we addressed was based on this user story: As a
house flipper I want to organize my remodel plans and keep a timeline so
that I can ensure I am on time with my remodel and keep track of different
projects to maximize the house's selling price.
In order to address this requirement we added a sorted list of all of the
project's tasks by their due dates

1.2
The second requirement we addressed was based on this user story: As a
commercial construction contractor, I want to have a convenient app tha
twill keep track of all past, current, and future projects so that I can archive
all construction projects I’ve ever worked on.

In order to address this requirement we made it possible to create
multiple projects that can be easily swapped between which
dashboard you are using in order to keep track of all relevant project
information:

1.3
The third requirement we addressed was based on this user story:
- As an engineer, I would like to have a place to store all of my material lists, receipts,
warranties, plans, budgets, and anything else that would be relevant to a project and
digital, so that I can easily refer back to these documents and know where they are.

This was addressed by having a mutable list of all of these things that can be
easily added to or removed from each of these as well as To-dos and clients

2. How to run
2.1 - Download Program:
- Download the program from Team Orange
- Run executable .jar file
- The project home page will open

2.2 - The Home Page:
- At the homepage screen click the Profile button to gain access to login
screen

- If you're a new user, please click the register button and create an
account. (* please enter a UserName that is pretty Unique or not to
common, we currently have a lot of basic name registrations that might
cause an issue if you name is similar)

- Once you have a new account set up, to gain access to the Project
Directory screen, in the top text field enter your User Name and in the
bottom text field enter your Password. Then click the login button to
open the Project Directory screen.

2.3 - Project Directory:
- In the Project Directory class, start by entering a New Project Name in the
bottom text field and then click Create Project. Your new project should
populate the Project Select text field and comboBox on the Top of Project
Directory.

- If you want to load your project click the “Load Project” button, shortly
after (*might take several seconds to load) the Dashboard screen should
be visible. This Dashboard is tied to the project name that was loaded in
from the Project Directory and all data will be save to the database any
time you add data to the Resource column or the To-Do-List column on
the Dashboard screen.

2.4 - Dashboard:
- In the dashboard you will have three columns. The first column is the
Menu: Projects and Log Out button brings you back to the Project
Directory screen. Export button will export your registration information,
Import button will import registration data.

- The Second column is where you can enter in Resource data from your
project. You can add Receipts, Building Materials, Plans and Client List in
this column. I.e. To add a Receipt click the + symbol to the bottom right of
the comboBox you want to add to, this will open a small resource
pop-out screen where you can type in your receipt, once all information is
added, click the Add button and it will save this receipt to the database.
Use the view button to see the receipt you just created

- The Third column is where you can enter a task in a To-Do-List. To add a
task, click the + button at the top right of the To-Do-List column, there
should be a small panel that appears, the text field can be modified to a
specific task -> TEST TEST TEST -> “enter some task…”, then to the
bottom left input the date. The date for each task is required, Format for
date is: month/day/year or 00/00/0000.
