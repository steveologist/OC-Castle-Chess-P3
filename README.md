# ♕ Castle Chess ♔ #

The application needs to function independently without needing an internet connection. It should be developed using Python and initiated from the command line interface. Put simply, executing the program should follow this format: python <program name>.py. Moreover, it should be compatible with Windows, Mac, or Linux systems and include a requirements.txt file outlining the necessary dependencies for its execution.

## How it works

### - Player Management
This script simplifies the management of a chess tournaments, managing activities like player registration, round tracking, match scheduling, and result recording.

### - Tournament Management
Tournament data is persisted in JSON files, located in the data/tournaments directory. Each tournament includes details such as its name, location, start and end dates, number of rounds, current round number, and a list of registered players.

### - Tournament Rounds and Matches
Tournaments consist of multiple rounds, each containing a list of matches.
Each match consists of a pair of players, with results determining points awarded.

### - Code Structure and Maintenance
The code follows the Model-View-Controller (MVC) design pattern, with three main packages: models, views, and controllers.
Code cleanliness and maintainability are ensured through adherence to PEP 8 guidelines, with the use of flake8 for code formatting and linting.

## Requirements

- Python 3.6 or later

> [!NOTE]
> This is for Mac users

## How to run

Once the code has been downloaded, go to the project directory and enter the following commands in terminal :

  `python -m venv venv` *install a new vitual environement*
    
  `source venv/bin/activate` *activate the environement*
    
  `pip install -r requirements.txt` *install all the depedencies*
    
  `python3 main.py` *run the code*

  `deactivate` *when over, deactivate the environement*

## How to use Flake8

Once you are in the directory containing the project, run Flake8 by executing the following command:
  
  `flake8 --format=html --htmldir=flake-report .`
   `flake8 main.py`



