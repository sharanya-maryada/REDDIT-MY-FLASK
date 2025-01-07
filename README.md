Flask reddit type app
Steps to run:
Clone the repository into your machine using the git clone command.
Once cloned create a virtual environment into your machine with python -m venv venv
Activate the environment with .\venv\Scripts\activate.bat on Windows and source ./venv/bin/activate on Linux/MacOS
Once activated install the required libraries with pip install -r requirements.txt
After the installation is done open env and copy the content
Make a new file called .env to store environment variables
Fill in the required details
To set up the database do flask db upgrade to get updated with the current iteration of the database
After the above steps are completed, run the app locally with flask run command
Open a browser and navigate to localhost:5000 to view the project
