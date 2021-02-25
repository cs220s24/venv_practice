
## Virtual Environment Practice

This repo contains a simple program to read the current weather at Moravian College.  To run the program, you must have the `bs4` and `requests` libraries installed.


To setup your development environment perform the following steps (**in order**):

1. Create A Virtual Environment

  `python3 -m venv .venv`

2. Activate the Virtual Environment

  `source .venv/bin/activate`

3. Install the Requirements in `requirements.txt`

  `pip install -r requirements.txt`

  If this command fails with a message "Failed building wheel for bs4", run `pip install wheel` and then `pip install -r requirements.txt`

4. Execute the program in the shell

  `python weather.py`

5. Open the Project in PyCharm
6. Execute the program in PyCharm
