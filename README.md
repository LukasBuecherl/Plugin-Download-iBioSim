# bioSimPortal
Flask API to facilitate communication between SBOLCanvas and iBioSim

## Local Testing/Usage

### Note: Must be run in an Ubuntu terminal
To run locally without using a Docker container, first you must change the path variables in app.py:

 - At line 259, change the path to the full path of your home directory with reb2sac in it
 - At line 260, set the rest of the path to the src folder of reb2sac

Copy iBioSim into the working directory with app.py.

Navigate to the folder path with app.py in the terminal and run:

`flask run`

Now HTTP requests can be sent to localhost:5000
