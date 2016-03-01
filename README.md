# Swiss_System_Tournament

Swiss-system tournament is a common type of tournament in which players or teams are paired to face each other for several rounds of competition. Applications are Chess, Bridge, Badminton, Warmachine, Magic: The Gathering, Scrabble and other tournaments with too many players to play in round-robin style. Swiss-system tournament is comprised of three files:

* `tournament.py`: this file is used to provide access to your database via a library of functions which can add, delete or query data in your database to another python program (a client program). 
* `tournament.sql`: this file is used to set up your database schema (the table representation of your data structure).
* `tournament_test.py`: this is a client program which will use your functions written in the tournament.py module.

## Installation

After ensuring Python is installed on your local or virtual machine, in order to run this program:

1. Navigate to the directory in which you want to install Tournament Results.
2. Clone this repository to that directory.
3. Run `python tournament_test.py` to ensure all functions and database tables are properly working.
4. Create a new Python File and ensure to include `from tournament import *` at the top of the file.
5. Use `tournament_test.py` as a template to understand how to properly load your tournament data in to your new file.
6. Run `python your_file_name_here.py`.

Cloning from this repository will ensure that you always have the most up to date version of this software.

## Issues & Feature Requests

Please use GitHub to notify me of any issues or feature requests.

* Navigate to the repository on [GitHub](https://github.com/Wenyn-Wang/Swiss_System_Tournament.git).
* Click the `Issues` link on the menu towards the right.
* Then click `New issue`.
